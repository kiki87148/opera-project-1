# Project 1｜曲線之間：臺中國家歌劇院影展專題

- 姓名：林芮安
- 學號：D1446672
- 製作日期：2026-11-05
- 主題：延續先前臺中國家歌劇院網頁，改為影展專題介紹網站。
- 工具：ChatGPT（協助整理企劃、產生 HTML/CSS/JavaScript、檢查檔案連結）。

## 1. 本次實際提出的指令

> 用之前的台中國家歌劇院來做

接著提供 Project 1 作業要求截圖：完整網頁需有導覽列、側邊欄、分頁、SEO、Grid System、RWD；CSS 與圖片分別放置於 css、images 資料夾；提供 GitHub Markdown Prompt 說明、InfinityFree 首頁和 Vercel 網址。

## 2. 依需求整理的完整 Prompt（重現用，非逐字對話紀錄）

> 請延續我之前的「臺中國家歌劇院」主題，製作繁體中文的 Project 1 影展專題介紹網站。以「曲線之間」為暫定片名，內容為建築紀錄短片的課堂企劃。保留建築背景介紹，新增專題理念、拍攝企劃與建築走讀等獨立分頁。每頁要有主要導覽列、側邊欄目錄與分頁連結。以 CSS Grid 安排主要內容與側欄，加入桌機、平板與手機 RWD；在手機上保留完整資訊。使用 HTML5 語意標籤、各頁獨立 title 和 description、Open Graph、結構化資料與圖片 alt。把所有 CSS 放進 css/style.css，實際照片放入 images 資料夾並註明來源及授權。使用相對路徑，讓專案能直接上傳 InfinityFree 或以 GitHub 部署 Vercel。不使用需要後端或安裝套件的功能。未提供的片長、日期、組員與成片連結請標示「待確認」，不要捏造成已完成活動。另提供 PROMPTS.md、部署說明與作業檢查清單。

## 3. Vibe Coding 的使用方式

1. 以自然語言說明既有主題與作業條件。
2. 由 AI 整理頁面結構，產生共用外部 CSS 與各頁 HTML。
3. 對照作業條件檢查導覽、分頁、Grid、RWD 與 SEO。
4. 檢查圖片是否為本機檔案、連結是否指向正確檔案。
5. 實際部署後再測試手機、導覽、照片與分頁。

## 4. 實作對照

| 要求 | 本專案實作 |
| --- | --- |
| 導覽列 | 各頁 header 內的 nav.main-nav |
| 側邊欄 | 各頁 aside.sidebar，本頁章節錨點 |
| 分頁 | 4 個獨立 HTML 與頁尾 01–04 頁碼 |
| Grid System | .page-grid、.cards、.status dl |
| RWD | viewport 與 1050px、640px media queries |
| SEO | 各頁 title、description、lang、robots、OG、JSON-LD |
| CSS 分離 | css/style.css，無行內或內嵌 CSS |
| 本機圖片 | images/opera-exterior.jpg、favicon.svg |
| 可存取性 | skip link、alt、鍵盤焦點、aria-current、表頭 scope |

## 5. 人工確認事項

- 影展題材是否符合老師對本組作品的要求。
- 確認姓名學號及補齊組員、實際片長、成片與展映資訊。
- 本網站的拍攝企劃為建議草案，不代表已完成拍攝或已獲場地合作。
- 正式網址確定後，再補各頁 canonical、og:url、og:image 絕對網址及 sitemap.xml；目前未填入假的網域。
- 部署後以實際桌機與手機測試，並確認三個交件連結可供老師開啟。

## 6. 資料與圖片

- [歌劇院建築設計](https://www.npac-ntt.org/about/architecture/design)
- [歌劇院官方網站](https://www.npac-ntt.org/)
- 圖片：李家宇，[國家表演藝術中心－臺中國家歌劇院外觀](https://commons.wikimedia.org/wiki/File:國家表演藝術中心-臺中國家歌劇院外觀.jpg)，[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)。照片原檔未修改，部分版面裁切顯示。
