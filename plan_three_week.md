## 第三周学习计划
***

#### 时间段
2月20日 -- 2月26日  

#### 参与人
leopeng、victorwwang  

#### 任务情况
|任务编号|任务项|任务目标|完成进度|完成耗时|
|:--:|:--:|:--:|:--:|:--:|
|1|Android开发实战（三）|1.增加二级页面，点击列表项跳转到图书详情页；2.增加离线能力，无网络时图书数据也能正确展示在列表、二级页（需要数据持久化）；3.图片数据实现两级缓存，在内存缓存基础上增加Disk缓存，支持无网络时也能展示图片；|100% |2d|
|2|手Q看点业务代码熟悉(组件化分支)|TODO：|100%|1.5d|
|3|看点Bug修复|TODO：|70%|1.5d|

#### 学习资源
1. KM
2. 图书
3. Android官方文档

#### 学习心得

1. Android开发实战（三）
> - 增加二级页面，点击列表项跳转到图书详情页
> - 增加离线能力，无网络时图书数据也能正确展示在列表、二级页
> - 图片数据实现两级缓存，在内存缓存基础上增加Disk缓存
> - 已基本完成上述需求，还有一些细节需要调整，如无网络连接的提示问题、网络重试次数。
> - 优化UI性能及增强离线能力，查询用户时候，JSON数据和图片如果存在Disk缓存内容，先调用缓存跳转至列表页，再进行异步网络请求更新数据和UI。
> - 增加RatingBar，显示图书的评分。

2. 手Q看点业务代码熟悉(组件化分支)
> - 需求开发。

3. 看点Bug修复
> - 查看消息Tabs中的内存泄漏问题。
