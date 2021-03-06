## TypeScript

A doc to learn TypeScript.


**学习进度：**

| **学习内容**                                                 | **更新时间** | **备注**                                            |
| ------------------------------------------------------------ | ------------ | --------------------------------------------------- |
| [基本类型](https://github.com/P1kaj1uu/TypeScript/tree/main/study/%E5%9F%BA%E6%9C%AC%E7%B1%BB%E5%9E%8B) | 2022-3-18   |                                                     |
| [编译选项](https://github.com/P1kaj1uu/TypeScript/tree/main/study/%E7%BC%96%E8%AF%91%E9%80%89%E9%A1%B9) | 2022-3-18   |                                                     |
| [打包配置](https://github.com/P1kaj1uu/TypeScript/tree/main/study/%E6%89%93%E5%8C%85%E9%85%8D%E7%BD%AE) | 2022-3-18   | Webpack整合<br />Babel整合                          |
| [面向对象](https://github.com/P1kaj1uu/TypeScript/tree/main/study/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1) | 2022-3-18   | class、构造器、继承<br />supuer、抽象类、封装<br /> |
| [接口](https://github.com/P1kaj1uu/TypeScript/tree/main/study/%E6%8E%A5%E5%8F%A3) | 2022-3-18   |                                                     |
| [泛型](https://github.com/P1kaj1uu/TypeScript/tree/main/study/%E6%B3%9B%E5%9E%8B) | 2022-3-18   |                                                     |
| [贪吃蛇](https://github.com/P1kaj1uu/TypeScript) | 2022-3-19   |                                                     |

**其他学习：**

-   [TypeScript 入门教程](https://ts.xcatliu.com/)
-   [TypeScript 中文手册](http://www.runoob.com/manual/gitbook/TypeScript/_book/)
-   [深入理解 TypeScript](https://jkchao.github.io/typescript-book-chinese/)
-   [TS官方文档](https://www.tslang.cn/docs/home.html)
-   [TS与各框架整合官方案例](https://www.tslang.cn/samples/index.html)

<hr>

## **贪吃蛇小游戏**

使用TypeScript + Webpack + Less实现贪吃蛇的例子。

### **项目依赖**

TypeScript：

-   typescript；
-   ts-loader；

Webpack：

-   webpack；
-   webpack-cli；
-   webpack-dev-server；
-   html-webpack-plugin；
-   clean-webpack-plugin；

Babel：

-   core-js；
-   babel-loader；
-   @babel/core；
-   @babel/preset-env；

Less & CSS资源：

-   style-loader；
-   css-loader；
-   less；
-   less-loader；
-   postcss；
-   postcss-loader；
-   postcss-preset-env；

### **项目使用**

#### **编译运行**

在确保已经正确安装node和npm的前提下：

分别执行下面的命令安装依赖并编译项目：

```bash
# 安装依赖
npm i
# 编译打包
npm run build
```

编译完成后，使用浏览器打开dist目录下的`index.html`即可游玩；

#### **继续开发**

使用`npm run start`进入开发模式；

默认使用Chrome浏览器打开，可以修改`package.json`中的值：

```json
{
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack",
    "start": "webpack serve --open chrome.exe"
  }
}
```

