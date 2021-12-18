# server-test-03
VT server with nodejs express (trial 3)


## Work list (not completed)

nodejs/expressで構築する。


## ベクトルタイル配信
mbtilesフォルダから、mapbox/mbtilesをつかってPBFタイルを配信する。

* mbtilesがZL4,5,6のバラバラの区画で入っているので、ベクトルタイルのためのルーティングはonyxを改造したもの。
* MSALでのAzure AD認証をつける。

## ArcGIS Online 対応 (not yet)
ベクトルタイルサーバーのディレクトリ（パス）を作ってルーティングする。

* index.json を返せるように。
* tilemapはルーティングで対応
* style, sprites, glyphsは違う場所に置いてもいいかもしれない。
 
## Web Map APP (not yet)

* 一つはMapbox gl js のversion 1.Xで。
    * FOSS4G 2021で紹介されていたWaterGISのプラグインをつける。テンプレートはこちら。
        * レイヤーのオンオフ
        * 場所の切り替え
        * マップのエクスポート
* もう一つはMapLibreで
* 小縮尺用の地図は別に3種類作っておく。

