# agewell-kobe

Age-Well KOBE 2026の来場者向けクイズ（全50問）です。`index.html` を開くだけで動作する、単一HTMLファイルのWebアプリです。

## 公開方法（GitHub Pages）

1. GitHubのリポジトリページで **Settings** → **Pages** を開く
2. 「Build and deployment」の **Source** を `Deploy from a branch` に設定
3. **Branch** を `main`、フォルダは `/ (root)` を選択して **Save**
4. 数分後、`https://kota714.github.io/agewell-kobe/` でクイズが公開されます

## 回答集計について

`index.html` 内の `WEBAPP_URL` に、回答を記録するGoogle Apps ScriptのウェブアプリURLが設定されています。回答者がクイズを完了すると、名前・スコアがそのURLへ送信され、画面下部の「運営者用：みんなの回答を見る」からパスワードを入力して集計結果を確認できます。