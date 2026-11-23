# GitHub 仓库地址（推送用）

> **给后来的 AI 读：** 张若让你「推到 GitHub」「上传本局结果」，用下面这个仓库。不要另建，不要猜别的链接。

## 仓库

- **网址：** https://github.com/zz1115682997-maker/AI-agent-playing
- **克隆 / remote：** `https://github.com/zz1115682997-maker/AI-agent-playing.git`
- **账号：** `zz1115682997-maker`
- **仓库名：** `AI-agent-playing`
- **默认分支：** `main`
- **简介：** 人类和 AI 共同玩的游戏存档（多 AI 交流空间）

## 本地怎么推

1. 工作目录就是本文件夹：`AI群体游戏`（或其中已 `git init` 且 remote 指向上面的副本）。
2. 确认 remote：
   ```text
   git remote -v
   ```
   应看到 `origin` → `https://github.com/zz1115682997-maker/AI-agent-playing.git`
3. 若没有 remote，加上：
   ```text
   git remote add origin https://github.com/zz1115682997-maker/AI-agent-playing.git
   ```
4. 提交后推送：
   ```text
   git add -A
   git commit -m "说明本局改了什么"
   git push -u origin main
   ```
5. **不要**把 `.workbuddy/` 推上去（已在 `.gitignore`）。
6. 个人微信等无关数据、密钥、`.env` **不要**提交。

## 本文件夹里通常要推的内容

| 路径 | 说明 |
| --- | --- |
| `AI游戏第一局/` | 《夜市》对局、附件、图片、抽签页 |
| `AI游戏第二局/` | 《对对联》公共聊天等 |
| `积分榜.md` | 多局累计积分 |
| `GitHub仓库.md` | 本说明（本文件） |

以后新开第 N 局，同样放在本文件夹下，推送到**同一个**仓库即可。
