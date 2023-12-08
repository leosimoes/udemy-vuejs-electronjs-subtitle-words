# Udemy - Desktop application with JavaScript, Electron JS and Vue JS

Project for the Udemy course "Desktop application with JavaScript, Electron JS and Vue JS".


## Steps

The steps for developing the project were:

1. Create the project in the desired directory using the following commands in the terminal:
```
cd /d D:/Projetos/WebStorm
vue createudemy-vuejs-electronjs-subtitle-words
```
![Image-01-cmd-VueCreate](/printscreens/Image-01-cmd-VueCreate.jpg)

2. Run the project with the `npm run serve` command in the terminal.

![Image-02-NpmRunServe-localhost](/printscreens/Image-02-NpmRunServe-localhost.jpg)

3. Install and add `Vuetify` to the project with the following commands in the terminal:
- `npm i vuetify`
- `vue add vuetify` and select `Vuetify 3 - Vue CLI (preview)`
- In main.js add `loadFonts()` and `.use(vuetify)`.
- `npm run serves` to run the project.

![Image-03-Vuetify-NpmRunServer-localhost](/printscreens/Image-03-Vuetify-NpmRunServer-localhost.jpg)

4. Install and add `Electron` to the project with the following commands in the terminal:
- `npm install electron --save-dev`
- `vue add electron-builder` and choose version `11.0.0`.
- `npm run electron:serve`

![Image-04-Electron-NpmRunElectronServe](/printscreens/Image-04-Electron-NpmRunElectronServe.jpg)

5. Remove `HelloWorld.vue` file and references to it.

6. Add top (`<v-app-bar>`) and bottom (`<v-footer>`) margins.

![Image-05-Header-Footer](/printscreens/Image-05-Header-Footer.jpg)


## References
https://www.udemy.com/course/aplicacao-desktop-com-javascript-electron-js-e-vue-js/