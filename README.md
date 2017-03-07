# magnifier
一个商品放大镜的jquery插件
 * 依赖jquery >=1.7
 * 兼容性IE >= 9
 * @multiple 可放大的倍数，默认是2倍
 * @bgColor 暂时只能设置rgba的颜色
 * @canShow 如果因为加载等原因想暂时禁止鼠标的移入时间，可以通过给当前元素下的img节点增加**data-show**的属性，当属性值为false时，移入效果终止，直到data-show属性更改为非false等其他值。也可以一开始就设置false来禁止鼠标移入效果
 * @time 设置延迟时间，避免误触发，提高用户体验，单位（ms）
 
 简单的展示使用，外面一个div，里面放一个img就可以了。
 ```
 $('#imgBox').magnifier();
 ```
 
 [简单的展示页面](https://qiqihaobenben.github.io/dataexchange/index.html)
 
 [简书的相关介绍页面](http://www.jianshu.com/p/a285c5b6885b)
