# vue-base
快速搭建一个 vue 单文件组件开发环境，除了使用 vue-cli，还可以使用本仓库提供的环境。  
和 vue-cli 相比，有如下优点：
+ 只安装你需要的东西
+ 不“帮你”配置东西
+ 基于 parcel，比 webpack 快，且不用每个项目都安装 webpack 全家桶

## parcel
没用过？可以看看[这个](https://parceljs.org/getting_started.html)，一分钟上手  
webpack 因为**巨大**而已经被吐槽了很长时间，[parcel](https://parceljs.org/getting_started.html) 是另一款打包工具，特点是
+ 简单，不需要配置文件
+ 推荐全局安装，不需要为每个项目都安装（当然如果有需求，也可以为每个项目都装）
+ 打包迅速

这些特点让前端开发者远离：**写配置文件**、**寻找各种 loader/plugin** 等与开发网页没有太大关系的事务，也算是解放了生产力

## Go
