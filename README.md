# Vue.js Sample

[v-okinawa Meetup #5 LT大会](https://v-okinawa.connpass.com/event/223357/)の資料です。

* scriptタグで使うVue.js
* Vite を使った開発環境
* Nuxt を使った開発環境

3種類のサンプルを置いています。

下記の手順でも同じファイルが用意できます。

## script版sample

```
assets/
  ├─ index.html・・・CDNもしくは、ダウンロードしたVue.jsファイルとapp.jsを読み込む
  │
  └─ js/app.js・・・Vue.jsの処理を記述

```

## Vite版sample

```
vite/

// インストール
npm init vite@latest vite
cd vite
npm install

// ローカルサーバー
npm run dev

// build
npm run build
```


## Nuxt版sample

```
nuxt/

// インストール
npm init nuxt-app nuxt
cd nuxt

// ローカルサーバー
npm run dev

// 静的サイトジェネレート
npm run generate
```
