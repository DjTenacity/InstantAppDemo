#  InstantAppDemo
instant app 是谷歌推出的类似于微信小程序（或者说小程序类似于instant app）的一项技术，用户无须安装应用，用完就走，同时兼备h5的便捷和原生应用的优质体验。


# 工作方式和应用场景
## 工作方式：

当用户点击链接时，通过applink去打开相应的instant app，如果之前没有打开过，则会从play store去下载并打开，整个过程一气呵成，跟浏览器打开网页，如果有缓存先读缓存，没有就去服务器loading一样

## 应用场景：

通过直接点击链接进入（从社交网络或短信中点击链接）

通过浏览器搜索，如搜索X电商的y商品，通过点击浏览器的搜索结果可直接进入instant app

通过google play 可以先试用部分功能，觉得不错再安装完整功能

在游戏中方面的应用，跟上面类似，更偏相向于试玩

## 如何创建模板Demo
创建一个project
当走到选择form和sdk版本时，勾选 “include android instant app support
填写apps link 相关的url 参数，这里作为创建演示用默认值就好
项目创建完成后会生成4个模块.至此一个模板instant app创建过程就完成了

## 项目结构
4个模块

app 类型：com.android.application
base 类型：com.android.feature
feature 类型：com.android.feature
instantapp 类型：com.android.instantapp

## 2个入口
app
instantapp


## 文字来源 
https://mp.weixin.qq.com/s/z537MF9d-i5sVaRDeMPIOA
