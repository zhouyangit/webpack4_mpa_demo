# webpack4_mpa_demo
webpack4搭建多页面多环境demo

## v 1.0.1 改动
增加px2rem，以及rem.js文件（以750设计稿为准）
使用时引入rem.js，设计稿多少px，css就写多少px，自动转换为rem

## v 1.0.2 改动
添加公共代码提取，minChunks: 2

## v 1.0.3 改动
增加本地调试方法
npm run local
其余方法npm run dev, npm run test等均为build方法，如需变更，请去package.json中以及env-config中自行修改

