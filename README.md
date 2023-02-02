# Flask_Session
Login with session

網站身份驗證方式有以下幾種：

基本認證 (Basic Authentication)：基本認證是一种使用用戶名和密碼的簡單身份驗證方法，通常用於小型網站或簡單 API。

選擇性提供者認證 (OAuth)：OAuth 是一种用於 Web 应用程序的授權框架，允許用戶向第三方應用程序授權其訪問其在其他網站上存儲的數據。

JSON Web Tokens (JWT) 認證：JWT 是一種在 Web 应用程序中驗證用戶身份的常用方法，它是一种以 JSON 格式傳遞的令牌，其中包含用戶的身份信息。

令牌驗證 (Token-based Authentication)：令牌驗證是一种用於 Web 应用程序的身份驗證方法，其中客戶端通過 HTTP 要求傳送令牌，服務器使用此令牌驗證用戶。

Session 認證 (Session-based Authentication)：Session 認證是一种在服務器端存儲用戶身份信息的身份驗證方法。當用戶進行身份驗證時，服務器將生成一個 session ID，並將其傳送到客戶端。

單一登錄 (Single Sign On, SSO)：SSO 是一种身份驗證方法，允許用戶在訪問多個網站時只需輸入一次凭据