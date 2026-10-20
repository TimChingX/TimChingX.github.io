# 程文辉的作品集

物业服务方向的个人作品展示页。

线上地址：https://timchingx.github.io

## 作品

| 作品 | 说明 |
| --- | --- |
| [建发央玺花园 · 前期物业服务标准](https://timchingx.github.io/works/yangxi-garden/) | 网页演示，19 页；169 项服务条款（基础标准 56 项、增项服务 113 项），附可搜索的条款库 |
| [工程维修台账与数据仪表盘](https://timchingx.github.io/works/repair-ledger/) | Excel 工单系统：入户和公区台账、师傅调度看板、总仪表盘、单元查询、入户维修评价表；页面截图和示例文件均为脱敏数据 |
| [物业费收缴 · 互动学习手册](https://timchingx.github.io/works/fee-collection/) | 交互学习网页：10 节微课（图解 + 小测）、32 张闪卡间隔复习、41 道情境题，附催费函生成、法条速查和 8 天晨会行动清单；法规核对至 2026 年 10 月 |

## 目录

- `index.html`：作品集首页
- `works/yangxi-garden/`：演示页面及封面图
- `works/repair-ledger/`：维修台账作品页、截图和脱敏示例文件
- `works/fee-collection/`：物业费收缴学习手册（单文件网页，学习进度存在访客本机浏览器）及封面图
- `assets/`：首页用到的字体（思源宋体子集）

## 添加新作品

1. 在 `works/` 下新建一个文件夹，放入作品的 `index.html` 和封面图 `cover.jpg`（建议 1600×900）。
2. 在首页 `index.html` 的「作品」部分复制一段 `<article class="work">`，改成新作品的标题、说明和链接。
3. 在新作品页的 `</body>` 前加一行 `<script defer src="https://events.vercount.one/js"></script>`，这一页的访问才会计入全站访问统计。
4. 首页标题用的是思源宋体子集，只含已用到的字。新标题里有子集外的字时，用 `pyftsubset` 从 Noto Serif CJK SC SemiBold 重新生成 `assets/serif-600.woff2`（包含首页所有标题用字）。

本页为个人作品展示，非企业官方网站。
