
# mdBook DHCPv6 專案 + VSCode 深色主題

## 使用 VSCode 深色主題
已在 `book.toml` 中設定 `additional-css`，CSS 檔案位於 `src/theme/vscode-dark.css`。

## GitHub Pages 自訂網域設定
1. 在 GitHub 專案 **Settings → Pages → Custom domain** 輸入你的網域，例如：
   ```
   docs.webberliao.com
   ```
2. 在 DNS 設定 CNAME 記錄：
   ```
   docs.webberliao.com → <username>.github.io
   ```
3. GitHub Pages 會自動簽發 HTTPS 憑證（Let's Encrypt）。
4. 在專案根目錄建立 `CNAME` 檔案，內容為你的網域：
   ```
   docs.webberliao.com
   ```

> 完成後，你的文件將可透過自訂網域 + HTTPS 存取，效果與 `<username>.github.io` 類似，但更具品牌識別。
