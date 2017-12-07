# middleman-parcel

## インストール方法

```
$ brew install yarn
$ rbenv install 2.4.2
$ rbenv global 2.4.2
$ gem install middleman
$ git clone git@github.com:zacky1972/middleman-parcel.git
$ cd middleman-parcel
$ yarn install
```

## ローカルプレビュー

```
$ middleman serve
```

## 備忘録

* 最初のインストール時に次の設定にしました。
  * Asset Pipe Line をオフにしました
  * Compass, LiveReload はインストールしています
  * config.ru を有効にしました。Heroku などにデプロイするときに使います
