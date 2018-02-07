---
layout: post
title: Markdown 用法
categories: [Web]
tags: 
  - Markdown
comments: true
summary:開臺聖祖的第一Po
---

##### 開臺聖祖的第一Po
### 這篇文章的功能
---
這篇文章主要的目的，將是提供我個人做Markdown語法紀錄的使用，待我完整將本部落格所引用參考頁面的Markdown語法都囊括於此後，即會將它們都刪除。  
它們 as 其他範例md檔。  
另外在我打完這篇文章後，發現了[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)，所以我的排版也跟著他稍微調整一下順序，希望本文也能成為初心者的小幫手。

### 範例開始
---
### 標題
標題前加上#即可成為標題

# H1
## H2
### H3
#### H4
##### H5
###### H6

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
---
### 項目清單
清單項目直接加米字號

* 例如這樣
* 例如這樣2

```
* 例如這樣
* 例如這樣2
```
---
### 引用
引用話語使用大於符號

> 例如這樣
>> 多層次
>>> 真的假的

```
> 例如這樣
>> 多層次
>>> 真的假的

```
---
### 文字強調
就是粗體斜體跟刪除號

**永遠單身**  
*邊緣人*  
~~男朋友~~  

```
**永遠單身**  
*邊緣人*  
~~男朋友~~
```
---
### 註解
像是這樣[^1]

[^1]: <http://google.com>
###### 這樣寫：
```
像是這樣[^1]

[^1]: <http://google.com>
```
---
### 文字超連結
簡單來說就是hyperlink(?)

說到[一半](https://help.github.com/articles/creating-and-highlighting-code-blocks/)呢
```
說到[一半](https://help.github.com/articles/creating-and-highlighting-code-blocks/)呢
```
---
### 聚焦圖片
封面圖片可加在文章開頭，但有可能是我這個Theme才有的功能

```
feature-img: "assets/img/pexels/desk-messy.jpeg"
thumbnail: "assets/img/thumbnails/desk-messy.jpeg"
```
---
### 圖片
插入圖片就對了

![Image of my gang]({{ site.baseurl }}/images/2018/01/canberra.jpg)
```
![Image of a glass on a book]({{ site.baseurl }}/images/2018/01/canberra.jpg)
```
---
### 欄位
這是一個我覺得超酷的功能

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```
---
### 程式語言示範

``` js
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}

```

    
```
```js
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}
```\
```

---
### 直接引用Github
能直接引用Github上公開的檔案

<script src="https://gist.github.com/mmistakes/77c68fbb07731a456805a7b473f47841.js"></script>
###### 這樣寫：
```
<script src="https://gist.github.com/mmistakes/77c68fbb07731a456805a7b473f47841.js"></script>
```
---

