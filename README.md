# AIデベロッパーホーム

GitHub Pagesで公開されるシンプルなホームページです。AIデベロッパーが開発したアプリケーションへのリンク集を掲載しています。

## 公開中のアプリ

- [元本積立アプリ](https://chokin.aidev-sandbox.net) - 資産運用のための積立シミュレーションアプリ

## GitHub Pagesでの公開方法

このリポジトリをGitHub Pagesで公開するには、以下の手順に従ってください：

1. リポジトリの「Settings」タブを開く
2. 左側のメニューから「Pages」を選択
3. 「Source」セクションで「Deploy from a branch」を選択
4. ブランチとして「main」（またはデフォルトブランチ）を選択し、フォルダは「/(root)」を選択
5. 「Save」ボタンをクリック

設定後、数分でサイトが公開されます。公開されたURLはGitHub Pagesの設定ページに表示されます。

## ローカルでの確認方法

ローカル環境で確認するには、以下の方法があります：

1. 単純にindex.htmlをブラウザで開く
2. あるいは、簡易HTTPサーバーを使う場合：
   ```
   python -m http.server
   ```
   上記コマンドを実行後、ブラウザで `http://localhost:8000` にアクセスする

## カスタマイズ

- `index.html` - ホームページの構造
- `styles.css` - スタイル設定
- 新しいアプリを追加する場合は、`index.html`の`.app-list`内に新しい`.app-item`を追加してください。 