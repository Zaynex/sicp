## reference
[Scheme入门教程](http://deathking.github.io/yast-cn/index.html)
[Scheme安装包](http://www.gnu.org/software/mit-scheme/)
[MIT Scheme 的基本使用](http://www.math.pku.edu.cn/teachers/qiuzy/progtech/scheme/mit_scheme.htm)
[sicp中文参考资料](http://www.math.pku.edu.cn/teachers/qiuzy/progtech/)


## 基本演示
1. 打开后其实有两个界面，注意窗口名称分别是 Edwin:"scheme" 和 MIT/GUN Scheme
2. 在Edwin:"scheme"窗口中输入： Ctrl+x, 再按 z
3. 在MIT/GUN窗口中输入 (+ 1 2)
4. 你会得到 ;Value: 3 

## 常用操作
- C-x z （表示按 Ctrl-x 后按 z 键）：从 Edwin 中退到 Scheme 的命令交互状态。此时 Edwin 挂起，可用 (edit) 唤醒挂起的 Edwin，回到挂起前的状态。
- C-x c ：停止 Edwin 并回到 Scheme 的命令交互状态。

- C-x C-z：停止 Edwin 并挂起 Scheme 系统。再次启动 Scheme 将唤醒挂起的 Scheme 系统，回到挂起前的系统状态。

- C-x C-c：停止 Edwin 和 Scheme 系统。
