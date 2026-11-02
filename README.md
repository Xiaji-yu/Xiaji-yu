<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Xiaji-yu/Xiaji-yu/master/assets/hero-dark.svg">
    <img src="https://raw.githubusercontent.com/Xiaji-yu/Xiaji-yu/master/assets/hero-light.svg" alt="XIAJI" width="560">
  </picture>
  <br><br>
  <p><strong>夏祭</strong> · 独立开发者</p>
  <p>偏爱零依赖、可自托管、一个人也能维护完的系统。<br>
     做的都是自己每天在用的东西。</p>
</div>

---

## 最近

- 在写 **[agent-demo](https://github.com/Xiaji-yu/agent-demo)** —— 自托管的 QQ 智能体，核心与协议层解耦
- 在维护 **[xiaji-home](https://github.com/Xiaji-yu/xiaji-home)** —— 个人主页，零图片素材
- 在试 **[dsh-Go](https://github.com/Xiaji-yu/dsh-Go)** —— 把 DeepSeek Harness 装进手机

---

## 项目

### [agent-demo](https://github.com/Xiaji-yu/agent-demo) · 自托管的 QQ 智能体

NoneBot2 只当消息通道，核心 `agentcore` 是纯 Python 包，不感知 QQ——将来想拆成 HTTP 服务，只换壳，不动核心。

长期记忆按会话隔离，pgvector 做语义检索；工具调用有三级权限和命令白名单沙箱。

`Python` · `NoneBot2` · `PostgreSQL`

### [xiaji-home](https://github.com/Xiaji-yu/xiaji-home) · 黑白点阵个人主页

没有一张图片素材。首屏那座山由约 1.5 万颗**等大、同色**的圆点现场算出，明暗只靠疏密；动效全手写，不引动画库，生产包 gzip 后约 80 kB。

`React` · `Vite` · `Canvas`

### [dashboard](https://github.com/Xiaji-yu/dashboard) · 本机状态看板

零外部依赖：Python 标准库起 HTTP 服务，前端原生写。CPU、内存、磁盘、网速、温度、进程和容器状态一屏看完。

`Python` · `标准库`

### [Moments](https://github.com/Xiaji-yu/moments) · 出行照片挑图

批量导入照片，让识图 LLM 挑出值得发的 Top N 并说明理由。二次构图、文案生成和九宫格预览在计划里。

`TypeScript` · `LLM`

---

## 一些取舍

> 不是口号，是上面这些项目里真的按这个做的。

| 选择 | 放弃 |
| :--- | :--- |
| 标准库够用就不加依赖 | 为一个小功能引入一个包 |
| 把边界收在模块里 | 让调用方自己判断 |
| 一个人能维护完的系统 | 需要值班的系统 |
| 用完即删的原型 | 留在仓库里腐烂的代码 |

---

## 常用

`Python` · `TypeScript` · `React` · `Vite` · `Node` · `PostgreSQL` · `Docker` · `Linux`

---

## 联系

- 主页：[xiaji.xin](https://xiaji.xin)
- 邮箱：[variant305@gmail.com](mailto:variant305@gmail.com)
- 有问题直接开 Issue，比发邮件快

<div align="center">
<br/>
<sub>点阵是算出来的，不是画出来的。</sub>
</div>
