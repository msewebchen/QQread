# 转载使用他人脚本，切勿fork，原作者链接在脚本内注明



⚠️cookie获取方法：

进 小程序 点我的  获取cookie

进一本书 看 10秒以下 然后退出，获取阅读时长cookie，看书一定不能超过10秒

可能某些页面会卡住，但是能获取到cookie，再注释cookie重写就行了！



⚠️宝箱奖励为20分钟一次，自己根据情况设置定时，建议设置11分钟一次

hostname=mqqapi.reader.qq.com

############## 圈x

#企鹅读书获取cookie
https:\/\/mqqapi\.reader\.qq\.com\/mqq\/user\/init url script-request-header https://raw.githubusercontent.com/ziye12/JavaScript/master/qqread.js


#企鹅读书获取时长cookie
https:\/\/mqqapi\.reader\.qq\.com\/mqq\/addReadTimeWithBid? url script-request-header https://raw.githubusercontent.com/ziye12/JavaScript/master/qqread.js




⚠️调取cookie
复制以下代码到进脚本里某个空白处，无需保存，点击运行，就能打印企鹅的ck,然后依次换行填写进 COOKIE_QQYD 就可以了

console.log(qqreadurlVal+'\n\n'+qqreadheaderVal+'\n\n'+qqreadtimeurlVal+'\n\n'+qqreadtimeheaderVal)
