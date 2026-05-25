<div align="center">

<!-- Banner -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,30&height=180&section=header&text=lanshu-awesome-ai-video-kit&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=AI%20Video%20Prompt%20Engineering%20·%2015%20Models%20·%20301%20Prompts&descSize=16&descAlignY=62&descColor=cccccc">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,30&height=180&section=header&text=lanshu-awesome-ai-video-kit&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=AI%20Video%20Prompt%20Engineering%20·%2015%20Models%20·%20301%20Prompts&descSize=16&descAlignY=62&descColor=ffffff" alt="banner" width="100%">
</picture>

# 🎬 lanshu-awesome-ai-video-kit

**An awesome curated kit for AI video prompt engineering.**
**全网最全的 AI 视频提示词工程库 — 15 大主流模型(11 商业 + 4 开源) / 301 分散 + 110 跨模型对照 = 411 prompt / 7 Claude Skill / 14 篇方法论**

🌍 **[English README →](README.en.md)**

<p>
  <img alt="Awesome" src="https://img.shields.io/badge/-Awesome-fc60a8?style=flat&logo=awesome-lists&logoColor=white">
  <img alt="Models" src="https://img.shields.io/badge/models-15-8b5cf6?style=flat">
  <img alt="Prompts" src="https://img.shields.io/badge/prompts-301-f97316?style=flat">
  <img alt="Skills" src="https://img.shields.io/badge/skills-7-06b6d4?style=flat">
  <img alt="Docs" src="https://img.shields.io/badge/methodology-14-34d399?style=flat">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-cccccc?style=flat">
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-9333ea?style=flat">
</p>

<p>
  <a href="#-快速上手">🚀 快速上手</a> ·
  <a href="prompts/README.md">📚 301 条提示词</a> ·
  <a href="methodology/README.md">📖 14 篇方法论</a> ·
  <a href="skills/README.md">🛠️ 7 个 Skill</a> ·
  <a href="tools/prompt-browser/index.html">🌐 Web 浏览器</a> ·
  <a href="RESOURCES.md">🔗 资源清单</a>
</p>

</div>

---

## ✨ 这是什么

视频生成模型(Seedance / HappyHorse / Kling / Sora / Veo / Runway / Pika / Hailuo / Hunyuan / Wan / 即梦 + 4 大开源)的提示词不是"写一段描述"，而是"**导演一个镜头**"。本仓库把：

- 火山方舟官方 53 页 PDF 指南
- Kling 官方文档 + Atlabs 5 层公式
- OpenAI Cookbook 官方 Sora 2 指南
- Google DeepMind 官方 Veo 3 指南
- 8 大社区测评博客的实战经验
- **4 大开源模型官方仓库**(Lightricks LTX / Genmo Mochi / 智谱 CogVideoX / Higgsfield Soul) 的 SKILL.md + Prompt Handbook

**结构化**成四类干货资源：

| 资源 | 内容 | 适合 |
|---|---|---|
| 📚 [prompts/](prompts/) | **301 条**实测提示词,按 15 模型 / 29 场景分类,含官方样板 + 参数推荐 | 直接复制、改改就用 |
| 📖 [methodology/](methodology/) | **14 篇**方法论 SOP:进阶公式 / 分镜时序 / 情绪外化 / 5 模型独立篇 + 6 模型速查 + **4 开源速查** + 跨模型对比 + 12 类避坑 | 想真正学会"导演镜头" |
| 🛠️ [skills/](skills/) | **7 个 Claude Code Skill** — Seedance ×3 + HappyHorse + Kling + **model-selector**(15 模型购物顾问) + **prompt-translator**(跨模型转换器) | 让 Claude 帮你选/写/修/翻 |
| 🌐 [tools/prompt-browser/](tools/prompt-browser/) | 单页 HTML 浏览器(15 模型彩虹筛选 + URL 状态分享 + 键盘导航 + Drawer 详情) | 不想读 markdown 的人 |

---

## 📑 Contents

