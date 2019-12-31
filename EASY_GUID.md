## 提交代码

1. `git commit` 用于提交已经暂存的代码，一般会弹出 message 的输入框，输入信息后确认提交。
2. `git commit -m “message”` 直接带 message 提交。
    当提交的 message 很长或者我们想描述的更清楚更简洁明了一点，我们可以使用这样的格式，如下：

    ```
        git commit -m ‘

        message1

        message2

        message3

        ’
    ```
3. `git commit -a -m “massage”` 将所有已跟踪文件中的执行修改或删除操作的文件都提交到本地仓库。注意这里新加的文件不被添加。
