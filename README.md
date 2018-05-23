# -npm-install-error
本人win10，整理一些常见的npm报错与大家分享
ERROR 1~~~~~~~~~~~~
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! chromedriver@2.34.1 install: `node install.js`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the chromedriver@2.34.1 install script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Y\AppData\Roaming\npm-cache\_logs\2018-01-27T10_39_44_245Z-debug.log
solution ~~~~~~~~~~~~
网上教程说这是npm安装的时候，被墙了，可以用下面从国内镜像上来下载，
 但实际上即使我开了外网npm install也会报错，但以下方法从来没出现过问题。
npm install chromedriver –chromedriver_cdnurl=http://cdn.npm.taobao.org/dist/chromedriver
