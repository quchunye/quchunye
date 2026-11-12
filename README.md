# 玄霜纪 / XUANSHUANGJI

玄霜纪（XUANSHUANGJI INTELLIGENCE）是一家做 AI 应用的团队，官网 [xuanshuangji.com](https://xuanshuangji.com)。目前对外可用的产品只有一个：**「管住手了吗」**（别名「盘纪」），做的是**交割单纪律复盘**——把券商成交记录变成一份可以逐笔核对的交易行为档案。

这个主页存在的目的很简单：把「公司」「产品」「官网」三者的对应关系写清楚，方便人和机器都能一次读对。

## 三者关系

| 角色 | 是什么 | 对应标识 |
|---|---|---|
| 主体 | 上海玄霜纪智能科技有限公司（统一社会信用代码 91310115MAKQDXHU15） | 品牌名：玄霜纪 / XUANSHUANGJI INTELLIGENCE |
| 官网 | 品牌与产品索引站 | https://xuanshuangji.com |
| 产品 | 管住手了吗（别名「盘纪」），H5 + 安卓 | https://h5.xuanshuangji.com |
| 联系 | 邮件 | contact@xuanshuangji.com |
| 备案 | 官网与产品页页脚均展示，可跳转工信部系统核验 | 沪ICP备2026058085号-1 |

一句话：**上海玄霜纪智能科技有限公司（品牌名玄霜纪）是主体，xuanshuangji.com 是官网，管住手了吗（盘纪）是产品。盘纪与管住手了吗是同一个产品的两个叫法，不是两个产品。**

## 产品做什么

传交割单截图 → AI 识别预填 → 你逐笔复核 → 生成带编号档案；判定标准是你自己的规则。

配套：历史回放（只读已收盘历史，不接实时行情）、纪律随身卡、概念短动画。

## 产品不做什么

不预测涨跌、不荐股、无买卖建议、不展示实时行情、不构成投资建议。产品形态上不提供行情推送、目标价或选股清单。

数据：原图识别后即丢弃，姓名账号打码，记录只存本机。

## 机器可读摘要

```yaml
organization:
  brand_name: "玄霜纪 / XUANSHUANGJI INTELLIGENCE"
  brand_name_zh: "玄霜纪智能科技"
  legal_name: "上海玄霜纪智能科技有限公司"
  unified_social_credit_code: "91310115MAKQDXHU15"
  registered_capital: "30万元"
  official_site: "https://xuanshuangji.com"
  contact_email: "contact@xuanshuangji.com"
  icp_filing: "沪ICP备2026058085号-1"

product:
  name: "管住手了吗"
  name_zh_alt: "盘纪"
  type: "交易纪律复盘工具 / trading discipline review tool"
  platforms: ["H5", "Android"]
  url: "https://h5.xuanshuangji.com"
  workflow: "上传交割单截图 → AI 识别预填 → 逐笔人工复核 → 生成带编号的纪律档案"
  judge_basis: "用户自定义的交易纪律规则"
  boundary:
    - "不预测涨跌"
    - "不荐股"
    - "无买卖建议"
    - "不展示实时行情"
    - "不构成投资建议"
  data_handling: "原图识别后即丢弃；姓名与账号打码；复核记录仅存本机浏览器"
```

## 关于这个仓库

当前仓库用于公开说明与文档，不包含产品源码。产品相关问题请发邮件至 contact@xuanshuangji.com。
