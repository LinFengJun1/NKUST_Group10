# NKUST_Group10
 |        學號      |       姓名         |  
 | :-------------: | :-------------: |  
 | C108118233 | 劉家寧(組長)      |  
 | C108118202 | 陳文彥            |  
 | C108118220 | 羅欣寶            |  
 | C108118232 | 林楓竣            |  
 | C108118238 | 陳楷軒            |  
 | C108118249 | 林沛晴            |  
---
# 題目：求職整合平台
## 內容：    
> 身為社會新鮮人的你，在剛出社會開始找工作時，是否感到十分迷網，不知道到底該如何選擇「第一份工作」呢？不知道什麼樣的工作適合自己、又怕找到的工作跟心中理想不符合嗎？
>> 那求職整合平台正是你的好選擇！！整合各種職缺，並提供條件、距離等篩選功能讓用戶能發現更符合自己需求的職缺再投履歷，不用再怕亂槍打鳥的第一份工作就踩雷。
---
## 分工：   
| 收集資料 | 羅欣寶 | 
| :------------- | :------------- | 
| 建立資料庫 | 陳楷軒、林沛晴 | 
| 網頁設計 | 陳文彥、林楓竣 | 
| 撰寫使用者說明書 | 劉家寧 | 
| 系統整合、測試 | 全員 | 
---
## 甘特圖
![甘特圖](甘特圖.jpg)   
[甘特圖](https://hackmd.io/@isLy0nG2SxyJIpSQVodlwA/BJr2Os9HY)

## PERT/CPM圖
![PERT](PERT-CPM.PNG)
   
---   
## 功能性需求：
1. 依照條件的職缺顯示 (排序)
2. 有條件設定的職缺搜尋 (篩選)
3. 範圍指定的職缺搜尋 (定位)   

## 非功能性需求：
1. 反應時間：1筆資料1分鐘內
2. 使用性：使用容易
3. 可靠度：高，使用者不能隨意修改網站內容
   
---
## 功能分解圖   
![功能分解圖](功能表.png)
   一個求職整合平台系統的需求分析簡述如下：
1. 使用者藉由登入帳號進入網站操作
2. 使用者利用個人履歷表來輸入自己的履歷以方便公司瀏覽
3. 使用者根據需要的條件進行篩選找到符合自身需求的職缺
4. 顯示整合完畢的查詢結果
---   
## 使用案例圖   
![甘特圖](使用案例圖.png)   
![甘特圖](管理者使用案例圖.png)
---   

## DFD圖   
![DFD圖](DFD圖.jpg)

---
## DFD圖0
![DFD圖0](DFD圖0.png)

---

## UML類別圖
![UML類別圖](UML.jpg)
   
---

## 活動圖
### 查詢履歷(對應使用案例名稱-填寫個人履歷表)
![活動圖1](活動圖1.png)  
  
### 查詢職缺(對應使用案例名稱-依照條件篩選)
![活動圖2](活動圖2.png)   
  
### 管理者更新維護資料
![活動圖3](活動圖3.png)
---   

## 循序圖
### 查詢履歷(對應使用案例-填寫個人履歷表)
![循序圖1](循序圖1.png)   
   
### 查詢職缺(對應使用案例名稱-依照條件篩選)
![循序圖2](循序圖2.png)   
  
### 管理者更新維護資料
![循序圖3](循序圖3.png)
  
  
---
## 分鏡圖
![首頁](首頁登入前後.png)
![功能](功能.png)
![註冊和登入](註冊登入.png)
![個人資料](個人資料.png)
![履歷新增/修改](履歷增改.png)
![條件篩選](職缺搜尋.png)
![職缺類別通知](職缺類別通知.png)
![歷史紀錄](功能.png)
![客服](客服.png)
![指定範圍](區域搜尋.png)
---
## 實體關係圖   
![實體關係圖](實體關係圖.png)

---
## 使用案例說明   
| 使用案例名稱	| 填寫個人履歷表 | 
| :------------- | :------------- | 
| 行動者	| 使用者 | 
| 說明	| 建立/更新個人履歷表 | 
| 完成動作	| 1.　編輯填寫個人資料 <br>2.　完成並送出資料 | 
| 替代方法	| 1.　編輯填寫個人資料 <br>2.　填寫錯誤無法送出，系統傳送錯誤訊息 | 
| 先決條件	| 使用者須先登入 | 
| 後置條件	| 第一次填寫完畢後，之後查看&更新 | 
| 假設	| 無 |    

| 使用案例名稱	| 指定距離範圍 | 
| :------------- | :------------- |  
| 行動者	| 使用者 | 
| 說明	| 描述使用者點擊「指定距離範圍」的過程 | 
| 完成動作	| 1. 使用者點擊選單上的「指定距離範圍」<br>2. 輸入縣市、區域<br>3. 系統將會顯示該範圍的公司資訊 | 
| 替代方法	| 1. 使用者點擊圖文選單上的「指定距離範圍」<br>2. 輸入縣市、區域<br>3. 系統傳送錯誤訊息 | 
| 先決條件	| 使用者必須先輸入「地區」 | 
| 後置條件	| 查詢完畢後，使用者可繼續查詢其他地區資訊 | 
| 假設	| 無 |    

| 使用案例名稱	| 依照條件篩選 | 
| :------------- | :------------- |  
| 行動者	| 使用者 | 
| 說明	| 描述使用者點擊「依照條件篩選」的過程 | 
| 完成動作	| 1. 使用者點擊選單上的「依照條件篩選」<br>2. 選擇職務、工作性質<br>3. 系統將會顯示符合需求的公司資訊 | 
| 替代方法	| 1. 使用者點擊圖文選單上的「指定距離範圍」<br>2. 選擇職務、工作性質<br>	3. 系統傳送錯誤訊息 | 
| 先決條件	| 使用者必須先選擇「職務」或「工作性質」 | 
| 後置條件	| 查詢完畢後，使用者可繼續查詢其他職務或薪資需求 | 
| 假設	| 無 | 
---
## 求職整合平台_第十組簡報 
![求職整合平台_第十組](第10組.pptx)
