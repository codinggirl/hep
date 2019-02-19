# Hep

[![Greenkeeper badge](https://badges.greenkeeper.io/codinggirl/hep.svg)](https://greenkeeper.io/)

Hep is a HTTP middleware framework for node.js.

[English](#en) | [简体中文](#zh-CN)

<a id="en" name="en"></a>

---

## What's Hep

Hep is a HTTP middleware framework for node.js.

>>>
    Hep means Rose


## License

MIT

---

<a id="zh-CN" name="zh-CN"></a>

## Hep 是什么

Hep 是一个 HTTP 中间件框架，实现和 Koa 2 类似的功能。

目前，Hep 只是对 Koa 2 的简单包装。

>>>
    赠人玫瑰，手有余香
    
    Hep 是"玫瑰"的意思。我们期待这朵玫瑰，能给大家带来许多惊喜。
    
## 安装

你可以通过 npm 工具安装，也可以通过 cnpm 工具安装。两者选择其一即可。

### 通过 npm 安装

- 直接安装

```
npm -i hep
```

- 作为依赖项目安装

```
npm -i hep --save
```

### 通过 cnpm 安装

- 直接安装

```
cpm -i hep
```

- 作为依赖项目安装

```
cnpm -i hep --save
```

## 使用

```ecmascript 6
const Hep = require('hep')
const app = new Hep()

app.use(async (ctx, next) => {
    ctx.body = 'hello, world'
})

app.listen(3000)
```

## 授权协议

MIT

---

## License

MIT
