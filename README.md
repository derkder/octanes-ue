#### 编译源码遇到的报错（vs2022 + ue4.27）
https://blog.csdn.net/qq_59095655/article/details/132896929    
https://blog.csdn.net/qq_39049179/article/details/123736101    
   
#### 用RenderDoc调试
在自己的电脑上先下载RenderDoc  
UE中插件加一个RenderDoc    
运行下拉菜单渲染移动设备预览（这次还遇到一个就是改的管线是OpenFL的mobile的所以要先https://docs.unrealengine.com/4.27/en-US/SharingAndReleasing/Mobile/Android/GettingStarted/）点击运行   
RenderDoc： File -> Attach to就可以搜到现在跑的进程，点击capture就抓到了    
    
#### VisualStudio打断点失败的坑   
就是因为跑的都不是那个管线，要按照这个设置跑的才是那个管线   
https://docs.unrealengine.com/4.27/en-US/SharingAndReleasing/Mobile/Android/GettingStarted/    
