# Swift 讀書會 Week 3
* Chp 7 - 寫程式前的規劃 — App原型設計
* Chp 8 - 建立一個簡單的表格App

---

# 為什麼要做Prototype(原型設計)

* Auto Layout是一個以約束條件為基礎的佈局系統（constraint-based layout system）
* 它讓開發者能夠開發一個能自我調整型的UI，可以依照螢幕的尺寸以及裝置的方向來調整。

---

# 先在紙上畫草圖吧
![](https://i.imgur.com/vlekyyd.png)

---

* 2007，Apple推出的最原始iPhone，3.5英吋、320×480像素的畫面解析度的顯示器。

* 之後Apple推出了iPhone 4搭配視網膜（retina）顯示器。畫面的解析度變成兩倍到640×960像素。也就是一個點相對應兩個像素。

* 這些點與像素間的轉換工作，則由iOS處理。

---

* 以Hello World按鈕為例，如果要把它擺在視圖中間應會得到兩個約束條件：
水平置中
垂直置中
這些約束條件顯示了按鈕在介面中的佈局。

---

# 使用POP來Prototyping
* 檔案檢閱器（File Inspector）中，勾選「Use Size Classes」功能來啟動它。提示出現後，點選「Enable Size Classes」來確認這個變更

---

# Hifi Prototyping：使用Pages或FramerJS

* Auto Layout選單。
* Control鍵加上拖曳。

* ![](https://i.imgur.com/6JZIm39.png)

每一個按鈕有它自己的功能：

Align – 建立對齊的約束條件，例如：對齊兩個視圖的左側。
Pin – 建立間距的約束條件，例如：訂出UI控制的寬度。
Issues – 解決佈局問題。
Stack – 視圖嵌入至堆疊視圖（stack view）。堆疊視圖是Xcode 7的新功能。

---

# 創建簡單的表格APP Demo

* 當有任何的佈局問題，文件大綱視圖會顯示出一個紅／橘色的揭露箭頭（disclosure arrow），按下這個揭露箭頭，你會看見問題清單。
* 介面建構器可以聰明地幫助我們解決佈局問題，點選問題旁邊的指示圖標，選取「Update Frame」選項，然後點選「Fix Misplacement」按鈕。按鈕便會移 到視圖中間。
* 另一種解決佈局的方式-Issue，如下圖所示
![](https://i.imgur.com/0glKXST.png)

---

# 上課影片






