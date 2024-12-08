# 白诘草话-番外篇- 津名川家的圣诞节 汉化补丁

WIP

## Staff

TODO

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
