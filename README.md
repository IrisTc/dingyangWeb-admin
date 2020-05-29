# dingyang-admin

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## 自动化部署到服务器

```
npm run deploy
```

## 后端接口URL

本地进行项目开发时，进入server中开启node服务，端口号为3004，默认URL为`http://localhost:3004`，部署上线后就需要将这个url换成真正的域名，统一定义在`src/config.js`文件中

```
cd server
npm install
npm run dev
```

