---
title: Ethereum.org 翻译指南
lang: zh
description: 如何帮助翻译 ethereum.org
sidebar: true
---

# ethereum.org 翻译手册 {#translating-ethereum-guide}

如果您是翻译项目的新手，而且不知道从何下手，这里的一些常见问题会有所帮助。 使用本手册来寻找常见问题的答案。

## 如何翻译带有 `<HTML tags>` 的语句？ {#tags}

并非每个语句都以纯文本形式写入。 部分语句包含 HTML 标签 (`<0>` `</0>`) 等混合脚本。通常是句子中的超链接或不同格式。

- 翻译标签内的文本，但不翻译标签本身。 不能翻译或删除 `<` and `>` 中的任何内容。
- 为了保持语句完整，建议您点击左下方的"复制源代码"按钮。 这将复制原文语句并粘贴到文本框内。 这让您明确标签的位置，有助于避免错误。

![高亮显示复制源按钮的 Crowdin 界面](../../../../../contributing/translation-program/translation-guide/html-tag-strings.png)

您可以在语句中移动标签的位置，使其在句子中更加自然，但请确保移动整个标签。

## 上下文在哪里？ {#strings}

通常情况下，仅靠原文语句可能不足以让您提供准确翻译。

- 查看“屏幕截图”和“上下文”以获取更多信息。 在原文语句部分，您将看到附加的屏幕截图图像，从而了解使用该语句的上下文。
- 如果仍然不确定，请在“评论部分”中添加标记。 [不知道如何评论？](#comment)

![如何通过屏幕截图为语句提供上下文信息](../../../../../contributing/translation-program/translation-guide/source-string.png)

![为上下文添加一个示例截图](../../../../../contributing/translation-program/translation-guide/source-string-2.png)

## 如何留下评论或问题？ 我想标记一个问题或错别字... {#comment}

如果您想标记某个需要注意的语句，请随时提交评论。

- 点击右上角菜单栏的第二个按钮。 隐藏标签将出现在您的右侧。 留下新评论并点击底部的“问题”复选框。 您可以从下拉菜单选择一个选项，表明问题类型。
- 问题一旦提交，就将报告给我们的团队。 我们将解决这个问题，并通过回复评论和关闭问题来让您知道。

![如何发表评论和问题](../../../../../contributing/translation-program/translation-guide/comment-issue.png)

## 什么是翻译记忆库 (TM)？ {#translation-memory}

翻译记忆库 (TM) 是一项 Crowdin 功能，可在 [ethereum.org](http://ethereum.org/) 中存储所有先前已翻译的语句。 翻译过的语句会自动保存到 TM 中。 这款实用工具可以帮助您节省时间!

- 请看“TM 和 MT 建议”部分，您会看到其他翻译者如何翻译相同或类似语句。 如果发现匹配率很高的建议，可以点击以引用该翻译内容。
- 如果列表中没有任何内容，您可以搜索 TM 中以前做过的翻译并重新使用以保持一致性。

![翻译记忆库屏幕截图](../../../../../contributing/translation-program/translation-guide/translation-memory.png)

## 如何使用 Crowdin 词汇表？ {#glossary}

以太坊术语是我们翻译工作的另一个关键部分，因为通常新的术语在许多语言中尚未本地化。 另外，有些术语在不同背景下的含义不同。 [关于以太坊术语翻译的更多信息](#terminology)

Crowdin 词汇表是阐明术语和定义的最佳位置。 有两种方法来参照词汇表。

- 首先，当您在原文语句上发现带下划线的术语时，将鼠标移到上面，即可看到简要定义。

![词汇表定义示例](../../../../../contributing/translation-program/translation-guide/glossary-definition.png)

- 第二，如果看到一个不熟悉但没有下划线的术语，您可以在词汇表选项卡（右侧列第三个按钮）中搜索。 您会找到特定术语和项目中常用术语的解释。

![Crowdin 中“词汇表”选项卡位置的屏幕截图](../../../../../contributing/translation-program/translation-guide/glossary-tab.png)

- 如果仍然找不到，即可借此机会添加新术语！ 我们建议您在搜索引擎上进行查找，并将描述添加到词汇表中。 这将非常有助于其他翻译者更好地理解该术语。

![如何向 Crowdin 添加词汇表术语的屏幕截图](../../../../../contributing/translation-program/translation-guide/add-glossary-term.png)

### 术语翻译政策 {#terminology}

_适用于名称（品牌、公司、人物）和新的技术术语（Eth2、信标链等）_

以太坊提出了很多最近出现的新术语。 由于没有各自语言的官方译本，因此翻译者对有些术语的翻译不同。 这种不一致会造成误解，降低可读性。

由于语言多样性和每种语言的标准化程度不同，几乎不可能提出可适合所有支持语言的统一术语翻译规则。

经过慎重考虑，我们决定将最常用的术语留给你们翻译者。

如果发现您不熟悉的术语，我们建议您：

- 参考[术语表](#glossary)，您可能会发现其他翻译者以前的译法。 如果您认为之前翻译的术语不恰当，请随时通过向 Crowdin 词汇表添加新术语来恢复您的译文。
- 如果词汇表中之前没有翻译，我们建议您在搜索引擎或媒体文章中查找，显示该术语在社区中的实际使用情况。
- 如果根本找不到任何参考资料，请按您的直觉和理解翻译成自己的语言！
- 如果不太确定，可以不翻译这一术语。 有时，英语术语足以提供准确定义。

我们建议不翻译品牌、公司和人员名称，因为翻译可能会造成不必要的混乱和 SEO 困难。

## 联系我们 {#contact}

感谢阅读所有内容。 我们希望这对您加入我们的项目有所帮助。 欢迎加入我们的[Discord 翻译频道](https://discord.gg/TkJFaewsaM)，提出问题并与其他翻译者合作！
