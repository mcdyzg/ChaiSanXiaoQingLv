# phaser-boilerplate


----------

phaser游戏开发脚手架，支持ES6语法，支持class类继承

## USAGE

**develope(开发):**

1. npm install
2. npm start
3. open localhost:8081 in chrome

**build(打包):**

1. npm run build
2. open dist/

## 文件结构

- src(游戏代码目录)
- assets(素材目录)
- assets/img(素材图片文件夹，打包时会将本文件夹移动到dist/assets下)
- js(本地开发时需要引入的js放置在本文件夹下，打包时不会移动到dist下)
- dist(打包后产生的文件夹，将src/main.js压缩成app.min.js，将assets/img移动到dist/assets/img，将index.tpl.html打包成dist/index.html并在html中自动添加script src='app.min.js'标签。)

