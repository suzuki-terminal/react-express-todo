# React Todo Example

## 主要ライブラリ

- react

## セットアップ

```
npm install
npm start
```

open [http://localhost:8080](http://localhost:8080)


## React 導入のメリット

- VDOMによりViewの差分更新が行なえ, 総合的にパフォーマンスが良い.
- InputによりOutputが定まり, テストケースが発散しにくくなった.

## 課題

- API実行中にViewがUnmountされると, setStateでエラーが起きる
- 親の状態を変更する場合は, バケツリレーにより変更関数を渡さなければならない
- 全てがViewに記述されるため見通しが非常に悪い


## TODO

状態管理のためreduxを導入してみます。

[react-redux-express-todo](https://github.com/suzuki-terminal/react-redux-express-todo)
