# 白诘草话-番外篇- 津名川家的圣诞节 汉化补丁

在 Releases 中下载补丁，把其中内容复制到游戏文件夹下，打开 sirotume\_ex\_chs.exe 启动游戏。

## Staff

程序：scientificworld

翻译：scientificworld

校对：Misaka13514

润色：MujiTogawa

测试：Misaka13514、MujiTogawa

特别感谢：arc\_conv 开发者 w8m

## Thoughts

### scientificworld

第二次做汉化了，本次依然是短篇，祝各位游玩愉快。以及，圣诞快乐。

@Misaka13514 和 @MujiTogawa 在校对润色过程中对我的原文本做了很大优化，在这里表示感谢。

这次在程序体积上做了改进，至少不像上次一样把整个 frida 运行时搬来了不是……

### Misaka13514

### Muji Togawa

在百忙的备考（摸鱼）时间中，被 @scientificworld 摇来，第一次参与作品汉化。<br>
虽说心中满是欣喜，但责任感也随之而来，这确实是一件复杂的事啊。<br>
日后我也应该会更多地参与到Van♂illa组的汉化工作中（）

和 @Misaka13514 & @scientificworld 不厌其烦地咬文嚼字是件愉快的事~<br>
虽说是短篇作品，但也花费了不少的时间和精力才完成汉化。<br>
祝各位游玩愉快~ 若翻译有不妥之处还请斧正。

圣诞快乐。

## Build

1. 将脚本转为适当的编码（UTF8 转 GBK）
2. 提取原封包内容（可使用 crass 或 arc\_conv）并把汉化文件中不包含的部分复制进来
3. 使用 arc\_conv 重新封包，命令示例：`arc_conv --pack repipack N N.dat 2 1`。**不要随意改动文件夹名称，会导致游戏读取封包失败！**
4. 使用 RisohEditor 等工具汉化菜单栏文本
5. 把 exe 改名为 sirotume\_ex\_chs.exe，并使用 x32dbg 导入补丁、修补文件

## FAQ

### 启动时提示需要安装 DirectPlay

直接取消即可，不影响游戏运行。

也可以直接取消勾选菜单栏中的 配置 - 系统详细设置 - 在启动游戏时进行系统诊断。

### 报错提示 File I/O Error

请保证路径中仅有英文字符。

## Copyright

修改后的文本和 x64dbg 补丁以 Unlicense 许可证授权，属于公有领域；其余所有部分版权归 Littlewitch 所有。
