# KBase
键值对数据库.


# TODO
1. string
2. bitmap
3. max heap
4. list
5. set
6. zset
7. lock
8. bloom filter（布谷鸟过滤器）
9. 写命令日志，写日志可以有异步队列写，完全没有同步，正常关闭服务器等待队列为空才停机
10. 更好的io模型和线程调度优化，垃圾回收线程，假性删除，信号通知
11. redis协议支持
12. 慢执行记录 （数据，命令，时间，耗时，IP信息）
13. dump log
14. 客户端分析工具
15. 集群模式 一致性哈希
16. 高可用的支持