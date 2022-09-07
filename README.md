# Sitecoredemo Docker Headless Starter Kit

if you want to read Japanese readme. please click [here](README_ja.md)

The project will include all of the steps we have outlined in our blog series.

1. create .env file using .env.example
2. please change password `SitecoreAdminPassword` in `init.ps1`.
3. In an ADMIN terminal: Please change path for license file.

    ```ps1
    .\init.ps1 -LicenseXmlPath "C:\projects\license\license.xml"
    ```

4. please set `.env` file for `NODEJS_VERSION`. This parameter set node.js version. Please use `node -v` command.
5. please execute script : `up.ps1`

    ```ps1
    .\up.ps1
    ```

you can access to sitecore with Next.js environment.

The project will include all of the steps we have outlined in [our blog series](https://haramizu.com).
