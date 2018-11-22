== Description ==
1. 上传 `nines-taoke`目录 到 `/wp-content/plugins/` 目录或后台搜索Nines Taoke
2. 在后台插件菜单激活该插件
3. 后台`淘宝客配置`填写你的 `App Key` ,`App Secret` ,`Pid` 三个配置项以及新建一个新页面用来展示淘客商品
4. 其中pid参数必须是淘宝联盟->网站推广位  的pid(没有这个推广位的pid请申请),其它位置的pid将获取不到商品数据、

演示地址:https://www.aliluv.cn/shop
帮助地址:https://www.aliluv.cn/18.html

本插件所有的商品数据都是通过自已在'淘宝开放平台'所申请的应用(AppKey,AppSecret)和Pid调用淘宝客api接口(`https://eco.taobao.com/router/rest`);
其接口链接代码在functions/taobao.php第18行文件.

平台简介
一、什么是淘宝开放平台
淘宝开放平台（Taobao Open Platform）是基于淘宝各类电子商务业务的开放平台，提供外部合作伙伴参与服务淘宝用户的各类原材料，例如API、账号体系、数据安全等。她是大淘宝电子商务基础服务的重要开放途径，将推动各行各业定制、创新、进化，并最终促成新商业文明生态圈的建立。我们的使命是把淘宝网的商品、用户、交易、物流等一系列电子商务基础服务，像水、电、煤一样输送给有需要的商家、开发者、社区媒体和各行各业。


淘宝合作伙伴开发协议:http://terms.alicdn.com/legal-agreement/terms/suit_bu1_other/suit_bu1_other201704191118_23239.html

开放平台运营规则/使用规范:https://open.taobao.com/doc.htm?docId=108442&docType=1