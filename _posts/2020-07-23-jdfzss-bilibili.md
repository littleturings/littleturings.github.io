---
layout: post
title: 暑期活动视频 Videos of online summer session
date: 2020-07-23
author: 詹有丘 Ulysses
---

<style>
iframe {
	width: 100%;
	height: 500px;
}
fieldset, legend {
	margin: 0;
	padding: 0;
	width: 100%;
	height: 100%;
}
</style>

本次暑期线上活动过程中，我们还录制了[视频](https://www.bilibili.com/video/BV1bZ4y1T7x9)（更新中，直到8月3日课程结束）。<br/>
We also recorded [the videos](https://www.bilibili.com/video/BV1bZ4y1T7x9)
(updating until courses end on August 3) during the online summer session.

{% capture lessons %}
1:
Python介绍及基础语法<br/>
Python intro & basic syntax

2:
序列与控制语句<br/>
Sequences & Control flow

3+4:
函数与面向对象编程<br/>
Functions & OOP

5:
大O表示法、链表（单双）、队列、哈希表<br/>
Big O notation, linked lists (single & double), queues, Hash

6+7:
递归与栈、查找基础、二分查找、线性查找<br/>
Recursion & stack, basic search, binary search, linear search

8:
冒泡排序、选择排序、插入排序、归并排序、快速排序<br/>
Bubble sort, selection sort, insertion sort, merge sort, quick sort

9:
树结构、二叉树查找、最小值、添加、删除<br/>
Trees, binary tree search, minimum value, add, delete

10:
字符串排序、查找、正则表达式、数据压缩<br/>
String sorting, search, regular expressions, data compression
{% endcapture %}

{% capture empty_line %}

{% endcapture %}

{% capture colon %}:
{% endcapture %}

{% assign lessons = lessons | split: empty_line %}

{% for lesson in lessons %}
{% assign parts = lesson | split: colon %}
{% assign name = parts[1] %}
{% assign pp = parts[0] | split: "+" %}
<details>

<summary>
<p>{{ name }}</p>
</summary>

<p>
{% for p in pp %}
<iframe src="//player.bilibili.com/player.html?aid=371476253&bvid=BV1bZ4y1T7x9&cid=215579849&page={{ p }}" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
{% endfor %}
</p>

</details>
{% endfor %}

喜欢的话请点赞、收藏哦！<br/>
Wish you like and collect it!
