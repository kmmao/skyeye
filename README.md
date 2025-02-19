# skyeye

#### 项目介绍

智能办公OA系统[SpringBoot2-快速开发平台]，适用于医院，学校，中小型企业等机构的管理。包含文件在线操作、工作日志、多班次考勤、CRM、ERP进销存、项目管理、EHR、拖拽式生成问卷、日程、笔记、工作计划、行政办公、薪资模块、动态表单、知识库、公告模块、企业论坛、云售后模块、生产模块、系统模块化同步模块等多种复杂业务功能。

- 开源不易，给个`star`吧
- erp+生产演示视频：https://mp.weixin.qq.com/s/CrFM_VZShi-FIJ8zD0_Nqg
- 需要进微信群(加我拉你进群，wzq_598748873)，请提供自己的邮箱，默认订阅每周更新内容推送。
- 不需要进群的，请直接加微信：ZhiJinShuLi
- `本项目分为开源版和企业版，不喜勿喷，谢谢。`
- 企业版信息：https://docs.qq.com/doc/DQlRxcVRMWWVjbU1i?_from=1&disableReturnList=1
- 不会搭建环境的，可以出钱让作者帮忙搭建，一次100，先付。
- [项目文档](https://gitee.com/doc_wei01/skyeye/blob/master/%E9%A1%B9%E7%9B%AE%E6%96%87%E6%A1%A3.md)
- 采用Redis缓存做单点登录功能，全新风格的后台管理系统
- [MIT协议的高性能报表软件](https://gitee.com/doc_wei01/skyeye-report)

#### 功能介绍

功能|简介|功能|简介
-------|-------|-------|-------
菜单管理|配置系统菜单，操作权限，按钮权限标识等，用户可自定义桌面展示LOGO|员工管理|操作企业内部的员工信息，进行统一管理
用户管理|用户是系统操作者，该功能主要完成系统用户配置。|角色管理|角色菜单权限分配、设置角色按机构进行数据范围权限划分。
权限管理|给角色进行赋权|资源图标|系统中允许使用的font图标库
日志管理|系统正常操作日志记录和查询；系统异常信息日志记录和查询。|登录日志|系统登录日志记录查询包含登录异常。
多桌面管理|多个桌面程序，用户可通过鼠标滚动进行切换|系统基础设置|系统的基础信息设置
代码生成器|只能适用于该框架的代码生成器，配置模板即可生成，然后下载压缩包解压复制到项目中即可|自定义桌面菜单|用户可将自己常用的网站添加到系统中方便记录
在线性能监控|监视当前系统CPU、内存、磁盘、堆栈等相关信息。|多桌面|[演示](https://www.bilibili.com/video/av43650484)
聊天功能|[演示](https://www.bilibili.com/video/av43650782)，支持单聊，群聊，进群申请，组建群组，在线用户监控等。|[我的日程](https://gitee.com/doc_wei01/skyeye/blob/master/%E5%8A%9F%E8%83%BD%E6%96%87%E6%A1%A3%E4%BB%8B%E7%BB%8D/%E6%97%A5%E7%A8%8B%E6%A8%A1%E5%9D%97.md)(企业版)|[演示](https://www.bilibili.com/video/av45854959)|APP菜单管理(企业版)|手机端菜单以及权限管理
小程序管理(企业版)|微信小程序、H5手机自适应页面拖拽生成，可自定义配置小程序组件|多系统集成(企业版)|可以将多个系统进行应用集成，无需多次登陆，无需记录多个网址
流程图规划(企业版)|规划项目的流程图|问卷调查(企业版)|拖拽式生成问卷，可分页、复制、查看统计信息等
轻应用(企业版)|系统中提供各种小应用，如快递查询、高德地图等，用户可添加到自己的桌面上|开发文档(企业版)|系统支持二次开发，包含开发文档
工作日志(企业版)|记录每个员工的日报，周报，月报等，可同时发送多人，按时间轴查看等|多班次考勤管理(企业版)|记录每个员工的考勤打卡信息，包含报表，打卡，班次设置等
[我的笔记](https://gitee.com/doc_wei01/skyeye/blob/master/%E5%8A%9F%E8%83%BD%E6%96%87%E6%A1%A3%E4%BB%8B%E7%BB%8D/%E7%AC%94%E8%AE%B0%E6%A8%A1%E5%9D%97.md)(企业版)|员工可记录自己日常的笔记，目前支持MD，富文本，表格操作|报表管理(企业版)|统计功能信息，可根据客户自定义免费定制
[文件管理](https://gitee.com/doc_wei01/skyeye/blob/master/%E5%8A%9F%E8%83%BD%E6%96%87%E6%A1%A3%E4%BB%8B%E7%BB%8D/%E6%96%87%E4%BB%B6%E7%AE%A1%E7%90%86.md)(企业版)|公司内部、员工个人的文件管理，支持多格式文件在线查看，文档多人协作，在线解压缩等|附件管理(企业版)|保留员工所有上传过的附件，方便下次使用
邮件管理(企业版)|目前打通与QQ邮箱的交互，可以发邮件，收邮件，保存为草稿等|[工作流管理](https://gitee.com/doc_wei01/skyeye/blob/master/%E5%8A%9F%E8%83%BD%E6%96%87%E6%A1%A3%E4%BB%8B%E7%BB%8D/%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%BB%8B%E7%BB%8D%E6%96%87%E6%A1%A3.md)(企业版)|动态表单结合工作流生成自定义业务流程审核,可进行审批、撤回、回退、节点化表单项编辑设置、驳回、终止转办等功能，目前已支持四十多种流程管理
论坛(企业版)|包括标签管理，关键词管理，举报审核等操作，用户可自由发表文章，系统通过过滤算法进行关键词过滤|计划管理(企业版)|方便公司进行公司计划、部门计划、个人计划的规划，可根据类型（日计划、周计划、月计划、季度计划等）进行定义
动态表单(企业版)|通过自定义的方式生成提交表单页，可与动态数据进行结合，目前已和工作流结合|行政管理(企业版)|包含车辆管理、会议室管理、用品管理、印章管理、财产管理、证照管理。所有功能审核已和工作流结合
内部公告(企业版)|系统内部公告通知，可设置邮件通知，定时通知，人员选择等|通讯录(企业版)|记录个人、公司内部、公共通讯录信息
知识库(企业版)|企业文化支柱；[效果地址](https://gitee.com/doc_wei01/knowlg-pro)|[CRM客户管理](https://gitee.com/doc_wei01/skyeye/blob/master/%E5%8A%9F%E8%83%BD%E6%96%87%E6%A1%A3%E4%BB%8B%E7%BB%8D/CRM%E5%AE%A2%E6%88%B7%E7%AE%A1%E7%90%86%E6%A8%A1%E5%9D%97.md)(企业版)|包含客户、商机、跟单、合同等多个模块化功能
[ERP进销存管理](https://gitee.com/doc_wei01/erp-pro)(企业版)|包含采购、销售、零售、客户、供应商等多个模块化功能；[效果地址](https://gitee.com/doc_wei01/erp-pro)|[项目管理](https://gitee.com/doc_wei01/skyeye/blob/master/%E5%8A%9F%E8%83%BD%E6%96%87%E6%A1%A3%E4%BB%8B%E7%BB%8D/%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86.md)(企业版)|包含项目、工作量、讨论帖、项目文档、成本费用等功能
[云售后管理系统](https://gitee.com/doc_wei01/skyeye/blob/master/%E5%8A%9F%E8%83%BD%E6%96%87%E6%A1%A3%E4%BB%8B%E7%BB%8D/%E5%94%AE%E5%90%8E%E5%B7%A5%E5%8D%95%E6%A8%A1%E5%9D%97.md)(企业版)|包含工单的派工，接单，签到，配件申领审批，完工，评价，审核等操作|生产模块(企业版)|已完成，[演示视频](https://www.bilibili.com/video/BV1yA411e7mm/)
|学校模块以及考试模块(企业版)|[地址](https://gitee.com/doc_wei01/schoolExam)|EHR模块(企业版)|管理企业员工的基础信息|
|薪资模块(企业版)|员工薪资管理，支持多种类型设定|||

#### 技术选型

##### 后端技术:

技术|名称|官网
---|---|---
SpringBoot|核心框架|http://spring.io/projects/spring-boot
MyBatis|ORM框架|http://www.mybatis.org/mybatis-3/zh/index.html
Druid|数据库连接池|https://github.com/alibaba/druid
Maven|项目构建管理|http://maven.apache.org/
redis|key-value存储系统|https://redis.io/
webSocket|浏览器与服务器全双工(full-duplex)通信|http://www.runoob.com/html/html5-websocket.html
Activiti|工作流引擎|https://www.activiti.org/
spring mvc|视图框架|http://spring.io/
quartz 2.2.2|定时任务|http://www.quartz-scheduler.org/
ActiveMQ|消息队列|http://activemq.apache.org/replicated-leveldb-store.html
solr|企业级搜索应用服务器|https://lucene.apache.org/solr/
Spring Cloud|微服务框架(目前用户APP端接口)|https://springcloud.cc/

##### 前端技术：

技术|名称|官网
---|---|---
jQuery|函式库|http://jquery.com/
zTree|树插件|http://www.treejs.cn/v3/
layui|模块化前端UI|https://www.layui.com/
winui|win10风格UI|https://gitee.com/doc_wei01_admin/skyeye
codemirror|codemirror代码编辑器|https://codemirror.net/
handlebars|js模板引擎|http://www.ghostchina.com/introducing-the-handlebars-js-templating-engine/
webSocket|浏览器与服务器全双工(full-duplex)通信|http://www.runoob.com/html/html5-websocket.html
G6|流程图开发|https://antv.alipay.com/zh-cn/index.html
FullCalendar|日历插件|https://blog.csdn.net/qw_xingzhe/article/details/44920943

#### 代码描述
##### 前后台接口映射

```
<url id="前端请求id" path="后台接口" val="备注" allUse="是否需要登录">
	<property id="前端请求key" name="后台接收key" ref="限制条件（参考项目内文档）" var="key含义"/>
</url>
```

##### 后台代码编写规范

###### 控制层

```
@RequestMapping("后台接口")
@ResponseBody
public void 方法名(InputObject inputObject, OutputObject outputObject) throws Exception{
	服务层接口对象.方法名(inputObject, outputObject);
}
```

###### 服务层

```
@Override
public void 方法名(InputObject inputObject, OutputObject outputObject) throws Exception {
	Map<String, Object> map = inputObject.getParams();//接收参数
	Map<String, Object> user = inputObject.getLogParams();//获取当前登录用户信息
	/**
	 * 业务逻辑
	 */
	outputObject.setBean(bean);//返回单个实体Bean
	outputObject.setBeans(beans);//返回集合
	outputObject.settotal(total);//返回数量
	outputObject.setreturnMessage("信息");//返回前端的错误信息
	outputObject.setreturnMessage("信息", 错误码);//返回前端的错误信息，同时抛出异常（不常用）
}
```



#### 效果图

|效果图|效果图|
| ------------- | ------------- |
|![](https://s2.ax1x.com/2019/04/16/Avo0c8.png "1.png")|![](https://images.gitee.com/uploads/images/2019/0623/142954_6c8612f2_1541735.png "1.png")|
|![](https://images.gitee.com/uploads/images/2018/1107/104734_d9304e60_1541735.png "2.png")|![](https://images.gitee.com/uploads/images/2018/1107/104903_f244dfde_1541735.png "3.png")|
|![](https://s2.ax1x.com/2019/06/23/ZPS5h4.png)|![](https://images.gitee.com/uploads/images/2018/1118/191634_497ea929_1541735.png "微信图片_20181118191516.png")|
|![](https://images.gitee.com/uploads/images/2018/1118/193301_72d0bb49_1541735.png "微信截图_20181118193254.png")|![](https://s2.ax1x.com/2019/04/16/Av7lee.png "微信截图_20181120154643.png")|
|![](https://images.gitee.com/uploads/images/2018/1121/105120_65de9434_1541735.png "1.png")|![](https://images.gitee.com/uploads/images/2019/0623/145248_4a51c610_1541735.png)|
|![](https://images.gitee.com/uploads/images/2019/0122/113516_b0600e8f_1541735.png "1.png")|![](https://images.gitee.com/uploads/images/2018/1207/123501_3248346e_1541735.png "微信截图_20181207123447.png")|
|![](https://images.gitee.com/uploads/images/2019/0113/114947_1c7fa387_1541735.png "微信截图_20190113114922.png")|![](https://images.gitee.com/uploads/images/2019/0202/130711_7ed57951_1541735.png "3.png")|
|![](https://s2.ax1x.com/2019/06/23/ZPC6cd.png)|![](https://images.gitee.com/uploads/images/2019/0623/145351_dd55da65_1541735.png)|
|![](https://images.gitee.com/uploads/images/2019/0623/143810_e76aec71_1541735.png)|![](https://images.gitee.com/uploads/images/2019/0623/144143_1063782a_1541735.png)|
|![](https://images.gitee.com/uploads/images/2019/0904/143828_b7ef9748_1541735.png)|![](https://images.gitee.com/uploads/images/2019/0904/143937_42519798_1541735.png)|

#### 传统风格界面效果图

|效果图|效果图|
| ------------- | ------------- |
|![](https://images.gitee.com/uploads/images/2019/0904/143634_0c9da9ad_1541735.png)|![](https://images.gitee.com/uploads/images/2019/0904/143639_2e442328_1541735.png)|
|![输入图片说明](https://images.gitee.com/uploads/images/2019/1101/170700_738ed970_1541735.png "在这里输入图片标题")||


#### 合作方式

- 购买企业版源码
- 购买企业版Jar包
- 客户可提供文字版合作方式

### 捐助
如果您觉得我们的开源软件对你有所帮助，请扫下方二维码打赏我们一杯咖啡。
| 支付宝 | 微信 | 更新资讯公众号 |
| ------ | ---- | ---- |
| ![      ](https://images.gitee.com/uploads/images/2019/1016/094014_96f92c56_1541735.png "微信截图_20191016093832.png") | ![     ](https://images.gitee.com/uploads/images/2019/1016/094025_65ba24f0_1541735.png "微信截图_20191016093850.png")|![输入图片说明](https://images.gitee.com/uploads/images/2021/0320/091531_8c3ba4d8_1541735.jpeg "qrcode_for_gh_e7f97ff1beda_430.jpg")|
