# Gulp4-v2

## Начало работы
  #### `npm i` Установка 
  #### `gulp`Запуск
  #### `gulp clean` Очищает папку DIST
  

Panini: https://github.com/zurb/panini.git



`const { src, dest } = require("gulp");` 
чтение и запись исходников

`const gulp = require("gulp");` подключает GULP

`const autoprefixer = require("gulp-autoprefixer");` - автопрефикс

`const cssbeautify = require("gulp-cssbeautify");` - делаем css красиво

`const removeComments = require('gulp-strip-css-comments');` - удаляет комментарии в *.min.css

`const rename = require("gulp-rename");` - добавляет *.min к файлам

`const sass = require("gulp-sass");` - компилятор SASS

`const cssnano = require("gulp-cssnano");`  - сжимет CSS и удалет пробелы, и последние (;), делает весь CSS в одну 
строку

`const rigger = require("gulp-rigger");` - склеивает разные JS файлы в один

`const uglify = require("gulp-uglify");` - сжимает  JS файлы

`const plumber = require("gulp-plumber");` -  при ошибке в JS не слетают Таски в Gulp

`const imagemin = require("gulp-imagemin");` - сжатие и оптимизация изображений

`const del = require("del");` - очищает папку Dist

`const panini = require("panini");`  Работа с HTML, создает шаблоны и реализует фрагменты кода, плагин PANINI

`const browsersync = require("browser-sync").create();` // локальный сервер с live reload`

### Плагин Panini: https://github.com/zurb/panini.git

обновлено 13 07 2019


