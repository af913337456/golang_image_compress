### 编译步骤：
安装golang环境

在控制台输入 go get "github.com/nfnt/resize"

最后 go build imageCompress.go

### 使用方法：
双击 imageCompress.exe，跟随提示即可

### 启动后输出：
```java
请输入文件夹或图片路径:
如果输入文件夹,那么该目录的图片将会被批量压缩;
如果是图片路径，那么将会被单独压缩处理。
例如：
C:/Users/lzq/Desktop/headImages/ 75 200
指桌面 headImages 文件夹，里面的图片质量压缩到75%，宽分辨率为200，高是等比例计算
C:/Users/lzq/Desktop/headImages/1.jpg 75 200
指桌面的 headImages 文件夹里面的 1.jpg 图片,质量压缩到75%，宽分辨率为200，高是等比例计算
请输入：
```

### Linux 支持

可以自己在 Linux 环境下编译

### Compile Step:

config your golang environment;

go get "github.com/nfnt/resize"

go build imageCompress.go

### How to use：
double click imageCompress.exe,and just follow the tips
