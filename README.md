# buta7-nuxt-blog-contentful.netlify.app

## はじめに

以下を参考に構築

* [【まえがき編】Nuxt\.js \+ Contentful \+ NetlifyでSPAブログを自作する \- Qiita](https://qiita.com/hitsuji-haneta/items/9fb971855026386fa5c5)
* [【Nuxt\.js編】Nuxt\.js \+ Contentful \+ NetlifyでSPAブログを自作する \- Qiita](https://qiita.com/hitsuji-haneta/items/7e41bf5cdfde55b826a4)
* [【Contentful編】モダンな感じのSPAブログを自作する \- Qiita](https://qiita.com/hitsuji-haneta/items/6be4745b9bd6b098843f)
* [【Netlify編】Nuxt\.js \+ Contentful \+ NetlifyでSPAブログを自作する \- Qiita](https://qiita.com/hitsuji-haneta/items/c6c1a9ddd74886116b72)

## セットアップ

```shell
npm i -S contentful
npm i -S dotenv
```

## 備考

* 必須項目のheaderImageの画像がdraft状態だとfields.file.urlが取得できずエラーになる
