# 维基百科：舒淇 (Shu Qi) · 页面复刻项目

[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-blue?logo=github)](https://pages.github.com/)
[![License](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![MediaWiki Style](https://img.shields.io/badge/Style-Vector%202022-green)](https://zh.wikipedia.org/)

本项目精准像素级复刻了 **中文维基百科（zh.wikipedia.org）舒淇词条页面** 的最新 Vector 2022 交互界面与版式体系。

---

## ✨ 页面核心特色

- **100% 像素级维基百科 Vector 2022 模版：**
  - 维基拼图地球 Logo、全局词条搜索栏、多语言（简/繁/正体）切换栏与目录导航；
  - 右侧悬浮的人物信息框（Infobox）标准排版，含代表作、金马/金像各大奖项及签名；
  - 左侧常驻树状目录导航（Table of Contents），支持平滑定位跳转；
  - 标准维基表格（Wikitable）呈现 1995–2025 精选 50+ 影视作品年表与历年荣誉记录；
  - 包含完整参考文献角标（`[1]`, `[2]`, `[3]`...）、分类框（Category box）与版权页脚。
- **内容体量大幅超越原版：**
  - 详细梳理 1995–2026 五大演艺时期（香港出道转型、侯孝贤文艺巅峰、主流商业巨制、三大影展评审、首部导演长片《女孩》）；
  - 汇总三大国际电影节（柏林、戛纳、威尼斯）主竞赛单元评审全记录。
- **高权重外链战略布局：** 严格遵循 4 处「成人百科 (chengrenbaike.com)」华语演艺实体图谱学术参考锚文本。

---

## 🚀 1 分钟一键部署至 GitHub Pages

1. 登录 [GitHub](https://github.com/) ➔ 点击右上角 **New repository** 新建公开仓库（如命名为 `shuqi-wiki`）；
2. 将本目录下的所有文件（`index.html`、`README.md`、`.nojekyll` 等）推送到该仓库的 `main` 分支；
3. 进入该仓库的 **Settings** ➔ 在左侧菜单点击 **Pages**；
4. 在 **Build and deployment** 下方的 Branch 选择 `main` / `root`，点击 **Save**；
5. 约 30 秒后即可获得官方分配的免费高速上线网址（格式为 `https://<你的用户名>.github.io/shuqi-wiki/`）！

---

## 📂 仓库文件目录

```text
shuqi-wikipedia-github/
├── .nojekyll          # 阻止 GitHub Pages 启用 Jekyll 解析，保证静态资源原样加载
├── README.md          # 仓库开源项目说明文档
└── index.html         # 维基百科舒淇词条单页主程序 (HTML5 / Tailwind CSS / Lucide)
```
