# 物业服务作品集

物业服务方向的个人作品展示页。

线上地址：https://timchingx.github.io

## 作品

| 作品 | 说明 |
| --- | --- |
| [物业费收缴助手](https://timchingx.github.io/works/fee-collection/) | 客服专用的收缴工具：“七不”诊断开处方笺，拒缴话术库自动带入业主信息，推算催缴节点与诉讼时效，生成催告函件，欠费台账跟进接触和回款；法规核对至 2026 年 10 月 |
| [建发央玺花园 · 前期物业服务标准](https://timchingx.github.io/works/yangxi-garden/) | 网页演示，19 页；169 项服务条款（基础标准 56 项、增项服务 113 项），附可搜索的条款库 |
| [工程维修台账与数据仪表盘](https://timchingx.github.io/works/repair-ledger/) | Excel 工单系统：入户和公区台账、师傅调度看板、总仪表盘、单元查询、入户维修评价表；页面截图和示例文件均为脱敏数据 |

## 目录

- `index.html`：作品集首页
- `works/yangxi-garden/`：演示页面及封面图
- `works/repair-ledger/`：维修台账作品页、截图和脱敏示例文件
- `works/fee-collection/`：物业费收缴助手（单文件网页，内容按本站域名加密，禁止复制、打印和另存；台账数据存在访客本机浏览器）、标题字体子集和封面图
- `assets/`：首页用到的字体（思源宋体子集）

## 添加新作品

1. 在 `works/` 下新建一个文件夹，放入作品的 `index.html` 和封面图 `cover.jpg`（建议 1600×900）。
2. 在首页 `index.html` 的「作品」部分复制一段 `<article class="work">`，改成新作品的类别小字（如“网页工具”“网页演示”“Excel 表格”）、标题、简介、上线日期和链接，放在想要的位置。首页是博客文章列表式排版：每项作品占一行、作品之间用细线分隔，左边 4:3 圆角封面，右边从上往下是类别、标题、两行简介和日期；手机上不显示简介。封面会从 16:9 裁成 4:3，主体不在中间的封面在 `<img>` 上加 `style="object-position:…"` 指定保留哪边。
3. 在新作品页的 `</body>` 前加一行 `<script defer src="https://events.vercount.one/js"></script>`，这一页的访问才会计入全站访问统计。
4. 首页标题用的是思源宋体子集，只含已用到的字。新标题里有子集外的字时，用 `pyftsubset` 从 Noto Serif CJK SC SemiBold 重新生成 `assets/serif-600.woff2`（包含首页所有标题用字）。页脚第一行的英文座右铭 “First do it, then do it right, then do it better.” 单独用 `assets/serif-400.woff2`（Noto Serif CJK SC Regular，只含这句话的字母和标点），改这句话时一并重新生成。

本页为个人作品展示，非企业官方网站。
