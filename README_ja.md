# Sitecoredemo Docker ヘッドレススターターキット

ブログシリーズで紹介をした手順をすべて含めているプロジェクトになります。

1. .env.example のファイルをコピーして .env ファイルを作成します。
2. 以下のコマンドを管理者権限のあるターミナルで実行します。ライセンスファイルのある場所は任意です。

    ```ps1
    .\init.ps1 -LicenseXmlPath "C:\projects\license\license.xml"
    ```

3. env ファイルの `NODEJS_VERSION` に Node.js のバージョンを設定します。`node -v` コマンドで取得できます。