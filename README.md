<h3 align="center">
      <img alt="Logo" title="#logo" width="470px" src="https://github.com/dantls/week-next-level-booster1/blob/master/EColeta/logoEcoleta.png">
    <br><br>
    <br>
</h3>


# Sumário

- [Sobre](#sobre)
- [Tecnologias Utilizadas](#tecnologias)
- [Como utilizar](#como-utilizar)

<a id="sobre"></a>

## Sobre o projeto:

O <strong>Ecoleta</strong> é uma aplicação Web e Mobile que tem a motivação de ajudar pessoas a encontrarem pontos de coleta de materiais reciclavéis.
O projeto funciona como um marketplace, uma conexão entre empresas/entidades que coletam resíduos orgânicos e inorgânicos e as pessoas que precisam descartar esses resíduos.
A aplicação foi construída na trilha <strong>Booster</strong> da <strong>Next Level Week 1</strong>.

<a id="tecnologias"></a>

## Tecnologias Utilizadas:

O projeto foi desenvolvido com as seguintes tecnologias

- TypeScript
- Node.js <br><br>
  Libs auxiliares:
  - Celebrate
  - Cors
  - Express
  - Knex
  - Multer
  - Sqlite3
  <br>
- ReactJS <br><br>
Libs auxiliares:
  - Axios
  - Cep-promise
  - Leaflet
  - React-dropzone
  - React-icons
  - React-leaflet
  <br>
- React Native <br><br>
Libs auxiliares:
  - Axios
  - Expo
  - Expo-font
  - React-native-gesture-handler
  - React-native-maps
  - React-native-svg
  - Expo-location
  - Expo-mail-composer

<a id="como-utilizar"></a>

## Como utilizar:

1. Faça um clone :

```sh
  $ git clone https://github.com/dantls/week-next-level-booster1
```

2. Executando a Aplicação:

```sh
  # Instale as dependências
  $ npm install

  ## Crie o banco de dados
  $ cd server
  $ npm run knex:migrate
  $ npm run knex:seed

  # Inicie o servidor
  $ npm run dev

  # Inicie a aplicação web
  $ cd web
  $ npm start

  # Inicie a aplicação mobile
  $ cd mobile
  $ npm start
```

<h4 align="center">
    Desenvolvido por <a href="https://www.linkedin.com/in/danilo-gomes-394459103/" target="_blank">Danilo Gomes</a>
</h4>
