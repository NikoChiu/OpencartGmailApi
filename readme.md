1. Upload the right files to Opencart root folder
2. Require packages from composer and add autoload file
    ```
    composer require phpmailer/phpmailer && composer require google/apiclient
    ```
3. Refresh modifications in Opencart backend
4. Create oauth client credentials from google api console
5. Enter the client id and secret in the Opencart backend and save (Setting > Setting > Edit store > Gmail Api tap)
6. Go to Gmail Api tap again and then click the authorize button to get the authorization code
7. Enter the authorization code in the Opencart backend and save (Setting > Setting > Edit store > Gmail Api tap)