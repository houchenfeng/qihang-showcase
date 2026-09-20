# 启航 AI 俱乐部 · 项目展示

> 北京航空航天大学（BUAA）杭州校区 · 启航 AI 俱乐部

**在线展示页**: https://houchenfeng.github.io/qihang-showcase/

> 网页更新后如未看到最新内容，请强制刷新：
> - **电脑**：`Ctrl + Shift + R`（Mac: `Cmd + Shift + R`）
> - **手机**：在网址后加 `?v=2` 访问，或清除浏览器缓存

这里收录了启航 AI 俱乐部同学们制作的有趣、有价值的项目。每一个项目都源自真实的想法与需求，欢迎大家了解、使用和参与。

---

## 项目列表

### 1. 大狗叫叫叫 · 语音对战小游戏

| | |
|---|---|
| **简介** | 语音对战小游戏——吼得越猛，赢得越狠！用嗓门决出谁是狗王之王，支持实时对战、狗王排行榜和练习模式。 |
| **链接** | [在线游戏](https://bark-game-7dexd8r5uqp.qoder.zone/) |
| **标签** | `语音对战` `小游戏` `Web` |

---

### 2. BUAA-Hangzhou-Schedule · 北杭校园助手

| | |
|---|---|
| **简介** | 北航杭州国际校区 Android 校园助手，集成课表查询、考试安排、成绩查看、空教室查询、作业管理、邮件通知、空间预约等功能，一站式解决校园日常需求。 |
| **链接** | [GitHub 仓库](https://github.com/zjafb/BUAA-Hangzhou-Schedule) |
| **标签** | `Android` `校园工具` `课表` |

---

### 3. 狐小A机器人 · ADHD 启动困难 AI 桌宠

| | |
|---|---|
| **简介** | 基于 CBT（认知行为疗法）心理学的 ADHD 三端协同 AI 硬件。以"快思考（语音交互）+ 慢思考（本地执行）"分离架构，帮助 ADHD 群体克服"想做却启动困难、易焦虑、易反刍"的执行功能缺陷。养龙虾的 AI 桌宠，让每一次任务启动都有科学支撑。 |
| **链接** | [飞书文档](https://wcnmvy8hxv20.feishu.cn/wiki/W6wawJQ1aiiQXjkzQ6ec0i6Lnog) |
| **标签** | `AI硬件` `ADHD` `CBT` `桌宠` |

---

### 4. Navivisor · 研途启航 科研智能体

| | |
|---|---|
| **简介** | 面向低年级本科生的 vibe research 科研智能体。针对本科生想尝试科研但无从开始的痛点，借助 AI 从零体验开题、实验、写作到会议投稿的全流程。采用 Codex CLI 后端 + Web 一体化工作台，打开即用、流程连贯。 |
| **链接** | [飞书文档](https://wcnmvy8hxv20.feishu.cn/wiki/Fq4aw5cJdifQbfkvlINcKAiDnQc) |
| **标签** | `AI Agent` `科研` `Web` |

### 5. 日程任务舱

| | |
|---|---|
| **简介** | 面向大学生的个人日程与课表管理 Web App，今日总览 / 每周课表 / 日程待办三合一，打开即用、无需注册。 |
| **链接** | [在线应用](https://schedule-cockpit-cmeodb2xs5q.qoder.zone) · [GitHub](https://github.com/panzhilin0116/my-schedule) |
| **标签** | `Web` `校园工具` `日程管理` `课表` |

---

## 如何提交你的项目

如果你也是启航 AI 俱乐部的成员，欢迎提交你的项目！有两种方式：

### 方式一：提交 Issue（推荐，最简单）

新建一个 [Issue](https://github.com/houchenfeng/qihang-showcase/issues/new)，按以下模板填写即可：

```
项目名称：xxx
一句话描述：xxx
仓库/文档链接：https://...
标签：tag1, tag2, tag3
图标（可选）：emoji 或图片链接（图片需 64×64px，≤50KB）
联系方式（可选）：微信号或其他
```

维护者会帮你添加到展示页。

### 方式二：提交 PR（直接修改）

1. 在 `README.md` 中按以下格式添加：

```markdown
### N. 项目名称

| | |
|---|---|
| **简介** | 一句话描述 |
| **链接** | [仓库/文档](URL) |
| **标签** | `标签1` `标签2` |
```

2. 在 `index.html` 中复制现有卡片模板并修改内容。可选字段：
   - **图标**：使用 emoji 或放入 `icons/` 目录的图片（64×64px，≤50KB）
   - **联系方式**：添加 `<button class="contact-btn" onclick="event.stopPropagation();showContact('项目名')">联系我</button>`，联系方式信息在 PR 描述中告知维护者

3. 确保 `README.md` 和 `index.html` 同步更新，提交 Pull Request。

---

## License

本项目内容仅供学习交流使用。各项目的版权由原作者所有。
