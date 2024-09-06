# CMD-Grid <img src="./image/icon.png" width="30" height="30">

### CMD-Grid，简单配置后即可一键启动，自由设定行列数量，让所有程序输出一目了然，轻松监管程序状态。

# 界面效果图

[![photo](./image/example-1.jpg)](./image/example-1.jpg)


[![photo](./image/example-2.jpg)](./image/example-2.jpg)

# 配置示例
提供界面配置及json配置
```
[
  {
    "label": "程序标签1",
    "list": [
      [
        {
          "cmd": "name-1.bat",
          "cwd": "D:/my-project/",
          "title": "程序1"
        },
        {
          "cmd": "node index",
          "cwd": "D:/my-project/",
          "title": "程序2"
        }
      ],
      [
        {
          "cmd": "name-2.bat",
          "cwd": "D:/my-project/",
          "title": "程序3"
        }
      ]
    ]
  }
]
```
[![photo](./image/example-3.jpg)](./image/example-3.jpg)