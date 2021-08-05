# Sequelize + Postgres snippets

Sequelize CLI scripts/ORM config snippets for VS Code

## Install

Open the link in Visual Studio Code and click "Install" button.
[vscode:extension/elushnikova.sequelize-snippets](vscode:extension/elushnikova.sequelize-snippets)


## Use

1. Use these snippets in `config.json` file generated by Sequelize:

    Prefix | Description
    --- | ---
    `pg` | Add configuration for DB at local Postgres server.
    `pgh` | Add configuration for DB published to Heroku Postgres server.

1. Use in `package.json` "scripts" section: 
    Prefix | Description
    --- | ---
    `mg` | Add NPM scripts for migrations/seeds. Do **NOT** use in projects with production data. **For initial development/testing only.**

## License
[The Unlicense](https://choosealicense.com/licenses/unlicense/)