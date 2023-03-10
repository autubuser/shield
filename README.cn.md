# PC电脑屏蔽指定网站教程
#
>  *  [English | 英文](https://github.com/autubuser/shield/)
#
## `为什么要屏蔽恶意网站？`
>  * 如今电脑在家庭以及办公场所都非常普及，在网上可以浏览各种形形色色的网站，其中也不乏多数优秀网站，但也不存在不少对电脑存在安全，或者影响身心健康的网站，所以我们需要屏蔽掉一些恶意广告网站或者家长为了孩子健康成长需要屏蔽掉一些不良信息网站或游戏网站等等

#
## `我们要如何屏蔽恶意网站？`
#
>  ###  `Windows 屏蔽方式`
> 1. 键盘快捷键 <kbd>win</kbd> + <kbd>R</kbd> 呼出 运行/终端
> 
> 2. 然后键入 "hosts" 文件路径 "hosts" 文件所在目录
```javascript
C:\WINDOWS\system32\drivers\etc
```
> 3. 打开 "etc" 文件夹后，在 "hosts" 文件名上点击右键，然后点击 "打开方式"，之后再选择使用 "记事本" 方式打开
> 
> 4. 在文件最下方添加一行 127.0.0.1 + 需要屏蔽的网址，或 0.0.0.0 + 需要屏蔽的网址即可（前面的IP地址和右侧网址之间用空格隔开）

#
>  ###  `Macos 屏蔽方式`
> 1. 打开 "应用程序"，然后 "实用工具"，最后打开 "终端"
> 
> 2. 打开 "hosts" 文件，输入以下命令，然后按 <kbd>Enter</kbd> ：在主 "终端" 窗口中编辑 "hosts" 文件
```javascript
sudo nano -e /etc/hosts
```
> 3. 在文件最下方添加一行 127.0.0.1 + 需要屏蔽的网址，或 0.0.0.0 + 需要屏蔽的网址即可（前面的IP地址和右侧网址之间用空格隔开）
> 
> 4. 按 <kbd>ctrl</kbd> + <kbd>O</kbd> 保存，然后按 <kbd>ctrl</kbd> + <kbd>X</kbd> 关闭文件
#
> ## `注意事项`
> * 不要带上 "http://"，例如，如果你想屏蔽对 "google" 的访问，这一行应该是
```javascript
127.0.0.1 www.google.com
```
> * "Hosts" 文件只检查你输入的绝对ULR，例如: "google.com" 不要复制粘贴其他文档，这样可能会引入不可见字符，从而影响文本发挥作用
> 
> * 再次打开 "hosts" 文件，并删除想要取消屏蔽的URL条目,保存、退出即可恢复访问
#
> ## `有问题反馈`
> 在使用中有任何问题，欢迎反馈给我，可以在仓库留言来跟我交流
#
> ## `Star`
> 如果你喜欢我的作品，希望能 "Star" 支持一下。
> 
> 如果您发现有新的需要屏蔽的恶意网址,也欢迎 `提交代码` 或者 `留言`,添加进我们的屏蔽信息共享目录中,为优化营造绿色网络环境贡献你的一份力量!

#
> ## ```"恶意"网址列表```
> 你可以直接复制 "hosts" 文件中的数据添加到你本地的 "hosts" 文件末尾，或者直接下载 "hosts" 文件进行替换，如果遇到问题，你可以 "Google" 或者 "百度" 搜索解决
>
> ### `说明一下:`
> * 我们罗列的`网址`信息并不代表全部它就是存在`恶意`的,部分只是我们认为它可能不太适合被小孩接触到,如有冒犯或者你觉得被误判,请联系我,我将会对其进行删减!
>
> ### `温馨提醒[免责声明]:`
> * 任何系统操作都存在一定的风险，如果你对系统不够熟悉或者没有准备好，建议你不要进行任何修改操作，避免系统遭到破坏导致功能无法正常使用，这里只提供一个解决屏蔽不良信息网址的方法，你尝试修改操作表示你认同并了解这些操作可能带来的一切风险及后果，作者不对产生的任何后果负责!
#
> ## `写在最后:`
> * 我们无法将所有的不良网址都罗列添加到封禁列表，但是我们能封禁一条，未成年或者其他人面对这些 `"不良信息"` 污染的可能性就减少一份！营造绿色上网环境，绿色健康生活，平时多带孩子游玩运动，参与各种活动，多传输积极向上的生活态度，正面引导!
#
> ### `如果你有更好的屏蔽这些信息的方法，也欢迎分享贡献出来，感谢！`
#
