﻿# express-jade-document-management
A web document managment app built with [Dynamic Web TWAIN](https://www.dynamsoft.com/web-twain/overview/) and [Node.js Express](https://expressjs.com/).

## Usage
1. Apply for a valid license from [Dynamsoft online portal](https://www.dynamsoft.com/customer/license/trialLicense?product=dwt) and then update the license key in `public/Resources/dynamsoft.webtwain.config.js`.

    ```js
    Dynamsoft.DWT.ProductKey = 'LICENSE-KEY';
    ```
    
2. Start the web server:

    ```bash
    npm install
    npm start
    ```

3. Visit `localhost:3000` in a web browser.

    ![web document management with Dynamic Web TWAIN and Node.js Express](https://www.dynamsoft.com/codepool/img/2015/02/express_jade.png)
