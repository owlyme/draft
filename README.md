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


### [npm](https://www.npmjs.com.cn/getting-started/what-is-npm/)
> npm 为你和你的团队打开了连接整个 JavaScript 天才世界的一扇大门。它是世界上最大的软件注册表，每星期大约有 30 亿次的下载量，包含超过 600000 个 包（package） （即，代码模块）。来自各大洲的开源软件开发者使用 npm 互相分享和借鉴。包的结构使您能够轻松跟踪依赖项和版本。

#### npm 由三个独立的部分组成：
- 网站
- 注册表（registry）
- 命令行工具 (CLI)

### [Vue2-animate](https://the-allstars.com/vue2-animate/)
  各种效果