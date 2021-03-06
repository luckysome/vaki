## [0.6.2](https://github.com/limengke123/van/compare/v0.6.1...v0.6.2) (2019-05-13)


### Features

* **stock:** 股票显示列表加上code ([46bd326](https://github.com/limengke123/van/commit/46bd326))



## [0.6.1](https://github.com/limengke123/van/compare/v0.6.0...v0.6.1) (2019-05-13)


### Features

* **movie:** 优化搜索列表为电视剧时显示方式 ([1a10866](https://github.com/limengke123/van/commit/1a10866))
* **movie:** 更新电影天堂搜索链接地址，支持电影、电视剧等搜索 ([2776ee3](https://github.com/limengke123/van/commit/2776ee3))



# [0.6.0](https://github.com/limengke123/van/compare/v0.5.7...v0.6.0) (2019-05-10)


### Bug Fixes

* **util:** 修复error函数传入为空报错，error背景色修改为红色 ([ef12e26](https://github.com/limengke123/van/commit/ef12e26))
* **util:** 修复error函数传入多行文本报错 ([cc71fa0](https://github.com/limengke123/van/commit/cc71fa0))


### Features

* **movie:** 支持查询电影列表，并获取电影下载链接 ([86b65be](https://github.com/limengke123/van/commit/86b65be))
* **movie:** 新增电影天堂搜索的时候长度的限制，超过3个字节才能搜索 ([980a068](https://github.com/limengke123/van/commit/980a068))
* **stock:** 增加搜索股票时候的spinner ([ed802e2](https://github.com/limengke123/van/commit/ed802e2))
* **tool:** 支持电影天堂的搜索电影的功能 ([74f5987](https://github.com/limengke123/van/commit/74f5987))
* **tool/movie:** 更新araneida版本 ([b09dc4d](https://github.com/limengke123/van/commit/b09dc4d))



## [0.5.7](https://github.com/limengke123/van/compare/v0.5.6...v0.5.7) (2019-05-08)


### Bug Fixes

* **main:** 首页todo长度问题导致首次进入报错 ([df7ff49](https://github.com/limengke123/van/commit/df7ff49))



## [0.5.6](https://github.com/limengke123/van/compare/v0.5.5...v0.5.6) (2019-05-08)



## [0.5.5](https://github.com/limengke123/van/compare/v0.5.4...v0.5.5) (2019-05-08)


### Bug Fixes

* 修复inquirer包的引入问题，导致真正发版找不到该包 ([e276585](https://github.com/limengke123/van/commit/e276585))



## [0.5.4](https://github.com/limengke123/van/compare/v0.5.3...v0.5.4) (2019-05-08)


### Features

* **main:** 加入版本校验功能，提醒升级 ([8bec173](https://github.com/limengke123/van/commit/8bec173))
* **stock:** 修改自选股票样式展示 ([e33242e](https://github.com/limengke123/van/commit/e33242e))



## [0.5.3](https://github.com/limengke123/van/compare/v0.5.2...v0.5.3) (2019-05-08)


### Features

* **stock:** 增加股票添加自选功能 ([167ab4a](https://github.com/limengke123/van/commit/167ab4a))
* **stock:** 增加自选股票的查询功能 ([5840ae1](https://github.com/limengke123/van/commit/5840ae1))
* **todo:** 优化增加待办项的交互逻辑 ([7bafeec](https://github.com/limengke123/van/commit/7bafeec))



## [0.5.2](https://github.com/limengke123/van/compare/v0.5.1...v0.5.2) (2019-05-07)


### Features

* **read:** 过滤掉微博内容中的广告 ([e3a0de3](https://github.com/limengke123/van/commit/e3a0de3))



## [0.5.1](https://github.com/limengke123/van/compare/v0.5.0...v0.5.1) (2019-05-07)


### Features

* **read:** 修改微博、segementFault显示的样式 ([ae7dc9b](https://github.com/limengke123/van/commit/ae7dc9b))



# [0.5.0](https://github.com/limengke123/van/compare/v0.4.3...v0.5.0) (2019-05-06)


### Features

* **read:** 增加微博、segementFault跳转功能 ([d6e70e9](https://github.com/limengke123/van/commit/d6e70e9))



## [0.4.3](https://github.com/limengke123/van/compare/v0.4.2...v0.4.3) (2019-04-30)


### Features

* 修改加载中的样式显示 ([eaaea9f](https://github.com/limengke123/van/commit/eaaea9f))
* **main:** 加上一些基本信息 ([63b745a](https://github.com/limengke123/van/commit/63b745a))
* **read:** read上加入可选长度选项，同时默认配置的长度改为20 ([7320bd3](https://github.com/limengke123/van/commit/7320bd3))
* **read:** 增加all选项，一次行返回所有数据 ([371acf9](https://github.com/limengke123/van/commit/371acf9))
* **reading:** reading模块加上了weibo新功能 ([b5c5f7c](https://github.com/limengke123/van/commit/b5c5f7c))



## [0.4.2](https://github.com/limengke123/van/compare/v0.4.1...v0.4.2) (2019-04-29)


### Bug Fixes

* **main:** 修复target的显示长度的错误 ([88a112a](https://github.com/limengke123/van/commit/88a112a))
* **main:** 修复幸运数字不会随着日期变化 ([403d192](https://github.com/limengke123/van/commit/403d192))
* **main:** 修复长度超过设置默认值时未能显示... ([a148401](https://github.com/limengke123/van/commit/a148401))
* **tool:** 修复配置文件路径名错误 ([dde7a07](https://github.com/limengke123/van/commit/dde7a07))


### Features

* **main:** version颜色显示改为绿色 ([bfd8333](https://github.com/limengke123/van/commit/bfd8333))
* **main:** version颜色显示改为绿色加下划线 ([db5be55](https://github.com/limengke123/van/commit/db5be55))
* **read:** 加入配置文件，默认只显示10条数据 ([eaacb09](https://github.com/limengke123/van/commit/eaacb09))
* **reading:** 新增reading模块 ([05fef48](https://github.com/limengke123/van/commit/05fef48))
* **reading:** 新增segementFault搜索功能 ([457baad](https://github.com/limengke123/van/commit/457baad))



## [0.4.1](https://github.com/limengke123/van/compare/v0.4.0...v0.4.1) (2019-04-28)


### Features

* **main:** 无参数情况下 显示target数据 ([c02d664](https://github.com/limengke123/van/commit/c02d664))



# [0.4.0](https://github.com/limengke123/van/compare/v0.3.0...v0.4.0) (2019-04-28)


### Bug Fixes

* **package:** 移除main字段，该字段在这项目无用 ([b8de57f](https://github.com/limengke123/van/commit/b8de57f))
* **todo:** 修复每次触发命令都会清除终端的bug ([75c9839](https://github.com/limengke123/van/commit/75c9839))


### Features

* **main:** main command加入幸运数字 ([d2a8937](https://github.com/limengke123/van/commit/d2a8937))
* **main:** 主命令加上了配置文件 ([d72948d](https://github.com/limengke123/van/commit/d72948d))
* **todo:** 增加--filter选项，能够筛选是否完成 ([35d727e](https://github.com/limengke123/van/commit/35d727e))
* **tool:** tool模块的打开功能支持搜索选项，目前支持百度、知乎、github ([7fd027d](https://github.com/limengke123/van/commit/7fd027d))



# [0.3.0](https://github.com/limengke123/van/compare/v0.2.1-0...v0.3.0) (2019-04-27)


### Features

* **tool:** 增加tool模块，tool模块有opener功能 ([abd4b4f](https://github.com/limengke123/van/commit/abd4b4f))



## [0.2.1-0](https://github.com/limengke123/van/compare/v0.2.0...v0.2.1-0) (2019-04-26)


### Bug Fixes

* **package:** 恢复package.json的file字段 ([335eb60](https://github.com/limengke123/van/commit/335eb60))



# [0.2.0](https://github.com/limengke123/van/compare/v0.1.0...v0.2.0) (2019-04-26)


### Bug Fixes

* **package:** 移除无用字段 main ([e8d0830](https://github.com/limengke123/van/commit/e8d0830))


### Features

* 增加了没有传参数时候的默认处理方式 ([12b6289](https://github.com/limengke123/van/commit/12b6289))



# [0.1.0](https://github.com/limengke123/van/compare/f21651f...v0.1.0) (2019-04-26)


### Bug Fixes

* **package:** 只提交src下的代码给npm ([e2e8a9e](https://github.com/limengke123/van/commit/e2e8a9e))


### Features

* todo-list 的基本功能走通了 ([65f4444](https://github.com/limengke123/van/commit/65f4444))
* 划分sub-command，目前加入todo、stock两个子模块 ([6960b99](https://github.com/limengke123/van/commit/6960b99))
* 初始化项目，打印出首页 ([e49bd4d](https://github.com/limengke123/van/commit/e49bd4d))
* 新增readme.md ([0462c8f](https://github.com/limengke123/van/commit/0462c8f))
* 移除.idea、.vscode 编辑器配置依赖 ([f21651f](https://github.com/limengke123/van/commit/f21651f))
* **package:** 报名冲突了 真可恶，我换一个名字 ([3e733d4](https://github.com/limengke123/van/commit/3e733d4))



