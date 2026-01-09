# 佐藤医院トップページ

## GitHubに保存する手順
1. GitHubで新規リポジトリを作成します（例: `satoclinic`）。
2. このフォルダでターミナルを開き、以下を実行します。

```
git init
git add .
git commit -m "Initial commit"
```

3. GitHub上で表示されるリモートURLを追加してpushします。

```
git remote add origin https://github.com/<ユーザー名>/<リポジトリ名>.git
git branch -M main
git push -u origin main
```

## GitHub Pagesで公開する手順
1. GitHubのリポジトリ画面で **Settings** を開きます。
2. 左メニューの **Pages** を開きます。
3. **Branch** を `main`、**Folder** を `/ (root)` に設定して **Save** を押します。
4. 数分後に表示されるURL（`https://<ユーザー名>.github.io/<リポジトリ名>/`）へアクセスすると公開されます。
