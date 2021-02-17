# nuxt-docker-optimization

Nuxt.js アプリケーションの Docker イメージを軽量化するデモ。
手元の環境では 1.15GB のイメージを 188MB まで小さくすることができている。

## コマンド

```sh
$ yarn build-docker # 最適化されていないイメージをビルド
$ yarn build-docker-optimized # 最適化されたイメージをビルド
$ yarn run-docker # 上で作成したイメージを実行
```
