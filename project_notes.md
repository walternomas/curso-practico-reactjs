### Dependencias en package.json

```json
"react": "^17.0.2",
"react-dom": "^17.0.2",
"react-router-dom": "^5.2.0",
"webpack": "^5.50.0",
"webpack-cli": "^4.8.0",
"webpack-dev-server": "^4.0.0"
```

### Instalación de React y React DOM

```bash
npm init -y
npm i react@17 react-dom@17
```

### Carpetas y primeros archivos
- src
  - index.js
  - components
    - App.jsx
- public
  - index.html

### Otras instalaciones

#### Babel
```
npm install @babel/core @babel/preset-env @babel/preset-react
```

#### Webpack
```
npm install webpack webpack-cli webpack-dev-server 
```

#### HTML Plugin
```
npm install babel-loader html-loader html-webpack-plugin
```

### SASS
```
npm i mini-css-extract-plugin css-loader style-loader sass sass-loader -D
```

## Quiz: Configurando el entorno de desarrollo para React

### Ya tienes tu loader de Babel instalado y conectado con Webpack. ¿Dónde defines los presets con los que vas a trabajar?
.babelrc

### ¿Cuál es el archivo de configuración donde definimos los loaders con los que trabajaremos cada distinto tipo de archivo en nuestro proyecto?
webpack.config.js

### ¿Cuál es el loader de Webpack necesario para trabajar con código JavaScript interpretado por Babel?
babel-loader

### ¿Cuál es el comando correcto para trabajar con la versión 17 de React y React DOM.
npm install react@17 react-dom@17 --save

### ¿Cuál es el comando correcto para instalar la última versión de React y React DOM.
npm install react react-dom --save


## Quiz: Maquetación en React

### ¿Qué cambios necesita el siguiente elemento HTML para funcionar correctamente con React.js y JSX?
```javascript
<img src="url">
```
Falta el cierre de la etiqueta:
```javascript
<img src="url" />
```

### ¿Qué cambios necesita el siguiente elemento HTML para funcionar correctamente con React.js y JSX?
Párrafo

### ¿Qué cambios necesita el siguiente elemento HTML para funcionar correctamente con React.js y JSX?
```javascript
<input type="text">
```
Falta el cierre de la etiqueta:
```javascript
<input type="text" />
```
