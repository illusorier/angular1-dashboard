AngularJS如何与ES6进行结合？

#### Webpack和Gulp的对比

就拿本项目来说，实现一个JS、CSS预编译并注入HTML中，然后建立一个本地开发服务器这么一个流程，webpack会简便非常多。

### TODO:

1. enable using templateUrl
2. ng-annotate with ng-uglify
3. watch styles and scripts
4. vendor.js

compile => inject => watch => compile => inject => reload

##### build的流程

clean

scripts, styles( js和css的预处理 ) => inject ( 将js和css注入html ) 

partials( templateUrl的处理 )

html ( templateCacheHtml的注入 )

build流程结束

##### watch的流程