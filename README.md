# duilib

由官方的duilib( https://github.com/duilib/duilib ) 复制过来的，仅为了个人学习使用。<br />
可以使用vs2008打开，新增一些学习测试用的demo，之后也可能会做很少的修改，但代码尽量会与官方保持一致。<br />
有任何问题请联系我，邮箱juhuaguai@yeah.net<br />
腾讯使用的的duilib修改版： https://github.com/tencentyun/TIMSDK/tree/master/cross-platform/Windows/IMApp/Basic/duilib <br />
网易使用的duilib修改版： https://github.com/netease-im/NIM_Duilib_Framework/tree/master/duilib <br />

<br />

<br />

<br />
本仓库改动日志：<br />
1.将解决方案sln切换为vs2008打开<br />
2.添加webbrowser控件对js方法window.close的响应<br />
3.给combo控件增加selectedid属性，以便于在xml中可以直接配置默认选中的item<br />
4.给combo控件增加textcolor/font/align属性，便于自由配置combo控件显示的文字的颜色/字体/水平对齐方式<br />
5.给combo控件的下拉窗口增加Notify过滤，将下拉窗口中的DUI_MSGTYPE_ITEMCLICK,DUI_MSGTYPE_ITEMACTIVATE,DUI_MSGTYPE_LINK ,DUI_MSGTYPE_CLICK异步转发到combo控件所在的窗口的notify中<br />
6.修复listElement listContainerElement标签的selected属性false不生效的bug<br />

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

