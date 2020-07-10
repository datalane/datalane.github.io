---
title: "Training Daily Progress"
date: 2020-07-10
tags: [Excel, data, BI]
excerpt: "Author: Tao Jiang Publish Date: 07/07/2020"
mathjax: "true" 
category: Data-Visualization
comments: true
---
<br>Download Report: [Link](https://github.com/taojiangdt/Excel)
<br>Report Purpose:<font style="background:#E6E6E6">
<br>- Show segment results by Channel for current period(month or quarter) vs. last period vs. same period last year as well as YTD current period vs. last year.
<br>- Allow dynamic views for different time period chosed. For example,the current period in the below is Q2'14, when it changes to another quarter or another month,the report should change according without renaming, relinking orrebuilding the worksheet.
<br>- Accurancy checking.
</font> 
<br>Method:
<br>Formula: Vlookup(), IF(SUM()), SUMIF().


<!--<img src="{{ site.url }}{{ site.baseurl }}/images/Excel/dynamicExcelReport.jpg" alt="">-->
<!--<iframe width="900" height="500" frameborder="0" scrolling="no" src="https://onedrive.live.com/embed?resid=8B290B34D8C72783%211919&authkey=%21AI0EgLL6Qi5p6N4&em=2&AllowTyping=True&ActiveCell='Report'!X6&wdHideGridlines=True&wdInConfigurator=True"></iframe>-->

<iframe width="900" height="501" frameborder="0" scrolling="no" src="https://onedrive.live.com/embed?resid=8B290B34D8C72783%211995&authkey=%21AAjYfKUsbAYTnpc&em=2&wdAllowInteractivity=False&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True"></iframe>


{% comment %}
{% if jekyll.environment == "production" %}
   {% include discourse.html %}
{% endif %}



{{page.tags | capitalize | join: ', '}}
{% include Business-Intelligence.md %}
header:
  image: "/images/Excel/dynamicExcelReport.jpg"
{% endcomment %}
<!--
header:
  image: "/images/Excel/dynamicExcelReport.jpg"-->