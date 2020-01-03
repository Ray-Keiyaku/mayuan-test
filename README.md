# 马原刷题工具
最近考试周，用了一些马原word题库，觉得看起来有点不顺手，就稍微改造了一下，写了一个刷题工具出来（笑

## Usage

```bash
git clone https://github.com/jeasonlau/mayuan-test
cd ./mayuan-test
sudo chmod +x ./mayuan
./mayuan
```

## Notice

+ 刷题工具采用顺序刷题，请尽量使用`exit`退出:

  ```bash
  请输入答案:exit
  ```

  以确保保存您的刷题进度。

+ windows用户使用

  ```python
  - os.system('clear')
  + os.system('cls')
  ```

  

