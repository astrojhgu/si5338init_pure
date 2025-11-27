# 用法
1. 安装[bluespec 编译器](https://github.com/B-Lang-org/bsc)
2. `git clone https://github.com/astrojhgu/si5338init_pure`
3. `cd si5338init_pure`
4. 如果必要，修改Si5338.bsv头部的三个定义，包括时钟频率、串口波特率、`mem`文件名
5. `make`
6. 复制`build`目录下的相关文件到vivado工程目录
7. 复制必要的`bluespec`预制`.v`文件到vivado 工程目录（使用`bsc -help`命令查看预制`.v`文件的路径）
8. 生成`si5338`的`mem`文件，并导入vivado工程
