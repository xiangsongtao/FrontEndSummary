# 我的技术栈及代码库（目录持续更新）

> 有好东西要学会分享！  
> 这里存放我我的技术栈及代码片段搜集总结，希望能对你有用！  
> 开发环境：WebStorm for MAC

Angualr 1.x：
-------
 - 我所遵守的[代码规范](https://github.com/johnpapa/angular-styleguide/blob/master/a1/i18n/zh-CN.md)   
 
 
Gulp自动构建：
-------
> 以下是我常用到的插件

 - **文件合并** gulp-concat； 
 - **scss编译** gulp-sass 
 - **css压缩** gulp-clean-css 
 - **css加前缀** gulp-autoprefixer  
 在css属性上加前缀，用于兼容不同内核的浏览器
 - **js压缩** gulp-uglify 
 - **px转rem** gulp-px3rem  
 用在ionic的css文件，移动端是使用rem为单位，但是ionic是使用的px，在此批量转化。
 - **将多任务合并** merge-stream  
 比如说移动lib中的文件和tpl模板文件，可以讲这两个任务合并到一起。
 - **目录清理** gulp-clean  
 清空dist目录
 - **任务队列化** gulp-sequence  
 gulp任务默认是异步执行的，某些任务需要前置任务执行完毕才可执行
 - **文件名打上MD5值** gulp-md5-plus  
 防止浏览器缓存资源文件
 - **改名字** gulp-rename  
 用法1: 改名字；  
 用法2: gulp.dist(*.tpl)时，去除文件目录结构，将资源全部放到同级目录下。
 
IONIC开发：
-------
 - **项目结构** ； 
 - **待续** 

 
Nodejs：
-------
 - **待续** 

工具：
-------
 - **Photoshop切图** [CUTTERMAN](http://www.cutterman.cn/)；  
 - **Photoshop标注** [PARKER](http://www.cutterman.cn/v2/parker) (建议购买)； 
 - **本地JSON结构检查及预览** [JSON Accelerator](https://itunes.apple.com/us/app/json-accelerator/id511324989)；
 - **在线JSON结构检查及预览** [JSON在线工具](http://www.kjson.com/)；
 - **本地图片压缩** [hummingbird](https://github.com/stormtea123/hummingbird)；
 - **代码片段管理** [SnippetsLab](https://itunes.apple.com/cn/app/snippetslab/id1006087419) (比较习惯线下管理工具)；
 - **模拟HTTP请求及API测试** [Postman](http://www.getpostman.com/)；
 - **SVN版本管理** [SmartSVN](http://www.smartsvn.com/)；
 - **Git版本管理** [GitHub Desktop](http://desktop.github.com/)；
 - **MySQL数据库查看** [Navicat for MySQL](http://www.kjson.com/)；