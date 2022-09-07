# Sitecoredemo Docker ヘッドレススターターキット

ブログシリーズで紹介をした手順をすべて含めているプロジェクトになります。

1. .env.example のファイルをコピーして .env ファイルを作成します。
2. `init.ps1` ファイルに記載している `SitecoreAdminPassword` のパスワードを変更します
3. 以下のコマンドを管理者権限のあるターミナルで実行します。ライセンスファイルのある場所は任意です。

    ```ps1
    .\init.ps1 -LicenseXmlPath "C:\projects\license\license.xml"
    ```

4. env ファイルの `NODEJS_VERSION` に Node.js のバージョンを設定します。`node -v` コマンドで取得できます。
5. `up.ps1` を実行してください。

    ```ps1
    .\up.ps1
    ```

しばらくすると Next.js と Sitecore が動いている環境が起動します。

このプロジェクトの作成手順は[ブログ](https://haramizu.com)を参照してください。