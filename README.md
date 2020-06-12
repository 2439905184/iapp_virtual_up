# iapp_virtual_up
开发中 iapp版vup虚拟主播
目前已经实现了 摄像头图像预览 和悬浮窗 
待解决的问题是如果用悬浮窗显示摄像头内容会 显示不出来
1.使用open cv开源库作为人脸识别
2.调用live2d 官方的sdk来实现虚拟形象展示

3.说明 所有的.iyu文件都是界面文件加iapp的iyu语言 mjava则是原生java模块 
一般比较复杂的逻辑写在mjava模块里 简单的就写在iyu语言里
4.如何构建 下载我上传的.iapp文件并打开iapp软件导入就可以了 然后调用iapp打包
5.由于iapp是特殊的安卓开发软件 里面的文件必须用iapp编译 android studio aapt等是编译不了的.
