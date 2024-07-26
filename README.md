# 🚘 Responsive Car website
## [Watch it on youtube](https://youtu.be/bDngcOQ8Img)
### 🚘 Responsive Car website

- Responsive Car website Using HTML CSS & JavaScript
- Contains animations when scrolling.
- Smooth scrolling in each section.
- Developed first with the Mobile First methodology, then for desktop.
- Compatible with all mobile devices and with a beautiful and pleasant user interface.

💙 Join the channel to see more videos like this. [Bedimcode](https://www.youtube.com/c/Bedimcode)

![preview img](/preview.png)

学习笔记
justify-self属性的使用 justify-self:center可以使object居中 但是前提是display：grid
图标的使用: remixicon图标库
[](https://remixicon.com/)
swiper组建的使用: 使用swiper来进行轮播图的实现
[轮播图](https://swiperjs.com/demos#pagination-dynamic) 
[主要配置](https://codesandbox.io/s/e56nh3?file=/index.html)
[主要配置](https://codesandbox.io/s/hoyjrj?file=/index.html)
使用swiper时首先要引入swiper-bundle.min.css和swiper-bundle.min.js
在需要进行轮播元素的父级元素添加class="swiper-wrapper" 需要轮播的元素添加class="swiper-slide"
然后在js中定位到需要使用swiper的元素 参考[主要配置]进行配置


mixitup组件的使用 mixitup用来进行条件筛选 首先引入mixitup.js
[参考文档](https://www.kunkalabs.com/mixitup/docs/get-started/)
在筛选元素添加data-filter属性
eg:<button type="button" data-filter="all">All</button>
然后在被筛选元素的class中添加 mix 筛选条件(例如data-filter='tesla' 被筛选元素的class中要添加mix tesla)
在js文件中调用

scrollreveal组件的使用,可以使元素实现一个懒加载的样子 --效果很好看推荐使用
[官方文档](https://scrollrevealjs.org/guide/hello-world.html)
引入scrollreveal.min.js文件
然后在js文件中操纵即可
