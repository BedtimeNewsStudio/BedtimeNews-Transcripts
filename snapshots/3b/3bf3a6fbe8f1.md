---
source_url: "https://web.vip.miui.com/page/info/mio/mio/detail?fromPathname=mioSingleBoard&postId=52299728"
captured_at: 2026-11-08T08:11:36Z
title: "Xiaomi miclaw，今日开启小范围封测"
tool: firecrawl
---

> **网页快照**：2026-11-08 08:11 UTC 抓取自 [原始页面](https://web.vip.miui.com/page/info/mio/mio/detail?fromPathname=mioSingleBoard&postId=52299728)（工具：firecrawl）。

# Xiaomi miclaw，今日开启小范围封测

Xiaomi miclaw，今日开启小范围封测

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)
小米技术

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![勋章](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

小米官方账号 · PC端

![](https://cdn.cnbj1.fds.api.mi-img.com/vip/fffb788fe0383dce4698d6d6da60e505a7a24a9f8345e9853e51e1183224ab06?thumb=1&w=96&q=80&f=webp)![帖子贴图](https://cdn.cnbj1.fds.api.mi-img.com/vip/fffb788fe0383dce4698d6d6da60e505a7a24a9f8345e9853e51e1183224ab06?thumb=1&w=1080&q=80&f=webp)

Xiaomi miclaw 是我们探索 Agent 的一小步，它是基于小米 MiMo 大模型构建的 AI 交互测试产品，今天开始小范围封闭测试。Xiaomi miclaw 聚焦验证大模型在小米“人车家全生态”系统中的执行能力，探索模型从“对话能力”向“系统级执行能力”的落地路径。它的能力来自四个层次：系统底层能力、个人上下文理解、生态互联、自进化。

它能让手机成为 AI 的工具，在理解你的意图和给予授权后，调用一方应用、生态能力，也能自主选择系统级工具，完成你的命令。它能认识你、记住你，也能判断你一句模糊的任务，帮你完成操作。它还能持续成长，能够调整自己的行为，也能扩展自己的能力，最后通过记忆系统把经验沉淀下来，越用越懂你。

由于这是一个前沿探索型产品，在稳定性、功耗表现与复杂场景执行成功率方面仍在持续优化过程中。部分高复杂度任务可能存在执行效率波动或阶段性失败的情况。本次封测不公开招募，采用邀请制。再次提示，不推荐在日常主力设备上升级，建议科技发烧友、 AI 重度用户事先做好数据安全备份，在可控环境中测试、体验。

## 01 系统底层能力：让 AI 有手有脚

### ▍为什么系统身份是前提

Xiaomi miclaw 以系统应用身份运行，拥有系统核心应用能力。

运行在应用沙箱内的 AI，无论模型多强，主要能做的事就是回答问题和联网搜索。系统级 AI 不一样，它能提供系统级的操控。

### ▍50+ 系统级工具

Xiaomi miclaw 把手机的系统能力封装成了 **50+** 系统能力和生态服务（不断扩展中）：

![](https://cdn.cnbj1.fds.api.mi-img.com/vip/1aadc0db4034661284d01420b56b99a9101d2183d598ce0ae2b7d156543d0df0?thumb=1&w=96&q=80&f=webp)![帖子贴图](https://cdn.cnbj1.fds.api.mi-img.com/vip/1aadc0db4034661284d01420b56b99a9101d2183d598ce0ae2b7d156543d0df0?thumb=1&w=1080&q=80&f=webp)

每个工具接收结构化参数，返回执行结果。哪些工具可用取决于用户授权了哪些权限。

### ▍基于大模型的推理-执行引擎

有工具还不够。关键是让模型自己决定调用顺序。Xiaomi miclaw 的核心引擎是一个推理-执行循环：

> 用户输入 → 模型推理（选工具、定参数）→ 工具执行 → 结果回传 → 模型继续推理 → ... → 任务完成，输出回复

模型在每一步自己判断：该调哪个工具，传什么参数，做完了没有。工具执行有独立超时保护，全程异步架构，不阻塞系统线程。

底层对主流大模型协议做了统一抽象，换模型不用改上层逻辑。用户端的体验是流式更新：能看到 AI 正在调哪个工具、执行到哪一步。

### ▍上下文管理：多轮对话不丢线索

长对话不掉线，多轮工具调用最怕“聊着聊着忘了初心”。Xiaomi miclaw采用三级智能记忆管理：自动保留关键决策点，动态压缩冗余交互，核心指令本地缓存优化。即使连续执行20步复杂操作，AI依然记得你最初的需求背景，无需重复解释，让深度服务从一而终连贯顺畅。

- **轮次压缩**：老对话整体压缩，突出最近的交互

- **Token** **压缩**：逼近上下文窗口上限时，按消息粒度智能压缩

同时，系统提示词采用多级设计，动态信息注入到首条用户消息。这个设计让提示词部分可以被模型缓存，实测节省 **50-90%** 的 token 开销。

## 02 个人上下文：让 AI 真正理解你

### ▍从"你说了什么"到"你过着什么生活"

一般的AI助手缺少足够的上下文语境，几乎只关注你发给它的那条消息。Xiaomi miclaw 在经过用户授权后，基于你的使用习惯给你提供服务。

### ▍"感知→关联→判断→行动"

普通应用只有"感知→行动"：收到通知，显示通知。Xiaomi miclaw 在中间加了两步，包括关联和判断，这是 AI Agent 和传统软件的分界线。

**场景：出行自动准备**

收到推送"购票成功 G1234 北京→成都 周五 08:30"。接下来发生了什么：

![](https://cdn.cnbj1.fds.api.mi-img.com/vip/c6f7f17f2fe8506a5c21c3aad8b9ab5765c68d38ecc7dfffe015a92710ec8dd6?thumb=1&w=96&q=80&f=webp)![帖子贴图](https://cdn.cnbj1.fds.api.mi-img.com/vip/c6f7f17f2fe8506a5c21c3aad8b9ab5765c68d38ecc7dfffe015a92710ec8dd6?thumb=1&w=1080&q=80&f=webp)

![](https://cdn.cnbj1.fds.api.mi-img.com/vip/361710f6b2f7c2df02b734a718f535044402f69e268f249fcb75b579f5687632?thumb=1&w=96&q=80&f=webp)![帖子贴图](https://cdn.cnbj1.fds.api.mi-img.com/vip/361710f6b2f7c2df02b734a718f535044402f69e268f249fcb75b579f5687632?thumb=1&w=1080&q=80&f=webp)

**7** 步自动完成，串联了 **6** 个工具。这里面模型的推理能力当然重要，但前提是 AI 能读到你的短信和日历。

**场景：消费洞察**

银行扣费短信 → AI 读取近 3 个月短信 → 关联历史发现两个视频平台同时在扣月费 → 判断内容重叠 → 月底推送消费简报，建议退订其中一个，每年省近 **400** 元。

### ▍数据安全

数据处理的基本原则：对话历史、用户配置、技能文件都存在设备本地，云端只在推理时传输当前对话消息，且数据在传输过程中经过加密，确保用户数据的安全和隐私。操作敏感的工具（如发短信、建日程）每次执行前会弹确认框。

## 03 生态互联：从一台手机到整个智能生活

### ▍当 AI 能帮助你控制家庭设备

前两章讲的都是手机本身。第三层把 AI 的手伸到手机之外，接入小米 IoT 生态。

米家平台连接了超过 10亿台设备 。Xiaomi miclaw 实现了完整的米家协议客户端，可以读取设备状态、发送控制指令，在用户授权的情况下，理论上能控制所有用户接入米家的 IoT 设备

这个协议客户端的关键工作是"翻译"：IoT 设备的能力定义通常是一套机器可读的规格描述（参数类型、取值范围、约束条件），Xiaomi miclaw 把它编译成大模型能理解的自然语言参数说明。经过翻译，模型看到的是"打开客厅空调，参数：开关（开/关）"这样的自然语言描述。

### ▍场景：家庭办公模式联动

日历事件"10:00 重要客户会议" → AI 判断需要安静环境：

- 手机自动静音

- 扫地机暂停

- 来电按紧急程度区分：老板来电震动提醒，快递员静默记录

- 会后恢复所有设备状态，推送未接来电和消息摘要

传统智能家居靠预设规则，Xiaomi miclaw 不同，AI 根据当前上下文实时判断该做什么。同样的"有会议"，如果是内部周会，AI 可能只静音手机；如果是重要客户到访，才会联动全屋设备。判断依据是什么？日程里写的是"重要客户"还是"周会"，你以前开会时的习惯，加上当前家里设备的状态。

### ▍开放协议扩展

生态不止于小米自有设备。两个开放通道让第三方也能接进来：

**MCP** **（** **Model Context Protocol** **）**：AI 工具集成的开放标准。Xiaomi miclaw 实现了完整的 MCP 客户端，支持标准化通信协议、流式响应和异步服务发现。PC 上已有的数千个 MCP 工具，理论上可以直接接入手机 AI。

**开放** **SDK**：Xiaomi miclaw 发布了第三方应用接入 SDK，通过签名级权限保护确保安全。第三方 App 主动声明自己能提供的工具能力，Xiaomi miclaw 动态发现和调用。适配关系反过来了：App 主动告诉 AI "我能做什么"，AI 按需调用。

## 04 自进化：AI 能力的持续增长

以上三层是 Xiaomi miclaw 出厂时就有的能力。但还有一点更值得说： **它能做的事不是出厂时就定死的。**

Xiaomi miclaw 的元能力，简单说就是"创造工具的工具"：

1. **文件级记忆** → 创造任意数据结构。AI 用这个能力自主设计了记忆系统：创建记忆目录、定义存储格式、写入检索规则。用得越多，它越了解你的偏好、常用联系人、历史任务。

2. **子** **智能体** **创建** → 专业分工。每个子智能体有独立提示词和工具白名单，在权限沙箱内独立执行。你可以有一个专门管日程的子智能体、一个专门做信息摘要的子智能体。

3. **MCP** **服务配置** → 动态接入外部能力，随时扩展可调用的工具范围。

4. **脚本执行** → 沙箱运行 Python/JavaScript，具备通用编程能力。

这 4 种能力叠在一起，Xiaomi miclaw 就有了一条成长路线：先是调整自己的行为（改提示词和文件），再扩展自己的能力（造子智能体、接 MCP），最后通过记忆系统把经验沉淀下来，越用越懂你。

没有人预先写好这些流程。AI 拿到基础工具，自己组合出了更高阶的用法。

## 写在最后

有系统底层能力才能“动手”，有个人上下文才能理解你，有生态互联才能管到手机之外。而自进化，让这些能力不断强大。

当大模型真正长进手机系统里，手机本身就变成了 AI 的身体的一部分。

## 场景演示

注：以下视频在开启演示模式下录屏，并经过加速剪辑处理

**1.欢迎回家**

1.问题：我半个小时后带我的朋友贝贝回家，给家里准备一下，热烈欢迎下贝贝

2.回答：

正在加载 视频播放器。

播放视频

播放

静音

当前时间 0:00

/

时长 0:00

加载完成: 0%

0:00

尝试直播，当前为延时播放直播

剩余时间 -0:00

1x

播放速度

- 2x
- 1.5x
- 1x, 选择
- 0.5x

节目段落

- 节目段落

描述

- 关闭描述, 选择

字幕

- 字幕设定, 开启字幕设置弹窗
- 关闭字幕, 选择

音轨

画中画

打开对话窗口。Escape键将取消并关闭对话窗口

文字Color白黑红绿蓝黄紫红青Transparency不透明半透明背景Color黑白红绿蓝黄紫红青Transparency不透明半透明透明窗口Color黑白红绿蓝黄紫红青Transparency透明半透明不透明

字体尺寸50%75%100%125%150%175%200%300%400%字体边缘样式无浮雕压低均匀下阴影字体库比例无细体单间隔无细体比例细体单间隔细体舒适手写体小型大写字体

重置 恢复全部设定至预设值完成

关闭弹窗

结束对话窗口

![封面](https://cdn.cnbj1.fds.api.mi-img.com/vip/67c83db3a7249381af6a7c2fa486243232e016d1c21a0e74ac92a5aa30fb3444?thumb=1&w=1920&q=80&f=webp)
点击重新加载

**2\. 检查耗材**

1.问题：我就在小米之家，看看我家里缺啥耗材

2.回答：

正在加载 视频播放器。

播放视频

播放

静音

当前时间 0:00

/

时长 0:00

加载完成: 0%

0:00

尝试直播，当前为延时播放直播

剩余时间 -0:00

1x

播放速度

- 2x
- 1.5x
- 1x, 选择
- 0.5x

节目段落

- 节目段落

描述

- 关闭描述, 选择

字幕

- 字幕设定, 开启字幕设置弹窗
- 关闭字幕, 选择

音轨

画中画

打开对话窗口。Escape键将取消并关闭对话窗口

文字Color白黑红绿蓝黄紫红青Transparency不透明半透明背景Color黑白红绿蓝黄紫红青Transparency不透明半透明透明窗口Color黑白红绿蓝黄紫红青Transparency透明半透明不透明

字体尺寸50%75%100%125%150%175%200%300%400%字体边缘样式无浮雕压低均匀下阴影字体库比例无细体单间隔无细体比例细体单间隔细体舒适手写体小型大写字体

重置 恢复全部设定至预设值完成

关闭弹窗

结束对话窗口

![封面](https://cdn.cnbj1.fds.api.mi-img.com/vip/a2edfd9321fdd08f8cd92039b6166462701d59203b628459aea783169d83d6b1?thumb=1&w=1920&q=80&f=webp)
点击重新加载

**3.体重控制**

1.问题：看我相册里拍的食物的照片，下周帮我减掉3kg体重

2.回答：

正在加载 视频播放器。

播放视频

播放

静音

当前时间 0:00

/

时长 0:00

加载完成: 0%

0:00

尝试直播，当前为延时播放直播

剩余时间 -0:00

1x

播放速度

- 2x
- 1.5x
- 1x, 选择
- 0.5x

节目段落

- 节目段落

描述

- 关闭描述, 选择

字幕

- 字幕设定, 开启字幕设置弹窗
- 关闭字幕, 选择

音轨

画中画

打开对话窗口。Escape键将取消并关闭对话窗口

文字Color白黑红绿蓝黄紫红青Transparency不透明半透明背景Color黑白红绿蓝黄紫红青Transparency不透明半透明透明窗口Color黑白红绿蓝黄紫红青Transparency透明半透明不透明

字体尺寸50%75%100%125%150%175%200%300%400%字体边缘样式无浮雕压低均匀下阴影字体库比例无细体单间隔无细体比例细体单间隔细体舒适手写体小型大写字体

重置 恢复全部设定至预设值完成

关闭弹窗

结束对话窗口

![封面](https://cdn.cnbj1.fds.api.mi-img.com/vip/fc889848aa92668cdd914285426cd74e2579b5639764479a79920aafac1e835c?thumb=1&w=1920&q=80&f=webp)
点击重新加载

**4.起床毁灭**

1.问题：明天早上7点叫醒我，起不来你就使劲折腾

2.回答：

正在加载 视频播放器。

播放视频

播放

静音

当前时间 0:00

/

时长 0:00

加载完成: 0%

0:00

尝试直播，当前为延时播放直播

剩余时间 -0:00

1x

播放速度

- 2x
- 1.5x
- 1x, 选择
- 0.5x

节目段落

- 节目段落

描述

- 关闭描述, 选择

字幕

- 字幕设定, 开启字幕设置弹窗
- 关闭字幕, 选择

音轨

画中画

打开对话窗口。Escape键将取消并关闭对话窗口

文字Color白黑红绿蓝黄紫红青Transparency不透明半透明背景Color黑白红绿蓝黄紫红青Transparency不透明半透明透明窗口Color黑白红绿蓝黄紫红青Transparency透明半透明不透明

字体尺寸50%75%100%125%150%175%200%300%400%字体边缘样式无浮雕压低均匀下阴影字体库比例无细体单间隔无细体比例细体单间隔细体舒适手写体小型大写字体

重置 恢复全部设定至预设值完成

关闭弹窗

结束对话窗口

![封面](https://cdn.cnbj1.fds.api.mi-img.com/vip/4d0bc9202d6b2f6f4ea148c4d88863bc833323ddca4d6d424081912af3d7c37e?thumb=1&w=1920&q=80&f=webp)
点击重新加载

**5.每日播报**

1.问题：每天早上8:16向我进行语音播报，提醒我当天的日程，然后再搜索3~4条

与 Al 和财经相关的新闻，其它的内容你可以自由发挥

2.回答：

正在加载 视频播放器。

播放视频

播放

静音

当前时间 0:00

/

时长 0:00

加载完成: 0%

0:00

尝试直播，当前为延时播放直播

剩余时间 -0:00

1x

播放速度

- 2x
- 1.5x
- 1x, 选择
- 0.5x

节目段落

- 节目段落

描述

- 关闭描述, 选择

字幕

- 字幕设定, 开启字幕设置弹窗
- 关闭字幕, 选择

音轨

画中画

打开对话窗口。Escape键将取消并关闭对话窗口

文字Color白黑红绿蓝黄紫红青Transparency不透明半透明背景Color黑白红绿蓝黄紫红青Transparency不透明半透明透明窗口Color黑白红绿蓝黄紫红青Transparency透明半透明不透明

字体尺寸50%75%100%125%150%175%200%300%400%字体边缘样式无浮雕压低均匀下阴影字体库比例无细体单间隔无细体比例细体单间隔细体舒适手写体小型大写字体

重置 恢复全部设定至预设值完成

关闭弹窗

结束对话窗口

![封面](https://cdn.cnbj1.fds.api.mi-img.com/vip/ae48cfe752d3ff4869224e0a615a2f57498d60245d8a10198c7d9fc4f37c17ca?thumb=1&w=1920&q=80&f=webp)
点击重新加载

**6.理财雷达**

1.问题：你能帮我关注一下现货行黄金的价格吗？每两分钟向我播报一次

2.回答：

正在加载 视频播放器。

播放视频

播放

静音

当前时间 0:00

/

时长 0:00

加载完成: 0%

0:00

尝试直播，当前为延时播放直播

剩余时间 -0:00

1x

播放速度

- 2x
- 1.5x
- 1x, 选择
- 0.5x

节目段落

- 节目段落

描述

- 关闭描述, 选择

字幕

- 字幕设定, 开启字幕设置弹窗
- 关闭字幕, 选择

音轨

画中画

打开对话窗口。Escape键将取消并关闭对话窗口

文字Color白黑红绿蓝黄紫红青Transparency不透明半透明背景Color黑白红绿蓝黄紫红青Transparency不透明半透明透明窗口Color黑白红绿蓝黄紫红青Transparency透明半透明不透明

字体尺寸50%75%100%125%150%175%200%300%400%字体边缘样式无浮雕压低均匀下阴影字体库比例无细体单间隔无细体比例细体单间隔细体舒适手写体小型大写字体

重置 恢复全部设定至预设值完成

关闭弹窗

结束对话窗口

![封面](https://cdn.cnbj1.fds.api.mi-img.com/vip/a150c77594bd58e61044dc38e1e279787982a6771729a8143138186538a5edb1?thumb=1&w=1920&q=80&f=webp)
点击重新加载

03-05 ·

来自小米社区 ·

浏览

8.9万+

全部评论 1060

热门

最新

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

拿铁不加美式

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

Xiaomi 17 Pro Max · OS3.0.300.9 Beta

想加入内测

03月06日 04:43 · 北京

17

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

SheldonLiu18

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

Xiaomi 12 Pro · OS3.0.2.0 正式版

我也想加入内测

03月06日 00:24 · 山西

12

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

瑞烨烨

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

OS3.0.300.10 Beta

资深OpenClaw重度使用者，七天tokens使用量3亿，申请加xiaomi miclaw 看过豆包手机之后对于ai手机智能管家有着充分和向往并且正在使用米家用AI很频繁希望可以给到我一个测试机会。并且后续会参与需要的反馈与调研。谢谢

03月07日 23:51 · 河南

10

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

Mi:xA5N7h

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

Xiaomi 17 Pro Max · OS3.0.45.0 正式版

老米粉了，求邀请

![评论图片](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

03月07日 10:53 · 广东

6

- ![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

迷曼陀罗

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

REDMI K80 至尊版 · OS3.0.303.0 正式版

等级太低了

07月08日 13:14 · 上海

赞

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

Mi:1A7gmO

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

REDMI K90 · OS3.0.24.0 正式版

AI产品经理申请内测，日常负责企业AI中台，包括智能体、知识库、数据库等平台。

03月06日 06:11 · 山东

5

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

Nyan\_Hikari

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

Xiaomi 17 Pro Max · OS3.0.45.0 正式版

本17PM机主申请参与封测😉

如果有识别教务系统的课表并能根据课程时间智能化地开启和关闭消息免打扰等功能就好了，期待一波

03月06日 02:38 · 浙江

5

- ![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

Nyan\_Hikari

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

Xiaomi 17 Pro Max · OS3.0.45.0 正式版

回复 Mi:u9cqlAj：每次都要自己点那个小爱建议，而且只是静音不是免打扰，下课自动恢复，有时候忘了上课就会响😢

03月23日 08:33 · 浙江

赞

- ![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

Mi:u9cqlAj

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

REDMI K80 至尊版 · OS3.0.9.0 正式版

现在就有啊

03月22日 20:55 · 内蒙古

1

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

吃喵酱的九节狼

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

内测资格在哪获取？哪位大神能分享一下

03月12日 06:00 · 四川

3

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

Mi:nAPGSC

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

OS3.0.45.0 正式版

申请加入

03月09日 03:45 · 安徽

2

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

youyou383856

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

我也想参与内测

03月06日 22:22 · 内蒙古

2

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

Mi:u6UF1qa

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

Xiaomi 17 Pro Max · OS3.0.45.0 正式版

怎么加入啊

03月06日 02:15 · 浙江

2

展开更多评论
![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)
小米技术

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

Xiaomi miclaw 本周更新各位参与封测的用户们好， 本周，Xiaomi miclaw 迎来一次重要更新。 作为国内首款手机端 AI 智能体应用，自上线以来，我们收获了众多用户的积极反馈与宝贵建议。本期更新聚焦三大方面：新功能上线、体验优化与问题修复，力求为大家带来更流畅、更强大的使用感受。 此外，我们将新增覆盖三款机型：Xiaomi 15S Pro、REDMI K90和REDMI K90 Pro Max。 一、本周手机端 Xiaomi miclaw 更新日志 【新功能】 - 智能家居扩展：新增摄像头配置、共享家庭设备支持、国家/地区选择 - 第三方 MCP 服务接入：增加部分三方 APP MCP 接入服务，同时支持连接

03-13 · PC端

67

58

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)
小米技术

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

Xiaomi miclaw上线PC、Mac和有屏音箱版，正式开启多终端小范围封测今天，我们将正式开启PC、Mac和有屏音箱版Xiaomi miclaw小范围封测，上午10:00起，用户即可前往小米社区申请测试资格。Xiaomi miclaw是基于小米 MiMo 大模型构建的 AI 交互测试产品，也是国内首款手机端AI智能体应用，于3月6日上线并开启小范围封测。 本次封测新增Xiaomi miclaw PC及Mac版，作为基于小米 MiMo 大模型构建的桌面端 AI Agent 测试产品，该产品将 miclaw 的系统级执行能力延伸到PC和Mac平台，支持文档整理、数据分析、批量文件处理等桌面场景，并可与手机端 miclaw 跨设备协作 —— 在电脑上说一句话，就能自动调度

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

04-20 · PC端

24

49

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)
小米技术

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

Xiaomi miclaw 封测 QA01 什么是Xiaomi miclaw？ Xiaomi miclaw是基于小米 MiMo 大模型构建的 AI 交互测试产品。该产品聚焦验证大模型在小米“人车家全生态”系统中的执行能力，探索模型从“对话能力”向“系统级执行能力”的落地路径。 作为技术探索项目，当前该产品在稳定性、功耗表现、复杂场景执行成功率方面仍在持续优化过程中，仅面向科技发烧友、极客用户开放，通过小规模测试，持续优化执行稳定性与能力边界。同时，部分高复杂度任务可能存在执行效率波动或阶段性失败的情况。因此，我们不推荐普通用户在日常主力设备上升级。当前，Xiaomi miclaw 仅是面向科技发烧友、极客用户的小规模测试性探索产品

03-05 · PC端

626

221

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)
小米技术

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

2026首届openvela AI硬件开发者大赛火热报名中AI 硬件爆发时代，开发者亟需高成熟度、低功耗、原生智能的系统基座。openvela 作为小米开源 AIoT 操作系统，经亿级量产设备落地验证，搭载全栈系统智能引擎，成为全球 AI 硬件开发者优选操作系统。 本届大赛面向全球开发者开放报名，全程不设固定命题、不限创新方向，支持选手自由发挥、大胆创作。选手可依托 openvela 操作系统，不限领域、不限形态开展 AI 硬件创新，可参考：全新硬件平台底层适配、沉浸式智能交互、可穿戴智能应用等方向；官方配套全套技术赋能资源，助力开发者探索更多全新 AI 硬件产品形态，推动技术创新落地与生态商业化发展。 赛事全程 4 个月，设置线上初赛、线下决赛、现

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

07-07 · PC端

9

49

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

晨末莫

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

我找到了继续使用miclaw电脑版的方法。有没有谁还有手机版的第一个版本miclawapk，我想试试。

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

10-09 · Xiaomi 17 Pro Max

16

3

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

一笑^\_^倾城

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

感谢陪伴，短暂的道别为了更好的再次相见

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

10-03 · Xiaomi 17 Pro

4

7

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

刘夏桐

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

这是啥呀？

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

10-04 · REDMI K90

2

3

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

wangyoucao07421

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

你得赔我五毛

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

10-02 · Xiaomi 15

7

5

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

Savingao

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

Mino该怎么免费使用啊，就只有那个🦞可以免费用3小时吗

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

09-26 · Xiaomi 17 Pro Max

3

2

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

小马1107

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![活动图标](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

关注作者

发个帖子纪念一下

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/lazyLoad.1d52a851.png)

09-23 · Xiaomi 18 Pro Max

168

223

加载失败，点击重试

![用户头像](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/defaultMedia/default-avatar.d19eb0f3.svg)

登录后才可评论

154

1107

384

![头像](https://cdn.cnbj1.fds.api.mi-img.com/middle.community.vip.bkt/d64dffe8b3064416242f9fb421e88daf)

小米技术

永远相信美好的事情即将发生

0关注

3325粉丝

48动态

热门帖子

换一批

![](https://cdn.vip-community.miui.com/vip--mifans-lts/prod/v313/static/media/logo.bb74fc6c.svg)

### 下载小米社区APP

千万米粉的大本营

©xiaomi.cn

小米集团隐私政策 \| 小米社区隐私政策 \| 用户协议

京ICP备10046444号-1

京公安网备11010802037410

发表评论

创作声明

**AI合成内容** 在这里声明

包含AI合成内容

暂不选择

发布

取消

```
删除评论后不可恢复
```

取消

确认

```
确定屏蔽该评论？
```

取消

确认