# devcontainer for Ruby 3.1.2

Ruby 3.1.2 の開発環境用の devcontainer

- formatter: [rufo](https://github.com/ruby-formatter/rufo)

## 利用方法

1. GitHub アカウントがある場合、 `Use this template` から任意のリポジトリを作成する。ない場合、 `Download zip` からダウンロードする。
2. VSCode を開き、 `Reopen in Container` を実行する

## 構成

docker-compose で構成

- ruby(FROM ruby:3.1.2)

## VSCode extensions

- devcontainer
  - [rebornix.Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
- workspace
  - [kaiwood.endwise](https://marketplace.visualstudio.com/items?itemName=kaiwood.endwise)
  - [jduponchelle.rainbow-end](https://marketplace.visualstudio.com/items?itemName=jduponchelle.rainbow-end)

## リファレンス

- [Visual Studio Code Doc - Developing inside a Container](https://code.visualstudio.com/docs/remote/containers)
- [saboyutaka/sinatra\-devcontainer](https://github.com/saboyutaka/sinatra-devcontainer)
