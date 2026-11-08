# トップに入口の一覧を置く（#1）

## 目的

https://singularitysociety.github.io/ が 404 なので、組織の各リポジトリが公開しているページへの入口を置く。

## やること

- `index.html` を 1 枚置く。ビルドなし、外部の読み込みなし（CSS も中に書く）。
- 並べる入口:
  - 公式サイト https://singularitysociety.org/
  - 行動規範・カルチャー・開発の心得 `/societys_statement/`
  - セキュリティ教育 `/security-education/`
- ライトとダークの表示を切り替える（`prefers-color-scheme`）。スマートフォンの幅で横にはみ出さない。
- `.nojekyll` を置き、Jekyll の処理を通さない。
- 入口を増やすときは `index.html` に 1 項目足し、README の手順に従う。

## 確かめること

- マージ後、トップが 200 を返し、3 つのリンクがすべて 200 を返す。
- 下の階層の 2 つのページが、トップの公開後も開ける。
