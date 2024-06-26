## Instale os pacotes 

```
    yarn add express
    yarn add @types/express @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint@7.21.0 eslint-config-airbnb-base eslint-config-prettier eslint-plugin-import eslint-plugin-prettier typescript ts-node-dev -D

```

## Baixe os arquivos descritos em

[Clique aqui...](https://efficient-sloth-d85.notion.site/ESLint-e-Prettier-Trilha-Node-js-d3f3ef576e7f45dfbbde5c25fa662779)

O resultado do tutorial é o arquivo ```.eslintrc.json``` 


## Configure o package.json

```
...
   "scripts": {
    "dev": "ts-node-dev --transpile-only --ignore-watch node_modules --respawn src/index.ts"
  },
...

```