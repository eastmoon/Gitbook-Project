## 電子書安裝程序

### 安裝

```
npm install
```
> 相關套件與工具已經導入專案中

##### 使用插件

插件主要透過程序來產生流程圖等繪圖語法。

+ [flowchart](https://flowchart.js.org/)
+ [mermaid](https://github.com/knsv/mermaid)

### 測試

```
npm start
```
> 啟動一個伺服器來觀看編寫結果
>
> 網址：http://localhost:4000

### 編譯

```
npm run build
```
> 重新將編譯內容輸出，讓測試檔可以重讀新內容

### 輸出

1. 安裝 [Calibre-ebook](https://calibre-ebook.com/download)
> [Mac OS 需注意官方文件設定](https://toolchain.gitbook.com/ebook.html)

2. 執行輸出命令，並在 BUILD 檔案夾下輸出指定的電子書 (pdf, epub) 檔案
> 若未執行第一步將無法正確輸出電子檔

+ 產生電子書 (PDF、Epub)
```
npm run ebook
```

+ 產生 PDF 檔案
```
npm run pdf
```

+ 產生 Epub 檔案
```
npm run epub
```
