# magnifier
一个商品放大镜的jquery插件
 * 依赖jquery >=1.7
 * @multiple 可放大的倍数，默认是2倍
 * @bgColor 暂时只能设置rgba的颜色
 * @canShow 如果因为加载等原因不想鼠标移入还有效果，可以通过给当前元素增加data-show的属性，
 * 当属性值为false时，移入效果终止，知道data-show属性更改为非false等其他值。也可以一开始就设置false来禁止鼠标移入效果
 * @time 设置延迟时间，避免误触发，提高用户体验
 
 简单的展示使用，外面一个div，里面放一个img就可以了。
 ```
 $('#imgBox').magnifier();
 ```
 [简单的展示页面](https://qiqihaobenben.github.io/dataexchange/index.html)
