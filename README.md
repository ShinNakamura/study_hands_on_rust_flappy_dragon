# Hands-on Rust (English Edition) で勉強中

書籍 : [Hands-on Rust (English Edition) Kindle版 英語版  Herbert Wolverson  (著) ](https://www.amazon.co.jp/gp/product/B09BK8Q6GY/)

Rust勉強のために書いているコードを途中経過もコミットしながら公開しているものです。

- このリポジトリに残されているコードは書籍内のコードとは完全に一致しません。あくまでも僕の勉強過程を記録したものです。

## First Game

第3章の「Build your first game with Rust」の内容に沿ったコーディングをしています。

## ビルドしたexeを直で叩いたときにコマンドプロンプトを表示しない

`main.rs` の冒頭に次のように書く。

```rust
#![cfg_attr(not(debug_assertions), windows_subsystem = "windows")]
```

参考: [RustでWindowsのコマンドプロンプトウィンドウを抑止する方法](https://qiita.com/LNSEAB/items/6f60da458460274e768d)
