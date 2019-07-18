# GeckoForm Postman examples

To get started first install Postman, available for free from getpostman.com.

Import the collection and create an environment called "GeckoForm", it should contain three items called "refresh-token", "access-token" and "refresh-token".
GeckoSupport will be able to provide you with these API tokens.

You can use the "Auth/Refresh Token" request to refresh all three tokens, the values in the environment will automatically be updated.

As you execute the other requests they will automatically use the latest token from the environment.