# AnimateQueue Js动画队列
##用于生成一系列动画
###用法
```
var queue = new AnimateQueue();
queue.add(function(){
  //TODO animate1
}, delay);
queue.add(function(){
  //TODO animate2
}, delay);
queue.add(function(){
  //TODO animate3
}, delay);

//开始执行一连串动画
queue.start();
```
