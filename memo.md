# MVPでも最初から決めておく
- LLM API Keyの設定
    - 環境変数
    - GASのプロパティ
        - ユーザ : そのユーザのみ。他の人に共有した際に未設定になる
        - スクリプト : スクリプトにアクセスできるユーザ全員。編集権があるユーザは内容が見えてしまう
- LLMモデルの設定機能

# Gemini API
- [API Key作成と使用量、課金量確認](https://aistudio.google.com/app/apikey)
- [モデル一覧（URLのモデル名欄もここにあるものを使う）](https://ai.google.dev/gemini-api/docs/models?hl=ja)
- [料金一覧](https://ai.google.dev/gemini-api/docs/pricing?hl=ja)
    - 請求アカウントと紐づけると、最初から有料（Tier 1）でカウントされるので、無料の範囲で試す場合は請求アカウントと紐づかないプロジェクトを作成し、そのプロジェクトでAPI Keyを発行する
- [Google CloudのAPI管理](https://console.cloud.google.com/apis/dashboard)