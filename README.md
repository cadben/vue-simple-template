# vuecli3+axios+vue-router+vuex项目通用模板
二次封装axios、预设less等、配置router、vuex
最基础的项目模板，其他插件根据需求自行添加

## 技术栈
vuex + vue-router + axios + less + eslint/prettier

### 命令说明
```
yarn serve 或者 npm run serve   // 启动开发环境

yarn build 或者 npm run build   // 打包生成环境

yarn lint 或者 npm run lint   //使用eslint+prettier格式化代码

```
## 项目说明
在vue-cli3脚手架的基础上，添加了一些必要的配置文件，同时也保持最纯洁的模板，根据项目可引用其他框架。
更适合大型项目及多人协作

### less
使用 `style-resources-loader` 配置全局参数


### axios
封装后的axios，更优雅的使用axios

### router
模块化router，对一级以下的路由`(routes.children)`进行分类管理

##### vue-cli其他配置
传送门： [vue-cli3](https://cli.vuejs.org/zh/).
