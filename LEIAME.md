# Udemy – Aplicação Desktop com JavaScript, Electron JS e Vue JS

Projeto para o curso da Udemy "Aplicação desktop com JavaScript, Electron JS e Vue JS".


## Passos

As etapas para o desenvolvimento do projeto foram:

1. Crie o projeto no diretório desejado utilizando os seguintes comandos no terminal:
```
cd /d D:/Projetos/WebStorm
vue createudemy-vuejs-electronjs-subtitle-words
```
![Imagem-01-cmd-VueCreate](/printscreens/Image-01-cmd-VueCreate.jpg)

2. Execute o projeto com o comando `npm run serve` no terminal.

![Image-02-NpmRunServe-localhost](/printscreens/Image-02-NpmRunServe-localhost.jpg)

3. Instalar e adicionar `Vuetify` no projeto com os seguintes comando no terminal:
- `npm i vuetify`
- `vue add vuetify` e selecione `Vuetify 3 - Vue CLI (preview)`
- Em main.js adicionar `loadFonts()` e `.use(vuetify)`.
- `npm run serve` para execute o projeto.

![Image-03-Vuetify-NpmRunServer-localhost](/printscreens/Image-03-Vuetify-NpmRunServer-localhost.jpg)

4. Instalar e adicionar `Electron` no projeto com os seguintes comando no terminal:
- `npm install electron --save-dev`
- `vue add electron-builder` e escolher versão `11.0.0`.
- `npm run electron:serve`

![Image-04-Electron-NpmRunElectronServe](/printscreens/Image-04-Electron-NpmRunElectronServe.jpg)

5. Remover arquivo `HelloWorld.vue` e referências a este.

6. Adicionar margens superior (`<v-app-bar>`) e inferior (`<v-footer>`).

![Image-05-Header-Footer](/printscreens/Image-05-Header-Footer.jpg)

7. Criar componente `VWordAmount` com propriedades `name` e `amount`.

8. Criar componente `VHome` com propriedades `name` e `amount`.
- tendo um componente `VWordAmount`;
- com o valor de groupedWords, como uma lista de objetos com `name` e `amount`, em data;
- sendo um componente de `App.vue`.

![Image-06-Home-Pills](/printscreens/Image-06-Home-Pills.jpg)


## Referências
https://www.udemy.com/course/aplicacao-desktop-com-javascript-electron-js-e-vue-js/