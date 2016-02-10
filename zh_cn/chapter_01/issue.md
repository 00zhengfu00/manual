# Issue 指引

在[新建 Issue](https://github.com/v2ray/v2ray-core/issues) 之前请先阅读下面的内容，以提高 Issue 的质量和效率。

## 语言
V2Ray 支持中文和英文两种语言的 Issue，请选择你所熟悉的语言来提问，以避免一些不必要的误会。管理员会以 Issue 发起者使用的语言来回复；如果 Issue 使用了其它的语言，则以英文回复。

## 开放分类
在创建 Issue 的时候可标记为以下分类： 

### Bug
代码的质量问题，可以是功能性（Functionality），稳定性（Reliability）或者性能（Performance）。在 Bug 的内容中请注明下列内容以方便重现：

* 操作系统：如 Windows 10，Ubuntu 14.04 等，64 位 / 32 位
* V2Ray 版本：版本号或源码同步日期
* Golang 版本：如果有的话
* 问题描述：任何的错误信息，不正常的行为等
* 日志文件：如果有的话
* 上下文：之前运行过什么命令／程序，安装过什么其它软件等

如对软件使用有任何问题也请发到这个类别。

请在一个 Issue 中只描述一个问题，如果你遇到多个问题，请分别创建不同的 Issue，以方便讨论和解决。如果合在一起发，将有很高的机率被标记为 Chat 而降低解决问题的优先级。

### Chat
聊天或其它相关性不强的内容。标记为 Chat 的 Issue 将在最后回复 7 天后关闭。

### Enhancement
有关新特性的建议，如果是针对现有代码的修改，请详细描述您的建议。

## 以下分类仅供管理员使用
### Duplicate
此 Issue 与之前的某一个 Issue 重复。

### Help Wanted
标记为 Help Wanted 的 Issue 接受 Pull Request，一般为新特性的实现，如果您对其中某一个感兴趣，欢迎供献代码。

### Invalid
无法重现的 Bug 或没有意义的 Issue。

### Won't fix
此 Issue 是一个合理的问题，但不影响软件的正常使用，故不修复。
