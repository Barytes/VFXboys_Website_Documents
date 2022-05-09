# 待办事项及指南

## 1. 外观和内容

### 1.1 首页背景图替换

登录管理员账号-->顶条菜单“自定义”

![image-20220509104442688](.\imgs\自定义.png)

首页区域-->大标题区域-->更换图片

![image-20220509104442688](.\imgs\首页区域.jpg)

![image-20220509104442688](.\imgs\大标题区域.jpg)

![image-20220509104442688](.\imgs\大标题更换图片.jpg)

### 1.2 首页Features简介替换

![image-20220509103014318](.\imgs\Features.png)

​	自定义-->首页区域-->Features区域-->编辑3个Features

​	![首页Futures](.\imgs\首页Futures.jpg)	![首页Futures](.\imgs\编辑Features.jpg)

### 1.3 文档补充：关于我们、加入我们、广告合作、用户协议、隐私政策（脚注）

![footnote](.\imgs\footnote.jpg)

仪表盘-->页面：所有页面-->编辑对应页面

![页面](.\imgs\页面.jpg)

## 1.4 更换精选视频

仪表盘-->页面：所有页面-->首页，编辑

![页面-首页](.\imgs\页面-首页.jpg)

![精选编辑](.\imgs\精选编辑.png)

## 2. 电商

### 2.1 导入产品

#### 2.1.1 逐个导入

仪表盘-->产品：新增

![新增产品](.\imgs\新增产品.jpg)

填写各项信息：产品名称、产品介绍、产品类别、产品标签、产品图片、产品相册、虚拟/可下载、价格、下载文件等

![新增产品](.\imgs\新增产品信息.jpg)

#### 2.1.2 批量导入

仪表盘-->产品：全部产品-->导入

![导入](.\imgs\导入.jpg)

按提示导入csv文件

![导入](.\imgs\导入csv.jpg)

