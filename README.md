## 命令行参数

| 参数 | 简写 | 说明 | 默认值 |
|------|------|------|--------|
| `--file` | `-f` | 输入文件路径，每行一个 URL | - |
| `--url` | `-u` | 要检查的目标 URL | - |
| `--timeout` | `-t` | 每个请求的超时时间（秒） | 5 |
| `--help` | `-h` | 显示帮助信息 | - |

## 使用方法

### 检查单个 URL

```bash
CurlX -u https://www.example.com
```

### 从文件批量检查 URL

```bash
CurlX -f urls.txt
```

### 设置超时时间

默认超时时间为 5 秒，可以使用 `-t` 参数自定义：

```bash
CurlX -f urls.txt -t 10
```

### 查看帮助信息

```bash
CurlX -h
```
