# SpringBoot 多模块项目搭建
- 创建一个SpringBoot 的父项目
- 创建启动子模块（普通maven project）
- 复制父项目java 目录下的包到启动子模块的java目录下
- 复制父项目resources 目录下的包到启动子模块的resources目录下
- 删除父项目的src文件夹
- 创建其他非启动maven子模块
- 测试项目构建是否正常
    ```
    mvn clean package
    ```