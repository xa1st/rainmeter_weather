Rainmeter的weather插件，用于修复从weacher.com获取天气失败

简单天气 v1.0.0

作者：[猫南南](https://blog.del.pub/code/rainmeter_weather.html) 

食用方法：

1. 去weather.com 搜自己所在的城市，可以精确到区，比如 “中国西安市莲湖区”，获得地址，如 https://weather.com/zh-CN/weather/today/l/7e1166b88281aca3bfadc891829b5ac82206d9b7a85b0d84ae4874c0fba4cceb

2. 然后用 记事本(重要) 将 简单天气.ini 打开，找到 ;你本地的天气访问地址，这一行，下面的

```
weatherUrl = http://weather.com/zh-CN/weather/today/l/7e1166b88281aca3bfadc891829b5ac82206d9b7a85b0d84ae4874c0fba4cceb
```

替换成你的，如果你获得的地址是 https:// 请换成 http:// 不然拿不到，具体没查到原因，因为我没有找到webparse.dll的源码....，然后保存..

3. 回到界面，刷新皮肤...打完收工....