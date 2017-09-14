# recyclerviewtest
更强大的滚动控件——RecyclerView

打开app/build.gradle文件，在dependencies闭包中添加如下内容：
 compile 'com.android.support:recyclerview-v7:24.2.1'
 
 添加完之后记得点击一下Sync Now进行同步。然后修改activity_main.xml中的代码如下所示：
 <?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <android.support.v7.widget.RecyclerView
        android:id="@+id/recycler_view"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />

</LinearLayout>

更详细的内容欢迎下载源代码进行学习
 
