# Android快速开发脚手架
整理了android开发中经常使用到的一些库

- 网络:
  - okhttp
  - retrofit
  - rxjava
  - com.squareup.okhttp3:logging-interceptor
  - rxjava适配器
  - json转换器
  - rxandroid
  - fastjson
- 代码简化:
	- lombok
	- butterknife
- 时间选择器:
	- pickerView
- 图片选择:
	- takephoto_library
- sql数据库ROM框架:
	- sugar || greendao
- fragment管理:
	- Fragmentation
- 下拉刷新:
	- SmartRefreshLayout
- 头部固定:
	- StickHeadScrollView
- web混合开发:
	- JsBridge
- 沉浸式状态栏:
	- ImmersionBar
- 消息传递
	- EventBus
- 路由跳转
	- ARouter
- 其他
	- fragmentargs 轻松的为fragment添加参数信息，并提供创建方法。
	- ParcelableGenerator 可实现自动将任意对象转换为Parcelable类型，方便对象传输。
	- auto-service google的一个帮助编写编译时注解的库
- K/V 数据库
	- MMKV MMKV is an efficient, small, easy-to-use mobile key-value storage framework used in the WeChat application
# 目录结构
- api
- constant
- utils
- modules
- entity
- application
- http
	- test
		- api
		- ui
			- fragment
			- activity
		- viewmodel
		- entity
> 后面有时间会整理出一个demo工程，使用mvvm开发模式

# 基本的多模块项目
- lib-annotation
- lib-compiler
- lib-api
- app-sample

# 多模块项目
- lib-router-module
- lib-core-module
- lib-base-module
- app-home-module
- app-login-module
- app-gesture-module
- app-function-module
# 插件式开发
> 一些复杂的项目可能会用到插件式开发，通过插件化可以做到热修复和热拔插，还可以减少app的体积
> 比如一些集团用的APP，可能有很多个系统比如10个APP，并且是多租户的，一般为了方便使用，会采用插件式开发APP，进入APP后选择对应的系统下载对应的插件包来加载。
> 例子: 淘宝app
- Atlas 插件式APP开发框架
# 小程序开发模式
> 可以使用类似支付宝小程序或者微信小程序，提供底层api供html页面调用，一个小程序就是一个html程序。
