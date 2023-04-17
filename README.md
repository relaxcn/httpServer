使用 C++ 11 编写的 HTTP 高性能 Linux 服务器

1. 使用了线程池 +非阻塞 socket + epoll +事件处理(Reactor )的并发模型。
2. 使用了状态机解析 HTTP 请求报文,支持解析 GET 和 POST 请求。
3. 服务器利用数据库实现了用户注册,登录功能,可以请求服务器图片和视频文件。
4. 实现同步/异步日志系统,记录服务器运行状态。
5. 经 Webbench 压力测试可以实现上万的并发连接数据交换。

### 测试截图

![397f380d9fff9031cb9665fb312b423a.png](https://img.gejiba.com/images/397f380d9fff9031cb9665fb312b423a.png)

![5d6b88f34b472b0e34c7062c664323b9.png](https://img.gejiba.com/images/5d6b88f34b472b0e34c7062c664323b9.png)

![493a10c75e4e0f67fd132d41f0e19dd4.png](https://img.gejiba.com/images/493a10c75e4e0f67fd132d41f0e19dd4.png)

![0fe1f45eac0bfd607ef8b593fbc67a94.png](https://img.gejiba.com/images/0fe1f45eac0bfd607ef8b593fbc67a94.png)

![7b8ef17b076c8eca6f0ee433125961e4.png](https://img.gejiba.com/images/7b8ef17b076c8eca6f0ee433125961e4.png)
