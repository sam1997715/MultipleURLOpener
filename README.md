# URL多開器

### 介紹
一次多開多個分頁，減少重複開啟的動作。

---

### 使用需求
+ 需要在電腦安裝完成 [Python 3](https://www.python.org/) 

### 前置安裝
1. 需要預先安裝 requirements.txt 所相依的套件
   ### 套件安裝教學
   1. 開啟電腦的指令視窗 (Windows:按下<kbd>Win</kbd>+<kbd>R</kbd>，在開啟欄輸入 <code>cmd</code>後按確定)
   2. 變換當前路徑至下載下來的資料夾 <code>cd %USERPROFILE%\Downloads\LineStickerDownloader</code>
      (如果不是下載在下載需更換對應路徑)
   3. 執行安裝指令 
      <pre><code>pip install -r requirements.txt</code></pre>

2. 對 <code>LineSticker.py</code> 按下右鍵，並選擇 <u>Edit with IDLE 3.x</u>
3. 按下鍵盤 <kbd>F5</kbd> 即開始運行下載器
4. 下載完成的貼圖將放置同路徑的資料夾下

### 初始介面

可以透過拉伸視窗調整介面

<img decoding="async" src="https://github.com/sam1997715/MultipleURLOpener/blob/main/%E8%AA%AA%E6%98%8E%E5%9C%96%E7%89%87/%E5%88%9D%E5%A7%8B%E4%BB%8B%E9%9D%A2.png?raw=true" width="50%">

### 操作步驟

<img decoding="async" src="https://github.com/sam1997715/MultipleURLOpener/blob/main/%E8%AA%AA%E6%98%8E%E5%9C%96%E7%89%87/%E4%BB%8B%E9%9D%A2%E4%BB%8B%E7%B4%B9.png?raw=true" width="40%">

1. 預先準備好多個想要開啟的網址，並且用分行的方式分隔開每個網址。
2. 將多個已經分隔好的網址直接貼上文字框。
3. 檢查選項是否符合需求，預設值：
   + ☑️ (checked) 開啟重複的分頁
     > 將會開啟先前已經開啟過的網址
   + ⬛ (unchecked) 不照順序開啟(較快)
     > 照順序開啟網址
4. 按下 <code>確認</code> ，馬上使用預設的瀏覽器開啟網址。

### 範例

<img decoding="async" src="https://github.com/sam1997715/MultipleURLOpener/blob/main/%E8%AA%AA%E6%98%8E%E5%9C%96%E7%89%87/%E8%88%89%E4%BE%8B1.png?raw=true" width="90%">

1. 網址經過分行分隔每一條網址，並建議暫存在剪貼簿中(即<kbd>Ctrl</kbd>+<kbd>C</kbd>或任何與<kbd>Copy</kbd>相同功能按鍵)。
   假設有以下網址需要開啟：
    + https://www.google.com
    + https://www.msn.com
    + https://tw.yahoo.com
    + https://www.github.com
   
   則需要將以上全部的網址以分行的方式隔開，並暫存於剪貼簿中。
2. 直接在多開器的文字框中直接貼上(即<kbd>Ctrl</kbd>+<kbd>V</kbd>或任何與<kbd>Paste</kbd>相同功能按鍵)。
3. 確定選項符合需求(此例情況：若重複仍開啟，且需照順序開啟)。
4. 按下</code>確定</code>鍵後即可開啟成功。

<img decoding="async" src="https://github.com/sam1997715/MultipleURLOpener/blob/main/%E8%AA%AA%E6%98%8E%E5%9C%96%E7%89%87/%E8%88%89%E4%BE%8B2.png?raw=true" width="90%">
