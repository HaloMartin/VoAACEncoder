# VoAACEncoder
Android aac encoder using voaac

AAC编码库VoAACEncoder
适用于Android端，已经编译生成动态库so文件，使用方法简单，方法如下：
  - 下载并复制[libVoAACEncoder.so](https://github.com/HaloMartin/VoAACEncoder/blob/master/libs/armeabi/libVoAACEncoder.so "libVoAACEncoder.so")文件到项目中
  - 复制[VoAACEncoder.java](https://github.com/HaloMartin/VoAACEncoder/blob/master/src/com/sinaapp/bashell/VoAACEncoder.java "VoAACEncoder.java")到指定的包路径(*`com.sinaapp.bashell`*)
  - 使用`VoAACEncoder`类中的三个jni接口进行AAC编码
  
该项目fork了https://github.com/illuspas/VoAACEncoder ，做了一些修改以适配最新的要求。
感兴趣可以参考简书文章链接：https://www.jianshu.com/p/f54f0209a3ed
