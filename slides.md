---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: 《戏剧疗法》读书报告
info: |
  这是一个15分钟的PPT读书汇报，内容包括核心内容介绍，自己的学习体会和问题
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
---

# 《戏剧疗法》读书报告

小组X：苏雨昕，XXX，XXX，XXX

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  单击空格以进入下一页 <carbon:arrow-right />
</div>

---
layout: two-cols
layoutClass: gap-16
level: 1
---

# 目录

我将围绕这本书的核心内容、我个人的一些学习体会以及由此引发的一些思考和问题

::right::

<Toc text-sm minDepth="1" maxDepth="2" />

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
transition: slide-up
layout: section
level: 1
---

# 核心内容

作者在前言中就点明了本书旨在回答的几个关键问题，这也是本书的核心脉络

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
transition: fade-out
layout: image-left
image: https://cover.sli.dev
level: 2
---

# 什么是戏剧疗法？

戏剧疗法，顾名思义，就是有目的地运用戏剧和表演过程来实现治疗目标

书中第一章提到，戏剧疗法运用包括

- 角色扮演
- 情景演出
- 木偶
- 面具
- 讲故事
- 仪式和游戏等

戏剧疗法的重点在于治疗的过程本身。

---
transition: fade-out
layout: image-left
image: https://cover.sli.dev
level: 2
---

# 戏剧疗法治疗师都做些什么？

戏剧疗法治疗师是受过戏剧和治疗双重训练的专业人士

他们的主要任务是根据来访者的需求，选择和设计合适的戏剧活动，创造一个安全、信任的治疗环境，并引导和支持来访者参与到戏剧过程中。

书中第二章和第三章都提到，治疗师需要评估来访者的情况，决定采用个人治疗还是团体治疗。

书中第三章还强调了建立信任关系、设置清晰边界（包括物理、时间和情感边界）、处理移情和反移情等的重要性。

---
transition: fade-out
layout: image-left
image: https://cover.sli.dev
level: 2
---

# 谁能从戏剧疗法中受益？

这本书告诉我们，戏剧疗法的受益人群非常广泛

书中多个章节（如第一、七、八、九章）都提到了具体的适用人群，包括：

* 承受压力的人
* 有情绪困扰或精神健康问题的人
* 有学习障碍、社交困难或沟通障碍的人
* 经历过创伤的人
* 老年人
* 儿童
* 物质滥用者
* 罪犯

---
transition: slide-left
layout: image-left
image: https://cover.sli.dev
level: 2
---

# 戏剧疗法治疗师都在哪里工作？

书中第三章提到，随着戏剧疗法专业性的发展和认可度的提高，其应用场所也越来越多样化

戏剧疗法治疗师可以在各种机构工作，包括：

* 医院
* 日托机构或社区健康中心
* 学校
* 养老院或老年人服务中心
* 私人诊所或咨询中心
* 监狱或法庭医学中心
* 非政府组织或社会服务机构

---
transition: slide-up
layout: section
level: 1
---

# 我的学习体会

阅读这本书的过程，对我来说是一次充满启发和感动的旅程。最大的体会是，戏剧远不止于娱乐，它蕴含着强大的疗愈力量

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
transition: fade-out
layout: image-right
image: https://cover.sli.dev
level: 2
---

# 我深刻体会到“距离”和“隐喻”在治疗中的重要性

书中反复强调，戏剧创造了一个“假装”的空间。

第六章介绍的角色扮演、剧本使用、故事讲述等方法都体现了这一点。这让我意识到，有时候，“不直接”反而更有效。

---
transition: fade-out
layout: image-right
image: https://cover.sli.dev
level: 2
---

# 我认识到“过程”重于“结果”的理念

戏剧疗法强调的是参与者在戏剧活动中的体验、探索和领悟

书中第一章开篇就明确指出，戏剧疗法的重点是治疗的过程，而不是表演的水平。

第五章和第六章介绍的各种练习和方法，无论是简单的热身游戏，还是复杂的即兴表演，都服务于这个“过程”。

---
transition: slide-left
layout: image-right
image: https://cover.sli.dev
level: 2
---

# 这本书让我对“创造力”有了更深的理解

戏剧疗法本质上是一种创造性的治疗方法

书中第二章提到，强化过的创造性能力有助于问题的解决。这让我反思，在面对生活中的困境时，我们是否也能尝试用更具创造性的方式来应对？

---
transition: slide-up
layout: section
level: 1
---

# 我的问题与思考

在学习和思考的过程中，我也产生了一些疑问，主要是关于戏剧疗法在实践层面的一些问题

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
transition: fade-out
layout: image-left
image: https://cover.sli.dev
level: 2
---

# 如何成为一名戏剧疗法治疗师？

在英国，戏剧疗法治疗师需要接受专业的硕士层级的培训

书中第一章提到，在英国，戏剧疗法治疗师需要接受专业的硕士层级的培训，并通过卫生健康专业委员会（HPC）的认证注册。

这让我好奇，在不同的国家和地区，

- 成为戏剧疗法治疗师的路径是怎样的？
- 需要具备哪些戏剧背景和心理学知识？
- 培训过程具体是怎样的？

书中提到培训包含理论学习、技巧训练、个人体验、督导下的实践等，但具体的细节仍让我很感兴趣。

---
transition: slide-left
layout: image-left
image: https://cover.sli.dev
level: 2
---

# 戏剧疗法的疗效如何衡量和验证？

关于效果评估的讨论似乎不多

书中通过大量的案例（贯穿多个章节）展示了戏剧疗法的积极效果，

- 帮助抑郁症患者重拾希望
- 帮助受虐者处理创伤
- 帮助精神分裂症患者改善沟通
- 提升老年人生活质量

它的疗效是否得到了广泛的实证研究支持？如何客观地评估戏剧疗法带来的改变？

它与其他心理治疗方法（如认知行为疗法、精神分析等）相比，其独特性和有效性如何？

---
transition: fade-out
layout: end
level: 1
---

# 结语

我的分享就到这里，谢谢大家！

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
