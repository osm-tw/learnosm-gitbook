---
layout: doc
title: 開始使用 JSOM 編輯
permalink: /zh-tw/beginner/start-josm/
lang: zh-tw
category: 初學者
published: false
---

開始使用 JSOM 編輯器
=============================

在這個章節裡，我們將會學到如何一步一步地下載與安裝 JOSM，Java程式寫的 OpenStreetMap 編輯器。我們將會修改一些設定，使 JSOM 更好用。接著我們會打開一個範例地圖，並且學習一些 JOSM 軟體的基礎操作。還記得在介紹章節裡，我們曾要求你繪製你城鎮或村莊的地圖嗎？我們將會 在這個介紹章節再一次的繪製你的地圖，而這次是數位化的。在這之後，你應該對使用 JOSM 繪製地圖有更好的了解。

下載 JOSM
-------------

- 如果以已經擁有一個 JOSM 的複製在 CD 或 USB 隨身碟上，你可以跳到下一個章節，安裝 JOSM
- 如果你還沒有 JOSM，或是希望最新的版本，打開你的瀏覽器 ─ 可能是 Firefox、Chrome、Opera或是 IE 瀏覽器。
- 在視窗頂端的地址列，輸入下面的文字： [josm.openstreetmap.de](http://josm.openstreetmap.de) 並且按下Enter。
- 你也可以透過搜尋「JOSM」找到 JOSM 網站。 
- 網站應該長這個樣子：

  ![JOSM website][]

- 如果你的電腦裝的是 Windows ，請點選「Windows Installer」下載 JOSM。

  ![Windows installer][]

- 如果你有一個不一樣的作業系統，點選適於你系統的連結。你的下載應該就會開始。在這個章節裡，我們將會假定你使用 Windows ，但這個介紹也與其他作業系統類似。

安裝 JOSM
------------

> 如果你還沒有在電腦上安裝 JAVA，可能會在安裝 JOSM的時候發生問題。如果你在這個階段發生問題，請嘗試下載安裝 JAVA。你可以在這裡下載JAVA：[http://www.java.com/en/download/](http://www.java.com/en/download/)

- 在電腦上找到 JSOM 安裝檔，在上面雙擊以開始安裝。
- 安裝過程中，請點選「OK」、「Next」、「I Agree」與「Install」。安裝完成後，點選「Finish」以啟動 JOSM。
- 之後，當你想要啟動 JSOM ，你可以點選電腦左下角的開始選單，並點選 JOSM 程式。
- 你可能會看到一個視窗跳出來，詢問你是否想要升級軟體。因為這是新的，所以你不需要升級。點選「Cancel」按鈕。如果你不想再看到這個訊息，在按下「Cancel」之前，勾選底下的框框。
- 當 JSOM 啟動以後，應該看起來像這樣：

  ![JOSM splash page][]

JOSM 偏好
--------------------

有許多不同的設定可以讓你客製化 JOSM。語言應該是你會想要調整的設定。JOSM 已經被翻譯成許多不同的語言，而你可可能會習慣使用其中一種。

- 要打開偏好視窗，請點選 Edit -\> Preferences。

  ![Preferences window][]

- 在左邊，點選看起來像油漆桶與油漆刷的圖像。
- 在視窗上方，點選寫著「Look and Feel」的分頁。
- 在「Language」旁的下拉選單中選取你的語言。

  ![Look and feel][]

- 點選「OK」。
- 你需要重新啟動 JOSM 以使你的改變生效。點選左上方的「File」，然後點選選單下方的「Restart」。

學習使用 JSOM 進行基礎繪圖
-----------------------------

- 現在，讓我們打開一個樣本 OSM 檔案以學習使用 JOSM 繪製地圖的基本方法。注意，這個地圖不是真的，也不是一個真實地方的真實地圖，所以我們將不會把地圖存到 OpenStreetMap
- 請在這裡下載這個樣本 OSM 檔案
- 現在，我們用 JOSM 來打開這個樣本地圖。點選左上角的「Open」按鈕。

  ![Open file][]

- 找到 **sample.osm** 檔案。這個檔案可能在你的下載資料夾中，除非你把它儲存到其他地方。點選檔案，然後點擊「Open」。
- 你現在應該會看到一個地圖樣本，像這個樣子：

  ![Sample file][]

### 基本操作

- 要上下左右移動地圖，請按住滑鼠的右鍵，並且移動你的滑鼠。
- 有幾種不同的方式可以縮放地圖。如果你有滑鼠，你可以使用滾輪來縮放。如果你使用筆記型電腦，而且沒有滑鼠，你可以使用地圖左上方的比例尺來縮放地圖。你可以在比例尺的標記上按住滑鼠左鍵，使用滑鼠把比例尺上的標記左右拖動。

  ![Scale bar][]

- 看看樣本地圖，地圖上有幾個不同的物件。地圖上有一條河，一座森林，一些建築物，許多倒立，以及兩間商店。使用滑鼠左鍵點擊以選取物件。

### 點、線、面

- 當你點選樣本地圖上的不同物件，注意地圖上有三種不同的物件類別：點、線、面。
- 點，就是以符號代表一個位置。在樣本地圖上有兩個點，一個鞋店，以及一個超市。鞋子符號代表鞋店，購物車的符號則代表超市。
- 地圖上也有許多線，代表路。如果你仔細看看這些線，線裡也有許多點。這些點並沒有任何符號或其他資訊，但這些點協助定義線的位置。
- 最後，在樣本地圖上也有許多面，代表不同的地區－一座森林，一條河，以及數個建築。一個面可以用來呈現一個區域，像是一個場所或是一個建築。一個面也是以許多線構成的－差異在這些線頭尾相連。

> 用點、線、面這三種基礎物件，就可以很簡單的描述一個地圖。在 OpenStreetMap 裡有許多特別的術語，你將會在學習的過程中學到。在 OSM 裡，點被稱作「 **節點（node）** 」，線被稱為「 **路徑（way）** 」，面被稱為「 **封閉路徑（closed way）** 」，因為面只是頭尾相接的線。

- 當你選擇一個物件的時候，你可能會注意到地圖右邊會跳出一個名為「Properties」的視窗，裡面有列表。列表上的項目就是標記（tag）。標記是描述一個點、線或面是什麼的資訊。我們將會在下面的章節學到這些標記。現在，你只要知道這些資訊可以描述這個物件究竟是森林、河流、建築物，或是其他東西。
- 試想，如果你要手繪一個地圖，你會怎麼描繪這些點、線與面？有哪些地方最好以點、線、面呈現？

### 修改物件

- 選取地圖左邊的森林。確定你點到的是圍繞森林的縣，而不是線上的點。現在按住你的滑鼠左鍵，並且移動你的滑鼠。你應該可以把森林移動到地圖的其他地方。
- 點選森林周圍線上的一個點。按著你的滑鼠左鍵，並且移動你的滑鼠。這次你應該可以移動這個點。這就是改變形狀、或是移動一個點的方法。

### 繪製

- 在JSOM的左邊，有一欄按鈕。許多按鈕都會在右邊開啟新提供更多地圖資料的新視窗。最重要的按鈕，在這些欄位的上方。這個按鈕會改變滑鼠的功能。
- 頂端的那些按鈕你將會很常用。這些按鈕可以用來選取物件，以及繪製新物件。
- 現在，你已經用過選取工具了，長得像這樣：

  ![Select tool][]

- 在你開始繪製之前，你必須先確定沒有選取任何東西。請點選地圖中間空白的地方，以確定沒有選取任何東西。
- 點選第二個按鈕，繪製工具。

  ![Draw tool][]

- 找到一個地圖的空白區域，在上面點兩下滑鼠左鍵，這會繪製一個「點」。
- 要繪製一條線，先單擊滑鼠左鍵，移動你的滑鼠再按一次，，重複以上動作直到你覺得ok。要結束一條線，請雙擊滑鼠左鍵。
- 繪製一個面跟繪製一個現一樣，不過在最後滑鼠要在啟始點上雙擊，以完成一個面。

### 新增圖示

- 現在我們知道如何繪製點、線、面了，但我們還是不知道如何定義這些點、線、面代表什麼。我們希望別人看到這些點的時候，知道這些點代表商店、學校、或其他東西，也能夠知道我們的面代表的是一個場地、建築、或其他的東西。
- 點選左邊欄位裡的選取工具按鈕。

  ![Select tool][]

- 用繪製工具選取其中一種你想要繪製的物件。在上方選單，點選「Presets」。把你的游標移到子選單中，你想要使用的標記上面。
- 當你在標記上按下左鍵，就會跳出一個選單詢問你更多資訊。你不用一定要在每個欄位中填入，但你可能會想要加入更多重要的欄位，例如物件的名字。
- 當你輸入完資訊後，點選「Apply Preset」。如果一切順利，你的點、線、面應該會改變顏色，或是顯示一個符號，這是因為你已經定義這個物件了。

繪製你的地圖
-----------------

- 現在，讓我們來繪製一個地圖，以練習你學到的技巧吧！你可能會想要重繪你剛剛在紙上繪出的地圖
- 把地圖拖離樣本地圖。按著滑鼠右鍵並且移動滑鼠，直到你找到一個可以拿來繪製的空白區域。
- 使用繪製工具來建立點、線、面。透過Presets選單來描述你的物件。
- 當你完成以後，你就擁有你自己的地圖了，而這個地圖會很像我們從sample.osm打開的樣本地圖。

總結
-------

做得好！如果一切順利，你已經學到如何在電腦上設定JOSM，以及如何使用基礎工具來繪製地圖。在下一章，我們會更詳細的了解使用JOSM繪製OSM地圖的步驟。

[JOSM website]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image00_josm-website.png
[Windows installer]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image01_windows-installer.png
[JOSM splash page]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image02_josm-splash-page.png
[Preferences window]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image03_preferences-window.png
[Look and feel]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image04_look-and-feel.png
[Open file]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image05_open-file.png
[Sample file]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image06_sample-file.png
[Scale bar]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image07_scale-bar.png
[Select tool]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image08_select-tool.png
[Draw tool]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image09_draw-tool.png
