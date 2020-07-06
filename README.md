# Node と Deno の比較

- TypeScript をデフォルトでサポート
- npm がなく、import で外部モジュールの url を渡すことで利用出来る
- require が廃止され、ESModule がデフォルトのモジュールシステム
- ファイル・ネットワーク・環境変数などは明示的に有効にしないとアクセス出来ない
- Fetch API がデフォルトでサポート

# 各ファイルの実行方法

## fetch.ts

```bash
# deno run --allow-net fetch.ts
```

## fetch.ts

```bash
# deno run --allow-net fetch.ts
```

## test.ts

```bash
# deno test test.ts
```
