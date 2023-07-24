# img-build

按需构建镜像

每个文件夹分为三部分：
- `build.sh`: 运行构建镜像的 `shell` 脚本，需要位于此文件所在文件夹下才能正常运行
- `Dockerfile`: 构建镜像的文件，描述镜像所需资源
- `docker-compose.yml`: 使用 `docker-compose` 启动镜像的文件
