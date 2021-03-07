# Week 1 learning note
### command line

pwd 顯示路徑
ls  顯示檔案    |   ls -al = 詳細內容  | ls -al > +"檔案名稱" = 輸出詳細資訊到新增檔案
cd  切換資料夾  |   cd .. = 回上一層
man 指令說明    |  man + "指令"
echo 印出      | echo + "想印出的內容"  (類似print) 
>  新增指定內容到新增檔案(覆蓋)
>> 新增指定內容到檔案(新增，不會覆蓋原先資料)


touch 建檔(輸入新檔名)or最後修改時間
rm  刪除   |  rm -r + "檔案"  刪除資料夾所有資料
mkdir  新增資料夾
cd 資料夾中檔案部分名稱按tab會自動輸入完畢
mv 移動檔案到特定資料夾  | mv + "檔案" + "資料夾" 
mv 更改檔案名稱  | mv + "檔案" + "更改檔案名稱" 

cp 複製檔案  | cp + "檔案" + "複製檔案名稱" 
cp 複製資料夾以及所有檔案 | cp -r + "資料夾"  

vim 文字編輯器 | vim = "檔案"  | i =  insert文字  | esc = 跳出  | :q = 跳出 vim模式  | :wq = 存檔+跳出 vim


cat 觀看檔案內容 | cat + "檔案"
cat可以接著用grep抓取關鍵字(類似ctrl+f)
grep 抓取關鍵字  | grep + "關鍵字" + "檔案"
wget 下載檔案　　| wget + url 
curl 送出request| curl + api　｜ curl -I + api  = 顯示header資訊

|   pipe(將左邊輸出到向右邊使用)

.. = 上一層 各指令通用