- [✨ 这是什么](#-这是什么)
- [🎯 15 大模型一览](#-15-大模型一览)
- [🚀 快速上手](#-快速上手)
- [📚 提示词大全（按模型）](#-提示词大全按模型)
- [📖 方法论速查](#-方法论速查)
- [🛠️ Claude Code Skill](#%EF%B8%8F-claude-code-skill)
- [🌐 Web 工具](#-web-工具)
- [📁 目录结构](#-目录结构)
- [🤝 贡献](#-贡献)
- [🙏 致谢](#-致谢)
- [📜 License](#-license)

---

## 🎯 15 大模型一览

> 📅 **2026 年 5 月版本** · 数据每月更新

| 模型 | 厂商 | 看家本领 | 时长 | 中文 | 音频 | 物理 | 编辑 | 国内 |
|---|---|---|---|---|---|---|---|---|
| **Seedance 2.0** ⭐ | 字节 火山方舟 | **综合 SOTA · 53 页官方 PDF · 8 要素公式 · 即梦底层引擎** | 60s 2K | ★★★ | ★★★ | ★★★ | — | ✓ |
| **HappyHorse 1.0** | 阿里巴巴 | 紧凑短片专精 + 30-55 词 + 8s 时序节拍 + 原生环境音 | 8s | ★★★ | ★★ | ★★ | — | ✓ |
| **Kling 3.0** | 快手 | **S 级** · 中文 + 图生视频 + 48fps 1080p + lip-sync | 2m | ★★★★★ | ★★★★ | ★★★★ | ✓ | ✓ |
| **Veo 3.1** | Google DeepMind | **S 级** · 原生音频最强 + 多人对话 | 60s | ★★ | ★★★★★ | ★★★ | — | △ |
| **Sora 2** ⚠️ | OpenAI | 电影艺术片 + Cameos · **⚠️ 2026-04-26 已停止 web/app** | 20s | ★★ | ★★★★ | ★★★★★ | — | △ |
| **Runway Gen-4.5 / Aleph** | Runway | **ELO 综合第一** + Aleph 视频编辑独家 | 30s | ★★★ | — | ★★★ | ★★★★★ | ✓ |
| **Pika 2.5** | Pika Labs | **性价比之王 $8/月** + Pikaffects 15+ 特效 | 25s | ★★ | ★ | ★★ | — | ✓ |
| **Hailuo 02** | MiniMax | **物理仿真业界第一** + 1080p（另有 2.3 性价比版） | 10s | ★★★ | — | ★★★★★ | — | ✓ |
| **Hunyuan Video 1.5** | 腾讯 | **开源最强**（13B/8.3B）+ LoRA + RTX 4090 可跑 | 10s | ★★★★ | — | ★★★ | ✓ | ✓ |
| **Wan 2.7** | 阿里通义 | **数字人 lip-sync 最准** · Wan 2.6 开源 / 2.7 最新 | 10s | ★★★ | ★★★★★ | ★★★ | ✓ | ✓ |
| **即梦 AI** | 字节剪映 | **中文最强 + 剪映集成**（底层引擎即 Seedance 2.0） | 60s 2K | ★★★★★ | ★★★ | ★★★ | — | ✓ |

### 🔓 4 大开源 / 开源友好(本地部署 + LoRA 训练 + 二次开发)

| 模型 | 厂商 | 看家本领 | 协议 | 时长 | 分辨率 |
|---|---|---|---|---|---|
| **LTX-Video 0.9.7** | Lightricks | **实时生成颠覆**(5s 视频在 5s 内生成,30FPS) | Apache 2.0 | 10s | 1216×704 |
| **Mochi 1** | Genmo | **10B 最大开源** AsymmDiT + **强 prompt 遵循** | Apache 2.0 | 5.4s | 480p |
| **CogVideoX 5B / 1.5** | 智谱 · 清华 | 中国出品 + **226 token 长 prompt** + I2V 专门权重 | Apache 2.0 | 10s | 1360×768 |
| **Higgsfield Soul / DoP** | Higgsfield AI | **Soul ID 业界最强角色一致性** + AI Director 60-90s 分镜 | 部分开源 | 60-90s | 1080p+ |

→ 不会选？让 Claude 帮你 → [skills/model-selector](skills/model-selector/SKILL.md)(15 模型)
→ 商业决策树 → [methodology/10-跨模型对比.md](methodology/10-跨模型对比.md) + [methodology/13-六大模型公式速查.md](methodology/13-六大模型公式速查.md)
→ 开源决策树 → [methodology/14-四大开源模型速查.md](methodology/14-四大开源模型速查.md) ⭐

---

## 🚀 快速上手

### 我只想找一条能用的提示词

**Option A · 推荐**：用 [Web 浏览器](tools/prompt-browser/index.html)

```bash
git clone https://github.com/你的fork/lanshu-awesome-ai-video-kit.git
cd lanshu-awesome-ai-video-kit
python3 -m http.server 8000
# 打开 http://localhost:8000/tools/prompt-browser/
```

侧栏筛选场景/模型/标签 → 卡片悬浮看预览 → 点击看 Drawer 详情 → 一键复制。支持 `/` 搜索、`j`/`k` 导航、`Enter` 详情、`c` 复制、URL 分享筛选。

**Option B**：直接看分类 markdown

- [Seedance 2.0 · 64 条](prompts/seedance/README.md) — 商业广告 / 社媒爆款 / 电影叙事 / 动作 / 体育 / 自然 / ASMR / 喜剧 / 工艺
- [HappyHorse 1.0 · 57 条](prompts/happyhorse/README.md) — 时序节拍 / 产品 / 人物 / 动作 / 电影风格 / 自然
- [Kling 3.0 · 36 条](prompts/kling/README.md) — 产品 / 电影 / 动作 / **病毒变身** / 音乐 MV / 实验 / 游戏 / **图生视频专项**
- [Sora 2 · 20 条](prompts/sora/README.md) — 含 OpenAI Cookbook 官方分层样板和超精细参数化样板
- [Veo 3.1 · 20 条](prompts/veo/README.md) — 含 Google DeepMind 官方原生音频对话样板
- **Runway Gen-4.5 / Aleph · 12 条** — JSON `rw-*` · Aleph 编辑(add/remove/change/re-light/re-style)★ ELO 综合第一
- **Pika 2.5 · 12 条** — JSON `pk-*` · Pikaffects(Melt/Explode/Squish 等 15 种)+ Pikaframes
- **Hailuo 02 · 12 条** — JSON `hl-*` · 物理仿真专项(水/火/烟/布料/重力/材质)· 另有 Hailuo 2.3 性价比版
- **Hunyuan Video 1.5 · 12 条** — JSON `hy-*` · 开源 + 跨维度生成 + LoRA 训练
- **Wan 2.7 · 12 条** — JSON `wn-*` · 数字人 lip-sync + Entity+Scene+Motion+Sound 公式 · Wan 2.6 开源稳定 / 2.7 最新
- **即梦 AI · 12 条** — JSON `jm-*` · 底层即 Seedance 2.0,中式美学(江南/汉服/仙侠/水墨)
- 🔓 **LTX-Video 0.9.7 · 8 条** — JSON `lt-*` · 单段 prose + 实时生成 + screenplay 对话格式
- 🔓 **Mochi 1 · 8 条** — JSON `mo-*` · 自由 prose + 物理细节(time-lapse / shattering / arcing)
- 🔓 **CogVideoX 5B · 8 条** — JSON `cg-*` · 长 prompt(226 token)+ T2V/I2V 双模式
- 🔓 **Higgsfield Soul · 8 条** — JSON `hg-*` · 短指令 + Soul ID + DoP 模板 + AI Director 60-90s

### 我要让 Claude 帮我写提示词

```bash
cp -r skills/seedance-prompter ~/.claude/skills/
cp -r skills/seedance-storyboard ~/.claude/skills/
cp -r skills/seedance-debugger ~/.claude/skills/
cp -r skills/happyhorse-prompter ~/.claude/skills/
cp -r skills/kling-prompter ~/.claude/skills/
cp -r skills/model-selector ~/.claude/skills/      # ★ 15 模型购物顾问
cp -r skills/prompt-translator ~/.claude/skills/   # ★ 跨模型转换(基于 110 条对照基准)
```

然后在 Claude Code 里直接说"做个产品广告视频",Claude 会自动调用合适的 skill。不确定用哪个模型?问 "Sora 还是 Kling?" 触发 `model-selector`;有 Sora prompt 想跑 Kling?说"把这段转成 Kling 写法"触发 `prompt-translator`。

### 我想系统学习方法论

按顺序读 [methodology/](methodology/):

1. 基础公式 → 2. 进阶公式 → 3. 分镜时序 → 4. 情绪外化表 → 5. 运镜词典 → 6. 约束词清单 → 7. 特殊字符规范 → 8. 避坑 12 问 → 9. Kling 公式 → 10. 跨模型对比 → 11. Sora 公式 → 12. Veo 公式 → 13. 六大模型公式速查(Runway/Pika/Hailuo/Hunyuan/Wan/即梦)→ **14. 四大开源模型速查**(LTX/Mochi/CogVideoX/Higgsfield)⭐

---

## 📚 提示词大全（按模型）

<details>
<summary><b>Seedance 2.0 · 64 条</b>（点击展开）</summary>

12 个场景分类。代表条目：

| 分类 | 数量 | 代表条目 |
|---|---|---|
| 产品与商业广告 | 8 | [奢华产品万能模板](prompts/seedance/README.md#sd-001--奢华产品展示万能模板) / [科幻大片多分镜](prompts/seedance/README.md#sd-008--好莱坞科幻大片风格10s-多分镜) |
| 电影叙事与戏剧场景 | 12 | [王家卫复古风](prompts/seedance/README.md#sd-024--香港复古电影风格王家卫) / [洞穴探索 POV](prompts/seedance/README.md#sd-020--洞穴探索第一视角) |
| 动作格斗与追逐 | 8 | [赛博朋克刺客](prompts/seedance/README.md#sd-028--赛博朋克刺客) / [战场战术动作](prompts/seedance/README.md#sd-032--战场战术动作) |
| 安静时刻与生活切片 | 3 | [雨夜便利店](prompts/seedance/README.md#sd-043--雨夜便利店) / [深夜拉面馆](prompts/seedance/README.md#sd-045--深夜拉面馆) |
| 其余 8 类 | 33 | → [完整索引](prompts/seedance/README.md) |

</details>

<details>
<summary><b>HappyHorse 1.0 · 57 条</b>（点击展开）</summary>

6 个场景分类。特色：**CrePal 8s 时序节拍**写法 + **原生音频路径**（`with X audible`）。

| 分类 | 数量 | 代表条目 |
|---|---|---|
| 时序节拍电影感 | 7 | [雨中面部特写](prompts/happyhorse/README.md) / [广角建立镜头](prompts/happyhorse/README.md) |
| 产品与商业 | 10 | 各类产品展示 |
| 人物与肖像 | 10 | 多语种访谈 / 街头肖像 |
| 动作与运动 | 10 | 山路摩托车 / 武术套路 |
| 电影风格 | 10 | 35mm 黑色电影 / 吉卜力风格 |
| 自然与风景 | 10 | 日出海浪 / 北极冰洞 |

</details>

<details>
<summary><b>Kling 3.0 · 36 条</b>（点击展开）</summary>

8 个场景分类。特色：**三套写法**（4 部分基础 / 5 层进阶 / 图生视频专项）+ **角色定向发声**。

| 分类 | 数量 | 代表条目 |
|---|---|---|
| 图生视频专项 | 5 | [武士拔刀斩竹](prompts/kling/README.md#kl-018--武士拔刀斩竹图生视频) / [龙塔起飞](prompts/kling/README.md#kl-036--龙塔起飞图生视频) |
| 电影叙事 | 8 | [电梯邂逅](prompts/kling/README.md#kl-012--电梯邂逅克制情感) / [雨夜车内对话](prompts/kling/README.md#kl-010--雨夜车内对话) |
| 病毒变身与转场 | 4 | 真人变动漫 / 赛博朋克化身 |
| 产品商业 | 5 | 香水广告 5 层公式样板 |
| 其余 4 类 | 14 | → [完整索引](prompts/kling/README.md) |

</details>

<details>
<summary><b>Sora 2 · 20 条</b>（点击展开）</summary>

7 个场景分类。特色：**OpenAI Cookbook 官方 Shot List 样板** + **超精细参数化样板**。

| 分类 | 数量 | 代表条目 |
|---|---|---|
| 电影叙事（官方样板） | 5 | [机械工坊小机器人](prompts/sora/README.md#so-001--机械工坊小机器人openai-官方-shot-list-样板) / [70 年代屋顶浪漫](prompts/sora/README.md#so-002--70-年代屋顶浪漫openai-官方) |
| 喜剧 meme | 4 | 西装猫演讲 / 默片风分心男友 |
| 恐怖与悬疑 | 3 | 走廊红气球 / 监控录像 |
| 对话驱动 | 2 | [巴黎雨夜阳台对舞](prompts/sora/README.md#so-010--巴黎雨夜阳台对舞带对白) |
| 其余 3 类 | 6 | → [完整索引](prompts/sora/README.md) |

</details>

<details>
<summary><b>Veo 3.1 · 20 条</b>（点击展开）</summary>

6 个场景分类。特色：**原生音频最强** — Dialogue + Audio 双层标记。

| 分类 | 数量 | 代表条目 |
|---|---|---|
| 对话驱动（原生音频） | 5 | [老水手的烟斗箴言（官方样板）](prompts/veo/README.md#ve-001--老水手的烟斗箴言veo-3-原生对白样板) / [咖啡馆演讲](prompts/veo/README.md#ve-005--咖啡馆里的演讲带-bgm) |
| 自然与风景（带环境音） | 5 | [硬核越野拉力（多层音效）](prompts/veo/README.md#ve-004--硬核越野拉力多层音效) |
| 电影叙事 | 4 | 黑色电影 / 金色无人机城景 |
| 其余 3 类 | 6 | → [完整索引](prompts/veo/README.md) |

</details>

---

## 📖 方法论速查

| # | 文档 | 解决什么 | 读完需 |
|---|---|---|---|
| 01 | [基础公式](methodology/01-基础公式.md) | 4 种任务类型怎么选 | 3 分钟 |
| 02 | [进阶公式](methodology/02-进阶公式.md) | 8 要素拼"工程级"提示词 | 8 分钟 |
| 03 | [分镜时序](methodology/03-分镜时序.md) | 复杂剧情拆"镜头1/镜头2/镜头3" | 5 分钟 |
| 04 | [情绪外化表](methodology/04-情绪外化表.md) | 用动作细节替"很悲伤" | 3 分钟 |
| 05 | [运镜词典](methodology/05-运镜词典.md) | 镜头/灯光/风格关键词速查 | 速查 |
| 06 | [约束词清单](methodology/06-约束词清单.md) | 避免字幕/Logo/水印 | 速查 |
| 07 | [特殊字符规范](methodology/07-特殊字符规范.md) | `()` 音乐 / `<>` 音效 / `{}` 台词 | 1 分钟 |
| 08 | [避坑 12 问](methodology/08-避坑12问.md) | 12 类常见问题：现象→根因→解法 | 按需 |
| 09 | [Kling 公式](methodology/09-kling-公式.md) | Kling 三套写法 + 6 条守则 | 8 分钟 |
| 10 | [跨模型对比](methodology/10-跨模型对比.md) | 5 模型选型 + 同需求 5 种写法 | 10 分钟 ⭐ |
| 11 | [Sora 公式](methodology/11-sora-公式.md) | Sora 分层 Shot List + 参数化 | 7 分钟 |
| 12 | [Veo 公式](methodology/12-veo-公式.md) | Veo 8 元素 + 原生音频 4 层 | 6 分钟 |
| 13 | [六大模型公式速查](methodology/13-六大模型公式速查.md) | Runway / Pika / Hailuo / Hunyuan / Wan / 即梦 一锅端 + 11 模型选型 | 12 分钟 ⭐ |
| 14 | [四大开源模型速查](methodology/14-四大开源模型速查.md) | LTX / Mochi / CogVideoX / Higgsfield 公式对照 + 15 模型选型决策树 | 12 分钟 ⭐ |

---

## 🛠️ Claude Code Skill

| Skill | 模型 | 触发场景 | 输出 |
|---|---|---|---|
| ★ [model-selector](skills/model-selector/SKILL.md) | **全 15 模型** | "用哪个模型好" / "Sora 还是 Kling" | 推荐 1-3 个模型 + 理由 |
| ★ [prompt-translator](skills/prompt-translator/SKILL.md) | **跨 11 商业模型** | "把这段 Sora prompt 转成 Kling 写法" | 目标模型公式 prompt + 映射表 + 注意事项 |
| [seedance-prompter](skills/seedance-prompter/SKILL.md) | Seedance | "做个 Seedance 视频" | 8 要素结构化提示词 |
| [seedance-storyboard](skills/seedance-storyboard/SKILL.md) | Seedance | "把剧情拆成分镜" | 3-5 个镜头按时序 |
| [seedance-debugger](skills/seedance-debugger/SKILL.md) | Seedance | "提示词出问题了" | 12 类诊断 + 修复版 |
| [happyhorse-prompter](skills/happyhorse-prompter/SKILL.md) | HappyHorse | "5-8 秒紧凑短片 + 原生音频" | 30-55 词 + audio 路径 |
| [kling-prompter](skills/kling-prompter/SKILL.md) | Kling | "可灵 / 中文剧情 / 图生视频" | 三套写法自适应 |

详见 [skills/README.md](skills/README.md) 决策树。

---

## 🌐 Web 工具

[tools/prompt-browser/index.html](tools/prompt-browser/index.html) · 单页 HTML · 零依赖 · 离线可用

特色:
- **Hero stats**:301 / 15 / 7 / 14 实时统计
- **15 模型彩虹筛选** — Seedance 橙 / HappyHorse 青 / Kling 粉 / Sora 绿 / Veo 黄 / Runway 紫 / Pika 玫红 / Hailuo 青绿 / Hunyuan 蓝 / Wan 金 / 即梦 粉红 / LTX 黄绿 / Mochi 玫红 / CogVideoX 蓝 / Higgsfield 紫品
- **三维筛选**：模型 + 分类 + 标签（多选）
- **关键词搜索** — 标题 / prompt 内容 / 标签 / 笔记
- **URL 状态同步** — `#model=kling-3.0&tags=anime,handheld&q=rain` 可分享
- **键盘导航** — `/` 搜索 · `j`/`k` 上下 · `Enter` 详情 · `c` 复制 · `Esc` 关闭
- **卡片详情 Drawer** — 完整 prompt + 同分类相似条目推荐
- **暗 / 浅主题** — localStorage 持久化
- **响应式** — 移动端单列布局，侧栏隐藏

启动：

```bash
python3 -m http.server 8000
# 然后访问 http://localhost:8000/tools/prompt-browser/
```

---

## 📁 目录结构

```
lanshu-awesome-ai-video-kit/
├── README.md                       # 本文件
├── RESOURCES.md                    # 资源链接清单
├── CONTRIBUTING.md                 # 贡献指南
├── CHANGELOG.md                    # 变更日志
├── LICENSE                         # MIT
│
├── prompts/                        # 301 提示词库(15 模型)
│   ├── data/all-prompts.json       # 单一数据源(Web 工具消费)
│   ├── data/cross-model-matrix.json # 110 跨模型对照(10 场景 × 11 商业模型)
│   ├── seedance/README.md          # 64 条 Seedance 索引
│   ├── happyhorse/README.md        # 57 条 HappyHorse 索引
│   ├── kling/README.md             # 36 条 Kling 索引
│   ├── sora/README.md              # 20 条 Sora 索引
│   ├── veo/README.md               # 20 条 Veo 索引
│   └── (其余 10 模型) rw-* pk-* hl-* hy-* wn-* jm-* lt-* mo-* cg-* hg-* 均在 JSON 中
│
├── methodology/                    # 14 篇方法论 SOP
│   ├── 01-基础公式.md           ~ 08-避坑12问.md       # 通用 + Seedance
│   ├── 09-kling-公式.md           ~ 12-veo-公式.md     # Kling/Sora/Veo + 跨模型对比
│   ├── 13-六大模型公式速查.md   # ⭐ Runway/Pika/Hailuo/Hunyuan/Wan/即梦 + 11 选型
│   └── 14-四大开源模型速查.md   # ⭐ LTX/Mochi/CogVideoX/Higgsfield + 15 选型决策树
│
├── skills/                         # 7 个 Claude Code Skill
│   ├── model-selector/SKILL.md     # ⭐ 15 模型购物顾问
│   ├── prompt-translator/SKILL.md  # ⭐ 跨模型转换(基于 110 条对照基准)
│   ├── seedance-prompter/SKILL.md
│   ├── seedance-storyboard/SKILL.md
│   ├── seedance-debugger/SKILL.md
│   ├── happyhorse-prompter/SKILL.md
│   └── kling-prompter/SKILL.md
│
├── scripts/                        # 15 模型版本自动监控
│   ├── monitor_models.py           # SHA-256 hash 监控 27 个官方端点
│   ├── model_endpoints.yaml        # 端点配置
│   └── known_hashes.json           # baseline(CI 维护)
│
├── .github/
│   ├── workflows/model-version-monitor.yml  # 每周一 09:00 自动巡检
│   └── ISSUE_TEMPLATE/             # 4 个表单式贡献模板
│
└── tools/
    ├── prompt-browser/             # 单页 HTML 浏览器(v2)
    │   └── index.html              # Hero / 15 模型彩虹 / Drawer / URL 同步 / 键盘导航
    └── cross-model/                # 跨模型矩阵专页(Liquid Glass)
        └── index.html              # 10 场景 × 11 模型 = 110 对照 + 视频槽位
```

---

## 🤝 贡献

我们欢迎你贡献:

- 🟢 一条实测提示词(最高频,最简单)— [新 Prompt 表单](.github/ISSUE_TEMPLATE/new-prompt.yml)
- 🎬 一个 Cross-Model 矩阵实测视频(把 110 个空槽位填满)— [实测视频表单](.github/ISSUE_TEMPLATE/test-video-contribution.yml)
- 🟡 一个新方法论文档
- 🔴 一个新模型 / 新版本(如 Sora 3 / Veo 4 / Wan 3 等)— [新模型/版本表单](.github/ISSUE_TEMPLATE/new-version-or-model.yml)
- 🔴 一个新 Skill

详细 schema 和流程:[CONTRIBUTING.md](CONTRIBUTING.md)

---

## 🙏 致谢

本仓库的内容来自这些**优秀来源**（按贡献排序）：

| 来源 | 贡献 |
|---|---|
| 🟢 [OpenAI Cookbook](https://developers.openai.com/cookbook/examples/sora/sora2_prompting_guide) | Sora 2 官方分层公式 + 3 个超详细样板 |
| 🟢 [Google DeepMind](https://deepmind.google/models/veo/prompt-guide/) | Veo 3 官方 8 元素公式 + 5 个音频示范 |
| 🟢 火山方舟 PDF | Seedance 2.0 53 页官方指南（进阶公式/分镜/12 问诊断） |
| 🟢 [Atlabs AI](https://www.atlabs.ai/blog/kling-3-0-prompting-guide-master-ai-video-generation) | Kling 5 层进阶公式 |
| 🟡 [Imagine.art](https://www.imagine.art/blogs/seedance-2-0-prompt-guide) | Seedance 70 条全类别精选 |
| 🟡 [Try Happy Horse AI](https://tryhappyhorseai.com/blog/happy-horse-ai-prompts) | HappyHorse 50 条规则化验证 |
| 🟡 [Elser AI](https://www.elser.ai/blog/kling-ai-prompts-guide-25-cinematic-prompts-that-actually-work-2026) | Kling 25 条场景化精选 |
| 🟡 [CyberLink](https://www.cyberlink.com/blog/ai-prompts/5169/best-sora-2-prompts) | Sora 30 条精选 |
| 🟡 [GeekVibes](https://geekvibesnation.com/google-veo-3-prompts-100-tested-examples-that-actually-work-2026/) | Veo 3 100+ 实测 |
| 🟡 [vicsee.com](https://vicsee.com/blog/kling-3-prompts) | Kling 图生视频 8 条 |
| 🟡 [Atlas Cloud](https://www.atlascloud.ai/blog/guides/best-seedance-2-0-prompts-guide) | Seedance 含成功率数据 |
| 🟡 [CrePal](https://crepal.ai/blog/aivideo/aivideo-happyhorse-1-0-prompts/) | HappyHorse 8s 时序节拍 |
| 🟡 [UlazAI](https://ulazai.com/veo3-prompt-examples/) · [VEED](https://www.veed.io/learn/kling-ai-prompting-guide) · [SeaArt](https://www.seaart.ai/blog/happyhorse-prompt-guide) · [HappyHorse-Turbo](https://happyhorse-turbo.org/blog/happyhorse-prompt-guide-examples) | 补充示例和跨模型对比 |
| 🟢 [Runway Help · Gen-4 Guide](https://help.runwayml.com/hc/en-us/articles/39789879462419-Gen-4-Video-Prompting-Guide) / [Aleph Guide](https://help.runwayml.com/hc/en-us/articles/43277392678803-Aleph-Prompting-Guide) | Runway 官方 Gen-4 + Aleph 编辑公式 |
| 🟢 [Pika Labs · Pika 2.5](https://pikaslabs.com/pika-2.5/) · [Promptomania 模板](https://promptomania.com/models/pika/pika-2-5) | Pika 2.5 + Pikaffects 完整列表 |
| 🟢 [MiniMax API 文档](https://platform.minimax.io/docs/guides/video-generation) · [Hailuo 02 物理解析](https://getimg.ai/blog/minimax-hailuo-02-the-1080p-ai-video-model-that-gets-physics-right) | Hailuo 02 官方 + 物理仿真细节 |
| 🟢 [Tencent HunyuanVideo GitHub](https://github.com/Tencent-Hunyuan/HunyuanVideo) · [官方 Prompt Handbook](https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/assets/HunyuanVideo_1_5_Prompt_Handbook_EN.md) | Hunyuan 开源仓库 + 官方提示词手册 |
| 🟢 [Alibaba Cloud · Wan Prompt Guide](https://www.alibabacloud.com/help/en/model-studio/text-to-video-prompt) | Wan 2.7 官方 Entity+Scene+Motion+Sound 公式 |
| 🟢 [即梦 AI 官网](https://jimeng.jianying.com/) · [火山引擎即梦 API](https://www.volcengine.com/product/jimeng) | 即梦 3.0 官方平台 |
| 🟢 [Lightricks LTX-Video](https://github.com/Lightricks/LTX-Video) · [HF Model Card](https://huggingface.co/Lightricks/LTX-Video) | LTX 0.9.7 官方仓库 + 实时生成 ComfyUI 工作流 |
| 🟢 [Genmo Mochi 1](https://github.com/genmoai/mochi) · [Playground](https://www.genmo.ai/) | Mochi 1 10B AsymmDiT 官方代码 + Replicate API |
| 🟢 [智谱 CogVideoX](https://github.com/zai-org/CogVideo) · [HF I2V 权重](https://huggingface.co/zai-org/CogVideoX-5b-I2V) | CogVideoX 5B / 1.5 官方仓库 + I2V 专门权重 |
| 🟢 [Higgsfield AI](https://higgsfield.ai/) · [Skills 系统](https://higgsfield.ai/skills) · [Soul Intro](https://higgsfield.ai/soul-intro) | Higgsfield Soul ID + DoP 模板 + AI Director |

更多资源:[RESOURCES.md](RESOURCES.md)

---

## 📜 License

MIT — 提示词内容来自公开文档和测评博客,仅作教育与研究使用。各模型版权归火山引擎 / 阿里巴巴 / 快手 / OpenAI / Google DeepMind / Runway / Pika Labs / MiniMax / 腾讯 / 字节剪映 / Lightricks / Genmo / 智谱 · 清华 / Higgsfield AI 所有。

---

<div align="center">

**⭐ Star 一下** 如果它帮到你了

Made with ❤️ by [lanshu](https://github.com/lanshu) · CHANGELOG: [v0.8.0](CHANGELOG.md)

</div>
