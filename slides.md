---
# try also 'default' to start simple
theme: default 

# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080

# apply any windi css classes to the current slide
class: 'text-center'

# https://sli.dev/custom/highlighters.html
highlighter: shiki

# show line numbers in code blocks
lineNumbers: false

# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)

# persist drawings in exports and build
drawings:
  persist: false
---

# 程序员的软技能

代码之外的生存指南

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/forrestchang/programmer-soft-skills" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
  <a href="https://twitter.com/tisoga" target="_blank" alt="Twitter"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-twitter />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# 介绍

作为一名程序员，除了需要掌握「硬技能」之外（例如编程语言、架构设计等），也需要一些「软技能」来傍身，这些「软技能」可以帮助你更好地成长。

今天主要会分享以下几个主题的内容：

- 🕐 **时间管理** - 如何更好地规划任务，管理时间，提高生产力
- 📚 **快速学习** - 如何快速掌握一门技能
- 👏 **个人营销** - 如何提升影响力

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
---

# 🕐 **时间管理**

---
layout: two-cols
---

# Getting Things Done

- David Allen
- 中文版：《搞定》
  - [微信读书](https://weread.qq.com/web/bookDetail/c0e328b05cf118c0e998aee)
- 一种任务管理的流程
  - 类似于我们现在使用的 Jira 上的 Workflow
- 核心：清空大脑

::right::

<img class="h-120" src="https://images-na.ssl-images-amazon.com/images/I/81Sna4a0jPL.jpg">


---
layout: two-cols
---

# GTD Workflow

1. Capture 收集
    - Inbox
    - Quick Capture
2. Calarify 厘清
    - 区分是否是可行动的
    - Project? Next Action? Reference?
3. Plan 规划
    - 找到 Next Action
    - Weekly Plan -> Daily Plan
4. Do 行动
    - Pomodoro Technique

<br>

👉 [用 OmniFocus 3 完成了上千个任务后，我总结出了这些经验](https://sspai.com/post/49105)

::right::

<img class="h-120" src="https://playbook.datopian.com/assets/img/gtd-clarify-flow.02e76115.png">

---
layout: two-cols
---

# 工具

- 滴答清单
- Todoist
- OmniFocus
- Things 3

::right::

<img class="h-auto m-10" src="https://cdn.vox-cdn.com/thumbor/uTUIdbjQEZihp3WOz-wVRzb-BMA=/0x0:2426x1820/920x613/filters:focal(1019x716:1407x1104):format(webp)/cdn.vox-cdn.com/uploads/chorus_image/image/54862145/Things_Hero_2___macOS.0.png">

---
layout: two-cols
---

# 番茄工作法

- Pomodoro Technique
- 一种注意力训练的方法
- 流程
  - 设定好一个目标
  - 确定每个番茄的时间（一般是 25 分钟）
  - 开始计时并专注在当前的目标上，直到这个番茄时间结束
  - 如果有插入的事情，就先记录下来（之前讲到的 Inbox）
  - 完成一个番茄后休息 5 分钟
  - 循环

::right::

<img class="h-auto m-10" src="https://images.prismic.io/sketchplanations/62e61034-b66a-4ede-a5db-a5cbc39d55e7_SP+587+-+The+Pomodoro+technique.jpg?auto=compress,format&w=1200">

---
layout: two-cols
---

# 深度工作 Deep Work

- Cal Newport
  - CS 教授，畅销书作家，博客
- 深度工作：专注、不间断、不分心的工作，这种工作会将你的认知能力推到极限
- 浮浅工作：这类工作对认知要求不高，并且不能创造太多价值，任何人都可以做到

<br>
<br>

👉 [知识工作者的深度工作系统 Part 1](https://twitter.com/Tisoga/status/1515663828536598528)
<br>
<br>
👉 [知识工作者的深度工作系统 Part 2](https://twitter.com/Tisoga/status/1516040155852804098)

::right::

<img class="h-110 m-4" src="https://kbimages1-a.akamaihd.net/11cc59b5-7b19-40e3-8d8a-de1538cfa5e7/1200/1200/False/deep-work-1.jpg">

---
layout: two-cols
---

# Maker's Schedule vs Manager's Schedule

👉 [Maker's Schedule, Manager's Schedule](http://www.paulgraham.com/makersschedule.html)

- Paul Graham
  - YCombinator, 黑客与画家
- Makers
  - 大段并且连续的时间
  - 避免 context switching
- Managers
  - 被会议分割成一个个小的时间段

Tips:
- 找到自己的 Maker 时间
  - Paul 创业的时候是白天开会，然后从 18:00 开始写代码到 03:00


::right::

<img class="" src="https://i0.wp.com/tylerdevries.com/wp-content/uploads/2019/07/maker-schedule-vs-manager-schedule.jpg">

<style>
  h1 {
    font-size: 1.4rem;
  }
</style>

---
layout: two-cols
---

# 案例：Cal Newport

- [Deep Habits: Plan Your Week in Advance](https://www.calnewport.com/blog/2014/08/08/deep-habits-plan-your-week-in-advance/)
- [How to schedule deep work: Time blocking](https://youtu.be/ykNcnrNvpTI)

::right::

<img class="h-60" src="https://pbs.twimg.com/profile_images/1403013239487680512/FEfDeOTX_400x400.jpg">

---
layout: two-cols
---

# 案例：Lex Fridman

- MIT 研究员，知名 Podcast 主播
  - 采访过的对象：Elon Musk, Mark Zuckerberg, Ray Dalio 等
  - Podcast: [Lex Fridman YouTube](https://www.youtube.com/c/lexfridman/videos)
- [A day in my life](https://youtu.be/0m3hGZvD-0s)
  - 每天工作 12 小时，8 小时深度工作 + 4 小时低强度工作
  - 上午和下午各有 4 小时的 deep work session，在这个 4 小时中，Lex 不会让任何事情打断自己，也绝不刷社交网络

::right::

<img class="h-60 m-5" src="https://cdns-images.dzcdn.net/images/talk/fa8715fd91b40c027dab37c6d6e91936/1000x1000.jpg">

---
layout: two-cols
---

# 案例：George Hotz

- 计算机黑客，2007 年破解了 iPhone，2009 年破解了 PS3
- 低成本自动驾驶解决方案 comma.ai 的创始人
- 经常在 Twitch 上直播 live coding
  - 每次持续 5+ 小时
  - [从零实现一个 SLAM (Simulataneous localization and mapping)](https://youtu.be/7Hlb8YX2-W8)
  - 同时定位与地图构建，自动驾驶的核心技术之一

::right::

<img class="m-5" src="https://i.insider.com/5776b7bf4321f1c72f8b50bd?width=1000&format=jpeg&auto=webp">

---
layout: two-cols
---

# 间隙日志 Interstitial Journal

👉 [Replace Your To-Do List With Interstitial Journaling To Increase Productivity](https://betterhumans.pub/replace-your-to-do-list-with-interstitial-journaling-to-increase-productivity-4e43109d15ef)

<br>

- 写下来是为了更好地思考
- 可以避免拖延
- 记录下日志方便之后回溯

::right::

<img class="h-120 m-5" src="https://pbs.twimg.com/media/Eyn0kOkXEAQM7ml?format=jpg&name=900x900">

---
layout: center
---

# 📚 **快速学习**

---

# 主动学习

- 带着目的去学习
  - 解决某个问题
  - 了解某个领域的知识
- 学院派
  - 从零开始学习，学完一部分再学另一部分
  - 耗时长
  - 如果没有用起来很容易忘记
- 实用派
  - 基于目的的学习方式
  - 先表面，再深入
  - 以用起来为主

---
layout: two-cols
---

# 学习金字塔

- 主动学习与被动学习
- 做和教是最好的学习方式

<br>

<img class="w-auto" src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2FJiayuanWorkspace%2FMUgMRjx260.png?alt=media&token=4b449e05-6ba7-4379-a9fa-9a86c2fa37fe">

::right::

<img class="" src="https://www.thephuketnews.com/photo/listing/1374138536_1.jpg">

---
layout: quote
---

You don't learn, then start. You start, then learn. -- Sahil Lavingia

<img class="h-30" src="https://i.insider.com/6001b1f2dd0659001a8b73bc?width=500&format=jpeg&auto=webp">

<style>
  p {
    font-size: 1.6em;
    background-color: #2B90B6;
    background-image: linear-gradient(45deg, #23c5D4 10%, #296b8c 20%);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
  }
</style>

---
layout: two-cols
---

# Do -> Learn

- Sahil Lavingia
  - Pinterest #2
  - Gumroad CEO
  - [Reflecting on My Failure to Build a Billion-Dollar Company](https://sahillavingia.com/reflecting)
- 先行动起来，遇到不会的再去学习
- Get Your Hands Dirty
- 一个 🌰 : Figma 的学习经验
  - 分钟级别速成
  - [Figma UI Design Tutorial: Get Started in Just 24 Minutes! (2022)](https://youtu.be/FTFaQWZBqQ8)
  - 用到什么查什么


::right::

<img class="h-100 m-5" src="https://images-na.ssl-images-amazon.com/images/I/41qdZH4FhLL._SX329_BO1,204,203,200_.jpg">

---

# Feynman Technique

- 理论物理学家
- 量子力学奠基人之一，1965 年获得诺贝尔物理学奖
- 费曼物理学讲义
- [别逗了，费曼先生](https://weread.qq.com/web/bookDetail/cd732d70718db043cd73bb3)

<br>

<div class="flex gap-2">
  <img class="h-70" src="https://caltech-prod.s3.amazonaws.com/main/images/feynman01-NEWS-WEB.width-600_tSwRQP5.jpg">
  <img class="h-70" src="https://upload.wikimedia.org/wikipedia/commons/8/87/The_Feynman_Lectures_on_Physics.jpg">
  <img class="h-70" src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1594515882l/54477308._SX318_.jpg">
</div>

---
layout: two-cols
---

# Feynman Technique

1. 选择一个想要学习的主题
2. 把这个主题讲给一个完全不会的人听
3. 如果讲的过程中卡壳了，就回过头去重新把卡壳的这部分学习一下
4. 简化所讲的内容，能不能用更简单的话来讲

::right::

<img class="m-5" src="https://25r4fj22vjh18a4i91qamh06-wpengine.netdna-ssl.com/wp-content/uploads/2020/02/feynman-technique_graphic-1_resize-1.png">

---

# Feynman Technique

- 写博客
  - 2014 - 2022
  - [Jiayuan Thoughts](https://blog.jiayuanzhang.com/)
- 利用 Twitter 来进行公开写作
  - 2020 年公开写作实验
  - [利用 Twitter 来进行低成本写作](https://blog.jiayuanzhang.com/post/low-cost-writing-with-twitter/)
- 参与技术分享
  - 2019, Python Open Days, [How to Build a Web Framework from Scratch](https://youtu.be/p8GXdWWHPQU)
  - 2019, PyCon, [The Past and Future of GIL](https://slide.jiayuanzhang.com/the-past-and-future-of-gil/#/)

---
layout: two-cols
---

# 知识的复利

- 注重积累
- 建立自己的知识管理系统

<br>
<br>

<img class="h-80" src="https://m.media-amazon.com/images/I/412AXfNUJSL.jpg">

::right::

<img class="" src="https://cdn.corporatefinanceinstitute.com/assets/Simple-vs-Compound-Interest-1.png">

---
layout: center
---

# 👏 **个人营销**

---
layout: two-cols
---

# 把自己当做产品

- 找到 PMF
  - [Do Things That Don't Scale - Paul Graphaham](http://paulgraham.com/ds.html)
- 创造价值
- 持续迭代
- 案例：[左耳朵耗子（陈皓）](https://coolshell.cn/haoel)
  - 2002 年开始写技术博客
  - 极客时间专栏「左耳听风」售出 15 万份（收入约 5000 万+，实际可能没有这么多）
- 案例：[阮一峰](http://www.ruanyifeng.com/)
  - 《黑客与画家》、《软件随想录》等书的译者
  - 坚持博客输出内容
  - 科技爱好者周刊（目前已经更新到 211 期）

::right::

<img class="" src="https://aktiasolutions.com/wp-content/uploads/2019/01/PRODUCT-MARKET-FIT-AJUSTE-PRODUCTO-MERCADO-LEAN-PRODUCT-MANAGEMENT-AKTIA-SOLUTIONS.jpg">

---
layout: two-cols
---

# Show Your Work

- Think in system
- Share something small everyday
- Tell good stories
- Teach what you know
- Charge a fair price
- Stick around, don't quit

::right::

<img class="m-5" src="https://austinkleon.com/wp-content/uploads/2012/10/00-show-cover.jpg">

---

# 建立联系

- 多利用公司资源和不同的人 1:1
  - Project: 每天和不同部门/职业的人 1:1
- 画板策略 - Ryan Holiday
  - [The Canvas Strategy](https://ryanholiday.net/the-canvas-strategy/)
    - Find canvases for other people to paint on.
  - 优先为他人创造价值
  - 放下 Ego

---

# 建立联系

<img class="h-120" src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2FJiayuanWorkspace%2FuqxpprAgWM.png?alt=media&token=4c43a815-8e8c-4c85-8557-1070494fdc8c">

---

# 建立联系

<img class="h-100" src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2FJiayuanWorkspace%2FFfGobNpOOh.png?alt=media&token=6b5187ab-838a-4b85-bb67-40097843a4a9">

---

# 建立联系

<img class="h-110" src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2FJiayuanWorkspace%2FKH6_7CSFiH.png?alt=media&token=eff7fa18-9a83-4c93-a82b-d7315ffd1cfc">

---
layout: center
---

# Q&A