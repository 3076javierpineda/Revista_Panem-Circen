// como empezar a compilar sass //

   Abrir vsc
1. abrir terminal git bash ctrl+ñ
   a. npm install nodemon node-sass
   b. npm init
      varios enter hasta yes

2. abrir el archivo package.json y editarlo
    a. A continuacion de && exit 1" colocar una , presionar enter
       y pegar el siguiente texto

    "build-css": "node-sass --include-path scss scss/main.scss css/style.css",
    "watch-css": "nodemon -e scss -x \"npm run build-css\""    

3. crear las carpetas con sus respectivos archivos
    a. scss/main.scss
    b. css/style.css

4. en la terminal escribir el comando // ambos una sola vez
    a. npm run build-css 
    b. npm run watch-css 

5. Cada vez que se quiera seguir compilando en SASS
    a. abrir terminal con ctrl+ñ
    b. npm run watch-css

//fin

