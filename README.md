# 修改範圍
* 卡片部分
 * 增加  h-100 讓其等高
* 下方圖片文字部分
 * 增加row 使用格限系統

 ．請修正 X 軸

產生 X 軸的主要原因是因為使用 Bootstrap 的 .row (推薦景點) 少了外層的 .container 包住，因此需用 .container 包住 .row。

 

．行動版單欄式排版要呈現正常

因為 .row 包含了 display: flex; 和 flex-wrap: wrap; ，因此同學可將 .d-flex 移除喔。