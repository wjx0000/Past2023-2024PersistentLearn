# HTTP/206响应

最后一条会话返回了HTTP/206 “Partial Content”响应.这种响应是在客户端表明自己只需要目标URL上的部分资源的时候返回的.这种情况经常发生在客户端继续请求一个[未完成的下载](http://blogs.msdn.com/b/ieinternals/archive/2011/06/03/send-an-etag-to-enable-http-206-file-download-resume-without-restarting.aspx)的时候(通常是当客户端加载一个体积较大的嵌入文件,比如视屏或PDF文件),或者是客户端尝试实现[带宽遏流](http://msdn.microsoft.com/en-us/library/windows/desktop/aa362708(v=vs.85).aspx)的时候.