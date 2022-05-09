# 使用文档

## 1. 管理员身份设置

### 1.1 设置管理员昵称密码

【管理员账号只能为admin，无法更改】

仪表盘——>用户：个人资料——>昵称、公开显示为

![admin_un](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/admin_un.jpg)

仪表盘——>用户：个人资料——>账户管理：新密码

![admin_pw](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/admin_pw.jpg)

### 1.2 管理员邮箱设置

**两项都需要设置！**

【管理员登录相关】仪表盘——>用户：个人资料——>电子邮箱地址——>确认邮件

![admin_email](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/Inkedadmin_email_LI.jpg)

【网站email通知相关】仪表盘——>设置——>常规——>管理员电子邮箱——>确认邮件

![常规-管理员email](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/常规-管理员email.jpg)

## 2. 网站行为

### 2.1 首页

#### 2.1.1 大标题区域

大标题区域显示标题、文本、跳转按钮和大标题背景。跳转按钮设置跳转到特效小哥的b站空间。本部分内容可以在仪表盘——>自定义——>首页区域——>大标题区域设置。

![大标题](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/大标题.jpg)

#### 2.2.2 Features区域

特效视频跳转至特效小哥b站空间：特效小哥精选频道。魔法教程跳转至特效小哥b站空间：魔法课频道。创意广告跳转至本站“广告合作”页面。本部分内容可以在仪表盘——>自定义——>首页区域——>Features区域设置。

![Features](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/Features.jpg)

#### 2.2.3 精选视频

本部分展示了一些特效小哥的精选视频。点击图片将跳转至b站对应视频。精选视频可以在仪表盘——>所有页面——>首页处设置。背景图片可以在仪表盘——>自定义——>首页区域——>关于区域设置。

![精选视频](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/精选视频.jpg)

#### 2.2.4 精选产品区域

本部分展示一些商店的精选产品。本部分可以在仪表盘——>自定义——>首页区域——>店铺设置。

![精选产品](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/精选产品.jpg)

#### 2.2.5 联系我们区域

本部分显示联系特效小哥的方式，以及一个向管理员邮箱发送email的表格。用户填写相关信息和验证码并提交后，管理员邮箱将收到电子邮件通知。本部分可以在仪表盘——>自定义——>首页区域——>联系设置。联系我们表单可以在WPForms插件处设置。

![联系我们](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/联系我们.jpg)

![联系表格](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/联系表格.jpg)

![联系邮件](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/联系邮件.jpg)

### 2.2 素材商店、商品详情

#### 2.2.1 素材商店

素材商店页显示现有的商品。用户可以按不同排序查看商品，也可以将商品添加至购物车或立即购买。立即购买按钮将跳转至结账页面。商品管理可以在仪表盘——>产品处管理。

![素材商店](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/素材商店.jpg)

#### 2.2.2 商品详情

商品详情页显示商品相册、商品名称、商品价格、商品标签、商品分类、商品描述和用户评价。上述信息可以在仪表盘——>产品——>具体产品处编辑。用户可以将商品添加至购物车或立即购买。

![商品详情](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/商品详情.jpg)

### 2.3 购物车

购物车为空时，显示购物车为空的提示以及返回商店的按钮。点击“返回商店”将跳转至素材商店。

![空购物车](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/空购物车.jpg)

购物车非空时，购物车页面将显示购物车与结账二合一的页面（one-page checkout）。用户可以修改产品数量、删除产品、填写账单姓名（必填）、邮箱地址（必填）、备注信息，以及支付。

![opc](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/opc.jpg)

![opc](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/opc2.jpg)

支付方式取决于WooCommerce付款设置中的支付网关。点击支付按钮将跳转至对应支付网关进行付款。支付完成后，页面将跳转至收到订单页，该页提示用户已收到订单并显示订单详情。同时本站将向用户所填写的电子邮箱发送一份订单完成的电子邮件。若支付失败，页面将跳转至为订单付款页，订单状态将标记为待付款。

![收到订单](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/收到订单.jpg)

![支付失败](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/支付失败.jpg)

**注意！未登录的访客用户也可以添加商品至购物车并结账。**购物车页将显示登录与注册按钮，允许其登录或注册他的账户。然而，用户不登录或注册也可以正常结账，只是无法在本站查看其订单。但是，用户仍然可以通过订单的电子邮件查看订单信息以及下载产品。

这是一个业务上的考量，笔者认为这一设置是便捷且合理的。若需要更改，可以在仪表盘——>WooCommerce设置——>账户和隐私处进行更改。

