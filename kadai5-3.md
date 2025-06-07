## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
  ：https://zipcloud.ibsnet.co.jp/api/search
  ：ユーザーが郵便番号を入力すると、それに対応する住所を自動入力できる。
* リクエストとレスポンスのフォーマット
  ：リクエスト：HTTPメソッドGETでデータを取得
  ：レスポンス：JSON
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
  ：Nominatim
  ：https://nominatim.org/release-docs/latest/api/Search/
* エンドポイントと機能
  ：https://nominatim.openstreetmap.org/ui/search.html
  :都市を入力すると緯度と経度が出力される
* リクエストとレスポンスのフォーマット
  ：リクエスト：HTTPメソッドGET
  ：レスポンス：JSON
### Q3-3. 感想
* 今回の課題で苦労したこと
  ：今までWebAPIを使用できなかったので、WebAPIをプログラムに組み込むことは苦労した。
* 演習を通して理解できたこと
  ：WebAPIをプログラミングに組み込む方法。APIの呼び出しは非同期で行われること
* Web APIの利便性や課題など
  ：外部の情報を自分でWebサイトに出力できる
  ：APIの利用ルールがAPIによって異なるので、仕様書を読まなければいけない
