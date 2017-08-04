experimental_pni
================
国土地理院ベクトルタイル提供実験（地名情報）

## 地名情報の GeoJSON タイル
国土地理院が整備している地名情報のうち、居住地名、自然地名、公共施設、住居表示住所について、GeoJSONタイルに変換したものを提供実験いたします。

## 地名情報
### テンプレートURL：
- 地名情報（居住地名）
https://cyberjapandata.gsi.go.jp/xyz/experimental_nrpt/{z}/{x}/{y}.geojson
- 地名情報（自然地名）
https://cyberjapandata.gsi.go.jp/xyz/experimental_nnfpt/{z}/{x}/{y}.geojson
- 地名情報（公共施設）
https://cyberjapandata.gsi.go.jp/xyz/experimental_pfpt/{z}/{x}/{y}.geojson
- 地名情報（住居表示住所）
https://cyberjapandata.gsi.go.jp/xyz/experimental_jhj/{z}/{x}/{y}.geojson
- サンプル：
https://cyberjapandata.gsi.go.jp/xyz/experimental_nrpt/15/27574/14087.geojson

### ベクトルタイルスタイル定義： 
- 地名情報（居住地名） 
https://cyberjapandata.gsi.go.jp/xyz/experimental_nrpt/style.js
- 地名情報（自然地名） 
https://cyberjapandata.gsi.go.jp/xyz/experimental_nnfpt/style.js
- 地名情報（公共施設） 
https://cyberjapandata.gsi.go.jp/xyz/experimental_pfpt/style.js
- 地名情報（住居表示住所） 
https://cyberjapandata.gsi.go.jp/xyz/experimental_jhj/style.js

## データについて
電子国土基本図（地名情報）のうち、居住地名、自然地名、公共施設、住居表示住所をズームレベル15のGeoJSONタイルに変換したものを提供実験いたします。
提供範囲は日本全国になります。
データの内容の詳細は、電子国土基本図（地名情報）ファイル仕様書（PDFファイル）（http://www.gsi.go.jp/common/000187334.pdf ）
及び電子国土基本図（地名情報）「住居表示住所」ファイル仕様書（http://www.gsi.go.jp/common/000187306.pdf ）等をご覧ください。

なお、以下の属性については本提供実験には含まれません。
- 居住地名：都道府県名のよみ、市区町村名のよみ  
- 自然地名：行政コード、都道府県名、市区町村名  
- 住居表示住所：住所コード（可読）、住所コード（数値）、経度、緯度  


## デモサイトについて
デモサイトを次の場所に用意しております。
- 本レポジトリ  
http://gsi-cyberjapan.github.io/experimental_pni/
- 地理院地図  
http://maps.gsi.go.jp/#18/35.682597/139.856129/&base=ort&ls=ort|experimental_nrpt|experimental_nnfpt|experimental_pfpt|experimental_jhj&disp=11111&lcd=experimental_jhj&vs=c1j0l0u0t0z0r0f0&d=vl

## 提供の位置づけ
国土地理院ベクトルタイル提供実験におけるデータの提供の位置づけは次のとおりです。
- 本提供実験は、ベクトルタイル提供における技術的・施策的課題を国土地理院が把握するとともに、外部からの技術的な提案を受け取り、外部との技術的な議論を通じてベクトルタイルの適切な提供方法を研究開発することを目的とするものです。
- 本提供実験の期間は、2014年8月1日から本提供実験終了までとなります。
- 本提供実験のデータは、国土地理院コンテンツ利用規約( http://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html )に従って利用できます。
- 本提供実験のベクトルタイルは基本測量成果と位置付けているものではありませんが、基本測量成果としての提供を検討するにあたって、提供を行うものです。
- 本提供実験の利用により生じた損失及び損害等について、国土地理院はいかなる責任も負わないものとします。

## 履歴
2017-08-04「地名情報（居住地名）」、「地名情報（自然地名）」、「地名情報（公共施設）」及び「地名情報（住居表示住所）」の提供実験を開始。
