# Base Webpack
Projeto Base de Webpack com suporte para ES6 (Babel), PUG e SASS.

# Uso
A pasta "app" é a pasta de desenvolvimento.
<br />
Uma vez o webpack tendo feito o build, o resultado é gerado na pasta "build".

# Scripts NPM
- Para rodar o servidor do projeto, sem build:
```sh
$ npm start
```
- Para fazer o build do projeto minificado para produção:
```sh
$ npm run build
```
- Para fazer o build do projeto para desenvolvimento:
```sh
$ npm run build:dev
```
Após rodar o servidor, o browser irá abrir na URL do projeto e a cada alteração no código, ocorrerá refresh automático.
<br />
Caso deseje mudar a porta padrão (9000), basta alterar a mesma no arquivo "webpack.config.babel.js".
