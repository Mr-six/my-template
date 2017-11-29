# my-template

## 项目说明:
此项目基于 vue-webpack-complate 实现单页敏捷开发,减少配置过程,上手即用.(添加了 sass 编译支持, 修改 build 打包时 assetsPublicPath: './',暂用相对路径进行本地打包测试, 线上发布时,可将置为 '/')

krpano分支用于开发全景单页,公共资源位于 static 文件夹中. 具体参考readme文件.

## krpano 分支说明
主要文件位于 static/krpano 文件内
```
-- static
  |-- krpano
      |-- panos    # 全景图片(将项目中panos文件放入)
      |-- plugins  # krpano 插件系统
      |-- skin     # krpano 皮肤文件
      |-- tour.js  # krpano 基础js文件
      |-- tour.xml # 场景xml文件
```
项目添加时使用krpano生成全景并设置好热点位置
其中主要文件为 tour.xml 以及 自定义修改皮肤文件
将tour.xml文件 和 全景图片文件放到指定位置,并导入皮肤修改文件即可

### krpano 版本升级
替换krpano 文件夹下的对于文件即可

> my template

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
