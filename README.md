# CSS3-background-size
CSS3 新增的 background-size 是一个很有用的属性，用于定义背景图片的尺寸，有了这个属性，你就可以任意指定背景图片的大小。其中最常用的值应该要数 cover 了，该值能让背景图片缩放至填满整个容器，即使是图片面积小于容器面积。  由于 background-size 是 CSS3 新增的属性，所以 IE 低版本自然就不支持了，但是老外写了一个 htc 文件，名叫 background-size polyfill，使用该文件能够让 IE7、IE8 支持 background-size 属性。其原理是创建一个 img 元素插入到容器中，并重新计算宽度、高度、left、top 等值，模拟 background-size 的效果。
