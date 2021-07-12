# Mission - API Blueprint

## Prerequisite

- [Node.js](https://nodejs.org/en/) Version >=14.x.x
- [VS Code](https://code.visualstudio.com/)
  - [API Blueprint Viewer](https://marketplace.visualstudio.com/items?itemName=develiteio.api-blueprint-viewer) (Optional)
  - [API Elements extension](https://marketplace.visualstudio.com/items?itemName=vncz.vscode-apielements) (Optional)
- [Drakov](https://github.com/Aconex/drakov) Version 1.0.4

## Required Install Drakov v1.0.4

```shell
npm install -g drakov@v1.0.4
```

## Run Mock API Blueprint

```shell
drakov -f "*.apib" -p 8080 --watch --public
```

### Mock route

```
POST http://localhost:8080/badge/claim
GET http://localhost:8080/badge/available
GET http://localhost:8080/badge/status
GET http://localhost:8080/badge/status/inprogress
GET http://localhost:8080/badge/status/achievedCompleted
```
