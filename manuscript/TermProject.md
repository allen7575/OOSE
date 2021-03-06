# Term project


基本要求
* 人數: 3-5/組
* 必須完成至少兩個遊戲，並從中探討重用性。
* 除了基本的遊戲規則必須完成以外。必須儘量應用物件設計的技巧達到程式碼重用、架構容易擴充等特點。
* 必須使用版本管理工具管理程式，如 CVS, Git, or Mercurial

## 系統需求

可以有兩個選擇：

1. 中國象棋, 台灣暗棋, 西洋棋 任選其二
2. 五子棋, 黑白棋, 蘋果棋 任選其二

基本功能: 
- 符合各棋類遊戲的規則
- 支援回合制比賽，並且可以讓使用者選擇幾戰幾勝
- 視窗化的遊戲介面

延伸功能:
悔棋、、遊戲存檔、網路對玩、手機介面、玩家可選擇照片、玩家限時設定、人機對戰

## Report

本計劃共需完成三項報告：
* R1: 系統規劃 
      1. 組員名單
      2. 主要內容：功能樹、功能特色、畫面規劃
      3. 書面報告 (R1-doc)
      4. 繳交時間：`開學後第三週`
* R2: 系統雛形
      1. 組員名單
      2. 可執行的系統雛形
      3. 主要內容：功能樹、品質樹、物件設計、設計說明、demo
      4. 繳交物：印出的投影片、上台報告（R2-slide, R2-represent)
      5. 繳交/報告時間：`期中考後兩週`
* R3: 期末報告
      1. 組員名單
      2. 最終修正後的系統
      3. 功能樹、品質樹、物件設計、設計說明、設計心得、demo
      4. 主要內容：上台報告、書面報告（參考下方R3 樣板)
      5. 繳交物：不印出的投影片、印出的書面報告、上台報告 (R3-doc, R3-slide, R3-represent)、code (from version control system)
      6. 繳交/報告時間：`期末考前一週`
      

## 指引與原則

#### 書面報告基本原則 (doc)
- 不要大量貼程式碼，必須以『設計圖』為主
      - Package diagram, Class diagram, activity diagram (flow diagram), sequence diagram

#### 投影片製作基本原則 (slide)
- 投影片內容以條列為主、不是整段文字
- 必須採用投影片樣板，以求一致
- 當我們用投影片報告設計時，會發現螢幕太小無法完整的呈現設計，這時候可以：
      - 先畫 package diagram 把系統的架構畫出來，注意要畫各 package 之間的`相依關係`。
      - 之後再畫每一個 package 的設計圖，如此就不會幾在一起很擁擠
      - 不要把所有的 method, attribute 都放上去。重點的方法放上去就好，例如 getter 與 setter method 就可以省略。

#### 上台基本報告原則 (represent)
- 每個人都要上台報告

R2
- 必須展示系統
- 需印出投影片，報告前時給老師。原則上兩頁一張的模式，但以圖形文字清晰為主。

R3 

- R3-doc 必須包含執行的畫面




