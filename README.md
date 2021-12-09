# Automate Versioning and Commit
Automatizando versionamento e commits com commitizen e standard-version

<br>

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)



## Comandos NPM Usados

```sh
## Instalando o Commitizen
npm install -g commitizen
```

```sh
## Instalando o Commitizen no projeto.
npm install -D commitizen
```

```sh
## Inicializando o configurador do changelog.
commitizen init cz-conventional-changelog --save-dev --save-exact
```

```sh
## Instalando o Standard Version no projeto.
npm install -D standard-version
```

```sh
## Adiconando o Script de release no package.json.
npm set-script release "standard-version"
```
