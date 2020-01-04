# 马原刷题工具
最近考试周，用了一些马原word题库，觉得看起来有点不顺手，就稍微改造了一下，写了一个刷题工具出来（笑

## Directory structure

```c++
.
├── archive					//数据文件夹
│   ├── data				//json题库
│   └── flag				//当前进度
├── mayuan or mayuan.exe	//主程序
└── README.md				//说明文档
```



## Usage

+ linux

    ```bash
    git clone https://github.com/jeasonlau/mayuan-test
    cd ./mayuan-test
    sudo chmod +x ./mayuan
    ./mayuan
    ```
    
+ windows

  下载该仓库，下载release中打包好的程序放入仓库根目录，双击运行


## Notice

+ 刷题工具采用顺序刷题，请尽量使用`exit`退出:

  ```bash
  请输入答案:exit
  ```

  以确保保存您的刷题进度。

