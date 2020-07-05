---
layout: post
title: 加入我们 How to join
date: 2020-07-04
author: 詹有丘 Ulysses
---

首先，你需要[联系我们][contact]。我们会让你成为[小小图灵社的GitHub组织][github]的一员。<br/>
First, you need to [contact us][contact].
We will make you member of [GitHub organization of Little Turings][github].

然后，在你的计算机上克隆此站点（你将需要用到[Git](https://git-scm.com){:target="_blank"}）：<br/>
Then, clone this site on your computer
(you should use [Git](https://git-scm.com){:target="_blank"}):
```shell
git clone https://github.com/littleturings/littleturings.github.io.git
```

发布一则帖子宣布你的加入。如果你熟悉Git和命令行的话，这将只需要烧一壶水的时间。在命令行运行：<br/>
Create a post to announce your joining.
If you are familiar with Git and command line,
it will take no more than the time required to boil a pot of water.
Run on command line:
```shell
cd littleturings.github.io
touch _posts/YYYY-MM-DD-NAME.md
```
其中`YYYY-MM-DD`是日期，`NAME`是你的英文名（小写）。<br/>
where `YYYY-MM-DD` is the date,
and `NAME` is your English name (lower case).

现在你创建了一个文件。用纯文本编辑器打开它，填入这样的内容：<br/>
Now you have created a file.
Open it with a text editor, and write:
```markdown
---
layout: post
title: 新成员NAME_CN New member NAME_EN
date: YYYY-MM-DD
author: NAME_CN NAME_EN
---

...
```
其中`NAME_CN`是你的中文名，`NAME_EN`是你的英文名（首字母大写），`YYYY-MM-DD`是日期，`...`是新帖子的正文，你可以填入任何内容（使用Markdown语法）。正文中的内容最好是中英双语的，中文和英文之间用`<br/>`分隔。两个自然段之间间隔一个空行。<br/>
where `NAME_CN` is your Chinese name, `NAME_EN` is your English name (whose initial is capitalized),
and `...` is the main contents (in Markdown syntax).
You had better write the main contents in both Chinese and English, with `<br/>` separating
Chinese part and English part.
There should be empty lines between paragraphs.

例如，在文件`2020-01-01-jack.md`中写道：<br/>
For example, in file `2020-01-01-jack.md`:
```markdown
---
layout: post
title: 新成员张三 New member Jack
date: 2020-01-01
author: 张三 Jack
---

大家好，我是张三。很高兴来到这里。<br/>
Hello. My name is Jack. I am glad to be here.

我希望能和大家一起交流编程问题。<br/>
I want to discuss problems about programmes with you.
```

写完之后，发布它：<br/>
After you finish writing, publish it:
```shell
git pull
git add **/*
git commit -m "MESSAGE"
git push -u origin master
```
其中`MESSAGE`是你的提交信息。建议填写`New member NAME`，其中`NAME`是你的名字。你会被要求登录GitHub。<br/>
where `MESSAGE` is the commit message, which is recommended to be `New memeber NAME`,
where `NAME` is your name. You will be required to login GitHub.

如果顺利的话，几秒后访问[主页](/)，你将顺利地看到你刚刚发布的帖子。<br/>
If everything goes well, visit [the home page](/) a few seconds later,
and you will see the post you have just published.

[contact]: /contact
[github]: https://github.com/littleturings
