# sharelatex
配置好docker-compose文件及路径，方便以后部署

```
cd /
mkdir data
cd data
git clone https://github.com/luoxding/sharelatex.git
cd sharelatex
#新增个映射文件夹，方便传输文件
mkdir src
docker-compose up -d
```

其中使用的镜像为我之前配置好的2021导出版本
