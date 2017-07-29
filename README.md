# vue-build-demo
> 零配置构建，支持单文件，css 预处理，支持 webpack config

起步，只需
```
yarn global add vue-cli
```

常用命令
```
vue build index.js -o
vue build Component.vue
vue build Component.vue --prod --lib
vue build -h
```

如果需要预处理，则需要改为项目内安装，且要装相应 loader 信赖
```
yarn add vue-cli
yarn add pug pug-loader stylus stylus-loader
```

> Everything in ./static folder will be copied to dist folder

参考：[vue-cli/build.md at master · vuejs/vue-cli](https://github.com/vuejs/vue-cli/blob/master/docs/build.md)
