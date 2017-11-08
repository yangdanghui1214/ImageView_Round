# ShadowImageView
## 摘要
    更加细腻的阴影效果，在一些提高用户体验的特殊场景使用

## 英文文档
[View English Documents](https://github.com/yingLanNull/ShadowImageView)

## 显示效果
![1](https://github.com/yingLanNull/ShadowImageView/blob/master/show/shadow1.png)
![2](https://github.com/yingLanNull/ShadowImageView/blob/master/show/shadow2.png)

## 动图
![1](https://github.com/yingLanNull/ShadowImageView/blob/master/show/shadow.gif)

## 新增显示效果
![3](https://github.com/yingLanNull/ShadowImageView/blob/master/show/shadowcolor.png)

## 下载APK体验
[点击下载](https://github.com/yingLanNull/ShadowImageView/blob/master/show/app-debug.apk)

## 使用方法

#### Gradle 配置
```
dependencies {
    compile 'com.yinglan.shadowimageview:shadowimageview:1.0.4'
}
```

### 布局

```
	    <com.yinglan.shadowimageview.ShadowImageView
	            android:id="@+id/shadow"
                android:layout_width="300dp"
                android:layout_height="300dp"
                app:shadowRound="20dp"
                app:shadowSrc="@mipmap/lotus"
                app:shadowColor="@color/colorAccent"/>

```

### 设置图片
```
    shadow.setImageResource(resID);
    shadow.setImageDrawable(drawable); 
    shadow.setImageBitmap(bitmap);
```

### 设置图片半径
```
    shadow.setImageRadius(radius);
```
### 设置图片阴影颜色
```
    shadow.setImageShadowColor(color);
```
## 注意

阴影效果的简单实现，可能会有潜在的问题做学习交流使用，期待大家有更好的实现方式。目前暂不支持直接使用加载网络图片，如需要展示网络图片可变通使用网络图片加载库，demo中有使用方法。


## 开源协议
The work done has been licensed under Apache License 2.0. The license file can be found
[here](LICENSE). You can find out more about the license at:

http://www.apache.org/licenses/LICENSE-2.0