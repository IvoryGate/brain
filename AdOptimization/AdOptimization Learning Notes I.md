# AdOptimization Learning Notes I —— Job Description

[TOC]

> 

## 术语

后文中会用到的术语

|           NAme           | description  |
| :----------------------: | :----------: |
|  CPI : cost per install  | 单次安装费用 |
|  CPM : cost per million  | 千次展示费用 |
| CTR : click through rate |    点击率    |
|  CVR : convertion rate   |    转化率    |
|                          |              |

$$
\text{CPI}=\frac{\text{cost}}{\text{install}}
$$

$$
\text{CPM}=\frac{\text{cost}}{\text{impression}}\times1000
$$

$$
\text{CTR}=\frac{\text{click}}{\text{impression}}
$$

$$
\text{CVR}=\frac{\text{install}}{\text{click}}
$$

联立上述4个式子，可得：

$$
\text{CPM}=\text{CPI}\cdot\text{CVR}\cdot\text{CTR}\times1000
$$




## 归因

## 市场调研

在市场调研部分，主要使用了[Appmagic](https://appmagic.rocks/), [Insightrackr](https://www.insightrackr.com/en/?referer=google_ads&from_type=marketing&source=google&campaign_id=22257792677&adgroup_id=175250869396&ad_id=733629641440&keyword=insightrackr&gad_source=1&gad_campaignid=22257792677&gclid=CjwKCAjwyb3DBhBlEiwAqZLe5BA_GWSQJ5tfyrQ7w8ePu2f6PXj4owx00cJ5rOqxsw2uSIQt9oeblRoCNd4QAvD_BwE), [Google Play](https://play.google.com/store/games)平台，对于其具体操作在本文中不做赘述。

> Appmagic: Tap into the deepest market insights with our unparalleled classification  system, exclusive advertising analysis, and trendspotting features.  Do`t just track your competitors—get ahead of them. One might say it is magic!
>
> Insightrackr: Insightrackr is a mobile marketing strategy analysis platform that  delivers real-time insights to fuel faster, smarter user growth.
>
> Google Play: *Google Play* gives you one place to find, enjoy, &  share Apps, Music, Movies & Books - instantly anywhere across the  web & android devices.

## 过数据

根据「过数文档」，依次查看每个产品的每个campaign，并对每个campaign做出相应决策，如何做决策不在本文中讨论。

```mermaid
graph TD
start[Start] --> product["选择一个产品"]
product --> ROI("查看ROI拟合数据")
ROI --> CAR("查看收支数据")
CAR --> |宏观判断| campagin("选择一个计划")
campagin --> analyse("分析 spend ROI 留存 CPI 激活率 等数据")
analyse --> |需要调整| change("对预算，Goal, 素材等做出调整")
analyse --> |无需调整，下一计划| campagin
change --> |无需调整，下一计划| campagin
campagin --> |完成计划调整，下一产品| product
product --> |完成全部产品调整| ed[End]
```

## 素材

### 素材参考

从AppMagic中找到自家产品的竞品，找到体量最大的产品

在insightrackr上查找，按曝光量降序

素材的一般要求：

1. 简洁

2. 清晰

3. 时长20s～60s 

### 素材创意

