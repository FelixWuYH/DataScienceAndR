<!-- title: R 語言翻轉教室 -->

測試結果： Linux ![](https://travis-ci.org/wush978/DataScienceAndR.svg?branch=course) Windows [![Build status](https://ci.appveyor.com/api/projects/status/tej2qnpdxwy2r5lp/branch/course?svg=true)](https://ci.appveyor.com/project/wush978/datascienceandr/branch/course)

聊天室： [![Gitter](https://badges.gitter.im/wush978/DataScienceAndR.svg)](https://gitter.im/wush978/DataScienceAndR?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# R 語言翻轉教室

這是一個以著重於實作，一個動態的**R 語言在地化中文教材**。和其他R 教材相比，這份教材具有以下的特色：

1. **完整**。由於教材是參考CRAN上介紹R 的官方文件：[An Introduction to R](https://cran.r-project.org/doc/manuals/R-intro.pdf)所撰寫的，同學即使只有使用這份教材學R ，即可獲得所有用R 所需要的所有知識。
2. **在地化的中文資料處理**。教材是特別針對處理台灣的Open Data所設計，所以會涵蓋所有要載入中文資料所需要的知識。網路上雖然已經有很多很棒的R 教材，但是他們通常沒有描述如何處理中文資料。
3. **新**。在2012年以後，R 的成長是非常快速的，所以教材會納入許多近年來被R 社群證實很棒的套件們。
4. **套件的使用與探索**。R 的一大優勢就是蓬勃的套件系統。雖然教材中無法介紹所有的套件，但是會教同學如何探索一個第一次接觸的R 套件。
5. **互動**。我們基於R Community貢獻的R 語言套件swirl 所撰寫的互動式學習環境，可以讓同學以最貼近實際使用R 的狀況來學R
5. **教材設計**。每個單元的開始，我們設計大量的操作讓同學是透過用**肌肉**來記憶R 的指令。並且在單元的最後都擁有來自實務且具有挑戰性的關卡。

## 線上體驗區（需參加實體課程）

請奇數編號的同學打開： <http://140.112.170.201:28787>

請偶數編號的同學打開： <http://www.wush978.idv.tw:28787>

並依照課堂上給的帳號密碼登入。

有興趣的同學也可以在聊天室聯繫我們，取得線上體驗的帳號密碼。

## 快速安裝區

同學也可以依照以下的動作快速設定學習環境：

1. 安裝R
2. 安裝Rstudio(Windows 使用者請安裝Rstudio或自備編輯UTF-8 編碼的程式碼，OS X 與Linux使用者可依據自己喜好決定是否使用Rstudio)
3. 打開R ，執行：`source("http://wush978.github.io/R/init-swirl.R")`
4. 輸入`library(swirl);swirl()`後即進入教學環境。
5. 進入Hello DataScienceAndR課程檢查你的電腦能不能執行本教材的所有功能，並瞭解本教材所提供的功能。

有興趣了解安裝細節的同學，請操考：

- [Windows](https://github.com/wush978/DataScienceAndR/wiki/Windows-%E8%A8%AD%E5%AE%9A%E6%8C%87%E5%8D%97)
- [Mac OS X](https://github.com/wush978/DataScienceAndR/wiki/Mac-OS-X-%E8%A8%AD%E5%AE%9A%E6%8C%87%E5%8D%97)
- [Ubuntu](https://github.com/wush978/DataScienceAndR/wiki/Ubuntu-%E8%A8%AD%E5%AE%9A%E6%8C%87%E5%8D%97)

安裝上和執行Hello DataScienceAndR課程的同學請到[求助專區](#求助專區)取得協助

## 互動式學習環境快速上手區

在輸入`swirl()`之後，同學即進入R 的互動式學習環境(swirl環境)。請參考以下動作做操作：

### 1. 進入學習環境

![Imgur](http://i.imgur.com/sYGDy72.png)

ps. 如果你之前有進行過swirl的課程，swirl會出現下圖的選項詢問你是否要接關。請根據你的需求作答：

![Imgur](http://i.imgur.com/SwlSa3W.png)

如不接關，請選取：`No. Let me start something new.`

### 2. 選擇課程(Course)

![Imgur](http://i.imgur.com/Sfj0K1l.png)

### 3. 選擇你要進行的單元(Lesson)

![Imgur](http://i.imgur.com/OFgU4wM.png)

目前課程主要分成：

- RBasic區：講解R 語言的基礎知識與使用方法。所有以下的課程都需要知道RBasic的知識。
- RDataEngineer區：講解載入資料至R 語言，以及清理、整理資料的所需知識。
- RProgramming區：介紹R 語言的程式功能。
- RDataMining區：介紹R 語言在Data Mining中常用的套件。

## 求助專區

有問題的朋友，歡迎到以下地方討論。由於現在網路上機器人眾多，所以麻煩先註冊一個Github帳號後我才會在網路上和你討論。

- [Issue回報區](https://github.com/wush978/DataScienceAndR/issues)
- Gitter聊天室：[![Gitter](https://badges.gitter.im/wush978/DataScienceAndR.svg)](https://gitter.im/wush978/DataScienceAndR?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

## 緣起

這個Repository主要是為了準備我在臺大的資料科學課程，幫陳老師講的兩堂R 的課程。課程素材主要就是投影片和swirl。內容則是參考CRAN上介紹R 的官方文件：[An Introduction to R](https://cran.r-project.org/doc/manuals/R-intro.pdf)。
另外也要感謝社群中所有有參與籌備資料科學愛好者年會2015的同伴。

## 課程投影片

1. RBasic
  - Introduction [HTML](http://wush978.github.io/DataScienceAndR/slide/RBasic-Introduction.html) [PDF](http://wush978.github.io/DataScienceAndR/slide/RBasic-Introduction.pdf)
  - Data Structure [HTML](http://wush978.github.io/DataScienceAndR/slide/RBasic-DataStructure.html) [PDF](http://wush978.github.io/DataScienceAndR/slide/RBasic-DataStructure.pdf)
1. RDataEngineer
  - Introduction [HTML](http://wush978.github.io/DataScienceAndR/slide/RDataEngineer-Introduction.html) [PDF](http://wush978.github.io/DataScienceAndR/slide/RDataEngineer-Introduction.pdf)

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/tw/"><img alt="創用 CC 授權條款" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/tw/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Data Science and R</span>由<a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/wush978/DataScienceAndR" property="cc:attributionName" rel="cc:attributionURL">Wush Wu和Chih Cheng Liang</a>製作，以<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/tw/">創用CC 姓名標示-相同方式分享 3.0 台灣 授權條款</a>釋出。
