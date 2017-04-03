### 項目名稱與介紹 ###
***
這是一份提供經常使用 Github 的人所使用的README範本，而我將會將這裡記錄下README經常所使用到的標題與內容，而我將會將這裡記錄下README經常所使用到的標題與應放置的內容，舉例來說，這裡是項目的描述區塊，用於描述專案的特性與使用對象。

### 目錄 ###
***
1.如何開始
2.功能
3.用法
4.API
5.測試
6.部屬
7.版本紀錄
8.FAQ
9.貢獻
10.版權
11.小知識
### 如何開始 ###
***
這裡描述說專案進行前所需要的環境以及安裝軟體，通常會依照語言而有對應的版本套件管理，請看看如下操作。
#### 預先安裝 ###
在使用這面文檔之前，請先安裝好 git ，安裝 git 的方法
請到 github 裡面去下載吧
#### 安裝 ####
輸入下方指令於支援 git 指令的 bash 就可以立刻取得這份檔案了喔
```bash
git clone http:example.com/project.git
```
### 功能 ###
***
這裡最好條列式出你的專案有哪些功能存在，這份範本就可以如下
1.複製貼上好方便
2.全都是中文，不再有語言障礙
3.臨時應急需求時可以用
4.學生demo時可以嚇嚇其他組員
### 用法 ###
***
這邊可以放上專案擁有那些用法，這份專案最重要的地方，同時在下面附上範例程式碼，好讓後面的人看得懂，最好也把結果給放上來，可以用截圖的方式或是在註解說明，這邊就是要抓住他人的眼球，一瞬間了解專案特性或是解決那些問題。

例如以下圖片示範
![alt](http://i.imgur.com/QgEX9Sg.png "圖片示範用法")


### API ###
***
這裡是放置文件的地方，請把所有能使用到的function給放上來，至於放上甚麼可以有兩種方式呈現，一種是逐一列表說明，另外一種是用表格說明(比較像是spec)。
#### 方法一 ####
> 此法多用於指令做介紹
```bash
$ cmd options
```
* -c, --clear - 清除所有內容
* -a, --all - 取得所有內容
* -h, --help - 取得指令

#### 方法二 ####

>此法多用於提供函數的專案

|函示名稱|參數(argv1, argv2, argv3)|性質|備註|
| --- | --- | --- | --- |
| getName | id(int), null, null | 回傳 string | 無 |
| setAge | id(int), age(int), null | 無 | 無 |
### 測試 ###
***
這裡放上測試的方法
```bash
test foo.cpp -bar
```
### 部屬 ###
***
這裡可以記載部屬於何處以及方法
```bash
deploy myApp@somewhere
```
### 版本紀錄 ###
***
這裡還處於施工狀態
[目前正在參考此處撰寫](https://github.com/skywinder/github-changelog-generator#usage)
### FAQ ###
***
Q.這份文件始於什麼時候？
A.github上面都有紀錄
Q.這篇文章是用什麼語法撰寫的
A.這裡是用Markdown語法撰寫而成
### 貢獻 ###
***
* _Heng-Shiou Sheu_-Initial work - [linkToGithub](foor@bar.com)

開放 issue 以獲取更好的方法
鼓勵多發 pull request 來一同改進這份文件

### 版權 ###
***
放上這份文件屬於哪種版權的地方，看是要MIT, Apache之類的
>[取得版權使用](https://choosealicense.com/)

MIT © Heng-Shiou Sheu
### 小知識 ###
***
1.適當的加入emoji可以讓文件活潑起來[連結](https://www.webpagefx.com/tools/emoji-cheat-sheet/)
2.如果專案有用到的話，可以放上 badge[連結](https://shields.io/) ，例如程式碼覆蓋率，CI有沒有過，套件版本管理版本號
3.有意願的話，多國語言版本的Readme也是很好的
4.更多資源可以參考 [awesome-readme](https://github.com/matiassingers/awesome-readme)