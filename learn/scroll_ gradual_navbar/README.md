
# 参考来源

### 实现方式1: classList.toggle("sticky",window.scrollY>0);

classList.toggle 方法来切换 header 元素的类名。toggle方法接受两个参数，第一个参数是要切换的类名（在这个例子中是"sticky"），第二个参数是一个布尔值，表示是否要添加这个类名。如果第二个参数为true，则添加类名；如果为false，则移除类名。

B站视频: [HTML5+CSS3+JS小实例：滚动渐变导航栏](https://www.bilibili.com/video/BV1E44y1L7G5)

项目源码: [86.html](https://gitee.com/wyanhui02/html_css_demo/blob/master/html/86.html), [86.css](https://gitee.com/wyanhui02/html_css_demo/blob/master/css/86.css)

### 实现方式2：监听scroll事件，给背景设置透明度

参考网站：[YIKE 时光](https://huohuo90.com/home)