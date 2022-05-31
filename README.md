# Graph QL API tutorial
- WEB APIのクエリ言語

## Directory
- backend
  - GraphQL server
- frontend
  - Vite(React)

## Pros
- 単一エンドポイント
- 必要なデータを取得可能
  - Overfetch Underfetch対策
- 型指定でデータが明確

## Query Types
1. query
  - データ取得（GET）
2. mutaition
  - データ更新（POST/PUT/DELETE...etc）
3. subscription
  - イベント通知・オンライン（Websocket）

[Archetecture](https://www.tutorialspoint.com/graphql/images/graphql_hybrid_approach.jpg)

## Terms
- Resolver
  - Schema定義の実際のデータ操作を行うメソッド。特定フィールドデータを返す

# Library
- Vite
  - ビルドツール
- Apollo
  -
- apollo/client
- apollo/react-hooks graphql apollo-boost
  - backendで用意したAPIにアクセスするために必要

## How to build
``` bash
$ npm create vite@latest
$ npm i
```
