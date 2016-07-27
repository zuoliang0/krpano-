如遇到问题请先尝试自己解决，本人已不在维护和提供帮助
已经不从事该项目
=======
使用方法，<br/>
1.引用插件<br/>
```
<include url="xml/photoShow.xml"  />
```
2.导入按钮图片根目录<br/>
```
<include url="xml/imgs.xml" />
```
<br/>
3.按照格式修改imgs.xml<br/>
4.在需要调用的场景<scene >标签中增加title属性，属性名要和imgs中imgShow name=""的name属性相同！<br/>
5.在需要显示幻灯片的场景中的按钮或图片上的onclick事件中增加onclick="showImgs()"  action<br/>
<br/>
<br/>
具体可以参看demo中的例子<br/>
krpano制作的一个图片幻灯片插件，免费版欢迎使用<br/>
