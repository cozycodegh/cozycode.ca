# Cordova-Plugin-InAppPurchases

Add the plugin to a cordova project to view and make in-app purchases and subscriptions with JavaScript calls.
```
cordova plugin add cordova-plugin-inapppurchases
```

To install the latest version on an app with an out-dated version, add and remove the plugin:
```
cordova plugin rm cordova-plugin-inapppurchases
cordova plugin add cordova-plugin-inapppurchases
```
Then, remove and re-add platforms to re-build the plugin:
```
cordova platform rm android
cordova platform add android
```
[View new updates](https://github.com/cozycodegh/cordova-plugin-inapppurchases/releases)

View the documentation to make calls to the plugin from `www/index.js`:

[`inAppPurchases.getAllProductInfo(productIds)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/getAllProductInfo.md) <br>
[`inAppPurchases.restorePurchases()`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/restorePurchases.md)  <br>
[`inAppPurchases.purchase(productId)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/purchase.md)  <br>
[`inAppPurchase.completePurchase(productId,consume)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/completePurchase.md)

<p align="center">

Feel free to comment here or [fork the code](https://github.com/cozycodegh/cordova-plugin-inapppurchases)!

<p>

