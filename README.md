# LIT-installation-guide

In order to make the installation as smooth as possible, it is strongly recommend to install in the following order:

1. Install [LIT-api](https://github.com/thammarith/LIT-api) first
  - Note the url that Heroku returns after setting up because it is needed in the next steps

2. Install [LIT-backend](https://github.com/thammarith/LIT-backend) for product & order management
  - Change the `host` variable in `./src/config.js` to the URL got from step 1

3. Install [LIT-LIFF](https://github.com/thammarith/LIT-LIFF) for LIFF itself
  - Change the `apiUrl` variable in `LIT-LIFF/public/connect-api.js` to the URL got from step 1

Consult the README.md files in the corresponding repository for more details
