# 网安知识库 · 公开镜像

网络安全体系化学习资料的静态镜像站，保留原站的前端体验（主题、搜索、侧边栏与文档内跳转）。

## 目录

| 路径 | 内容 | 来源 |
| --- | --- | --- |
| `/` | 入口页（本站自制） | — |
| `/wintrysec/` | wintrysec 技能笔记：Web 安全、域渗透、Linux、安全开发、攻防对抗、工具 | https://wintrysec.github.io/ |
| `/gm7/` | d4m1ts 知识库：渗透测试、代码审计、编程开发、移动安全、应急响应、AI（已排除 Introduction 与更新日志） | https://blog.gm7.org/ |

## 本地预览

静态站，无构建步骤：

```bash
python -m http.server 8765
# 打开 http://127.0.0.1:8765/
```

## 版权与来源

内容版权归原作者所有，详见 [NOTICE.md](NOTICE.md)。本站为非官方镜像，仅用于学习与检索；如原作者要求下线，将立即删除相关内容。

## 部署

站点按 GitHub Pages 项目页的子路径 `/sec-knowledge/` 做过 URL 前缀改写，仓库根目录即发布目录（含 `.nojekyll`）。
