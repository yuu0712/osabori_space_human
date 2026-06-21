# おさぼり宇宙人 VIP LP — GitHub Pages 公開用

## ファイル構成

```
github-pages/
├── index.html   # LP本体（CSS全部インライン・外部依存なし）
└── README.md    # この説明書
```

`index.html` 1ファイルで完結しとる。画像も外部CSSも使ってへんから、これだけアップすれば公開できるで。

## GitHub Pages 公開手順

### ① リポジトリを作成
GitHub にログインして新規リポジトリを作成（例：`osabori-lp`）。

### ② index.html をアップロード
`index.html` をリポジトリのルートにアップロード。
（`README.md` はあってもなくてもOK）

### ③ GitHub Pages を有効化
1. リポジトリの **Settings → Pages**
2. **Source** で `Deploy from a branch` を選択
3. **Branch** で `main`（または `master`） / `/(root)` を選んで **Save**

### ④ 公開URLにアクセス
数分後、以下で公開される：
```
https://<GitHubユーザー名>.github.io/osabori-lp/
```

## メモ
- 反映には数分かかる
- 独自ドメインは Settings → Pages の Custom domain で設定可能
- LPを更新したら、`index.html` を上書きアップロードするだけ
