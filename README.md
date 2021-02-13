# ErrorLog
zh-CN | What problems I encountered and how did I solve it (with failed attempts)

# Software


# MacBook
### Cannot fall asleep 无法进入睡眠状态，熄屏后立刻醒来
1. 退出所有APP后重新打开；无效。
2. [这篇文章](https://www.jianshu.com/p/7b55f2bb3cbd)里重置SMC之前的所有方法；无效。
3. [正文之后就看不懂了](https://blog.csdn.net/cneducation/article/details/21217963)
4. [写的看起来很厉害的样子，怕把电脑搞坏就放弃了](https://michaelkummer.com/tech/mac-sleep-fix/)
5. [插拔所有连接的外设并且一一尝试](https://www.cnet.com/news/tackling-macs-that-randomly-wake-from-sleep/)，成功√

结论：连了打印机。


# Other devices
## Kindle 
### 阅读时卡住无法翻页，重启多次未果
0. 今天早上醒来后再次重启了，发现这本书都没有办法打开了。

于是：删除Kindle内这本书的一切文件，包括azw3文件和sdr文件。

1. 重新导入了一遍TXT转为azw3，再次导入，失败。
2. 转成mobi导入，失败。
3. 重新安装calibre并再转换，失败。
4. 只导入txt文件，成功了。
5. 因为这里的txt是直接拖进文件夹的，所以也用拖入的方法试了一下，失败。

此时我导入了用calibre转换的其他txt→azw3，转换时预设相同。结果只有同作者的另一本书有同样的问题。

其他在亚马逊购入的书籍、网上下载的epub/azw3/mobi均没有受到影响。

文件读取失败的时候写的是：
> 文件已损坏，请从官网重新下载。

重新导入后就变成了
> 应用程序出错，无法启动选定的应用程序，请重试。

6. 根据谷歌到的结果，重启了依旧没有结果。
7. 排除了因为气温过低而可能导致的死机问题。

最后的解决办法是：

8. 删除这本书的所有记录和sdr文件，新建立一个txt文档放书，在calibre建立一个新entry，转换成azw3后导入成功了。

# What I have
Laptop: MacBook Pro 16 inch, 2019. 

System: macOS Catalina 10.15.7

Mouse: Logitech MX Master

Kindle: Oasis 3 (2020)
