# resizableImage
demo for stretchable/resizable UIImage

* 点击按钮为选择态，背景变蓝，字体变白，图标改变。
* 左按钮为左图标右标题，右按钮为*左标题右图标*，图标和标题间距为8pt。

`胶囊按钮`综合演示了：  
+ 按钮背景贴图（setBackgroundImage）：  
  + -[UIImage *resizableImageWithCapInsets*:resizingMode:]  
+ 按钮图标（imageView）：  
  + -[UIButton *setImageEdgeInsets*:]   
+ 按钮图标（titleLabel）：  
  + -[UIButton *setTitleEdgeInsets*:]   

---
1.初始胶囊按钮，背景为蓝圈白底，字体为蓝色。左右按钮初始图标分别为大拇指竖起和大拇指向下。
![初始胶囊按钮](https://github.com/fan2/resizableImage/blob/master/ScreenShots/0-%E5%88%9D%E5%A7%8B%E8%83%B6%E5%9B%8A%E6%8C%89%E9%92%AE.png)

2.选择左胶囊按钮，背景变蓝，字体变白，图标由大拇指竖起变为一朵鲜花。
![选择左胶囊按钮](https://github.com/fan2/resizableImage/blob/master/ScreenShots/1-%E9%80%89%E6%8B%A9%E5%B7%A6%E8%83%B6%E5%9B%8A%E6%8C%89%E9%92%AE.png)

3.选择右胶囊按钮，背景变蓝，字体变白，图标由大拇指向下变为一朵枯萎。
![选择右胶囊按钮](https://github.com/fan2/resizableImage/blob/master/ScreenShots/3-%E9%80%89%E6%8B%A9%E5%8F%B3%E8%83%B6%E5%9B%8A%E6%8C%89%E9%92%AE.png)

4.增加纵向UIImageView胶囊贴图效果：
![增加纵向UIImageView胶囊](https://github.com/fan2/resizableImage/blob/master/ScreenShots/5-%E7%BA%B5%E5%90%91%E8%83%B6%E5%9B%8A%E8%B4%B4%E5%9B%BE%E6%95%88%E6%9E%9C.png)

5.增加登录按钮贴图效果：
![增加登录按钮贴图效果](https://github.com/fan2/resizableImage/blob/master/ScreenShots/6-%E7%99%BB%E5%BD%95%E6%8C%89%E9%92%AE%E8%B4%B4%E5%9B%BE%E6%95%88%E6%9E%9C.png)

6.增加微信聊天气泡效果：
![增加登录按钮贴图效果](https://github.com/fan2/resizableImage/blob/master/ScreenShots/7-%E5%BE%AE%E4%BF%A1%E8%81%8A%E5%A4%A9%E6%B0%94%E6%B3%A1%E6%95%88%E6%9E%9C.png)
