
<img src='http://www.chiangmaijointour.com/upload/logo.JPG' height='240' align='right' />

# hexo-theme-chiangmai

hexo-theme-chiangmai is kind of Hexo theme using HTML5, SCSS, Pug, Gulp. An example page with hexo-theme-chiangmai could be found at the below.

> http://holaxprogramming.com/

## Install

### Prerequisite

- hexo-browsersync 
- hexo-renderer-pug
- hexo-generator-feed 
- hexo-generator-archive
- hexo-generator-sitemap 

``` bash
$ hexo init my-blog
$ cd my-blog
$ npm install
$ npm install --save hexo-renderer-pug hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
$ git clone https://github.com/stunstunstun/hexo-theme-chiangmai.git themes/chiangmai
```

### To use gulp

``` bash
$ cd themes/chiangmai
$ npm install --save-dev gulp gulp-sass gulp-autoprefixer
$ gulp
```

## Configuration

`_config.yml`

```yaml
theme: chiangmai

# hexo-generator-archive
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## Deploy

```shell
$ hexo clean
$ hexo generate
$ hexo deploy
```

## Update Theme

``` bash
cd themes/chiangmai
git pull
```