# OAuthとOIDC


* [OAuth & OIDC 入門編 by #authlete【動画】](https://www.youtube.com/watch?v=PKPj_MmLq5E)
* [一番分かりやすい OpenID Connect の説明](https://qiita.com/TakahikoKawasaki/items/498ca08bbfcc341691fe)
* [IDトークンが分かれば OpenID Connect が分かる](https://qiita.com/TakahikoKawasaki/items/8f0e422c7edd2d220e06)
* [OpenID Connect 全フロー解説](https://qiita.com/TakahikoKawasaki/items/4ee9b55db9f7ef352b47)
* [OAuth 2.0 全フローの図解と動画](https://qiita.com/TakahikoKawasaki/items/200951e5b5929f840a1f)

##  OAuth

* インプリシットフローはOAuth２．１で非推奨になっている！（webブラウザで使う。JSでアクセスTOKENを渡し、フラグメント部（#）はサーバ側には渡さない。）
* リソースオーナー・パスワード・クレデンシャルズフローも非推奨 
* OAuth2.0は認可の仕組みしか定義していない。（認証の仕組みは定義されていない）

## OIDC
* response_typeの仕様を拡張（OAuthではcode（Authrization cade フロー）かtoken（インプリシットフロー））し、
id_token,none,【code,token,id_token】の任意の組み合わせを追加
* scopeパラメータの取りうる値にopenidを定義
* 上記の組み合わせでフローが確定する。動画の60分くらいから参照

