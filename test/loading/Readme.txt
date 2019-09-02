https://blog.csdn.net/weixin_42067967/article/details/80152403

absolute

relative

父absolute + 子absolute

父absolute + 子relative

absolute 文档宽度及div宽度（脱离文档流 及margin auto 无用） 相对父定位（非static）

由此 垂直居中 可如下实现
 <div style="width:400px;height:400px;background-color: black;position:relative">
        <div style=" background-color: #FF0000;width: 200px;height: 200px;position: absolute;top: 0;left: 0;right: 0;bottom: 0;margin: auto,0;">
        </div>
    </div>
	
	注：position 默认值为 static 子元素 absolute 相对父元素（非static定位）结合 left right bottom right
	
	
	
	position 以及absolute的使用