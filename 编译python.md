# 编译python文件

python文件分为`.py`、`.pyc`、`.pyo`三种文件

- `.py`:原始的python文件，解释执行。
- `.pyc`:编译后的二进制文件，运行速度比解释执行快、
- `.pyc`:经过优化的编辑文件。


1. 编译`.pyc`文件,成为编译文件
```python
import py_compile
py_compile.compile("1.py")
```
2. 编译`.pyo`文件，成为编译文件。
```shell
python -O -m py_compile 1.py
```
