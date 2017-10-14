# 一个docker 的简单示例


## Build Setup

``` bash
# 安装项目依赖
npm install

# 先 build 下 nginx 才能访问 dist
npm run build

# 运行 docker-compose
cd docker-compose && docker-compose up --build
```

