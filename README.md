# 【RunAny】一劳永逸的快速启动工具 v2.0


只需配置一个自定义程序菜单，就可以快速启动任何电脑任何路径的程序😎

家里和公司电脑还是笔记本都使用同一套配置，云端同步就更是如虎添翼！


RunAny追求就是：<u>**一劳永逸**</u>
---

[版本更新历史](#ver)

---

RunAny启动软件就跟打字一样高效方便（如<kbd>\`</kbd>为热键）：

- \`ww就是work分类下的word
- \`aw就是app下的Wiz
- \`fw就是file下的WinRAR

(PS:输入\`可以<kbd>Win</kbd>+<kbd>\`</kbd>输入)

---


【自定义树形菜单配置方法：】
* 前加-为1级目录名,--为2级以此类推，如：`-app`、`--img`
* 单独一个-是1级分隔符，--2级亦是如此，如：`-`、`--`
* 前加;可以注释暂时不需要用的，如：`;cmd.exe`
* 每个菜单名首字母(或用&指定任意)便是启动快捷键，如：`IE(&E)`快捷键是e
* 可用竖|在添加别名前缀,便会显示自定义菜单名，如：`TC|Totalcmd.exe`会显示TC
* 如果有多个同名应用，可加上全路径指定运行
* 运行除exe后缀之外的，也可用全路径来实现

---

建议：hui0.0713@gmail.com

讨论QQ群：[3222783【AutoHotkey高级群】](https://jq.qq.com/?_wv=1027&k=43uBHer)、[271105729【QZ/VimD/TC/AHK】](https://jq.qq.com/?_wv=1027&k=43u3DuR)、[493194474【软客】](https://jq.qq.com/?_wv=1027&k=43trxF5)

支持RunAny：![支付宝](https://raw.githubusercontent.com/hui-Zz/RunAny/master/支持.jpg)

---

## <a name="ver">版本更新历史</a>

### v2.0 正式更名为RunAny，易用性大幅提升，兼容菜单文件编辑和GUI界面编辑

### v1.9 自定义配置优化

+ 添加Everything路径配置选项
+ 添加显示热键自定义配置选项
+ 菜单配置现在单独保存在RunMenuZz.ini
+ 只有在用户设置与默认不同才将配置保存在注册表HKEY_CURRENT_USER\Software\RunAny
+ 添加重置按钮，清除注册表配置，不留痕迹

### v1.8 集成Everything自动检索程序，从此程序随便放目录都能用RunMenu运行了😀
