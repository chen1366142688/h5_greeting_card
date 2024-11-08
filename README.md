这是一个带音乐的h5+canvas贺卡
![Image text](https://github.com/chen1366142688/h5_greeting_card/blob/main/static/yanshi1.png)
![Image text](https://github.com/chen1366142688/h5_greeting_card/blob/main/static/yanshi2.png)

## 记录一下如何通过GitHub访问网页
* 在项目地址前面加上 https://htmlpreview.github.io/? 可直接访问
* https://htmlpreview.github.io/?https://github.com/chen1366142688/h5_greeting_card/blob/main/index.html


## 项目重点
* css animation 属性的掌握
* musicBg 音乐控制函数，同时用于添加烟花爆炸的音效
* countDown 新年倒计时切换页面，开始绘图
* initFires 绘图，把烟花放数组中，添加烟花后添加一个遮盖层制作出甩尾的效果
* 用三角函数找到坐标，设置x,y的速度
* loop 监听小球变化
* requestAnimationFrame 传递loop，时动画基本根据浏览器更新速度相同
* Ball 球的类
* Fire 爆炸的类