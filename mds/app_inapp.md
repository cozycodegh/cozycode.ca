# Cordova-Plugin-InAppPurchases

Add the plugin to a cordova project to view and make in-app purchases and subscriptions with JavaScript calls.
```
cordova plugin add cordova-plugin-inapppurchases
```

For Android apps, create a file at `www/manifest.json` containing your Google Play Store billing key from the monetization page:<br>
```js
{ "play_store_key": "<Base64-encoded public key from the Google Play Store>" }
```

View the [documentation](https://github.com/cozycodegh/cordova-plugin-inapppurchases#cordova-plugin-inapppurchases) to make calls to the plugin from `www/index.js`:

[`inAppPurchases.getAllProductInfo(productIds)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/getAllProductInfo.md) <br>
[`inAppPurchases.restorePurchases()`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/restorePurchases.md)  <br>
[`inAppPurchases.purchase(productId)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/purchase.md)  <br>
[`inAppPurchases.completePurchase(productId,consume)`](https://github.com/cozycodegh/cordova-plugin-inapppurchases/blob/main/docs/completePurchase.md)

<ins>Updates</ins>

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

More from [cozycode.ca](https://cozycode.ca):  
  * [make apps with JavaScript](https://cozycode.ca/post?pon=make-an-app-with-cordova)
  * [how to make an in-app purchases with cordova](https://cozycode.ca/post?pon=cordova-plugin-inapppurchases)
  * [a demo app for in-app purchases](https://cozycode.ca/post?pon=cordova-plugin-inapppurchases-DEMO-APP)
  * [more on in-app purchases](https://cozycode.ca/post?pon=cordova-plugin-inapppurchases-backupreadme)
  * [add ads to a Cordova app](https://cozycode.ca/post?pon=cordova-plugin-ads)

