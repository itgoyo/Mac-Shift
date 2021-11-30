# b站视频地址： https://www.bilibili.com/video/BV1Zg4y1v7fc/   

# Mac-Shift
Mac使用shift快速切换输入法，程序员的输入法的代码利器

首先要下载一个修改键位的软件`Karabiner-Elements`,下载地址:https://pqrs.org/osx/karabiner/

- Karabiner改键位把 `left-shift`改成`f17`

![改建](/karabiner_keymps.png)
- `系统偏好设置`-`键盘`-`快捷键`-`输入法`

把`选择上一个输入法`改成`F17` (也就是按一下键盘左边的shift即可)

![F17](/keybord.png)

当然了这样子的方法不是最完美的，就是当你的组合快捷键要用到shift的时候，你的左边shift是没有用的，因为它的键位一就那个被改成了F17，所以只能用右边的shift来操作。以上只是本人的做法当然如果你有更好的方法可以和我分享一下。我的IDE使用到shift的组合键并不多，所以这么改基本能满足我的日常开发

本人使用的是`百度输入法`，因为百度输入法，会有一个输入法的悬浮窗口，如果是搜狗的话并没有这个，所以不方便查看当前是什么输入法。
对了`百度输入法`设置里面的shift切换输入法一定要关掉，不然就和自定义的shift功能冲突了，会出现3种情况，所以为了shift能自然的切换输入法，请把百度输入法自带的shift的选项关掉

![](/mac_shift.gif)

# 注意新增长按短按shift的功能
详细请查看：https://github.com/itgoyo/HHKB-Config
