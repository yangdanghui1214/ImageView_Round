# ShadowImageView
## Abstract
    More exquisite shadow effect, used in some special scene to enhance the user experience.

## Chinese Documents
[查看中文文档](https://github.com/yingLanNull/ShadowImageView/blob/master/READEME_CN.md)

## Picture
![1](https://github.com/yingLanNull/ShadowImageView/blob/master/show/shadow1.png)
![2](https://github.com/yingLanNull/ShadowImageView/blob/master/show/shadow2.png)

## GIF
![1](https://github.com/yingLanNull/ShadowImageView/blob/master/show/shadow.gif)

## Add Picture
![3](https://github.com/yingLanNull/ShadowImageView/blob/master/show/shadowcolor.png)

## Demo
[Download App](https://github.com/yingLanNull/ShadowImageView/blob/master/show/app-debug.apk)

## Usage

#### Gradle
```
dependencies {
    compile 'com.yinglan.shadowimageview:shadowimageview:1.0.4'
}
```

### In layout

```
	    <com.yinglan.shadowimageview.ShadowImageView
	            android:id="@+id/shadow"
                android:layout_width="300dp"
                android:layout_height="300dp"
                app:shadowRound="20dp"
                app:shadowSrc="@mipmap/lotus"
                app:shadowColor="@color/colorAccent"/>

```

### Set Picture
```
    shadow.setImageResource(resID); 
    shadow.setImageDrawable(drawable); 
    shadow.setImageBitmap(bitmap);
```

### Set the picture radius
```
    shadow.setImageRadius(radius);
```
### Set the shadow color of the image
```
    shadow.setImageShadowColor(color);
```

## FAQ
 See[PPMusicImageShadow](https://github.com/PierrePerrin/PPMusicImageShadow),  do a simple implementation, there may be a potential problem and use learning exchanges, looking forward to you have a better way of implementation.

## License
The work done has been licensed under Apache License 2.0. The license file can be found
[here](LICENSE). You can find out more about the license at:

http://www.apache.org/licenses/LICENSE-2.0