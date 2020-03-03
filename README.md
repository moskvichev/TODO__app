 # TODO__app
 # https://moskvichev.github.io/TODO__app/ 

Для работы с кодом приложения необходимо провести установку пакетного менеджера 
bower: 
```
$ npm install -g bower
```
После установки bower, в дериктории файлов установить компоненты менеджера: 
```
$ bower init
$ bower install bootstrap --save
$ bower install Font-Awesome --save
$ bower install gulp --save
```
Команда `bower list` покажет установленные компоненты, что будет подтверждать их правильную установку
```
$ bower list
├── bootstrap#4.4.1
├── components-font-awesome#5.12.1
└── gulp#4.0.2 extraneous
```
Установить task менеджер gulp
```
$ npm install gulp-cli -g
$ npm install gulp -D 
$ npx -p touch nodetouch gulpfile.js
```
Установить инструменты для gulp:
```
$ npm install --save-dev gulp-rename
$ npm install --save-dev gulp-sass
$ npm install --save-dev gulp-autoprefixer
$ npm install --save-dev gulp-sourcemaps
$ npm install --save-dev browser-sync
```
После этого можно использовать команды: 

```
$ gulp // запускает все процессы одновременно
$ gulp build // процесс сборки стилей (собирает и отключается)
$ gulp watchSass // наблюдает за изменениями стилей
$ gulp sync // открывает браузер
```
