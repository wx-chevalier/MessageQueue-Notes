[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![license: CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey.svg)][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/wx-chevalier/repo">
    <img src="header.svg" alt="Logo" style="width: 100vw;height: 400px" />
  </a>

  <p align="center">
    <a href="https://wx-chevalier.github.io/repo"><strong>在线阅读 >> </strong></a>
    <br />
    <br />
    <a href="https://github.com/wx-chevalier/Awesome-CheatSheets">速览手册</a>
    ·
    <a href="https://github.com/wx-chevalier">代码实践</a>
    ·
    <a href="https://github.com/wx-chevalier/Awesome-Lists">参考资料</a>

  </p>
</p>

<!-- ABOUT THE PROJECT -->

# Introduction | 前言

随着信息技术的快速发展及互联网用户规模的急剧增长，计算机所存储的信息量正呈爆炸式增长，目前数据量已进入大规模和超大规模的海量数据时代，如何高效地存储、分析、处理和挖掘海量数据已成为技术研究领域的热点和难点问题。当前出现的云存储、分布式存储系统、NoSQL 数据库及列存储等前沿技术在海量数据的驱使下，正日新月异地向前发展，采用这些技术来处理大数据成为一种发展趋势。而如何采集和运营管理、分析这些数据也是大数据处理中一个至关重要的组成环节，这就需要相应的基础设施对其提供支持。在现代微服务化的分布式应用中，不同服务之间往往需要进行频繁而广泛的通信，我们可以把消息队列比作是一个存放消息的容器，当我们需要使用消息的时候可以取出消息供自己使用。

> 参考维基百科的定义，在计算机科学中，消息队列和邮箱是用于进程间通信（IPC）的软件工程组件，或用于同一进程内的线程间通信的软件工程组件。与标准的请求-应答模式的 [RPC](http://ngte-be.gitbook.io/?q=RPC) 相比，RPC 更强调点对点交互、强事务保证和延迟敏感的服务/应用之间的通信，消息队列则更关注于异步通信、内容投递。

消息队列作为服务/应用之间的通信中间件，可以起到业务耦合、广播消息、保证最终一致性以及错峰流控（克服短板瓶颈）等作用。这里所谓的消息，可以看做一个小的，自包含的，不可变的对象，包含某个时间点发生的某件事情的细节：它通常包含一个来自时钟的时间戳，以指明消息发生的时间。例如，发生的消息可能是用户采取的行动，例如查看页面或进行购买。它也可能来源于机器，例如对温度传感器或 CPU 利用率的周期性测量。一个消息由生产者（producer）（也称为 发布者（publisher）或发送者（sender））生成一次，然后可能由多个消费者（consumer）（订阅者（subscribers）或接收者（recipients））进行处理。

![消息队列示意](https://pic.imgdb.cn/item/6086a9ead1a9ae528f1a0422.jpg)

更多介绍与导览参阅 [INTRODUCTION](./INTRODUCTION.md)。

## Nav | 关联导航

# About | 关于

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [Awesome-Lists](https://github.com/wx-chevalier/Awesome-Lists): 📚 Guide to Galaxy, curated, worthy and up-to-date links/reading list for ITCS-Coding/Algorithm/SoftwareArchitecture/AI. 💫 ITCS-编程/算法/软件架构/人工智能等领域的文章/书籍/资料/项目链接精选。

- [Awesome-CS-Books](https://github.com/wx-chevalier/Awesome-CS-Books): :books: Awesome CS Books/Series(.pdf by git lfs) Warehouse for Geeks, ProgrammingLanguage, SoftwareEngineering, Web, AI, ServerSideApplication, Infrastructure, FE etc. :dizzy: 优秀计算机科学与技术领域相关的书籍归档。

## Copyright & More | 延伸阅读

笔者所有文章遵循[知识共享 署名 - 非商业性使用 - 禁止演绎 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh)，欢迎转载，尊重版权。您还可以前往 [NGTE Books](https://wx-chevalier.github.io/books/) 主页浏览包含知识体系、编程语言、软件工程、模式与架构、Web 与大前端、服务端开发实践与工程架构、分布式基础架构、人工智能与深度学习、产品运营与创业等多类目的书籍列表：

[![NGTE Books](https://s2.ax1x.com/2020/01/18/19uXtI.png)](https://wx-chevalier.github.io/books/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/wx-chevalier/repo.svg?style=flat-square
[contributors-url]: https://github.com/wx-chevalier/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/wx-chevalier/repo.svg?style=flat-square
[forks-url]: https://github.com/wx-chevalier/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/wx-chevalier/repo.svg?style=flat-square
[stars-url]: https://github.com/wx-chevalier/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/wx-chevalier/repo.svg?style=flat-square
[issues-url]: https://github.com/wx-chevalier/repo/issues
[license-shield]: https://img.shields.io/github/license/wx-chevalier/repo.svg?style=flat-square
[license-url]: https://github.com/wx-chevalier/repo/blob/master/LICENSE.txt
