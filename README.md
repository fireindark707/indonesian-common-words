# 印尼语高频词汇

印尼语常用单词及中文解释、例句   
Commonly used Indonesian words with Chinese explanations and example sentences

## 使用说明

请直接下载 [dictionary.json](https://github.com/fireindark707/indonesian-common-words/blob/main/dictionary.json) , 可以用各类型文本编辑器打开阅读（浏览器也可以）。   
栏位：
- word：印尼文原词语
- meaning：中文词意
- explanation：词性解释及使用说明
- examples：例句及中文翻译
- rank：词频排序，数字越小代表词频越高，越应该优先掌握

目前收录高频词语前2000单词，会逐渐扩充。

例子：
```
"bahas": {
    "word": "bahas",
    "meaning": "讨论；解释",
    "explanation": "在印尼文中，bahas是一个动词，常用于表示讨论或解释某个话题或问题。",
    "examples": [
        "我们需要讨论一下这个计划的细节。 (Kita perlu membahas detail rencana ini.)",
        "老师正在解释新的课程内容。 (Guru sedang membahas materi pelajaran baru.)",
        "我们需要解释一下这个术语的含义。 (Kita perlu membahas makna istilah ini.)",
        "这个问题需要我们认真讨论。 (Masalah ini perlu kita bahas dengan serius.)"
    ],
    "rank": 1518
},
"dewasa": {
    "word": "dewasa",
    "meaning": "成年的；成熟的",
    "explanation": "在印尼文中，dewasa是一个形容词，用于描述一个人或事物已经到达成年或成熟的状态。",
    "examples": [
        "他已经成年了，可以独立生活了。 (Dia sudah dewasa, bisa hidup mandiri.)",
        "这个问题需要成熟的思考和决策。 (Masalah ini memerlukan pemikiran dan keputusan yang dewasa.)",
        "只有成年人才可以参加这个比赛。 (Hanya orang dewasa yang boleh mengikuti perlombaan ini.)",
        "成熟的人应该有自己的判断力和责任心。 (Orang dewasa seharusnya memiliki kemampuan untuk membuat keputusan dan tanggung jawab yang tinggi.)"
    ],
    "rank": 1511
},
"dengan": {
    "word": "dengan",
    "meaning": "和；与；同；用；通过",
    "explanation": "在印尼文中，dengan是一个介词，可以表示“和”、“与”、“同”、“用”、“通过”等含义。它用于连接两个或多个人、物或动作，表达它们之间的关系或方式。",
    "examples": [
        "我和朋友去了电影院。 (Saya pergi ke bioskop dengan teman.)",
        "他用英语和我交流。 (Dia berkomunikasi dengan saya dalam bahasa Inggris.)",
        "我通过电子邮件联系他。 (Saya menghubunginya dengan email.)",
        "他们一起工作。 (Mereka bekerja bersama dengan.)"
    ],
    "rank": 4
},
```
## 制作方法

1. 语料来自KASKUS（印尼网络论坛），包括新闻、娱乐、故事、食物旅游四个板块的共11000则帖文。每则帖文的标题、内容和留言被纳入语料计算。
2. 词语以空格进行切分，去除常见标点符号后筛选3个及以上字符长度的单词计算词频。单词总量786万。
3. 中文解释及例句由ChatGPT提供。

## 说明

1. 单词表经过印尼朋友确认，绝大多数例句都是正确的，单词词频也符合日常使用。
2. 例句中常见的Saya为正式表达，日常使用Aku比较好。
3. 三个字符长度的单词许多是缩写，涉及现实中专有名词的缩写错误率较高。如果不想学习这部分可直接略过，只看4个字符以上长度的单词。

## 掌握多少印尼语单词是足够的？

以下为词频前n单词在所有文本中的覆盖度（最大为1，数字越大越好）。  
一般说法认为掌握一篇文章的95%的单词意思，就可以读懂文章内容。也就是说如果要读懂绝大多数KASKUS论坛上的文章和留言，你需要约20000单词量。但是因为印尼语中的前缀后缀变化较多，理解一个词语的部分变化形式就可以推估其它变形下的词意，所以现实学习中应当不需要掌握这么多词语，可能10000单词量左右即可。从下方计算结果可以看出，掌握前4000单词，就可以认识印尼文章中的80%词语，达成初步理解。

Top 1000 words coverage: 0.6113853298140143   
Top 2000 words coverage: 0.7121990875286419   
Top 3000 words coverage: 0.7657901112290777   
Top 4000 words coverage: 0.8012088158739885   
Top 5000 words coverage: 0.82690515550389   
Top 6000 words coverage: 0.8464883238479337   
Top 7000 words coverage: 0.8621900025142841   
Top 8000 words coverage: 0.8751409831359739   
Top 9000 words coverage: 0.8860628499766385  
Top 10000 words coverage: 0.8953767710688354   
Top 11000 words coverage: 0.9033638219968302  
Top 12000 words coverage: 0.9103116948819558  
Top 13000 words coverage: 0.9164275382308601  
Top 14000 words coverage: 0.9218391021053821  
Top 15000 words coverage: 0.9266658658960267  
Top 16000 words coverage: 0.9310107676506305  
Top 17000 words coverage: 0.9349440444549857  
Top 18000 words coverage: 0.9384949617615054  
Top 19000 words coverage: 0.9417144160091695  
Top 20000 words coverage: 0.9446419791792847  
