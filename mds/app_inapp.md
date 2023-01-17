# Cordova-Plugin-InAppPurchases

Add the plugin to a cordova project to view and make in-app purchases and subscriptions with JavaScript calls.
```
cordova plugin add cordova-plugin-inapppurchases
```

View the [documentation](https://github.com/cozycodegh/cordova-plugin-inapppurchases#cordova-plugin-inapppurchases) to make calls to the plugin from `www/index.js`:

[`inAppPurchases.getAllProductInfo(productIds)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/getAllProductInfo.md) <br>
[`inAppPurchases.restorePurchases()`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/restorePurchases.md)  <br>
[`inAppPurchases.purchase(productId)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/purchase.md)  <br>
[`inAppPurchase.completePurchase(productId,consume)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/completePurchase.md)

[See updates to the plugin here.](https://github.com/cozycodegh/cordova-plugin-inapppurchases/releases)

To install the latest version on a Cordova app that has an out-dated version, add and remove the plugin:
```
cordova plugin rm cordova-plugin-inapppurchases
cordova plugin add cordova-plugin-inapppurchases
```
Then, remove and re-add platforms to re-build the plugin:
```
cordova platform rm android
cordova platform add android
```

<p align="center">

Feel free to comment here or [fork the code](https://github.com/cozycodegh/cordova-plugin-inapppurchases)!

<p>

