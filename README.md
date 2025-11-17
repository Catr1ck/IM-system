# IM-system
##### 项目描述：实现了一个基于 Golang 的即时通信系统，支持多用户在线聊天、消息广播、私聊、用户状态管理等功能。
##### 技术栈：TCP Socket、Goroutine、Channel、同步锁（sync.RWMutex）
详细介绍：使用 Goroutine + Channel 处理并发连接与消息广播，通过 sync.RWMutex 保证数据
安全。实现超时强踢、用户名修改、在线用户查询等功能，提升系统可用性。客户端提供命令行交
互界面，支持公聊、私聊等多种模式。
