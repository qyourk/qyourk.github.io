下载谷歌版Mock Locations1.24.2

搜索方法名ru.gavrikov.mocklocations.core2016.d.l
在方法内添加
```
const/4 v0,0x1
return v0
```

再搜索方法名ya.c.g
把.line5下的
const/4 v1,0x0
改为
```
const/4 v1,0x1
```

使用Arsc编辑器打开resources.arsc
点击

```
ru.gacrikov.mocklocations
```
选择7F12 string
继续选择string
找到0003 GOOGLE-MAPS_ANDROID_API_KEY
修改为
```
AIzaSyBcCb6Wg2CC98b-aALOjtS3G9afMC1qaNg
```
大功告成！
