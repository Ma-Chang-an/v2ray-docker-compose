# 使用docker-compose搭建v2ray服务器

1. 服务器安装Docker和Docker Compose
2. 使用uuid生成器生成uuid填入`./v2ray-config/config.json`中相应位置
3. 在当前路径启动服务
    ```shell
    docker-compose up -d
    ```
4. 启动成功