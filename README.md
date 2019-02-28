# react-webpack

wbepakc4 babel7 搭建react开发环境

### 工程化工具

- eslit 
- prettier-eslint-cli
- husky
- precommit 
- commitlint 


### 搭建环境中到的一些坑

babel7学习链接 https://blog.zfanw.com/babel-js/
webpack4搭建react环境  https://imweb.io/topic/5b8699a96a0f1b02454de3c0

目前直接安装babel 插件已经是7x版本 如果项目依赖的babel-core文件还是6.x 那么就会报错, 解决办法把babel相关依赖统一升级成7.x版本

.babelrc 配置

``` json
{
    "presets": ["@babel/preset-env", "@babel/preset-react"],
}
```