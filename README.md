精简了官方Zxing的DEMO，将程序调整为竖屏可用，且能正常识别条码

使用方法： 项目的gradle中增加：
allprojects {
    repositories {
        google()
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}

app 的gradle 中增加
implementation 'com.github.fightgod2004:ZxingModule:v1.0'
