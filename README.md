# カメラの切り替え動作テスト

前面・背面カメラを切り替えるテストコード。  
デバイスIDをセットすれば切り替えられるという記事を見かけるが、iOSでは上手くいかなかった。（Androidではできた）  
今は`facingMode`を`user`か`environment`で前面・背面を切り替えるのかもしれない。  

## 参考URL
+ [HTML5で背面カメラを取得する](http://ichiy.hatenablog.com/entry/2014/07/11/202327)
+ [WebRTCにおけるカメラの切り替え](https://teratail.com/questions/73726)
+ [MDN MediaDevices.getUserMedia()
](https://developer.mozilla.org/ja/docs/Web/API/MediaDevices/getUserMedia)

## ローカルでの開発
`$ yarn install`でパッケージをインストール。  
`$ yarn start`でBrowserSyncが立ち上げる。  
