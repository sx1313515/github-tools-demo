# GitHub Tools Demo

这是一个用于演示GitHub工具使用的示例仓库。

## 功能特点

- 简单的HTTP服务器
- 健康检查端点
- Go语言实现

## 使用方法

```bash
# 运行应用
go run main.go

# 访问应用
curl http://localhost:8080

# 健康检查
curl http://localhost:8080/health
```

## API端点

- `GET /` - 返回欢迎消息
- `GET /health` - 健康检查端点