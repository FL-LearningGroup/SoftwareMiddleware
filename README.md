# SoftwareMiddleware

SoftwareMiddleware

# Message Quence Middleware

## Why

为了解决高峰时期，服务器处理消耗过高，处理请求变慢，给客户端造成延迟。

## How
1. Client ---send operation message---> MQM

2. Client <---Immediately back   ---> MQM

3. MQM  ---async get operation message---> Server

## Where
1. 订单系统
