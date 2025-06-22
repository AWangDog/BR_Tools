# BR_Tools

## 介绍
+ 恶魔轮盘赌的弹药记录工具

## 启动参数
+ background : 静默启动
+ run : 启动时启用

## 打包命令
``` batch
pip install nuitka
```
``` batch
python -m nuitka --standalone --windows-console-mode=disable --mingw64 --output-dir=out --enable-plugin=pyside6 --windows-product-version=1.0 --remove-output --product-name=BRTools --file-description=BRTools --output-filename=BRTools --windows-icon-from-ico=bin\icon.ico main.py
```
+ 需要的库
``` batch
pip install PySide6
```
