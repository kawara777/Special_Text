# 特別課題
### URL
 インターネット上に存在する情報資源（文書や画像など）の場所を指し示す技術方式

-クエリ文字列とは
 サーバーに情報を送るためにURLの末尾につけ足す文字列（変数）のこと
 URLの末尾に特定の形式で表記される
 ユーザーがどこから来たかを知ることができ、Webサイトの集客に使われる

-パスパラメーター（パス変数）とは何か
 特定のユーザーや記事などの情報を表示することができるもの

-クエリ文字列との違いについて
 -パスパラメーター：Webページそのものを指定する(特定の情報を表示)。省略不可。
 -クエリ文字列(クエリパラメーター)：Webページのオプションを指定する(パスパラメーターで表示した情報をさらに細かく表示する)。省略可能。

-HTTPメソッドとは何か
 URLで指定した情報に対して「何をしたいか」を指示したもの

GET：リソース情報を取得する
POST：新しいリソース情報を送り込む
PUT：リソース情報を新しい情報で置き換える
PATCH：リソース情報の一部を新しい情報で書き換える
DELETE ：リソース情報を削除する

・HTTPステータスコードとは何か
ウェブブラウザから送られるリクエストに対し、ウェブサーバーから返信されるレスポンス内容を表す3桁の数字のこと

下記のHTTPステータスコードの意味を調べましょう。
- 200：OK【成功】リクエストは正しく処理され、要求された内容が返信されている
- 201：Created【新たに作成】リクエストは成功し、新規で作成されたリソースのURLが返信されている
- 400：Bad Request【不正】定義していないメソッドを使用されているので、リクエストが理解できず、不正扱いされている
- 404：Not Found【未検出】リクエスト先が見つからない、そもそも存在していないために、アクセスができない
- 500：Internet Server Error【サーバーエラー】サーバー側で処理方法がわからない事態が発生したことを示す

・リクエストヘッダーとは
WebブラウザからWebサーバーへの要求であるHTTPリクエストの要求内容の詳細を記述したもの

・リクエストボディとは
HTTPリクエストの要求内容に捕捉情報(追加や更新の内容)を入れるときに記述するもの

・レスポンスヘッダーとは
HTTPリクエストに対する返答(HTTPレスポンス)の詳細な情報を記述したもの

・レスポンスボディとは
HTTPリクエストに対する実際のファイル(HTMLファイル)の中身のこと

JSONとは
JavaScriptで定義されているオブジェクト表記法に由来するデータの記述方式
