# Downloader
下载文件

> - Netroid
```
Netroid库使用，实现多任务断点单线程下载
```

> - Downloader
```
Http协议下载文件，实现多任务断点多线程下载
存在问题：
    下载状态需要重新修正
    下载大文件时一直GC
```

1. 断点下载
2. 本地文件检测
3. 存储空间检测
4. 即时启动，暂停
5. 单下载线程三次重连

