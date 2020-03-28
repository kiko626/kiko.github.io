---
layout: post
title: MPV 快捷键
category: project
description: 03-28 | MPV Hot key.
---

字幕

    v : 切换字幕可见性。

    j 和 J : 切换字幕。

    x 和 z : 调节字幕显示延迟，单位100ms。

    u : 切换SSA/ASS字幕正常样式/无样式。

    r 和 t : 上下移动字幕位置。

    [ 和 ]： 载入上一个/下一个字幕。受到一些限制，可能不会总是好使。

    V : 切换字幕VSFilter方面兼容模式。



图像

    s : 截图。

    S : 不带字幕截图。

    Ctrl s : 按照屏幕尺寸，带有OSD的截图。

    A : 切换视频宽高比。

    f : 切换全屏状态。

    ESC : 退出全屏。

    _ : 切换视频轨道。

    T : 切换窗口总是在前面状态。

    w 和 e : 提升/降低摇摄扫描（pan-and-scan）范围

    o 或者 P : 显示进度条，已播放时间，总时间

    O : 切换正常和带有播放时间/持续时间的OSD状态。

    I : OSD中是否显示文件名。



音轨

    Ctrl + 和 Ctrl – : 调节音轨延迟，单位100ms。

    9 和 0 : 增大/减小音量。

    m : 静音。

    # : 切换音频轨道。




播放

    左/右方向键 : 快进/后退5秒钟。shift+左右方向键可以以1秒为进度调节。

    上/下方向键 : 快进/后退1分钟。shift+左右方向键可以以5秒为进度调节。

    l : 设置A-B循环点。详细见ab-loop命令。

    L : 切换是否无限循环。

    { 和 } : 半倍/双倍速度播放。

    BACKSPACE键 : 重制正常播放速度。

    < 和 > : 播放列表后一个/前一个。

    ENTER键 : 播放列表后一个。

    p / SPACE键 : 暂停。

    . : 按下一次会暂停，再次按下会进入到下一帧画面，视频依然是暂停状态。

    , : 按下一次会暂停，再次按下会进入到上一帧画面，视频依然是暂停状态。

    q : 停止播放并立即退出。

    Q : 停止播放并立即退出，但是可以记录上次视频播放位置。

    PGUP 和 PGDWN : 开始上一个/下一个章节。

    Shift+PGUP and Shift+PGDWN : 快进/后退十分钟。

    d : 开启/关闭隔行扫描（去交错）。




(The following keys are valid only when using a video output that supports the corresponding adjustment, or the software equalizer (–vf=eq).)

    1 and 2
    Adjust contrast.
    3 and 4
    Adjust brightness.
    5 and 6
    Adjust gamma.
    7 and 8
    djust saturation.
    Alt+0 (and command+0 on OSX)
    Resize video window to half its original size.
    Alt+1 (and command+1 on OSX)
    Resize video window to its original size.
    Alt+2 (and command+2 on OSX)
    Resize video window to double its original size.
    command + f (OSX only)
    Toggle fullscreen (see also –fs).
    command + [ and command + ] (OSX only)
    Set video window alpha.
