# NWU羽毛球馆预约辅助V5.0
目前暂未开源
直接使用网址：http://nwu.nat100.top

# 有没有会做前端vue开发的一起合作，联系我邮箱，非常感谢

# Badminton Hall Appointment Assistance  NWU羽毛球馆预约辅助

众所周知西大羽毛球馆预约系统是一坨答辩，本人作为一名羽毛球爱好者深受土豆服务器的迫害，每次从12点半开始等一直要等到接近1点页面才能加载出来，这时候已经基本上所有场次被抢光了
所以开发了这个系统，用于帮助用户快速抢馆，开发完后试用了下效果很不错，2s完成预约

还在开发中，增加功能，暂时不开源


前端页面：
![image](https://github.com/Oyzmandias/NWU_BRS_assistant/assets/69197910/f84c5a37-ed4a-4088-925f-6bcc25588d22)

![image](https://github.com/Oyzmandias/NWU_BRS_assistant/assets/69197910/8a5eaa87-023e-4f59-b923-3d1f4eed24f1)



# 系统使用说明：
- 1，本应用由一个编程和羽毛球爱好者开发，用于西北大学羽毛球馆自动抢馆，解决手机微信端载入速度极慢的问题，不对成功率负责，场次数量是固定的，狼多肉少必然导致大部分人抢不到
- 2，推荐电脑访问,推荐使用Edge或者Chrome浏览器，移动设备可以点击页脚链接去博客看使用说明，网页之所以设计黑色是因为防止大家凌晨吃闪
- 3，做了多线程并发下打散目标场次的算法优化，降低多线程抢同一场次产生的碰撞率，尽量提高成功率，此外，不同用户的预约任务提交顺序不影响成功率
- 4，应用不存储您的账号密码，只存储身份令牌用于自动登录，请放心使用

打开网站，点击登录，会自动跳到NWU统一认证页面，登录完成后携带用户token返回，会显示当前登录用户信息，然后选择你期望的场次范围，比如开始时间17，结束时间22，就会寻找下午5点到21：30之间的所有可预约场次，如果勾选不接受2小时，会自动排除2小时的可用场次信息

点击开始抢购按钮，等待一下会看到预约结果