**产品 CSV 编辑规则可见：[Product CSV Import Schema · woocommerce/woocommerce Wiki · GitHub](https://github.com/woocommerce/woocommerce/wiki/Product-CSV-Import-Schema#csv-columns-and-formatting)**

### 2.2 设置存储文件的服务器

不懂，请参阅相关教程

###  2.3 商品搜索功能

购买并安装插件[WooCommerce Product Search - WooCommerce](https://woocommerce.com/products/woocommerce-product-search/)

## 3. 安全和管理

### 3.1 服务器迁移（未验证）

#### 3.1.1 使用All-in-One-WP-Migration插件导入导出

（似乎需要购买插件Pro版本）

在新服务器安装Wordpress环境-->安装All-in-One-WP-Migration插件-->导入Wordpress备份文件

![WPM](.\imgs\WPM.jpg)

![WPM](.\imgs\WPM导入.jpg)

#### 3.1.2 云厂商的迁移服务

参考服务器所在云厂商的文档

### 3.2 启用HTTPS

参考服务器所在云厂商的文档（如何安装 SSL 证书）

![SSL](.\imgs\SSL.jpg)

### 3.3 域名注册和备案

参考服务器所在云厂商的文档（域名注册）

![域名注册](.\imgs\域名注册.jpg)

### 3.4 更换管理员账号和email

仪表盘-->设置-->常规

![设置常规](.\imgs\设置常规.png)

修改管理员电子邮箱-->保存设置-->在邮件中确认

![管理员email](.\imgs\管理员email.png)

![email保存](.\imgs\email保存.jpg)

### 3.5 收款账号设置

仪表盘-->WooCommerce插件-->设置-->付款

![WC设置](.\imgs\WC设置.jpg)

#### 3.5.1 支付宝设置

用收款账号访问[支付宝开放平台 (alipay.com)](https://open.alipay.com/)，按提示[创建应用 - 支付宝文档中心 (alipay.com)](https://opendocs.alipay.com/open/200/105310)，设置应用网关地址，获取支付宝AppID、应用私钥、支付宝公钥[配置密钥 - 支付宝文档中心 (alipay.com)](https://opendocs.alipay.com/open/02nlga)

![APPID](.\imgs\APPID.jpg)

在WooCommerce插件付款设置中，选择支付宝-->管理，填写AppID、应用私钥、支付宝公钥，保存设置

![支付宝管理](.\imgs\支付宝管理.jpg)

![WC-APPID](.\imgs\WC-APPID.jpg)

若需要支付测试，先在支付宝开放平台-->控制台-->[沙箱](https://open.alipay.com/dev/workspace)中获取沙箱应用，在WooCommerce插件设置中勾选支付宝沙盒模式，填写沙箱应用的AppID、应用私钥、公钥，保存设置

![支付宝控制台](.\imgs\支付宝控制台.jpg)

![WC-支付宝沙盒](.\imgs\WC-支付宝沙盒.jpg)

#### 3.5.2 微信支付设置（未验证）

仪表盘-->WooCommerce插件-->设置-->付款-->微信支付设置-->启用此付款网关

![WC-微信支付](.\imgs\WC-微信支付.jpg)

在微信公众号/微信小程序/微信商户号中（三选一）获取AppID、密钥，并填写在对应设置中，保存设置

![WC-微信AppID](.\imgs\WC-微信AppID.jpg)

### 3.6 验证码账号设置（联系我们表格）

![联系cap](.\imgs\联系cap.jpg)

仪表盘-->WPForm插件-->设置-->验证码

![WPF验证码](.\imgs\WPF验证码.jpg)

按提示选择hCaptcha或reCaptcha，创建账号、填写站点密钥和私钥、保存设置

![2Cap](.\imgs\2Cap.jpg)

### 3.7 为登录、注册添加验证码

#### 3.7.1 使用付费插件（简单）

购买Google reCaptcha for WooCommerce插件[WooCommerce reCaptcha Plugin: Google V2 & V3 Captcha](https://woocommerce.com/products/google-recaptcha-for-woocommerce/?quid=2c204ae2abe6b08ec2bf3ec79e51d07b)

按提示安装和设置

![reCaptchaWC](C:\Users\Barytes\Desktop\文档\imgs\reCaptchaWC.jpg)

#### 3.7.2 付费升级WPForm Pro并制作登录、注册页面（复杂）

参考：[How to Make a WordPress Custom Login Page (The EASY Way) (wpforms.com)](https://wpforms.com/how-to-create-a-custom-login-form-for-improved-site-branding/)

## 4. 优化（未验证）

### 4.1 搜索引擎优化（SEO）

使用Yoast SEO插件（或其他SEO插件），请参阅相关教程

![Yoast](.\imgs\Yoast.jpg)

### 4.2 网页速度优化

不懂，请参阅相关教程

## 5. 其他

### 5.1 社交平台登录/注册

仪表盘——>插件——>启用WP Open Social插件

![WPOS启用](.\imgs\WPOS启用.jpg)

转到WP Open Socail插件设置——>登录账号，启用需要的社交平台，访问？链接获取AppID和密钥，填写并保存

![WPOS登录](.\imgs\WPOS登录.jpg)

![qq互联](.\imgs\qq互联.jpg)

### 5.2 分享到社交平台

WP Open Socail插件设置——>分享服务，勾选需要的社交平台并保存设置

![WPOS分享](.\imgs\WPOS分享.jpg)

### 5.3 反垃圾评论

仪表盘-->插件-->启用Akismet 反垃圾评论插件，注册Akismet账号并设置

![Aki插件](.\imgs\Aki插件.jpg)

![Aki设置](.\imgs\Aki设置.jpg)

### 5.4 SMTP服务设置

**已知默认的邮件服务无法向gmail邮箱发送邮件。其他邮箱是否得到支持还需要测试。**

安装/购买提供SMTP服务的插件（WP Mail SMTP by WPForms、Post SMTP等），按提示进行设置【大概率需要付费】

### 5.5 测试

对网站功能进行测试

### 5.6 文档

完善或重新编写网站的开发/维护文档。当前文档只是一个较为简陋的指南。