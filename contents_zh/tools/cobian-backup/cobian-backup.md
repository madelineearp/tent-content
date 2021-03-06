[Title]: # ()
[Difficulty]: # (初學者)
[Order]: # (0)

# Cobian Backup 工具指南

## Cobian Backup
備分電腦檔案

**學習內容：** [備份](umbrella://lesson/backing-up)
**下載地址：** [http://www.cobiansoft.com/cobianbackup.htm](http://www.cobiansoft.com/cobianbackup.htm)
**電腦要求：** 
- XP, 2003, Vista, 2008, Windows 7; 
- Windows 95, 98 and ME 可以相容Cobian 7版本。
**本指南中所用軟體版本：** Cobian 10
**License版權宣告：**自由軟體
**程度：** 中級
**所需時間：**30分鐘

### 1.0 開始前應知道的二三事

Cobian Backup 用於檔案目錄的檔案庫, (用於備份儲存)。備份可讓你存放在電腦上其它目錄或是硬碟中，或是辦公室裏的其它電腦、可移除的行動設備(CDs, DVDs、USB記憶卡等)。Cobian Backup 讓你定期建立檔案目錄夾，它可以壓縮備份檔節省空間。它安靜地運行在電腦系統後台(即系統工作列)，必要時可以檢查其工作日程與執行備份的過程， Cobian Backup 也能在備份時進行壓縮與加密檔案。

**使用 Cobian　可以：**
- 備份所有文件檔案以及目錄夾
- 壓縮和解壓縮備份檔
- 加密和解密你的檔案庫文件

**簡易安裝Cobian**
- 到 www.cobiansoft.com/cobianbackup.htm　
- 點擊網頁中下載連結"Download Cobian Backup"
- 儲存程式安裝檔後雙擊開啟。
- 在繼續安裝前先閱讀指引文件。
- 成功安娤後Cobian可將原來的安裝程式檔刪除。

### 2.0 如何安裝Cobian Backup

**安裝手冊：** 在開始安裝前先確認你有最新版的**「微軟視窗安裝程式」**以及 **Microsoft.NET Framework**。安裝 Cobian Backup 相對簡單容易的過程。

**第 1 步.：** 雙擊檔案“cbsetup.exe”；此時會出現_開啟檔案－安全警告_的對話視窗。如果發生這種情況，請按執行來激活淡藍色的_「解壓縮資源」_進度條，幾分鐘後就會出現以下的畫面：
![image](tool_cobian1.png)

**第 2 步.：** 點擊下一步以進入_閱讀服務條款與同意接受的畫面_，請勾選_接受_選項後，再繼續下一步會進入下一個畫面：
![image](tool_cobian2.png)

**第 3 步.：** 點擊下一步後看到此畫面：
![image](tool_cobian3.png)

**第 4 步.：** 在_「服務選項」_勾選_「使用本機系統帳號」_，這樣你會回到上面畫面３的圖示。這個選項確認 Cobian Backup 會安靜地在系統後台全程運作，而你的備份也會定期地執行。

**第 5 步.：** 繼續下一步將會彈出下面訊息：
![image](tool_cobian4.png)

**第 6 步.：** 點選「是」以激活下面的安裝畫面，然後點選下一步繼續安裝程序。

**第 7 步.：** 選擇「完成」以完成安裝程序。結束安裝後，Cobian Backup圖示會出現在視窗的_系統工作列_。

### 2.1 如何備份你的目錄和檔案

這部份你將學會如何執行簡單的備份檔案庫或指定的檔案/資料夾。Cobian Backup 使用可設定的_備份任務_，其包括可指定的使用者的檔案或資料夾。備份任務可以隨時或指定某一時間執行，要創建一個新的備份任務,請進行以下步驟：

**第 1 步.</b> 點擊「排程」創建新備份任務，並激活_新任務_，視窗如下：
![image](tool_cobian5.png)

左側的清單包含一些分頁以及相關的螢幕-是用來設定不同的備份選項與參數，其顯示在右側背版。_「一般」_分頁的所有選項兹描述如下：

### 2.1.1 選項描述

_「任務名稱」_: _任務名稱_文字欄位讓你可以打入此次備份任務的名稱，使用一個可辨識的名字來區別備份工作。例如，如果備份的是影片檔案，可以命名為_影片備份_。

_「取消」:_這個選項_必須_維持未勾選。
警告: 啟動了_「取消」_會覆蓋了其它的選項,並阻止備份任務執行。

_「包括子目錄」：_這可包含所選資料夾目錄底下的所有子目錄都要進行備份。這會在處理大量的資料夾目錄上很有效率，例如你選擇了_「我的文件」_目錄後並勾選了這個選項，那麼所有在_我的文件_目錄下的檔案與資料夾都會被進行備份。

_利用時間戳記創建不同的備份：_這個功能讓你可以指定某個時間來自動進行備份任務，時間會包含在備分目錄裏。這樣讓你更方便辨識何時所進行的備份。

_使用檔案屬性邏輯：_這個功能只有在你選執行漸次或不同備份時才有關聯 (請見下方說明)，檔案屬性包含了這個檔案的資訊。
**注意：**下面的選項只有在_Windows XP_以上的版本才有。

_使用「磁區影子複本」:_ 這功能可讓備份檔案鎖上。
Cobian Backup 會查證這個資訊以決定原始檔案距上回備份後是否有所變動。如果你執行_「差異」_或_「漸次」_備份，這個檔案就會進行更新。

**注意：**如果你_關閉了_這個功能，就只能夠執行完整或_「傻瓜備份」dummy_(下面會介紹「傻瓜備份」)。

### 2.1.2 備份類型描述</b>
_「完整備份」:_它會把來源位置中的每一個檔案和資料夾都複製到備份目錄區裏。除非你啟動了_利用時間戳記創建不同備份_選項，則你同一來源位置將會有多個備份檔案(其以日期時間作為識別)，否則Cobian Backup 將會複寫之前的備份版本。

_「漸次」:_這個選項是指程式會檢查檔案距上回備份後是否有所變動。如果沒有變動，它會略過備份動作以節省時間。其利用的_檔案屬性邏輯_功能必須被開啟才能執行這樣的備份。_「差異」：_程式會查證原始檔案距上回**完整**備份後是否有所變動。如果不需要複制新檔案，就會略過以節省備份時間；如果你之前有執行過完整備份，那麼你可以繼續利用「差異」備份方式完成備份。

_「傻瓜任務」:_你可以使用這個方式讓電腦在某些時間來執行或關閉，它的進階功能其實和基本備份手續並無相關。

**第 2 步.：**點擊“OK”確認你所設定的備份選項與參數

### 2.2 如何創建備份檔案

要建立備份檔，請執行以下步驟:

**第 1 步.：** 點擊_新任務_視窗左側上的「檔案」，出現一個如下圖的_空白_畫面：
![image](tool_cobian6.png)

**第 2 步.：** 選擇你要備份的檔案，(例如在上面_圖3_中，_「我的文件」_資料夾為示範。)

**第 3 步.：** 在_「來源」_面版中點擊「新增」以開啟_「目錄」_選單。

**第 4 步.：** 如果要備份整個目錄，請選擇_「目錄」_,若只要備份單一檔案，請選擇_「檔案」_。要指定檔案或目錄作備份，則選擇_「手動」_，然後輸入要備份的檔案或目錄的路徑。

**注意.：** 你可以依需要增加檔案或目錄。如果你想要備份目前在 FTP 伺服器上的檔案，選擇 FTP site功能(你必須提供適當的伺服器登入資訊)。當你選好了檔案或目錄，它們會出現在_「來源」_</i>區。如在前面_圖3_所示，_「我的文件」_目錄正出現在那裏，這表示該目錄將會被放入備份任務中。而_「目的地」_面版則是指定備份檔案所該存放的位置。

**第 5 步.：** 在_「目的地」_面版中點選「新增」以開啟目錄選單。

**第 6 步.：** 選擇_「目錄」_以打開瀏覧視窗，在那裏選擇你要存放的備份檔案目的地位置。

**注意：** 如果想建立多個版本的備份檔，你得要指定不同的目錄。選擇_「手動」_方式，你必須輸入想要保持備份檔案的完整目錄路徑。若使用遠端網路伺服器來存放檔案庫，請選擇”FTP site“選項 (須提供適當的伺服器登入資訊)。其畫面應該是以上例子的重組,選擇來源檔案與目錄，選擇目的地位置等等。但此時還不能點擊_OK_！你還要設定備份的期程。

### 2.3 如何設定備份的任務期程

為了讓備份可以自動工作, 需要填寫_「排程」_部份的資訊，它可以讓你指定何時要進行備份。
設定排程選項，請依下列步驟：

**第 1 步.：** 從左側選擇「排程」，以啟動下面的面板：
![image](tool_cobian7.png)

在_「排程」_選項被列在下拉式選單，其描述如下：
_「一次」：_ 備份只在指定的日期和時刻裏進行一次，其指定的時間顯示在_Date/Time_。

_「每日」：_ 每天到了特定的時刻即會進行備份，其指定的時刻在_Date/Time_。

_「每週」：_ 每週執行一次備份。如上述的例子中，每週五會進行備份。當然你也可選擇其它日子，備份會在_Date/Time_指定的日子裏進行。

_「每月」：_ 備份會在月份方塊中所輸入的日子進行，其指定的時間顯示在_Date/Time_。

_「每年」：_ 備份會在月份方塊中所輸入的日期以及特定的月份中進行，其指定的時間顯示在_Date/Time_。

_「定時器」：_ 備份會在時間文字方塊中所輸入時間區隔進行備份，其指定的時間差顯示在_Date/Time_。

_「手動」:_ 你必須從主程式視窗來執行備份。

**第 2 步.：**點擊“OK”以確認選好了功能與排程設定如下圖：
![image](tool_cobian8.png)

當決定好了備份時程，就完成了最後一步設定，備份工作將會自動在指定的時間內進行。


### 3.0 如何壓縮備份檔

**第 1 步.：** 如 2.3 部份所介紹的建立備份任務後，你會得到所要儲存的備份檔。

**第 2 步.：**從左側選擇「檔案庫」以激活_「新任務」_畫面，如下圖：
![image](tool_cobian9.png)

**「壓縮」**面版是用於指定備份檔的壓縮方式。

**注意：**壓縮是為了減少檔案儲存的空間數量，如果你有太多老舊檔案雖然很少用到但還是希望保存，或許把它們存成一種不佔太多空間的格式是不錯的方法。壓縮會移除不必要的文件碼但仍會保留重要的資訊，它並不會破壞你原始的資料。檔案在壓縮中無法檢視，要檢視檔案必須透過還原手續來解壓縮檔案。

在_「壓縮類型」下拉選單中的三個子選項是:
_「不壓縮」“No Compression”:_它不會進行任何壓縮動作

_「拉錬壓縮」“Zip Compression”:_它為**　Windows　系統**標準的壓縮技術也是最方便的一種。建立的檔案庫可以利用 Windows 標準工具打開(或可下載 [ZipGenius](http://www.zipgenius.it/) 程式來讀取)。

選擇壓縮類型會自行啟動_「分割選項」“Split options”_部份以及它的相應下拉清單。

這個_Split options_適用於可移式媒體，如外接CDs、DVDs、軟磁片、USB 記憶卡等。不同的分開選項會分割檔案庫大小以適合所選用的存放載具。

例如如果你正在備份大量的檔案，也許該把它們燒入光碟.但是萬一檔案庫大於 700MB (CD的容量)，這個分開的功能就會自動把檔案庫切割成許多小於 700MB 檔案，以便可以燒入光碟片。如果你打算把備份檔放在你的電腦硬碟或是要備份的檔案遠小於儲存設備，可以直接跳過這一部份。當你在下拉式選單上選擇了_「分割選項」“Split options”_後會出現以下的選項。你的選擇將依照可移除式行動儲存裝置而定。
![image](tool_cobian10.png)

- 3,5 "吋軟碟，這只能儲存少數文件檔案的備份
- 壓縮 Zip-Zip Disk 磁碟 (檢查你所使用的容量大小)。你也需要一台特殊的 ZIP 磁碟機和客制化磁碟
- CD-R-光碟片 (檢查你所使用的容量大小)，電腦上要裝CD燒錄光碟機和相關軟體(請見 [DeepBurner 兔費版](http://www.deepburner.com/)或是其它[光碟燒錄工具](http://www.thefreecountry.com/utilities/dvdcdburning.shtml))
- DVD-DVD disk (檢查你所使用的容量大小)。電腦上要裝DVD燒錄光碟機和相關軟體(請見 [DeepBurner免費版](http://www.deepburner.com)或其它[光碟燒錄工具](http://www.thefreecountry.com/utilities/dvdcdburning.shtml))

如果你要備份到好幾個 USB 記憶卡上，你得要自定容量。

請執行以下步驟：

**第 1 步.選擇**_「自定大小」_(bytes)，然後在文字欄位輸入檔案庫的大小。讓你對比特大小有所概念
- 1KB (kilobyte) = 1024 bytes - 一份一頁辦公室文書檔案（Open Office格式）大約是 20kb
- 1MB (megabyte) = 1024 KB - 數位相機拍的照片一張大約是 1-3 MB
- 1GB (gigabyte) = 1024 MB - 大約是半小時 DVD 影片的大小

**注意:**當選擇自定大小來分割備份檔在 CD 或 DVD 光碟片時，Cobian Backup 將不會自動複製備份檔到籌移動式儲存裝置上，它會把這些備份檔案庫建立在你的電腦上然後你得再自行把它燒錄到光碟片上。

_「密碼保護」"Password Protect":_此功能可以讓你輪入密碼來保護備份檔案庫，只要在其提供的位置上重覆打入兩次密碼。若要解壓縮檔案时，會被要求輸入密碼它才會執行任務。

**注意:**若要進一步安全保護檔案庫，你該要考慮使用其它方法而不只是透過密碼而已。Cobian Backup 可讓你加密檔案庫，下面會介紹這個功能。

_評注:_這個選項讓你寫入一些對於備份檔案庫的描述，但並非必要強制。

### 3.1 如何解壓縮備份檔
要解壓縮備份檔，請依照以下步驟：

**第 1 步.「選擇」 >「工具」 >「解壓縮」**。

出現的解壓縮視窗畫面如下：
![image](tool_cobian11.png)

**第 2 步.：** 點擊開啟檔案的圖示，以便出現瀏覧視窗好讓你可以選擇要進行解壓縮的資料檔。

**第 3 步.：** 選擇該檔案(其應為 _zip_ 或 _7x_格式) 然後點擊“OK”。

**第 4 步.：** 選擇要把解壓縮後檔案所存放的目錄夾或位置。

**第 5 步.：** 點擊壓縮圖示以開啟另一個視窗好讓你可以選擇存放解壓檔案的目錄。

**第 6 步.：** 選擇完某一個目錄後，點擊“OK”。

使用微軟的檔案總管來檢視檔案是否跑到了所指定的目錄。

### 4.0 加密功能
為防止未授權者的近用，備份檔進行加密也許是必須的措施。加密其實是一個編碼、拼湊資料的手續，好讓它無法讓沒有特殊密鑰的人可以辨識和解密其訊息內容。有關加密的進一步資訊，請參考[「保護檔案」課程](umbrella://lesson/protecting-files)。

### 4.1 如何加密備份檔

_高強度加密_ 是用來進行指定加密的方法。

**第 1 步.：**點選_加密類型_的下拉式方框以出現不同加密方法的清單。為了讓事情簡化，我們推薦選擇 _Blowfish_ 或是 _Rijndael_ (128 bits)方式。這兩者都為檔案庫提供了優秀的安全保護，讓你的加密資料須透過密碼才能使用。

**第 2 步.：**選擇你所要的_加密類型_。**注意:** _Rijndael_和 _Blowfish_ 都提供差不多類似程度的安全保護。_DES_則是較脆弱但加密過程快。

**第 3 步.：** 在其提供的欄位中輸入密碼。「密語品質」列會顯示出密碼的強度太小，越靠右側則其密碼強度越高。請參考[密碼課程](umbrella://lesson/passwords)了解如何建立高強度的密碼。

**第 4 步.：** 點擊”OK“

### 4.2 如何解密備份檔

解密備份檔相對容易而快速。要解密備份檔，請執行以下步驟:

**第 1 步.「選擇」>「工具」 >「解密和密鑰」:**_這會啟動解密視窗如下:_
![image](tool_cobian12.png)

**第 2 步.：** 點擊「選擇」以便選取要解密的檔案。

**第 3 步.：** 選擊「目的地」以挑選出解密後檔案所存放的位置。

**第 4 步.：** 在「方式」的下拉式選單中，選擇之前對檔案進行的加密方式。

**第 4 步.： 選擇**合適的加密方式(也就是你之前所採的加密法)。

**第 5 步.：** 在_「密語」_欄位輸入密碼

**第 6 步.：** 選擊「解密」

則該檔案會在完成解密後存到你所指定的目錄下。如果該檔案之前有壓縮過，就得依上面 3.1 部份介紹的如何解壓來對其進行解壓縮。