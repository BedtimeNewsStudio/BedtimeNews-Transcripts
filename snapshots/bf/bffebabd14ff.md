---
source_url: "https://wallstreetcn.com/articles/3765648"
captured_at: 2026-11-16T10:06:38Z
title: "MiniMax发布M2.5模型：1美元运行1小时，价格仅为GPT-5的1/20，性能比肩Claude Opus - 华尔街见闻"
tool: tavily
---

> **网页快照**：2026-11-16 10:06 UTC 抓取自 [原始页面](https://wallstreetcn.com/articles/3765648)（工具：tavily）。

# MiniMax发布M2.5模型：1美元运行1小时，价格仅为GPT-5的1/20，性能比肩Claude Opus - 华尔街见闻

### 大家都在搜

# MiniMax发布M2.5模型：1美元运行1小时，价格仅为GPT-5的1/20，性能比肩Claude Opus

![](https://wpimg-wscn.awtmt.com/e6a5af79-24ca-42e8-a006-fbfff2f4a4be?imageView2/1/w/24/h/24)

MiniMax推出了其最新迭代的M2.5系列模型，在保持行业领先性能的同时，大幅降低了推理成本，试图解决复杂Agent应用在经济上不可行的痛点，并宣称其在编程、工具调用及办公场景中已达到或刷新了行业SOTA（当前最佳）水平。

2月13日，MiniMax公布的数据显示，M2.5展现了显著的价格优势。在每秒输出50个token的版本下，其价格仅为Claude Opus、Gemini 3 Pro以及GPT-5等主流模型的1/10至1/20。

**在每秒输出100个token的高速运行环境下，M2.5连续工作一小时的成本仅需1美元，若降至50 token/秒，成本进一步下探至0.3美元**。这意味着1万美元的预算足以支撑4个Agent连续工作一年，极大地降低了构建和运营大规模Agent集群的门槛。

在性能维度，**M2.5在核心编程测试中表现强劲，并在多语言任务Multi-SWE-Bench上取得第一，整体水平比肩Claude Opus系列。**同时，**模型优化了对复杂任务的拆解能力**，在SWE-Bench Verified测试中，**完成任务的速度较上一代M2.1提升了37%**，端到端运行时间缩短至22.8分钟，**与Claude Opus 4.6持平**。

目前，MiniMax内部业务已率先验证了该模型的能力。数据显示，**其内部30%的整体任务已由M2.5自主完成，覆盖研发、产品、销售等核心职能**。特别是在编程场景中，M2.5生成的代码已占据新提交代码的80%，显示出该模型在真实生产环境中的高渗透率和可用性。

## 击穿成本底线：无限运行Agent的经济可行性

M2.5的设计初衷是消除运行复杂Agent的成本约束。MiniMax通过优化推理速度和token效率实现了这一目标。模型提供100 TPS（每秒传输事务处理量）的推理速度，约为当前主流模型的两倍。

除了单纯的算力成本降低，M2.5通过更高效的任务拆解和决策逻辑，减少了完成任务所需的token总量。

在SWE-Bench Verified评测中，**M2.5平均每个任务消耗3.52M token，低于M2.1的3.72M。**

速度与效率的双重提升，使得企业在经济上几乎可以无限制地构建和运营Agent，将竞争焦点从成本转移至模型能力的迭代速度上。

## 编程能力进阶：像架构师一样思考与构建

在编程领域，M2.5不仅关注代码生成，更强调系统设计能力。模型演化出了原生的Spec（规格说明书）行为，能够以架构师视角在编码前主动拆解功能、结构和UI设计。

该模型在超过10种编程语言（包括GO、C++、Rust、Python等）和数十万个真实环境中进行了训练。

**测试显示，M2.5能胜任从系统设计（0-1）、开发（1-10）到功能迭代（10-90）及最终代码审查（90-100）的全流程。**

为了验证其在不同开发环境下的泛化性，MiniMax在Droid和OpenCode等编程脚手架上进行了测试。

**结果显示，M2.5在Droid上的通过率为79.7，在OpenCode上为76.1，均优于上一代模型及Claude Opus 4.6。**

**![](https://wpimg-wscn.awtmt.com/83ba5a06-fe24-4023-9b01-fe8ab9235ad9.png?imageView2/2/w/680)**

![](https://wpimg-wscn.awtmt.com/83ba5a06-fe24-4023-9b01-fe8ab9235ad9.png?imageView2/2/w/680)

## 复杂任务处理：更高效的搜索与专业交付

在搜索和工具调用方面，**M2.5展示了更高的决策成熟度，不再单纯追求“做对”，而是寻求以更精简的路径解决问题。**

在BrowseComp、Wide Search和RISE等多项任务中，M2.5相较于前代节省了约20%的轮次消耗，以更优的token效率逼近结果。

![](https://wpimg-wscn.awtmt.com/64d74851-df89-4a16-9a96-52f037ef189b.png?imageView2/2/w/680)

![](https://wpimg-wscn.awtmt.com/64d74851-df89-4a16-9a96-52f037ef189b.png?imageView2/2/w/680)

针对办公场景，MiniMax通过与金融、法律等领域资深从业者合作，将行业隐性知识融入模型训练。

在内部构建的Cowork Agent评测框架（GDPval-MM）中，M2.5在与主流模型的两两对比中取得了59.0%的平均胜率，能够输出符合行业标准的Word研报、PPT及复杂的Excel财务模型，而非简单的文本生成。

![](https://wpimg-wscn.awtmt.com/eb3035da-6988-4f4a-99c6-af524c5574bd.png?imageView2/2/w/680)

![](https://wpimg-wscn.awtmt.com/eb3035da-6988-4f4a-99c6-af524c5574bd.png?imageView2/2/w/680)

![](https://wpimg-wscn.awtmt.com/9675292f-2269-4b00-b0fc-92627253f960.png?imageView2/2/w/680)

![](https://wpimg-wscn.awtmt.com/9675292f-2269-4b00-b0fc-92627253f960.png?imageView2/2/w/680)

## 技术底座：原生Agent RL框架驱动线性提升

M2.5性能提升的核心驱动力来自于大规模强化学习（RL）。

MiniMax采用了名为Forge的原生Agent RL框架，通过引入中间层解耦了底层训推引擎与Agent，支持任意脚手架的接入。

在算法层面，MiniMax沿用了CISPO算法以保障MoE模型在大规模训练中的稳定性，并针对Agent长上下文带来的信用分配难题，引入了过程奖励机制（Process Reward）。

此外，**工程团队优化了异步调度策略和树状合并训练样本策略，实现了约40倍的训练加速**，验证了模型能力随算力和任务数增加呈现近线性提升的趋势。

![](https://wpimg-wscn.awtmt.com/22495de7-68e3-4f74-b9b0-fc2dc87475a9.png?imageView2/2/w/680)

![](https://wpimg-wscn.awtmt.com/22495de7-68e3-4f74-b9b0-fc2dc87475a9.png?imageView2/2/w/680)

目前，M2.5已在MiniMax Agent、API及Coding Plan中全量上线，其模型权重也将在HuggingFace开源，支持本地部署。

![华尔街见闻](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADwAAAA8CAYAAAA6/NlyAAAACXBIWXMAACE4AAAhOAFFljFgAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAARySURBVHgB5ZuBedsqEMfx+zqAR9AGSTagG/htoA2qN0HUCZo3gdIJmk6AO0HSCXAnSDb4FyyUYgIcks6y8vX3fZfYEidxCO4OjDbiTADYmn/SSGXkysi1ka377nNw8mLkp5G9kafNZvMi1o410sitEYX5KCONkUqsDVMpCR4jc8ZLcWkWMDREG9mJpTE3rRY2NKTDUl3d3OiTkWdcHm2kFucCvUP6gvXxZYwdm5JC6EOMEn1oWSNPRv41oexAFSQNRj9WrLGVWDcHIx8po7MGvyNjBw5GbnJJyz8izzfxfoy1VEaUG4JRkgY7Z7DWMZvD1vk2dTLapdG7+04szyFybOtkLP+Zrn1HlkKfVGhcho6xLjZXqEoM7nBZGsa6qNC+D4GxNk+txTxenIxl6Lovri4VQ11sri9N195Hz4KvK9+W1ginebn2jnfgQaVuLMFLkdPD6SSkO0PjWyR1Yy6aAoN9KnesDo5rQiiUiHSrc2A95bbQYEU0/m1Ed4vyB7X1FRucj4YwWLlyO/f9OnOtOtDtUE4bu+k5UITBO5Q7qwev3NheeazHB/xZXaQYG26GMJMNDeb4gzn/aoQoD0XFkcAhj7ZinHcummy71vdXRb4V6tXE/Wvv+lPYWeUW41AFFb8LdEjn5fR05r56RMOkaOxs6UqMw/aIVozDGks5LynyU9G993lsdx64muqwnnNXRXyYUDodcc8qc+1SHudkNDvCABXRkYmyw5hMrYaqEQ2TQwtMpyTcFOmgXw3VSPuTXdAwk5ljsEVmDLZZUOyJXUfKavSOKKbD4axeoda0KJLd2i2k/U/poA81lZG90/kalP/sfZ7qrE5uOIdsuEH/xLI66Me6P0sKnVKVOD4JjmlYSzSoiug07twwJmVCx2+IDvM5Oq1HzEMTBseejPKM0BGdYazKoGHmouzF7jEfSRjtN6qdmdluvXP/60h5OxQeve8teHjgmhpSIWqo8HH8ok89n5HxATgd5xo8tKl4OYUqY/AQbjr3fejm5DIQY/0s0oalveChTp3wws3n4NQvQfNJ8PF0/AueBQAyRHmfu0EnVzvwLj0dh92QePwQ87EG1amTwy96OJ3k264uRZr5icYfvr9+QjxBmNyKOfA2PVSZshp8VOHFFXiQhME6orMtaJg5qFhFWFI3ZJZzkPa4baSsAh8yVSEFHrYjr/8clON0VulMEHxPuY1cmzJCemU78JHfyAamEBW5bkfo+KsaGjzQv2/h7RLrVMJ5ry7QsdGCy1lplO7WA3N+jXIjFPiebi3GgLdry1OQ7loKy3KXsovap2WnaHN28tyLPotbcoOM3Vx+kzpJGWzDizW6Eu+DgyB242UX8Vz++1HEtxOtjYMo2HpIrlq6C1ijn8R6sXW7KdlcOgrwODJubJ2mbFwrNtqGGI3LY3OFRiwB+uTkHpdD4RJvu8BtV8ByKPwlb7eoVRgagr6rN+B7UasFs0MqeudhCq6iNkuTot9lMLyGVwVFD6LfLGNDy0/3fX+uV/F+Aw9RZTJKNsjQAAAAAElFTkSuQmCC)
