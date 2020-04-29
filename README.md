## Ellean/Discuz-Android
> Fork from [Comsenz/Discuz-Android](https://github.com/Comsenz/Discuz-Android)

`master` 保持原版，修订bug
其他分支  自定义版本

IDE:Android Studio 3.6.3
SDK:29
JDK:1.8.0_202
网络请求包:OKHTTP，OKhttp-android-support,okhttp-urlconnection,okio
图片加载缓存：picasso(基于okhttp)


## 更改内容注意事项
1. app/build.gradle
    1. applicationId 自定义包名
    2. buildTypes > release 自定义打包apk名称
3. 网络API
    1. AppNetConfig > BASE_ADDRESS 自定义网址
    2. 全局搜索`http://wsq.demo.comsenz-service.com/`替换成自定义网址
3. UI
    1. 主题色blue
    2. 相关图标替换，包含ic_launcher, splash在内
4. string.xml > app_name


## 问题反馈
https://bbs.comsenz-service.com/forum-58-1.html


