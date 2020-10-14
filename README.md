# planet

config
Config用来获取远程所有配置

target
目标后台版本

V2board
SSPanel Malio
SSPanel Uim-Dev版本
SSPanel Uim
SSPanel Staff
SSPanel Cool
SSPanel 书生
email
App内显示的Email联系地址，为空则不显示

tg
App内显示的TG联系方式，为空则不显示

loginless
是否开启免登录模式 0. 关闭

开启
loginless_link
免登录订阅地址

若Host与域名相同，请去除Host信息；
若有多个订阅地址，请用“,”隔开；
请在url后面添加订阅类型"lt=？"参数，（1:ss, 2:ssr, 3: v2ray），例：/subLink?lt=1
code_login
是否开启登录邮箱验证码 0. 关闭

开启
code_register
是否开启注册邮箱验证码 0. 关闭

开启
captcha_login
登录人机验证

不需要
reCAPTCHA
极验
captcha_register
注册人机验证

不需要
reCAPTCHA
极验
captcha_checkin
签到人机验证

不需要
reCAPTCHA
极验
notice
公告展示频率

每次打开都展示
每天只展示一次
每条只展示一次
checkin
是否开启每日签到功能 0. 关闭

开启
line_flag_regex
节点国旗获取正则

line_exclude_loc
节点名称中是否去掉国家信息 0. 否

是
payment_config
支付设置

Alipay 支付宝
Wechat 微信
自动处理
paytaro
leyupay
f2f
wolfpay
smpay
muggle
hosts
域名列表，最多三个

version
版本管理

code
版本号

name
版本名

content
版本更新内容，支持html模式

url
版本下载地址

md5
版本包文件md5值

force
是否强制更新 0. 否

是
qrcode
分享二维码图片地址，会在APP-分享中显示该图片，默认为下载地址二维码

create_time
版本创建时间（时间戳格式）
