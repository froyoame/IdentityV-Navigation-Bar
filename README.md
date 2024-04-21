![image](https://github.com/froyoame/IdentityV-Navigation-Bar/assets/119313191/5efc6ff8-d616-48d7-9dfe-ed2956ed9ef4)# IdentityV-Navigation-Bar
"This is my first project on GitHub",my English is poor,所以下面中文简述。
## 第五人格主题导航栏（极简失败版）心路历程与问题点
**这里首先 *感谢Vicky姐姐* 在B站发布的wpf教程** :heart_eyes_cat: ：(https://www.bilibili.com/video/BV1Ui4y1a717/?spm_id_from=333.999.0.0&vd_source=0672cf281eaefd42dd21ef6c6e0c33d4)
### 姐姐的账号
B站@小李趣味多：(https://space.bilibili.com/688707261)

GitHub：(https://github.com/jamesnet214)（姐夫）  
(https://github.com/vickyqu115/navigationbar)（姐姐）

正好我的毕设要用到wpf，我又幸运地看到姐姐发布的视频（不过我现在还是小白）。Vicky姐姐的讲解深入浅出，评论区的疑问也都非常详尽耐心地解答，她一下子就成为了我心中的榜样。
### 	:smiling_face_with_three_hearts: 
在姐姐提供的NavigationBar控件设计中，我突发奇想想用第五人格角色的头像代替Icon也实现点击跳跃动画效果，不出所料，，失败了哈哈，姐姐鼓励我写在GitHub她帮我看看，所以有了我的第一个Github项目。
# 问题所在
![image](https://github.com/froyoame/IdentityV-Navigation-Bar/assets/119313191/4dd3408b-5903-47e8-bbb9-d06a436e913c)

![image](https://github.com/froyoame/IdentityV-Navigation-Bar/assets/119313191/b4b39c93-9e0b-4f54-84d2-042716922d6a)
## `<Setter></Setter>`
因为我是想用图片代替`Icon`的效果。

姐姐教程里的设计是在`ListBoxItem`通过`Tag`传递参数，实现`Icon`图形的多样化。

如果我想替换成图片（角色头像），我尝试在`ListBoxItem`中通过`Background`的属性来在`Tag`中传递参数，具体参数就是图片的位置。但是可能这样做不合适，或者是设置属性时出了问题，总之目前运行效果就是不显示任何图像。

## 图片文件夹`pictures`丢失
图像本应在文件夹中,就像这样：

![image](https://github.com/froyoame/IdentityV-Navigation-Bar/assets/119313191/3b6c39b6-4309-423c-a733-2a9ca18f5154)

但是可能是我上传文件时不熟悉流程的原因，我刚刚本来想示例加载一个图片，结果去找却发现我好像没有上传，于是一张一张新添加了，这样就使得`pictures`文件夹不存在了。可能我上传的文件有一大部分是不需要的	 :rofl: 

![image](DemoApp/Aeroplanist.png)

另外姐姐说的`Build Action`设置是什么意思呀？
# 致谢	 :bouquet: 
虽然存在着问题，最后还是要感谢姐姐的激励。第一次在GitHub上传项目，制作得很粗糙。这似乎是未来的一丝预兆吧！总之加油！！
