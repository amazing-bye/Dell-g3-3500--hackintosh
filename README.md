# Dell-g3-3500-i7-10870h--hackintool
## 基础配置
* CPU i7-10870h
* 显卡 RTX2060（无解）+ Intel UHD630
* 无线网卡 bcm94360z3
* 硬盘 三星980


## 目前问题
* DRM问题:因为独显没法加载，目前Netflix播放、AppleMusic的无损音乐都有问题
* 睡眠问题:目前通过补丁让usb唤醒失效了，所以只能通过笔记本键盘唤醒，且唤醒后可能会发烫，不知道是不是唤醒过程又把独显启用了
* 意外重启:[IGPU] error: SafeForceWake acknowledgement never received on MEDIA domin...
* 雷电（没有雷电设备，暂未测试）
* 声卡：外放还行，但是麦克风不能用（智音），建议搞个外置声卡
* trim:升到了0.7.9，为了开机加速，已经设置了Setapfstrimtimeou为0，但是不知道trim究竟有没有开


## 声明
* clone了别人的再进行了相应的修改
* 三码还没有设置，这个百度搞一下很快（机型我选了mbp16,4的）
