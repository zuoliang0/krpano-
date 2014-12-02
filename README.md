krpano-
=======
使用方法，
1.引用插件
<include url="xml/photoShow.xml"  />
2.导入按钮图片根目录
<include url="xml/imgs.xml" />
3.按照格式修改imgs.xml
4.在需要调用的场景<scene >标签中增加title属性，属性名要和imgs中<imgShow name="">的name属性相同！
5.在需要显示幻灯片的场景中的按钮或图片上的onclick事件中增加onclick="showImgs()"  action

具体可以参看demo中的例子
krpano制作的一个图片幻灯片插件，免费版欢迎使用
