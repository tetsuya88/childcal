Cesiumを使った日野市子どもカレンダーマップ
======================
Cesiumを使った日野市子どもカレンダーをマッピングしたページです。
2015年12月における日野市の子どもカレンダーに記載されていたイベントをマッピングしました。
地面に表示される円は各幼稚園から1kmの範囲を示しています。
近隣のイベント探しに活用してください。
首都大学東京システムデザイン学部インダストリアルコース3年生の授業内で作成しました。
 
### 使い方

視点移動、ジオコーディング、地図表示の切り替え、現在地へ移動、ストリートビュー起動、ヘルプ起動の各機能がすでに実装されています。これらの機能は「ヒロシマ・アーカイブ」のものに倣っています。

+ 視点移動：左上のメニューボタン
+ ジオコーディング：左上のフォーム
+ 地図・衛星写真切り替え：右上のパラメータボタン
+ 現在地へ移動：下中央のボタン
+ ストリートビュー起動：ビルボード（アイコン）をダブルクリック
+ ヘルプ起動：右上の「？」ボタン
+ 幼稚園選択ボタン：プルダウンメニューから最寄りの幼稚園を選択してください。
 
### カスタマイズ

サンプルのKMLファイルと自分の作成したKMLファイルを入れ替えて、下記のカスタマイズを行うだけで表示できます。

+   `index.html 106行目` :
    視点配列を作成します。label, lat, lng, heading, pitch, rangeを指定可能です。画面左上のプルダウンメニューに表示されます。260行目のchangeViewPoint関数で処理されます。
+   `index.html 130行目` :
    KML配列を作成します。labelとurlを指定可能です。data/kmlに格納したkmlファイルについて指定してください。
 +   `index.html 422行目` :
    幼稚園・保育園の情報を追加します。同じ書式をコピーし、施設の名称と緯度、経度を書き変えてください。
    
+   `Cesium/Widgets/InfoBox/InfoBoxDescription.css` :
    KMLの<description>タグ内のスタイルはこのCSSで指定してください。
+   `その他` :
    自由に編集してください。


### 参考リンク

1. [GitHub Pagesでの閲覧](http://wtnv-lab.github.io/cesiumGitHubPages/ "日野市オープンデータ可視化")
2. [Cesium](http://cesiumjs.org/ "Cesium")
3. [KML Reference](https://developers.google.com/kml/documentation/kmlreference "KML Reference")
4. [Fusion Tablesを使ってみる](http://pc.nikkeibp.co.jp/article/column/20110829/1036486/ "Fusion Tablesを使ってみる-PC Online")
5. [オープンデータページ　日野](http://www.city.hino.lg.jp/index.cfm/196,129180,353,2132,html "オープンデータページ　日野")
6. [ヒロシマ・アーカイブ](http://hiroshima.mapping.jp/ "ヒロシマ・アーカイブ")
 
### ライセンス

Licensed under the [Apache License, Version 2.0][Apache]
[Apache]: http://www.apache.org/licenses/LICENSE-2.0
