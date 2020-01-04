# 马原刷题工具
最近考试周，用了一些马原word题库，觉得看起来有点不顺手，就稍微改造了一下，写了一个刷题工具出来（笑

## Directory structure

```c++
.
├── archive //数据文件夹
│   ├── data //json题库
│   └── flag //当前进度
├── mayuan or mayuan.exe //主程序
└── README.md //说明文档
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

  下载该仓库，下载release中打包好的程序放入仓库根目录，双击`mayuan.exe`运行

