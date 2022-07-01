# HyperealDriverTest

感谢群友星凌，三木，宇浩喵的赞助

不会写IVRvirualDisplay。魔改了部分Hypereal OpenVR Driver的字节码。

①解压至steamvr/driver目录下

②在steamvr设置内打开高级设置，启动项管理全部勾选

③修改steam/config/steamvr.setting文件，在`"steamvr":{`行的下一行添加内容为`"activeMulitipleDrivers":true,`的新行

感谢小凌瞎玩@bilibili制作的[视频安装教程](http://b23.tv/eUQDddw)

亦有本人简单录制的[安装方法](https://www.bilibili.com/video/bv14Y4y1n7Q9)

[蓝奏云](https://wwt.lanzoub.com/b0d48942b) 密码:6hpk

------

### Changelog:

#### 2022.7.1

- 添加手柄连接状态检测；

- 添加手柄电量检测；

- 添加错误提示（按官方SDK原样提供）；

- 无需点击“是”便可以正常使用手柄；
