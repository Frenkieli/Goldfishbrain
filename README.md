# Goldfishbrain
===

## 金魚腦30天練習（要加簡單RWD喔！）
---
就是不要斷點這種！

* day01 圖文滿版設計

>漸層色的運用，多個背景如何堆疊

* day02 格子窗的應用

>hover運用，和四個動畫的運用
>
>>opacity transform transform-origin clip-path 四種

* day03 卡片式人員介紹應用

>運用flex和 clip-path改寫成可以伸縮的方式(但是ie edge系列不能用)
>也可以做一個三角形的svg然後寬度高度100%支援度應該會高一點
>背景設在父層給圖片高度60%之類的父層在hover後40%漸層

* day04 交錯漂浮式版面

>運用選取器讓第一個div的margin-right: -10%;
>
>然後flex的flex-shrink伸縮比製作出來的

* day05 超通用橫式版面

>改寫成在包一個box然後用padding做間隔後做%數！padding做間隔真的很好用！

```css
    margin-top: auto;
    /* 左右butto對齊喔! */
    box-shadow: 0 10px 30px rgba(160, 0, 0, .5);
    /* 讓陰影帶點背景色會更好看！！ */
```
下一篇

* day06 網頁頁尾板塊

>尾巴部分還沒有改成不用flex，記得再回來改！
>
>用padding-top撐出高度然後內容絕對定位試試看好了

* day07 導覽列

>transform不作用在inline元素上，所以day07那邊才會有bug，a改成inline-block之後就完成了
>動畫跳動要多包一層不想管= =

* day08 變化你的導覽列

>姆...好吧，這個之後再重寫= =

* day09 網站麵包屑

>這個主要是選取器，就麵包屑

* day10 方塊酥版面

>方塊酥，練習float

* day11 破格式設計

>半圓形邊框可以用偽元素後設定４個邊框後兩個邊透明再變形旋轉

* day12 表格怎麼切

>表格caption用的css，可以控制在上面還是下面
```css
    caption-side: bottom;
```

* day13 側邊選單怎麼切

>基礎觀念

* day14 收合式側邊選單

>選取器應用

* day15 多層次收合選單

>選取器的原理應用

* day16 訂單進度條

>偽元素運動

* day 17 登入表單

* day22 文字排版-上集

```css
    column-count: 2;
    column-gap: 30px;
```


下一個

https://www.youtube.com/watch?v=G5MA36MboNw&list=PLqivELodHt3hxeuLX8PYaI8u1GcDaBoJo&index=18