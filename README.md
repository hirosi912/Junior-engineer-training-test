# Junior-engineer-training-test

# 產線狀態即時查詢網站
* 請依據需求提供一個查詢能夠即時查詢各產線機台目前的狀態的網頁
  網站包含兩個頁面：
  * 機台資訊的列表
  * 新機台申請頁面

## 需求
* 機台資訊列表 
  * 能夠依據廠區、產線來選擇機台的連動下拉選單
  * 按下查詢按鈕後，呼叫後端Api查詢機台資料
  * 以表格的方式呈現各機台資訊與狀態
    > 機台依據各狀態不同，於機台名稱的欄位以不同顏色顯示

* 新機台資料申請頁面
  * 使用PrimeNg製作元件
  * 申請項目包含以下
    > 機台名稱、申請人、申請人電話、申請日期
  * 各項目需驗證資料正確性
  * 按下Submit按鈕後，跳出包含申請資訊的確認視窗

* 頁面需有RWD功能
* 請將作業放置DevOps上做版控，能夠即時儲存目前進度

* 機台 Api Link: (待討論) 

## 環境工具
* VS Code
* Nodejs
* Angular CLI

## 規格
* Angular 15
* PrimeNg
* Ngrx

## 進階需求(加分項目)
* 不需查詢按鈕，表格連動顯示機台資訊
* 暫存系統目前畫面輸入與route狀態
* 切換版面風格(theme style)
> Ex. Change color / Dark mode  
* 模組化(Service, Component)
> Ex. 共用元件功能,如:連動選單,訊息視窗

## 驗收時間
* Regular: 4-5週
* Nice to have: 2-3週

## 驗收方式
* 將專案push至DevOps個人training branch
* Live Demo與系統說明與報告(5~10 mins, 報告非必要)

## 備註
* 進階需求非必要
* 若有困難可主動提出或請教指導員
