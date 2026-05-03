# おさぼり宇宙人 LP — GitHub Pages 公開用

## ファイル構成

```
github-pages/
├── index.html      # メインLP
├── styles.css      # スタイル
├── scripts.js      # スクリプト
└── README.md       # この説明書
```

## GitHub Pages での公開手順

### ① 新しいリポジトリを作成
GitHub にログインして、新規リポジトリを作成。
（例：`osabori-lp` という名前で）

### ② ファイルをアップロード
このフォルダ内の **3ファイル全部** をリポジトリのルートにアップロード：
- `index.html`
- `styles.css`
- `scripts.js`

（`README.md` はあってもなくてもOK）

### ③ GitHub Pages を有効化
1. リポジトリの **Settings → Pages**
2. **Source** で `Deploy from a branch` を選択
3. **Branch** で `main`（または `master`） / `/(root)` を選択
4. **Save** をクリック

### ④ 公開URLにアクセス
数分後、以下のURLで公開される：
```
https://<あんたのGitHubユーザー名>.github.io/osabori-lp/
```

## 注意事項

- 3ファイルとも **同じ階層** に置くこと（パスが相対指定やから）
- 反映には数分かかる
- 独自ドメインを使いたい場合は、Settings → Pages の Custom domain で設定可能
