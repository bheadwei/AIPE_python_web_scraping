# Project Gutenberg
爬取中文書籍，共 441 本。


## 📌 功能簡介

- 🔍 爬取 Project Gutenberg 中文書籍標題與連結
- 📥 自動下載 `.txt` 格式的電子書內容
- 🧹 清理掉非中文字符（保留標點符號）
- 💾 將內容儲存為 UTF-8 編碼的文字檔

## 安裝套件
- requests (2.32.3)
- beautifulsoup4 (4.13.4)

## 使用說明
- 執行`gutenberg_chineseBook.ipynb`
- 執行後會在資料夾中產生一個名為 `hw_txt` 的資料夾，裡面包含已清理完畢的 .txt 書籍檔

## 輸出結果
![](執行過程的擷圖或說明圖片)
已儲存：hw_txt\24193-燕子箋.txt
已儲存：hw_txt\25498-佛說無量壽經.txt
==================================================
發生錯誤，略過True Heart/Mind
==================================================
...
[執行結果影片連結](https://www.youtube.com/watch?v=pmVV6nDYgwg)
...

## 專案結構
.
├── gutenberg_chineseBook.ipynb    # 主程式
├── hw_txt/                    # 下載後的書籍文字檔案
└── README.md                  # 專案說明文件

## 注意事項
- 此爬蟲僅下載 .txt 版本的書籍（非每本書都有提供）

- 清理文字時會去除非中日韓統一表意文字（含英數、外文、符號等）

- 若需保留原始格式或處理 EPUB、HTML 請自行擴充程式

- 書籍內容來源為 Project Gutenberg，請依其 使用政策 合理使用
