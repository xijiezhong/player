# 音乐播放器
## 界面展示
![](https://github.com/xijiezhong/player/blob/master/img/example.png)
## 使用vue构建的一个简易功能版的仿网易云音乐播放器
整个文件很简单，一共两个组件：player和screen.<br>
screen就是界面中间显示歌曲专辑封面、歌曲相关信息以及歌词的界面.<br>
未来会考虑做成单页面应用.<br>
## 主要功能
播放器主要实现的功能就是<br>
### 从服务器获取信息构建页面
父组件player使用vue-resource从公司服务器上获取歌曲信息,通过子组件screen的props传给子组件
### 动画：专辑封面转动和歌词滚动
点击父组件的播放按钮和暂停按钮控制子组件screen上专辑封面转动和歌词滚动动画的随开随停<br>
也是通过子组件的props实现状态传递的

