

VM上的redis的绝对路径/home/wjx/redis-7.2.0/src

在redis客户端通过-a参数连接redis服务端不安全(会在命令历史中留下您的密码。如果其他人运行`history`命令，他们可以获得您的Redis密码。这是不安全的！).通过先连接上redis-server,再通过AUTH来输入username和requirepass来进行授权

Redis中KEYS(?,*)命令类似于MySQL的LIKE(_,%)通配符

Redis的TTL命令查看键的有效期剩余时间,查询的值为-2,代表键已经被移除;查询的值为-1,代表永存

![image-20231026112136427](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20231026112136427.png)

![image-20231026112615889](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20231026112615889.png)

![image-20231026152334930](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20231026152334930.png)

![image-20231026152401128](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20231026152401128.png)

![image-20231026153134086](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20231026153134086.png)

![image-20231029093535553](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20231029093535553.png)