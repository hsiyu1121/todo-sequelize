# 我的餐廳清單_登入版(2020/08/23)

使用Node.js, Express, Sequelize, MySQL 套件製作而成

![Alt text](https://github.com/hsiyu1121/todo-sequelize/blob/master/todo-sequelize.png)

## 功能清單
* 使用者可以註冊自己的帳號 
* 使用者操作錯誤，會給予適當的回應
* 使用者可以透過 Facebook Login 直接登入 
* 使用者可以建立並管理自己的餐廳清單 
* 點選"Todo List"即可回到首頁
* 使用者可以新增一個新的待辦事項
* 使用者可以瀏覽一個待辦事項
* 點選"Todo List"即可回到首頁
* 使用者可以瀏覽所有待辦事項
* 點選"Todo List"即可回到首頁
* 使用者可以修改一個待辦事項
* 使用者可以刪除一個待辦事項


## 環境需求
* Node.js: v10.15.0
* express: v4.17.1
* sequelize: v6.3.5
* sequelize-cli: v6.2.0

## 啟動方式
* 將專案下載至本機內

  ``git clone https://github.com/hsiyu1121/todo-sequelize.git``
* 切換至資料夾內

  ``cd todo-sequelize``
* 安裝相關的套件

  ``npm install``
* 建立資料庫

  ``npx sequelize db:migrate``
  
*執行Seeder

  ``npx sequelize db:seed:all``
* 透過node執行程式

  ``npm run start``
* 透過nodemno執行程式

  ``npm run dev``
* 開啟瀏覽器輸入以下網址

  ``http://localhost:3000``
  
## 測試帳號密碼清單
<table>
  <tr>
    <td>Email</td>
    <td>Password</td>
  </tr>
  <tr>
    <td>root@example.com</td>
    <td>12345678</td>
  </tr>
</table>
