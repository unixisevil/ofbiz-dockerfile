#Apache Ofbiz Docker image


# 镜像构建

```
docker build  -t  ofbiz  .

```

# 启动容器

```
docker run -d  --name ofbiz  -p 8443:8443  ofbiz

```

打开浏览器访问容器的8443 端口 /catalog  
