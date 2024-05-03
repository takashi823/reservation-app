# 予約システム

## ライブラリ

### icon

```sh
yarn add @heroicons/react

yarn add clsx
```

### formatter & linter

```sh
yarn add -D prettier eslint-config-prettier

yarn add --dev eslint-plugin-perfectionist eslint-plugin-prettier

yarn add --dev prettier-plugin-organize-imports
```

※ フォーマッター、リンター設定後に下記コマンドを実行するとプロジェクト全体をフォーマットしてくれる

### 実行コマンド(フォーマッター)

```sh
yarn lint:fix
yarn lint
```

### React Cosmos

```sh
yarn add --dev react-cosmos@next react-cosmos-next@next
```

cosmos.imports.tsは `yarn cosmos` でcosmos起動時に作成される。
.gitignoreに「cosmos.imports.ts」を追加しておきます。

### 実行コマンド(cosmos)

```sh
yarn cosmos
```

### Drizzle(ORM)

今回は、sqliteを使用するので、sqlite用のライブラリを追加します。

```sh
yarn add -D drizzle-kit @types/better-sqlite3
```

## 開発時の表示確認

開発時は、下記コマンドでnextとcosmosを起動しておく。

### 実行コマンド

```sh
yarn dev
yarn cosmos
```

表示確認は、下記のURLから確認する。

■ nextの表示
http://localhost:3000/

■ cosmosの表示
http://localhost:5001/
