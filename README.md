#Markdown

>网上关于Markdown的介绍和入门指南已经很多，再写一份似乎显得多余，但对于我自己来说，写这样一份文档是对自己的Markdown掌握情况的检验，也是为推广Markdown贡献力量。
如有错漏之处，还请指出。

##1.What
Markdown是一种轻量级标记语言。用来在输入文本的同时完成格式的编辑以及图片超链接的插入等工作。

##2.Why
- 在写作时，对于格式的编辑往往会打断思路，影响本来顺畅的行文。而使用Markdown写作则可以避免这种麻烦，整个过程中甚至可以做到全键盘操作，不需要使用鼠标甚至触摸板，大大***提高写作效率***。

- 现在的写作软件如Word、Pages，强大全能，但同样复杂臃肿。对于普通的文字写作来说，有大量功能是用不到的，反而会造成不便。Markdown作为一种标记语言，***对编辑器无要求***，文本可以在任何地方输入，之后使用软件转成html或者pdf即可。

- 作为纯文本，***分享时只需传送原文***，一来整个文件非常小，以k计；二来文本已经包括对格式的说明，收到的一方在查看时，原文的内容和格式并不会因为使用软件的差异而产生大的区别，这对于需要协作编辑的文本十分重要。

- Markdown可以***直接导出***成HTML、PDF等格式，兼容性及拓展性很强。


##3.How
###3.1 Markdown语法

- ###标题
                # 一级标题
                ## 二级标题
                ### 三级标题
                #### 四级标题
                ##### 五级标题
*效果是：*
>#一级标题
>## 二级标题
>### 三级标题
>#### 四级标题
>##### 五级标题
        
- ###强调
                *斜体*
                **粗体**
                ***粗斜体***
*效果是：*
> *斜体*
> **粗体**
> ***粗斜体***

- ###序列
                有序序列：
                1.内容
                2.
                3.
        
                无序序列：
                - 内容
                -
                -
                或
                * 内容
                *
                *

- ###引用
                >引用内容
        *效果是：*
        > >引用内容

- ###分隔
                ----------------
                ================
                ****************
                任意一种符号；符号的数量大于两个。
        *效果是：*
        > ------------------

- ###代码段
                按tab键
                或
                ```代码段```
        *效果是：*
        >```代码段```
        
- ###删除
                ~~删除内容~~
        *效果是：*
        >~~删除内容~~
        
- ###链接和邮件
                <邮箱地址>
                        <example@gmail.com>
                <网址>
                        <http://zhusunbg.duapp.com/yocson>
                [说明](网址)
                        [豆瓣](www.douban.com)
                [说明][序号]
                [序号]: 网址 （此句可在文档任意位置）
                        [豆瓣][1]
                        [1]: http://www.douban.com
        *效果是：*
        ><example@gmail.com>
        ><http://zhusunbg.duapp.com/yocson>
        >[豆瓣](http://wwww.douban.com)
    >[豆瓣][1]
[1]: http://www.douban.com

- ###图片
                ![说明]（网址)
                        ![重庆](http://img5.douban.com/view/photo/photo/public/p2181560267.jpg)
                ![说明][序号]
            [序号]: 网址 (此句可在文档任意位置)
        *效果是：*
        >![重庆](http://img5.douban.com/view/photo/photo/public/p2181560267.jpg)
        
        
- ###表格
                |标……题|标……题|标……题|
                |:---|:---:|----:|
            |左对齐|居中|右对齐|
            “：”的位置控制对齐方式
                
        *效果是：*
        >
        |标……题|标……题|标……题|
        |:---|:---:|----:|
    |左对齐|居中|右对齐|
    
- ###脚注
                内容[^序号]
                [^序号]：解释
        *效果是：*
        >内容[^1]
        
[^1]:相关解释

- ###输入原符号
                由于markdown使用了一些符号作为标记符，所以如想输入原符号，需在前面加一个“\”
        *效果是：*
        > \* \#
                

### 3.2 Markdown工具
###Mac：
[Mou](http://mouapp.com/)
>国人制作的一款非常优秀的软件，免费。入门建议使用。
![](http://mouapp.com/images/Mou_Screenshot_1.png)

[Ulysses III](http://www.ulyssesapp.com/)
>很专业，评价很高，但需购买。后期可以考虑使用。
![](http://www.ulyssesapp.com/img/screens/UL-iMac-overlay-01.png)

###IOS：
[Evermark](http://esoftmobile.com/evermark/)
>国内开发者做的小应用，轻量便捷，我一直在用。唯一的遗憾是没有iPad版，但我问了开发者，他答复新版本将会支持，会尽快发布。
![](http://esoftmobile.com/evermark/screenshot1.PNG)

[WordEver](http://wordever.info/)
>在找iPad端编辑器时发现的，键盘的功能非常强大。缺点是不支持中文，如果纯英文写作推荐这个软件。
![](http://wordever.info/images/slider/ipad-mini.png)

###Windows：
[MarkdownPad](http://www.markdownpad.com/)
>![](http://www.markdownpad.com/img/markdownpad2.png)

[MarkPad](http://code52.org/DownmarkerWPF/)
>![](http://code52.org/DownmarkerWPF/screenshot.png)
>由于我不是用Windows，所以以上两个软件仅作参考。

###Web:
[马克飞象](http://maxiang.info/)
>专为印象笔记打造，输入完直接保存到印象笔记。也有Chrome的拓展应用。
![](http://cl.ly/image/401z311c3t1w/Image%202014-05-09%20at%2010.25.38%20PM.png)

[简书](http://jianshu.io/)
>专业的写作网站，并大力推广Markdown写作。
![](http://ww4.sinaimg.cn/large/687afc7fjw1dzs5crii94j.jpg)

### 3.3 图片链接获取方法
- 如果是网络图片，直接右键图片，选择复制图片URL即可。
- 如果是本地图片，可以选择[Cloudapp](http://www.getcloudapp.com/)，免费账户是每天10张，每张不超过25M,基本够用。（Mac）

##延伸阅读
- [為什麼文科生也該用markdown寫作?](http://www.douban.com/note/221187015/)
- [为什么作家应该用 Markdown 保存自己的文稿](http://jianshu.io/p/qqgjln)
- [Markdown小技巧集合](http://www.yangzhiping.com/tech/markdown-tips.html)
