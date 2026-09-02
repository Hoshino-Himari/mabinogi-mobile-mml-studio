瑪奇 Mobile MML 作曲室

直接以瀏覽器開啟 index.html 即可使用，不需要安裝。

本版重點：
- 預設為手遊規格：6 軌、每軌最多 2400 字。
- 內建 Mutopia 公版歌曲庫：G 大調小步舞曲、F 大調波蘭舞曲、羊兒安全地吃草、我的心所喜愛的根源、給艾莉絲。
- 歌曲庫可依曲名／作曲家搜尋；每首都能一鍵載入並轉成 Mobile 六軌，再分別複製主旋律、和弦 1、和弦 2。
- 歌曲庫獨立成「歌曲庫」頁籤；作曲編輯器與歌曲瀏覽分開，方便日後繼續增加曲目。
- 控制按鈕採緊湊尺寸，桌面與手機版都保留清楚的主要操作層級。
- 歌曲庫保留各曲 Mutopia 作品頁與 Public Domain 標示；授權說明：
  https://www.mutopiaproject.org/legal.html
- 曲目來源頁：
  https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=75
  https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=1013
  https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=1794
  https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=378
  https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=931
- 超過 2400 字、使用第 7 軌或有阻擋語法錯誤時，會停用複製與下載，避免輸出不完整樂譜。
- Mobile 分軌複製會自動避開 MIDI 常見的疊加附點（例如 `r1..`），改用遊戲相容的標準／單附點音長；原曲音符與拍長不變。
- BPM 只接受整數 32–255；超出範圍的 `t` 指令會阻擋複製，避免遊戲貼譜報錯。
- 手機版提供「樂譜／捲軸／設定輸出」三頁籤。
- 鋼琴卷軸支援水平時間捲動、3/4 等拍號小節線與播放跟隨。
- 修正 MIDI 匯入會因嚴格模式變數錯誤而失敗的問題。
- 保留完整 MML、分軌複製、MIDI/MusicXML、Tempo Map、SF2/DLS、智慧拆軌、無損精簡與本機自動儲存。

注意：網站的合成音色只供預覽；最終音色與相容性仍需在實際遊戲版本測試。
