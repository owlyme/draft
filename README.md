### 关于polyfill还有个叫做[polyfill.io](https://polyfill.io/v3/)的神器，只要在浏览器引入
> https://cdn.polyfill.io/v2/polyfill.js

#### 是什么？
> 是一个就编译器
#### 用来做什么？
> babel 是一个工具链，主要用于将ECMAScript 2015+ 版本的代码转换为向后兼容的js语法，以便能够在当前和旧的环境中运行
- 语法转换
- 通过polyfill方式在目标环境中添加缺失的特性
- 源码转换
  
#### 怎么用？
> 通过在配置插件来完成，可在pack.json文件中添加babel属性，或者创建.babelrc配置文件
> ```
> {
>   presets: [
>     require("@babel/preset-env"),  // 预设环境
>   ],
>   plugins: [
>     // 相关插件
>   ]
> }
> ```


#### 原理？


