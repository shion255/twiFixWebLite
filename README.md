# twiFixWebLite
[Twitter Web Client](https://twitter.com/) のユーザースタイルシートです。  
ユーザースタイルシートのインストールには **Stylus** ([Firefox](https://addons.mozilla.org/ja/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Opera](https://addons.opera.com/ja/extensions/details/stylus/)) が必要です。  
ユーザースタイルシートは [こちら](https://raw.githubusercontent.com/AviSynthPlus/twiFixWebLite/master/twiFixWebLite.user.css) からインストールしてください。

## 機能
主な機能は Stylus にインストールした twiFixWebLite の [設定](https://i.imgur.com/CaH4veD.png) から確認できます。ここでは設定で変更不可能な機能を紹介します。

* ツイート時間が相対時間の時に絶対時間も併記する
* 隠れたリンクを表示する
* シングルフォトにマウスオーバーでフォーマット (JPEG, PNG) の表示
* マルチフォトの縮小表示
* 引用ツイートの全文表示
* マイリストの2列化
* 検索: `検索フィルター` を常時展開する
* status: 当該ツイートのシングルフォトをカットせずに表示する
* メッセージ: ダイレクトメッセージの幅の変更

### 非表示
* プロモーション, タイムライン上に表示される `おすすめユーザー` 等の邪魔な要素
* テキストエリアにフォーカスを当てた時にも表示されているテキスト（例: `いまどうしてる？`）
* ログインしていない時に表示される話題のツイート一覧（UI が崩れるため）
* ホーム: フォロー中のユーザーが過去に行ったリツイートの再表示
* リスト: `最近追加されたユーザー`, タイムライン上部の `ツイート`
* 検索: `関連記事`（タイムラインの幅を変更した時に重なる場合があるため）