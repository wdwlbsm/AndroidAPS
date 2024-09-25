#美国心理学会
*查看 wiki：https://wiki.aaps.app
*  所有参加过 AAPS 循环治疗的人都需要在循环治疗 3 天后填写表格 https://docs.google.com/forms/d/14KcMjlINPMJHVt28MDRupa4sz4DDIooI4SrW0P3HSN8/viewform?c=0&w=1

[ ![支持服务器] （https://img.shields.io/discord/629952586895851530.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge ）] （https://discord.gg/4fQUWHZ4Mw ）


[ ![ CircleCI ] （https://circleci.com/gh/nightscout/AndroidAPS/tree/master.svg?style=svg ）] （https://circleci.com/gh/nightscout/AndroidAPS/tree/master ）
[ ![ Crowdin ] （https://d322cqt584bo4o.cloudfront.net/androidaps/localized.svg ）] （https://translations.aaps.app/project/androidaps ）
[ ![文档状态] （https://readthedocs.org/projects/androidaps/badge/?version=latest ）] （https://wiki.aaps.app/en/latest/?badge=latest ）
[![codecov](https://codecov.io/gh/nightscout/AndroidAPS/branch/master/graph/badge.svg?token=EmklfIV6bH)](https://codecov.io/gh/nightscout/AndroidAPS)

DEV: 
[![CircleCI](https://circleci.com/gh/nightscout/AndroidAPS/tree/dev.svg?style=svg)](https://circleci.com/gh/nightscout/AndroidAPS/tree/dev)
[![codecov](https://codecov.io/gh/nightscout/AndroidAPS/branch/dev/graph/badge.svg?token=EmklfIV6bH)](https://codecov.io/gh/nightscout/AndroidAPS/tree/dev)

< img src = “https://cdn.iconscout.com/icon/free/png-256/bitcoin-384-920569.png”  srcset = “https://cdn.iconscout.com/icon/free/png-512/bitcoin-384-920569.png 2x”  alt = “比特币图标” 宽度= “100” >

3KawK8aQe48478s6fxJ8Ms6VTWkwjgr9f2

##如何支持此项目？
软件遵循GPL V3协议，是开源免费的，但开发者编写代码、维护需要投入大量时间精力。
大家的支持是项目取得胜利的动力。
支持原版请从上面英文链接捐赠。
支持码农哥增加的功能，请点击以下链接或者扫码。

< a href = "/Documentation/donation.jpg" > < img src = "/Documentation/donation.jpg?raw=true"  alt = "捐赠"  width = "300" > </ a >

https://afdian.net/a/manong
## How to Build
## 如何编译

### If your are familiar with Android development:
** 分叉此存储库。
** 用您自己的密钥库文件替换“keystore/demokeystore.jks”。`keystore/demokeystore.jks` with your own key store file.
** 在您的存储库的“操作秘密和变量”设置中添加以下秘密。    
< a href = "/Documentation/screen1.png" > < img src = "/Documentation/screen1.png?raw=true"  alt = "Actions secrets 的屏幕截图"  width = "800" > </ a >  
  `KEY_ALIAS`:  Key alais of your key store file.
  `KEY_PASSWORD`: key password of your key store file.
  `STORE_FILE`: Path of your key store file in your repository.
  `STORE_PASSWORD`: Store password of your key store file.
* Trigger build in Github Actions
* Download the `aaps.zip` file in `Artifacts`

### 如果你熟悉安卓开发：
* 克隆此代码仓库到你自己的Github账号
* 用你自己的安卓签名文件替换你克隆的仓库中的`keystore/demokeystore.jks`
* 在你克隆的仓库设置中的  `Actions secrets and variables` 选项中添加如下秘密环境变量：  
<a href="/Documentation/screen1.png"><img src="/Documentation/screen1.png?raw=true" alt="Screenshot of Actions secrets" width="800"></a>  
  `KEY_ALIAS`:  你的安卓签名文件的key alias。
  `KEY_PASSWORD`: 你的安卓签名文件的key密码。
  `STORE_FILE`: 你的安卓签名文件的路径。
  `STORE_PASSWORD`: 你的安卓签名文件的store密码。
* 在Github Actions中触发编译
* 下载`Artifacts`中的编译产物`aaps.zip` 

### If your are NOT familiar with Android development:
您需要获取密钥库文件的密钥才能签署您的应用程序。出于安全原因，所有密码都不在此存储库中。
**It's really recommanded that you can sign your apk file with your own key store file after learning some Android knowledge.**
Please follow these steps:
* Fork this repository.
* Scan the below QR code and subscribe "一型码农Lex" WeChat Channel.  
<a href="/Documentation/wechat_qr.png"><img src="/Documentation/wechat_qr.png?raw=true" alt="WeChat Channel QR code" width="340"></a>  
* Join the WeChat group and ask for the secrets. (Get the WeChat group QR code form the middle menu of "一型码农Lex" WeChat Channel. Scan to join.)
* Add below secrets in the  `Actions secrets and variables` settings of your repository.  
<a href="/Documentation/screen1.png"><img src="/Documentation/screen1.png?raw=true" alt="Screenshot of Actions secrets" width="800"></a>  
  `KEY_ALIAS`, `KEY_PASSWORD`, `STORE_FILE`, `STORE_PASSWORD`. 
* Trigger build in Github Actions
* Download the `aaps.zip` file in `Artifacts`

### 如果你不熟悉安卓开发：
你需要获取安卓签名文件的密码等信息，因安全原因，这些敏感信息不能公开发布于此。
**强烈建议学习相关知识，编译完APK后，用你自己的签名文件签名。**
请按如下步骤操作:
* 克隆此代码仓库到你自己的Github账号
* 扫描下方二维码关注“一型码农Lex”微信公众号。Scan the below QR code and subscribe "一型码农Lex" WeChat Channel.  
<a href="/Documentation/wechat_qr.png"><img src="/Documentation/wechat_qr.png?raw=true" alt="WeChat Channel QR code" width="340"></a>  
* 点击“一型码农Lex”微信公众号的中间菜单，获取入群二维码。进去索要签名文件的密码。
* 在你克隆的仓库设置中的  `Actions secrets and variables` 选项中添加如下秘密环境变量：  
<a href="/Documentation/screen1.png"><img src="/Documentation/screen1.png?raw=true" alt="Screenshot of Actions secrets" width="800"></a>  
  `KEY_ALIAS`, `KEY_PASSWORD`, `STORE_FILE`, `STORE_PASSWORD`，这些变量的值都在群中。
* 在Github Actions中触发编译
* 下载`Artifacts`中的编译产物`aaps.zip`
