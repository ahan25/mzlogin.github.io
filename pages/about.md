---
layout: page
title: About
description: Money's Back yard
keywords: Money's Back yard
comments: true
menu: 关于
permalink: /about/
---
## 声明

	1.本人过去、现在及将来都不认识此页文字所涉及的相关人物，自古与其无利益关系。此页文字完全是复制粘贴，来源国际互联网。

	2.此页文字涉及的事件与本人一点，一丝，一毫，半纳米…关系都没有。

	3.本人是文盲，并不明白此页文字的全部或部分意思（但不限于对文字的识别、阅读、理解、分析、记忆等等）。

	4.此页所有文字并不代表本人同意、支持或者反对观点。

	5.若此页文字违反国家有关法律、法规，行政命令、条例、文件、规定、协议、管理办法、解释说明等，请绿坝、GFW等牛B软件及时屏蔽；如未屏蔽，一切责任由此软件开发者承担。

	6.因屏蔽不及时所产生的任何法律（包括宪法、民法、刑法、书法、公检法、基本法、劳动法、婚姻法、输入法、引渡法、担保法、商标法、专利法、广 告法、国际 法、著作权法、吸星大法、今日说法、与台湾关系法及文中涉及或可能涉及以及未涉及之法，各地社会治安综合管理条例）纠纷或责任本人概不负责。

	7.本人谢绝任何跨小区，跨单位，跨村，跨乡，跨镇，跨区，跨省，跨国，跨星系等追捕行为，如有需要请直接联系文字出处原作者以及网络管理员或法 人代表。确因不抓不足以平民愤，或不抓就领不到薪水养家糊口的公职人员，建议携带工作证、身份证、结婚证/离婚证、独生子女证、健康证、暂住证、毕业证、 边防证、县以上 go-vern-ment机关出具的介绍信温情操作。抓捕按照以下排序倒序：文字出处原作者以及网络管理员以及网络运行商、电信运营商、电力供应商、电脑生产销售商。

	8.人生有风险，入世需谨慎。此页文字不暗示、鼓励、支持或映射读者做出生活方式、工作态度、婚姻交友、子女教育的积极或消极判断。未成年人请在监护人陪同下阅读本文。无完全民事行为能力者，请立即关闭网页。

	9.本人将于3分钟内完全忘记此页所有内容！故本人不能对该页内容负任何责任。

	10.此声明最终解释权归本人所有。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
