# Cowboy.WebSockets
Cowboy.WebSockets is a C# based library for building WebSocket services.

- WebSocket [[RFC6455]](https://tools.ietf.org/html/rfc6455)
- WebSocket Client for [Unity](http://unity3d.com/)
修改了原作者关于RFC协议中 数据压缩乱码的错误
修改了心跳包模式错误
修改了permessage-deflate 请求下自动扩展server_no_context_takeover 和 client_no_context_takeover子协议
兼容 ie ff chrome等主流浏览器。