![访客结账](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/访客结账.jpg)

### 2.4 我的账户

#### 2.4.1 未登录：登录与注册

功能：登录、注册

![登录注册](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/登录注册.jpg)

**登录**：用户填写用户名或电子邮件、密码进行登录。登录成功将跳转至首页。输入错误的信息将会显示错误提示。

![错误用户名](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/错误用户名.jpg)

**忘记密码**：跳转至忘记密码页，用户填写用户名或电子邮件后并提交后，本站将会向其发送一份密码重置邮件。提交错误信息将会得到错误提示。

![密码重置-邮件](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/密码重置-邮件.jpg)

![忘记密码-错误](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/忘记密码-错误.jpg)

![密码重置-邮件](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/密码重置邮件.jpg)

**注册：**用户填写电子邮箱地址并提交注册。本站将会向其邮箱发送一封设置密码的邮件，同时用户将自动登录并跳转至我的账户页。当用户没有设置密码时，他退出后，其账户存在于后台但无法登录。当用户通过邮件设置密码后，他才能登录。

![其他用户](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/其他用户.jpg)

![注册邮件](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/注册邮件.jpg)

#### 2.4.2 已登录：我的账户

功能：查看账户订单、查看下载、查看账户详情、账户退出

![我的账户-已登录](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/我的账户-已登录.jpg)

**订单：**用户查看订单状态、付款或取消订单。

![订单](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/订单.jpg)

**查看：**网站跳转至订单详情页。

![订单详情](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/订单详情.jpg)

**付款：**网站跳转至付款页。在付款完成之前，该订单将一直处于待付款状态。付款完成后，订单将处于已完成状态。

![订单-付款](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/订单-付款.jpg)

**取消：**网站显示订单已取消。该订单将转为取消状态。

![订单取消](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/订单取消.jpg)

**下载：**用户查看购买的产品剩余下载次数、过期时间，以及下载购买的产品。

产品下载次数、过期时间以及产品文件路径可以在仪表盘——>商品——>具体产品中设置。

![下载](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/下载.jpg)

![下载设置](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/下载设置.jpg)

**账户详情：**用户修改姓名、昵称、邮箱地址、密码。

当用户更改密码时，Wordpress服务器将会向他发送一封密码已更改的邮件。

![账户详情-信息](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/账户详情-信息.jpg)

![账户详情-密码](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/账户详情-密码.jpg)

**退出：**用户退出登录，重定向至登录-注册页

### 2.5 导航栏、脚注菜单

#### 2.5.1 导航栏

左侧展示网站Logo，右侧展示跳转到首页、素材商店、购物车和我的账户页面的链接。

处于大标题区域时，导航栏底色为透明。滚动到下方页面时，导航栏底色为白色（似乎无法更改）

![导航-透明](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/导航-透明.jpg)

![导航-白色](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/导航-白色.jpg)

**网站Logo设置**：仪表盘——>自定义——>站点身份——>Logo

![Logo设置](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/Logo设置.jpg)

**导航标签和排序设置**：仪表盘——>自定义——>菜单——>导航

![导航标签设置](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/导航标签设置.jpg)

**导航菜单设置**（标签、链接、排序等）：仪表盘——>外观——>菜单——>导航

【优先使用这一方式管理导航菜单】

![导航菜单设置](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/导航菜单设置.jpg)

#### 2.5.2 脚注菜单

展示跳转到关于我们、加入我们、广告合作、用户协议、隐私协议、Bilibili主页的链接。

**脚注标签和排序设置**：仪表盘——>自定义——>菜单——>Foot

![脚注标签设置](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/脚注标签设置.jpg)

**脚注菜单设置**（标签、链接、排序等）：仪表盘——>外观——>菜单——>Foot

【优先使用这一方式管理脚注菜单】

![脚注菜单设置](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/脚注菜单设置.jpg)

## 3. 已安装的插件

### 3.1 Akismet反垃圾评论（未启用）

保护站点免受垃圾评论。

使用方式：激活Akismet插件，然后转到Akismet设置页面来设置您的API密钥。

### 3.2 All-in-One WP Migration（未启用）

Wordpress数据迁移工具。可将网站内容打包导入或导出。

### 3.3 Checkout Field Editor for WooCommerce（已启用）

自定义WooCommerce结帐字段（添加，编辑，删除和重新排列字段）。

**相关页面**：结账页

**相关插件**：WooCommerce

