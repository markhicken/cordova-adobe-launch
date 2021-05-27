# cordova-adobe-launch
A basic implementation of Adobe Launch in Cordova. For more information, see the associated blog post over at [hickendesign.com](https://www.hickendesign.com/site/2017/05/rock-mobile-apps-cordova-adobe-dtm-launch/).

## To run it...
1. Clone the repo or download it locally.
```
git clone https://github.com/markhicken/cordova-adobe-launch.git
```

2. Update the DTM/Launch embed code in [www/index.html](www/index.html#L39).

3. Install dependencies and platforms
```
npm i
cordova platform add ios
```

4. Run it!
```
cordova run ios
```
