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

尾巴部分還沒有改成不用flex，記得再回來改！

用padding-top撐出高度然後內容絕對定位試試看好了

* day07 導覽列

>transform不作用在inline元素上，所以day07那邊才會有bug，a改成inline-block之後就完成了

下一個

https://www.youtube.com/watch?v=9xT8kziyYko