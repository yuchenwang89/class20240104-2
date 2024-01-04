---
title: 參考 - 網頁魔法起手式 JavaScript (被引用)
tags: JavaScript,君邑資訊
description: 網頁魔法起手式 JavaScript
---
<style>
    .footnotes-list{
        font-size: 1rem;
    }
    hr.footnotes-sep {
        height: auto !important;
        border-top: 0px solid #eee !important;
        margin-bottom: 0rem !important;
    }
    li>p {
        margin-top: 0.25rem !important;
        margin-bottom: 0.25rem !important;
    }
</style>


## 開始之前

本教學使用環境：

- Browser : Google Chrome
- Editor  : [JSFiddle: https://jsfiddle.net](https://jsfiddle.net/)

### 認識 JavaScript

#### 演進

最初由 Brendan Eich 在 1995 年創造，最初名為 LiveScript，是 Netscape 為了增加網頁的互動性而與 Sun Microsystems 合作的產物最後定名為 JavaScript。

而後微軟在 IE3 中開始支援 JavaScript，並且在與 Netscape 競爭的過程中進一步推動了 JavaScript 的發展和標準化。

#### 標準

1997 年為了建立 JavaScript 標準 ECMA 發布了第一個 JavaScript 標準，稱為 ECMAScript1 而後 ECMAScript 不斷地發展和改進並發布新的標準。

1999 - ECMAScript 3（ES3）
2009 - ECMAScript 5（ES5）
2015 - ECMAScript 6（ES6 / ES2015）
2016 - ECMAScript 2016（ES2016）

而後開始以年份作為標準的版本名稱。

瀏覽器支援 ES 版本參考
![](https://hackmd.io/_uploads/BkVPOIer2.png)

#### JavaScript 小百科

因為名稱與 Java 相近，常常會被混淆誤認與 Java 是同一種程式語言。

JavaScript 屬於直譯式程式語言（簡稱JS）無需預先編譯即可執行，可在 Client 端執行也可在 Server 端執行（例如：NodeJS），它一開始主要是用來建立互動式網頁的程式設計語言（例如：各式選單、滑鼠效果、拖曳、顏色或是樣式改變等），能夠賦予網頁互動性、動態效果和數據處理能力，與HTML、CSS搭配更能提高和優化使用者的使用體驗。

#### 應用

##### 在網頁上的應用：

- 動態文字
- 物件控制
- 事件控制
- 資料檢核
- 讀寫Cookie

###### 讓 JavaScript 負責處理一些 Client 端的資料加工或是檢核可以有效降低 Server 端的負荷，但也可能因此產生安全性議題，需要小心謹慎。

##### 在行動裝置上的應用：

- AngularJS<!-- 由Google維護的開放JavaScript函式庫，用來協助單一頁面應用程式運作，曾經紅極一時不過目前已停止維護。 -->
- React（ReactJS/React.js）
- Vue

#### 特色

##### 動態型別

不需要事先聲明變數的型別就可以執行依照需要動態給值，讓開發變得更具彈性，靈活使用。

##### 直譯式語言

無需事先編譯即可執行，在開發階段方便除錯和優化調整，提升開發速度。

##### 物件導向

支援物件導向程式設計，開發者可以使用物件、類別、繼承等概念來組織和結構化程式，提供程式碼可重複利用和模組化的特性。

##### 事件和非同步

在網頁開發中廣泛使用事件和非同步處理。透過事件引發可即時回應用戶操作和其他事件的發生，同時利用非同步的方式處理網路請求和資料庫查詢等操作，提升應用程式的效能和反應能力。

<!--
同步 https://zh.wikipedia.org/zh-tw/%E5%90%8C%E6%AD%A5
非同步 https://zh.wikipedia.org/zh-tw/AJAX 代表
-->

##### 網頁互動性

透過 DOM（Document Object Model）和瀏覽器 API，你可以動態操作網頁元素、修改內容、應用動畫效果和響應用戶操作。

##### 跨平台

可以在各種環境中執行，包括瀏覽器、伺服器（使用 Node.js）、行動裝置和桌面應用程式。
