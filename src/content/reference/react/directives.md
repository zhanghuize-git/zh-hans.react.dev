---
title: "Directives"
canary: true
---

<Canary>

这些指令仅在你 [使用 React 服务端组件](/learn/start-a-new-react-project#bleeding-edge-react-frameworks) 或构建可适配库时需要。

</Canary>

<Intro>

指令（directive）向 [与 React 服务端组件兼容的捆绑器（bundler）](/learn/start-a-new-react-project#bleeding-edge-react-frameworks) 提供指令（instruction）。

</Intro>

---

## 源码命令 {/*source-code-directives*/}

* [`'use client'`](/reference/react/use-client) 标记组件在客户端上执行的源文件。
* [`'use server'`](/reference/react/use-server) 标记可以从客户端代码调用的服务器函数。
