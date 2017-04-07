### weex for saas


### 查看文档后的入坑准备

#### 搭建 weex 的开发环境  weex-toolkit （npm i -g 即可）

#### 需要 了解 weex 为了兼容 三平台而做的 语义化标签 的理解

#### 需要处理 在程序编写完成后的 build 的环境问题。（安卓 IOS 和 web端）

    其中 安卓 需要 andriod studio
    IOS  需要 配合  Xcode 和 CocoaPods

#### weex  Android and IOS 的 APIs and 扩展

    这里其实就已经需要开发者拥有一定的 原生客户端的开发能力


#### weex 的开发需要 了解 并 使用 Weex 的模块


#### 最后 针对 三端的 各自的优缺点做处理

    虽然同一份代码可以运行在三端，但是 iOS 和 Android 和 Web 都有各自的优势和缺陷，如果你想实现一些平台特有的功能，
    Weex 也是支持的。如果你想要体现平台特有的优势，就得针对某个平台写一下原生代码。
    在写 iOS 或者 Android 代码的时候，肯定能确保在其他平台中不会执行到；但是在写 js 代码的时候，
    如果使用了只在 Web 上才有的特性，就得注意一些，不要让 iOS 和 Android 执行到这些代码。

## 最后打算 用 weex 来模拟一个简单的 apps 来做 组件展示的 demo

### 道友们 一致反对 weex 作为开发环境产物。纠结