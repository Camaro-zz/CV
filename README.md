# 联系方式
- 手机/微信：15168668353
- Email：camaro920620@gmail.com
- QQ：243535967

---

# 个人信息

 - 吴鑫/男/1992 
 - 2013年毕业/本科/台州学院/材料物理专业/自学C.PHP.JavaScript
 - 工作年限：4年
 - Github: http://github.com/Camaro_ZZ 
 - 期望职位：PHP程序员
 - 期望薪资：月薪13k~15k，特别喜欢的公司可例外
 - 期望城市：杭州
 
---
# IT专业技能
 - 熟练掌握PHP+MySQL的安装、配置、调试
 - 熟练掌握PHP面向对象编程
 - 熟练掌握Laravel、ThinkPHP等后端框架
 - 熟悉PHP缓存技术，熟悉redis的安装配置调试，
 - 熟练掌握微信公众号开发
 - 熟练掌握Jquery、vue、backbone 等前端框架
 - 了解gulp等前端打包工具
 - 熟悉git操做，熟悉svn操作
 - 熟练使用linux操作命令
 
---
# 工作经历
## 杭州微巴信息技术有限公司/PHP  (2016年3月 ~ 至今)
### 1.小京东 （2016年11月 ~ 2016年12月）
 项目描述：商家可以在后台总店开多个子店帐号，总店没有发布商品的权限，但是可以编辑修改审核商品，总店可以设置子店是自动审核还是手动审核，子店添加的商品可由总店决定是否上下假。手机端购买入口唯一，下单后自动拆分成不同子店不同配送方式的多个订单，商品由子店发货。
 
 负责内容：商家配送功能开发、总店子店的商品相关，在做总店审核商品，商品自动上锁（防止总店审核是子店也在修改商品的并发情况）时采用计划任务，总店在进入审核状态后，前端间隔一段时间发送一次请求后端进行响应，判断是否还处于审核状态，如果后端无响应超过10分钟，则自动解锁，或者总店点击审核按钮之后可以直接解锁。完成商品模块后，完成质量和速度都较好，去帮助同事解决订单列表的问题，订单列表通过连接elasticsearch服务器查询，包括总店修改订单价格退货操作等。
 
### 2.门票商品 （2016年8月 ~ 2016年9月）
 项目描述：后台添加门票类商品，客户可以根据时间和人数购买景区门票
 
 负责内容：手机端门票商品购买，兼容原先已有营销活动，手机端和后台门票核销，由于门票核销调用第三方接口，所以沟通成本增加

### 3.服务账户 （2016年7月 ~ 2016年8月）
 项目描述：商家可以在后台充值服务账户，短信发送和物流查询时进行扣费，否则无法发送短信和物流查询，降低公司的成本支出
 
 负责内容：负责短信发送和查询物流时的扣费操作和后台客户充值接口开发操作，由于是在原有系统中插入扣费插件，所以我把扣费操作写成事件，方便调用，在开发期间遇到多个容错问题，知道容错的重要性，学习使用不同的容错方式
 
### 4.疯狂竞猜（2016年5月 ~ 2016年6月）
 项目描述：这是一个通过猜价来达到吸粉和销售的营销工具，通过不一样的竞猜玩法以成功竞猜的价格购买，商家设置不同的猜价位数，可玩性高
 
 负责内容：手机端猜价功能，猜中购买功能
