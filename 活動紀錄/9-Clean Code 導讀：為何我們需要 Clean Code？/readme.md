
# 活動資訊

**第 9 期 ：**<br>
**主題**：Clean Code 導讀：為何我們需要 Clean Code？<br>
**講者**：ShawnL<br>
**時間**：2020/06/21 早上 11:00<br>
**場地**：科技大樓 復興南路二段200號6樓-602室 <br>
**內容**：由 Robert C. Martin 所撰寫的 Clean Code，從不同的原則、模式與實作，再到實際重構、啟發，一步一腳印的帶領我們認識何謂 Clean Code。那麼，我們自己又是如何看待的呢？。<br>
**簡報**：[簡報](https://docs.google.com/presentation/d/e/2PACX-1vRQqjNXuQkAcw_HeHTS9hKV_05WY6r6b9RciTBTOPujGfrN5axA5g90OD8OZTtkU8_DX63ahBuRBn5v/pub?start=false&loop=false&delayms=60000)

# 前言
## 讀書會
- 聽到不同的觀點與經驗
- 學習如何分享技術
- 嘗試自己所不會的

## 實體聚會
- 脫離媒介
- 即時交流
- 工作坊

## 讀書會的場次
- 艾賓豪斯的遺忘曲線 Hermann Ebbinghaus
=> 驗證閱讀最適合用來建立長期記憶
=> 從不同角度
=> 不斷重複看到

## 如何導讀
事前準備
- 列出本章學習目標
- 列出要解決/回答的問題
- 整理出尚未釐清的問題

## 準備簡報（範例）
- 大章節為標題
- 小章節為簡報
- 塞入需要補充的內容
- 去蕪存菁
- 練習展示

## 導讀過程
- 分享：你所看到的
- 詢問：別人所看到的
- 討論：交流雙方的意見

## 其餘
- 安排中場休息時間
- 是否需要活動用具
- 是否需要投影、器具準備
- 準備工具控管時間

## 流程
- 主講導讀約 30-60 分（依章節、人數）
- 過程含互動、問題討論、工作坊
- 請每個成員花五分鐘總結今日活動，做共筆筆記

## 筆記術
- 推薦學習 markdown => 快速上手、快速做筆記、多平台支援

# markdown

標題
> #  一級標題
> ## 二級標題

列表
> - 無序列表
> * 無序列表
> 1. 有序列表

粗體、斜體
> *斜體*
> **粗體**

程式碼
> `程式碼`
>
> ```js
> console.log('Markdown.')
> ```

連結、圖片
> [顯示文字](連結網址)
> ![](圖片網址)

註記、引言
> 單層
> > 雙層

# Clean Code 導讀

## 為何我們需要 Clean Code
工程師目的在於解決問題，但如果今天需要靠程式碼解決的時候：
- 想一下維護專案看程式碼的時間
- 多人共同開發、開源合作
- 在意小事，成就大業
> 5S 精神：整理（seiri）、整頓（seiton）、清掃（seisou）、清潔（seiketsu）、躾（shitsuke）
- bad smell

### bad smell
```js
a = 3
b = 2

if (b < a){
  doit()
} else
{
  dontdoit()
}

function doit(){
  console.log('success.')
}

function dontdoit(){console.log('failure.')}
```

## Clean Code 簡易現場實作
- 範例一
```js
a = 3
b = 2

if (b < a){
  doit()
} else
{
  dontdoit()
}

function doit(){
  console.log('success.')
}

function dontdoit(){console.log('failure.')}
```
- 範例二
```js

```

## 反思

# 參考項目

- [第一次讀書會導讀該怎麼做](https://medium.com/@fong1143/%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%AE%80%E6%9B%B8%E6%9C%83%E5%B0%8E%E8%AE%80%E8%A9%B2%E6%80%8E%E9%BA%BC%E5%81%9A-ba050b993319)
- [讀書會的組織與運作](https://www.ouk.edu.tw/Uploads/%E8%AE%80%E6%9B%B8%E6%9C%83%E7%9A%84%E7%B5%84%E7%B9%94%E8%88%87%E9%81%8B%E4%BD%9C.pdf)
- [遺忘曲線](https://zh.wikipedia.org/wiki/%E9%81%97%E5%BF%98%E6%9B%B2%E7%BA%BF)
- [嚮往美感的讀書會](https://medium.com/@raphee121/%E8%AE%80%E6%9B%B8%E7%AD%86%E8%A8%98-%E5%9A%AE%E5%BE%80%E7%BE%8E%E6%84%9F%E7%9A%84%E8%AE%80%E6%9B%B8%E6%9C%83-99%E5%89%87%E7%B6%93%E7%87%9F%E8%AE%80%E6%9B%B8%E6%9C%83%E6%99%BA%E6%85%A7%E5%BF%83%E6%B3%95-%E4%B8%8A-db03539c665c)
