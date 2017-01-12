README

===========================

该文件用来阐述项目如何使用

****

###　　　　　　　　　Author:月冷

###　　　　　　　　　 E-mail:15222615737@163.com

===========================

使用

------

###布局使用



```Java

//<ratingstar.yueleng.com.freedomstar_master.Star
android:id="@+id/star"

Star:starsNum ="5"//星星数

Star:starWidth ="18dp"//星星单个宽度
Star:starHeight ="18dp"//星星高度
Star:starDistance ="3dp"//星星间距
Star:starBackground ="@drawable/s2"//星星背景
Star:starDrawBackground ="@drawable/s1"//星星变化图
Star:starClickable ="false"//是否可点击

android:layout_marginLeft="10dp"

android:layout_width="wrap_content"

android:layout_height="wrap_content"/>


代码使用

------
/**

*设置显示几颗星

* 5.0f代表五颗星，4.2代表四颗星加上第五颗星得五分之一

*/

star.setMark(2.0f);

star.getMark();

/**

*设置控件监听

*/

star.setStarChangeLister(newStar.OnStarChangeListener() {

@Override

public voidonStarChange(Float mark) {

}

});
```

演示样式

------
![星星样式](https://github.com/songfuli/freedomstar-master/blob/master/star.png?raw=true)

--------------------------------

[csdn]:http://my.csdn.net/z690798364?locationNum=0&fps=1 "我的博客"
