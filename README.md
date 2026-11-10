# singularitysociety.github.io

Singularity Society の GitHub Pages のトップ（https://singularitysociety.github.io/ ）。

Singularity Society のサイト、note の記事、Receptron のプロダクト、おもちかえり.com、セキュリティ教育への入口を置く。

## 入口を足すとき

`index.html` の該当する見出しの下の `<ul>` に `<li>` を 1 つ足す。見出しが無ければ `<h2>` と `<ul>` を足す。同じ組織のリポジトリのページは `/<リポジトリ名>/` で書く。

ビルドはない。main にマージすると、そのまま公開される（`.nojekyll` で Jekyll の処理は通さない）。
