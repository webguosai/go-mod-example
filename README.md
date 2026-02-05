## 推送

1. 在github创建仓库：https://github.com/webguosai/go-mod-example

   ```bash
   # 仓库中执行，再推送到github
   go mod init github.com/webguosai/go-mod-example
   ```

2. 打开 https://pkg.go.dev/github.com/webguosai/go-mod-example 页面进行提交

## 使用

```bash
go get -u github.com/webguosai/go-mod-example
```

```go
package main

import (
    "fmt"
    "github.com/webguosai/go-mod-example/core"
)

func main() {
    fmt.Println(core.GetConfig())   // 调用 core 包中的 GetConfig 函数
}
```
