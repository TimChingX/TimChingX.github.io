# 程文辉的作品集

物业服务方向的个人作品展示页。

线上地址：https://timchingx.github.io

## 作品

| 作品 | 说明 |
| --- | --- |
| [建发央玺花园 · 前期物业服务标准](https://timchingx.github.io/works/yangxi-garden/) | 网页演示，19 页；169 项服务条款（基础标准 56 项、增项服务 113 项），附可搜索的条款库 |
| [工程维修台账与数据仪表盘](https://timchingx.github.io/works/repair-ledger/) | Excel 工单系统：入户和公区台账、师傅调度看板、总仪表盘、单元查询、入户维修评价表；页面截图和示例文件均为脱敏数据 |
| [上海住宅物业法规速查](https://timchingx.github.io/works/shanghai-property-law/) | 网页速查：《民法典》物业相关 66 条与《上海市住宅物业管理规定》110 条（2026 修正）按主题对齐合并，附 2026 修订对照、关键数字速查、客服场景速查和自测卡片 |

## 目录

- `index.html`：作品集首页
- `works/yangxi-garden/`：演示页面及封面图
- `works/repair-ledger/`：维修台账作品页、截图和脱敏示例文件
- `works/shanghai-property-law/`：法规速查页面及封面图
- `assets/`：首页用到的字体（思源宋体子集）

## 添加新作品

1. 在 `works/` 下新建一个文件夹，放入作品的 `index.html` 和封面图 `cover.jpg`（建议 1600×900）。
2. 在首页 `index.html` 的「作品」部分复制一段 `<article class="work">`，改成新作品的标题、说明和链接。
3. 首页标题用的是思源宋体子集，只含已用到的字。新标题里有子集外的字时，用 `pyftsubset` 从 Noto Serif CJK SC SemiBold 重新生成 `assets/serif-600.woff2`（包含首页所有标题用字）。

本页为个人作品展示，非企业官方网站。
