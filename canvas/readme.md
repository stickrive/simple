### canvas

#### L1
```
var cavans = document.getElementById('cavans'); //获取dom对象
var context = cavans.getContext('2d'); //获取画笔

context.moveTo(0, 0); //画笔放到（0, 0）
context.moveLine(100, 100); //绘制到(100, 100)
context.lineWidth = 5; //线条的宽度
context.strokeStyle = '#f6f6f6'; //线条的颜色
context.stroke(); //确认绘制  每次使用

beginPath();//开始绘制  绘制多线条时，stroke，会把之前的状态绘制一遍，stroke结束后使用beginPath 可避免
closePath();

context.

```