### 3.4 Customize My Account for WooCommerce（已启用）

自定义WooCommerce 我的账户页（添加，编辑，删除和重新排列字段）。

**相关页面**：我的账户页

**相关插件**：WooCommerce

### 3.5 One page checkout and layouts for WooCommerce（已启用）

该插件用于结合购物车和结帐流程，为用户提供更快的结帐体验，减少中断。

**相关页面**：结账页

**相关插件**：WooCommerce

### 3.6 Orbit Fox Companion（已启用）

主题模板库和icon库

**相关页面**：主题首页-Features

### 3.7 Wenprise Alipay Payment Gateway For WooCommerce（已启用）

WooCommerce 支付宝网关，用于支付宝结账功能

**相关插件**：WooCommerce

### 3.8 Wenprise WeChatPay Payment Gateway For WooCommerce（已启用）

WooCommerce 微信支付网关，用于微信支付结账功能

**相关插件**：WooCommerce

### 3.9 WooCommerce（已启用）

电商套件，本站电商功能的核心插件。可以管理商品、客户、订单、电子邮件等业务，同时管理商店、结账、账户页面显示。

### 3.10 WP Open Social（未启用）

使用 QQ、微信、微博、百度、谷歌、微软、脸书、推特等社交平台实现一键登录和分享，还有更多平台和功能。模块化结构，按需扩展。

### 3.11 WPC Buy Now Button for WooCommerce（已启用）

添加“立即购买”按钮

**相关页面**：素材商店页、商品详情页

**相关插件**：WooCommerce

### 3.12 WPForms Lite（已启用）

WordPress表单插件，可创建和管理表单相关事项

**相关页面**：主题首页-联系我们

### 3.13 Yoast SEO（未启用）

搜索引擎优化插件

### 3.14 重新生成缩略图（已启用）

重新生成一个或多个图片上传的缩略图。应该是被Wordpress主题所使用。

### 3.15 WP Mail Logging（已启用）

记录本站发送的所有电子邮件。

## 4. 管理员仪表盘简介

### 4.1 自定义

编辑网站外观、网站主题等设置。

![自定义](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/自定义.jpg)

![自定义编辑](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/自定义编辑.jpg)

### 4.2 媒体库

存放一些图片、视频，可以在Wordpress中调用

![媒体库](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/媒体库.jpg)

### 4.3 页面

编辑网站页面内容。

【建议修改】：关于我们、加入我们、广告合作、用户协议、隐私政策、退款和退货指南

【不建议修改（WooCommerce相关）】：我的账户、素材商店、结算、交易失败、订单信息、购买历史、结账、购物车

【按需修改】：首页（精选视频）

![页面](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/页面.jpg)

### 4.4 WooCommerce

【业务相关】订单、客户、报表等

![WC-业务](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/WC-业务.jpg)

【设置相关】

1. 结账表单：定义结账表单中的字段

   ![WC-结账表单](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/WC-结账表单.jpg)

2. 设置：WooCommerce的一些设置，例如付款、账户和隐私、电子邮件等

![WC-设置](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/WC-设置.jpg)

### 4.5 产品

导入导出产品、管理各项产品的具体设置

![产品](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/产品.jpg)

### 4.6 外观

选择主题、自定义页面外观、管理导航脚注菜单等

![主题](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/主题.jpg)

![外观-菜单](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/外观-菜单.jpg)

### 4.7 插件

管理已安装的插件、安装新插件、编辑插件代码

![插件](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/插件.jpg)

### 4.8 用户

管理用户、设置管理员资料

![用户](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/用户.jpg)

### 4.9 设置

设置站点标题、URL、**管理员电子邮箱**以及一些其他设置

![设置](https://github.com/Barytes/VFXboys_Website_Documents/blob/main/doc/imgs/设置.jpg)

### 4.10 已安装的插件相关

- **WPC Buy Now Button**

​		WPClever——>Buy Now

​		设置立即购买按钮

- **WPForms**

  WPForms

  关于联系我们表单，也可以用于管理一些其他的表单

- **Checkout Field Editor for WooCommerce**

  Checkout Layouts

  管理结账页面的布局

- **Customize My Account for WooCommerce**

​		SysBasics——>Customize My Account

​		自定义“我的账户”页面布局

- **WP Mail Logging**

​		工具——>WP Mail Log

​		网站的邮件日志管理

- **Orbit Fox Companion**

​		Orbit Fox

​		当前主题依赖的模板库
