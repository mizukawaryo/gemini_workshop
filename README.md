## Gemini APIをgithubを介して実行する方法

- このレポジトリをフォークする

- Google AI Studioにサインアップし、Gemini APIキーを取得する

- Github Action repository secretに`API_KEY`と名付けてGemini APIキーを設定する

`Settings -> Secrets and Variables -> Actions -> Repository Secrets`

- フォークしたレポジトリの中の`prompts/templates`に実行したいプロンプトを`.txt`ファイルで保存できる

- Geminiを呼び出し、実行する

`Actions -> Run Test Workflow -> Run Workflow`

実行が完了したら、workflow runをクリックした後下にスクロールしたら`Artifacts`の下にZIPファイルで出力された`gemini_results`をダウンロードできる
