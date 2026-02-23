## 使用方法

### 检查单个 URL

```bash
CurlX -u https://www.example.com
```

### 从文件批量检查 URL

创建一个文本文件（如 `urls.txt`），每行一个 URL：

```
www.baidu.com
https://www.google.com
www.github.com
```

然后运行：

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
