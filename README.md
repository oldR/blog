#### gulpfile.js放入站点根目录
```sh
npm install gulp -g
npm install gulp-minify-css gulp-uglify gulp-htmlmin gulp-htmlclean gulp --save
```
#### 压缩命令
```sh
hexo g && gulp
```

#### 其他插件
```sh
cd themes/next
# 加载进度条
git clone https://github.com/theme-next/theme-next-pace source/lib/pace

# 阅读进度条
git clone https://github.com/theme-next/theme-next-reading-progress source/lib/reading_progress

# 分享
git clone https://github.com/theme-next/theme-next-needmoreshare2 source/lib/needsharebutton
```
