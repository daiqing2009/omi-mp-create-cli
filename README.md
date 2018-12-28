# Fork 来自 omi-mp-create（原westore的进化版本）
> 极小却精巧的小程序框架，对小程序入侵性几乎为零，强制中心化或者强制去中心化都是耍流氓
> 创建store目录，提供类似vuex集中数据管理的开发体验，多人协作开发划分模块代码互不影响
> 数据变更之后不需要再setData，会在View层自动实现最短路径进行渲染，性能上一个档次。
> 添加了regeneratorRuntime，可在原生中直接用async await，wxp封装小程序所有Api
> 使用promise封装了原生get，post请求，支持async await then语法糖，配合store，开发体验更愉悦
#
项目中包含强制中心化和强制去中心化开发方案
pages/index/index 路径为强制中心化（推荐，配合stroe目录提供类vuex的集中数据管理）
pages/other/other 路径为强制去中心化（具体可以查看官方文档）
#
omi-mp-create 官方文档：https://github.com/Tencent/omi/edit/master/packages/omi-mp-create
westore 官方文档：https://github.com/Tencent/westore
