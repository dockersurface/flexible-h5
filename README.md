## 移动端页面适配dpr
- 使用：100px=1rem

## 前端自动化-构建工具
- 用 es6，typescript 编写的脚本文件需要编译成浏览器认识的 javascript
- 用 scss，less 编写的样式文件需要编译成浏览器认识的 css
- 检查代码是否符合书写规范，跑单元测试和集成测试
- 开发环境如果有 sourcemaps 的话调试起来就方便多了，修改完代码浏览器能自动刷新立即看到效果就更好了
- 生产环境部署代码需要压缩合并静态文件，添加文件指纹控制缓存
- 浏览器自动刷新看到效果

## gulp vs webpack
- gulp基于流的作业方式适合多页面应用开发
- webpack 适合大型单页应用方面

## gulp使用
- 参见官网：https://www.gulpjs.com.cn/docs/getting-started/quick-start/

## gulpfile.js
- sass的编译（gulp-ruby-sass）
- 自动添加css前缀（gulp-autoprefixer）
- 压缩css（gulp-minify-css）
- js代码校验（gulp-jshint）
- 合并js文件（gulp-concat）
- 压缩js代码（gulp-uglify）
- 压缩图片（gulp-imagemin）
- 自动刷新页面（gulp-livereload）
- 图片缓存，只有图片替换了才压缩（gulp-cache）
- 更改提醒（gulp-notify）
- 清除文件（del）