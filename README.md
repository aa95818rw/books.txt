## books.txt


## 專題名稱:
書籍類別分類網站  

## 組員
班級:資工二B  
學號:4070E074 4070E075  
姓名:林柏霆   張景韋  

## 專題規劃
首頁 新增書籍資料 修改書籍資料 刪除書籍資料 書本內容簡介 (按鈕鍵 點擊進入選單畫面)  
首頁>>功能選項 包含:回到首頁 訂閱周刊 加入會員 最新消息 關於我們 查詢書籍名稱/編號 後臺管理(新增.修改.刪除)   
新增書籍資料裡面 包含:書籍編號 書籍名稱 出版社 價格 作者 書籍類型(奇幻 武俠 紀錄片......等) >>儲存/取消  
修改書籍資料裡面 包含:書籍編號 書籍名稱 出版社 價格 作者 書籍類型(奇幻 武俠 紀錄片......等) >>儲存/取消  
刪除書籍資料 :點擊跳出提示框"是否確定刪除該書本資料 確定/取消" "確定>>已刪除該書本資料 取消>>關閉刪除視窗"  
書本內容簡介:書本名稱 簡單介紹該書本的劇情 >>儲存/取消   

## sql檔規劃
$sql = "INSERT INTO categories (name,house,price,Author,book) VALUES ($name,$house,$price,$Author,$book)"; 

//書籍資料 資料庫
create table bookinformation (
number INT,
bookname varchar(50),
bookmake varchar(100),
bookprice INT,
author varchar(50),
bookkind varchar(50)
);
