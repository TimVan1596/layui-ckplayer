# layui-ckplayer

#### 介绍
基于ckplayer视频播放器封装的，适用于layui的扩展组件
ckplayer版本： X2
原插件 [ckplayer 视频播放组件/larryms](https://gitee.com/layui_larryms/larryms)已经很久没有更新，且无法自定义设置，因此自己封装一份

#### 使用说明
![示例图片](https://images.gitee.com/uploads/images/2021/0520/092641_ce350c58_1464254.png "屏幕截图.png")

```
//定义一个变量：videoObject，用来做为视频初始化配置
                var videoObject = {
                    container: '#video', //视频播放器所在div
                    variable: 'player',
                    video: videoUrl, //视频的url地址
                    baseUrl: baseUrl //请求配置json所在目录，默认指向ckplayer下
                };
                var player = new ckplayer(videoObject);//初始化播放器
```


1.新增 baseUrl 属性，作为默认的请求配置json路径  
2.lib包里的ckplayer文件夹是源码文件，拖放至项目中即可使用  
3.example里有示例页面可供参考

#### 详细文档
请参考ckplayer和layui的文档  
[ckplayer文档](https://www.ckplayer.com/manual/)  
[layui插件文档](https://www.layui.com/doc/base/modules.html#extend)


#### 致谢/参考

1. [ckplayer 视频播放组件/larryms](https://fly.layui.com/extend/ckplayer/)
