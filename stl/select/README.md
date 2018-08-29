﻿# &lt;stl:select&gt; 下拉列表

```html
<stl:select
channelIndex="栏目索引"
channelName="栏目名称"
groupChannel="指定显示的栏目组"
groupChannelNot="指定不显示的栏目组"
groupContent="指定显示的内容组"
groupContentNot="指定不显示的内容组"
isChannel="是否显示栏目下拉列表"
isColor="仅显示醒目内容"
isDynamic="是否动态显示"
isHot="仅显示热点内容"
isRecommend="仅显示推荐内容"
isTop="仅显示置顶内容"
openWin="选择是否新窗口打开链接"
order="排序"
queryString="链接参数"
scope="选择的范围"
tags="指定标签"
title="下拉列表提示标题"
titleWordNum="标题文字数量"
topLevel="从首页向下的栏目级别"
totalNum="显示数目"
upLevel="上级栏目的级别"
where="获取下拉列表的条件判断">
</stl:select>
```

## 使用说明

通过 stl:select 标签在模板中显示栏目或内容下拉列表

stl:select 用于显示由栏目或内容标题组成的下拉列表，选择下拉列表中的项后页面转到对应的页面。

所有属于 HTML 标签 &lt;select&gt; 的成员均适用于 `<stl:select>` 标签。

title 属性代表下拉列表中的第一项，如果未设置此属性，第一项为内容列表第一项的标题。

如果设置了 channelIndex 属性，系统将寻找对应此栏目索引的栏目并显示此栏目的内容列表。
如果设置了 channelName 属性，系统将寻找对应此栏目名称的栏目并显示此栏目的内容列表。

`<stl:select>` 标签对应的实体为{stl:select}。

## 属性

| 属性            | 说明                   |
| --------------- | ---------------------- |
| isChannel       | 是否显示栏目下拉列表   |
| channelIndex    | 栏目索引               |
| channelName     | 栏目名称               |
| upLevel         | 上级栏目的级别         |
| topLevel        | 从首页向下的栏目级别   |
| scope           | 选择的范围             |
| groupChannel    | 指定显示的栏目组       |
| groupChannelNot | 指定不显示的栏目组     |
| groupContent    | 指定显示的内容组       |
| groupContentNot | 指定不显示的内容组     |
| tags            | 指定标签               |
| order           | 排序                   |
| totalNum        | 显示数目               |
| titleWordNum    | 标题文字数量           |
| where           | 获取下拉列表的条件判断 |
| queryString     | 链接参数               |
| isTop           | 仅显示置顶内容         |
| isRecommend     | 仅显示推荐内容         |
| isHot           | 仅显示热点内容         |
| isColor         | 仅显示醒目内容         |
| title           | 下拉列表提示标题       |
| openWin         | 选择是否新窗口打开链接 |