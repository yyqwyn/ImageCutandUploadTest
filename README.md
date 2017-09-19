# ImageCutandUploadTest
=
这是一个Android平台的Demo,实现了常用的一个功能——从图库选择一张图片并经过裁剪等处理后显示到界面上。Demo简单易用，完美运行，可以直接拿来使用。下载使用的朋友请给我star一下作为鼓励哦！（点亮右边的小星星））



#yyqwyn
=
    2017年9月19日18:01:58
修改内容：
  1.添加操作权限，相机，SD卡，本地文件
  2.添加圆形图片引用https://github.com/hdodenhof/CircleImageView
  3.由原来点击按钮更换图片更换为点击图片直接更换头像
  4.修改头像存储在手机本地/sdcard/myHead/head.jpg,下次启动仍可显示
   参考：http://blog.csdn.net/xiaoyuan511/article/details/39205591
 
  引用说明：
  需添加权
 <uses-permission android:name="android.permission.CAMERA"/>
 <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
 <uses-permission android:name="android.permission.MOUNT_UNMOUNT_FILESYSTEMS"/>

  Gradle
-------

dependencies {
    ...
    compile 'de.hdodenhof:circleimageview:2.1.0'
}
