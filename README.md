# Flask_Session
Login with session

網站身份驗證方式有以下幾種：

基本認證 (Basic Authentication)：基本認證是一种使用用戶名和密碼的簡單身份驗證方法，通常用於小型網站或簡單 API。

選擇性提供者認證 (OAuth)：OAuth 是一种用於 Web 应用程序的授權框架，允許用戶向第三方應用程序授權其訪問其在其他網站上存儲的數據。

JSON Web Tokens (JWT) 認證：JWT 是一種在 Web 应用程序中驗證用戶身份的常用方法，它是一种以 JSON 格式傳遞的令牌，其中包含用戶的身份信息。

令牌驗證 (Token-based Authentication)：令牌驗證是一种用於 Web 应用程序的身份驗證方法，其中客戶端通過 HTTP 要求傳送令牌，服務器使用此令牌驗證用戶。

Session 認證 (Session-based Authentication)：Session 認證是一种在服務器端存儲用戶身份信息的身份驗證方法。當用戶進行身份驗證時，服務器將生成一個 session ID，並將其傳送到客戶端。

單一登錄 (Single Sign On, SSO)：SSO 是一种身份驗證方法，允許用戶在訪問多個網站時只需輸入一次憑據

----------------------------------------------------------------------------------------------------------------------------------------------------------------

以下是各種網站身份驗證方式的優點和缺點：

基本認證 (Basic Authentication)：
優點：簡單實現，易於理解。
缺點：密碼不加密，不安全。

OAuth (Open Authorization)：
優點：安全，可擴展，可用於多個網站。
缺點：複雜實現，需要更多的開發工作。

JSON Web Tokens (JWT) 認證：
優點：簡單實現，安全，跨域兼容。
缺點：令牌可以被篡改，需要特別注意安全問題。

令牌驗證 (Token-based Authentication)：
優點：安全，靈活，易於實現。
缺點：對於大型網站可能不夠靈活，需要更多的開發工作。

Session 認證 (Session-based Authentication)：
優點：簡單實現，易於理解。
缺點：容易被會話劫持攻擊，不安全。

單一登錄 (Single Sign On, SSO)：
優點：方便用戶使用，安全。
缺點：實現複雜，需要更多的開發工作。

請注意，每種方法都有其特定的用例，因此選擇哪種方法取決於您的特定需求。