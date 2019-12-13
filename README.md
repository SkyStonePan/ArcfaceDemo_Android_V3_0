# ArcFaceDemo For ArcFace 3.0
Arcface3.0的Android Demo

>  该工程的库下载于2019/12/16，一年后活体功能会过期，需要在虹软视觉开放平台重新下载


#### 一、环境要求
**运行环境**

armeabi-v7a、arm64-v8a

**系统要求**

Android 4.4 (API Level 19)及以上

**开发环境**

Android Studio

#### 二、快速上手
1. 在src->main目录下新建文件夹jniLibs->armeabi-v7a，将SDK包中libs/armeabi-v7a目录下的libarcsoft_face.so和libarcsoft_face_engine.so添加到src->main->jniLibs->armeabi-v7a路径下；<br>

2. 在src->main目录下新建文件夹jniLibs->arm64-v8a，将SDK包中libs/arm64-v8a目录libarcsoft_face.so和libarcsoft_face_engine.so添加到src->main->jniLibs->armeabi-v7a路径下；

3. 在app目录下新建文件夹libs，将arcsoft_face.jar放入app->libs路径下，并依赖进工程

4. 将官网申请sdk获取到的APP_ID和SDK_KEY填入Common->Constants.java

5. 运行app

#### 三、问题指南
详细接入指南可见官网：https://ai.arcsoft.com.cn/manual/docs#/94 ;

常见问题可见SDK中的doc文档ARCSOFT_ARC_FACE_DEVELOPER'S_GUIDE.pdf，或见官网帮助与支持。