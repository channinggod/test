---

---

# duilib

由官方的duilib( https://github.com/duilib/duilib ) 复制过来的，仅为了个人学习使用。<br />
可以使用vs2008打开，新增一些学习测试用的demo，之后也可能会做很少的修改，但代码尽量会与官方保持一致。<br />
有任何问题请联系我，邮箱juhuaguai@yeah.net<br />
腾讯使用的的duilib修改版： https://github.com/tencentyun/TIMSDK/tree/master/cross-platform/Windows/IMApp/Basic/duilib <br />
网易使用的duilib修改版： https://github.com/netease-im/NIM_Duilib_Framework/tree/master/duilib <br />

<br />

浅红色文字：<font color="#dd0000">浅红色文字：</font><br /> 
深红色文字：<font color="#660000">深红色文字</font><br /> 
浅绿色文字：<font color="#00dd00">浅绿色文字</font><br /> 
深绿色文字：<font color="#006600">深绿色文字</font><br /> 
浅蓝色文字：<font color="#0000dd">浅蓝色文字</font><br /> 
深蓝色文字：<font color="#000066">深蓝色文字</font><br /> 
浅黄色文字：<font color="#dddd00">浅黄色文字</font><br /> 
深黄色文字：<font color="#666600">深黄色文字</font><br /> 
浅青色文字：<font color="#00dddd">浅青色文字</font><br /> 
深青色文字：<font color="#006666">深青色文字</font><br /> 
浅紫色文字：<font color="#dd00dd">浅紫色文字</font><br /> 
深紫色文字：<font color="#660066">深紫色文字</font><br />

<table><tr><td bgcolor=#FF00FF>背景色的设置是按照十六进制颜色值：#7FFFD4</td></tr></table>
<table><tr><td bgcolor=#FF83FA>背景色的设置是按照十六进制颜色值：#FF83FA</td></tr></table>
<table><tr><td bgcolor=#D1EEEE>背景色的设置是按照十六进制颜色值：#D1EEEE</td></tr></table>
<table><tr><td bgcolor=#C0FF3E>背景色的设置是按照十六进制颜色值：#C0FF3E</td></tr></table>
<table><tr><td bgcolor=#54FF9F>背景色的设置是按照十六进制颜色值：#54FF9F</td></tr></table>

```
<div style="background-color:red">11111111111111111111</div>
```



## 说明：

##### **官方库改为本仓库代码后，会遇到CDuiString的一些编译或者运行报错，原因在于我调整了CDuiString的代码（见下方第55点说明），解决方法就是重新使用本仓库的duillib的头文件和.lib重新编译和链接生成自己的程序，解决其中的编译报错（主要是CDuiString转换为LPCTSTR时报错,修改CDuiString.GetData()）即可。**

## 有问题欢迎反馈！



### 2020/12/31更新移除掉了libpng相关库，apng解析绘制直接使用stbimage和自己实现的代码来处理了。同时gif也由gdi+解析改为了stbimage处理。

# 这样看来是有机会将gif和apng统一成一个控件的，进一步来看考虑，是有机会让所有支持背景图的控件支持gif和apng的，暂无需求先不考虑了。

<br />

<br />
本仓库改动日志：<br />
1.将解决方案sln切换为vs2008打开<br />
2.添加webbrowser控件对js方法window.close的响应<br />
3.给combo控件增加selectedid属性，以便于在xml中可以直接配置默认选中的item<br />
4.给combo控件增加textcolor/font/align属性，便于自由配置combo控件显示的文字的颜色/字体/水平对齐方式<br />



```javascript
var a=b;
var ttt;
setTimeOut(function(){},1111);


```

```css
.test{
    font-color:red;
    left:0px;
    margin-top:99px;
}
```



| **1** | **5** |       |
| ----- | ----- | ----- |
| **2** |       | **5** |
| **3** |       | **5** |
| **4** |       | 5     |

