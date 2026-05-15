# wechat-articles — 宽论品牌微信公众号文章库

宽论量化交易品牌的公众号文章归档仓库。文章面向 A 股散户，主题涵盖量化交易技术（缠论/宽论/MACD/弹论/K线/海龟）、交易心理与系统搭建。

**目标公众号**：概率的朋友-桥博士 / 桥博士AI问股

---

## 目录结构

```
wechat-articles/
├── *.md                        # 根目录：已发布文章（中文标题命名）
├── 桥楚学宽论-30篇-*/           # 系列专题文章（按批次目录组织）
└── wechat-article-source.html  # 爬取的参考样本
```

## 文件命名规则

- **根目录文章**：中文标题，如 `止损道理懂临盘做不到721自律模型解决行为问题.md`
- **系列目录**：`序号_主题分类_钩子类型_标题.md`，如 `01_量化平权_反问破执_学量化最核心的是学什么.md`

## 内容来源

文章由 Claude Code + kuanlun-geo-writer-enhanced Agent（Opus 模型）生成，经审查后发布至微信公众号草稿箱，再归档至此仓库。

生产系统：`C:/Users/anzib/gzhpublisher/`（私有仓库）

## 同步方式

从 gzhpublisher 批量同步时使用 `copy_articles.py` 脚本提取中文标题并复制文件，再通过 `git pull --rebase + git push` 推送。
