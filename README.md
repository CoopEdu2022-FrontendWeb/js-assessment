# 令人愉快的测试

~~这里删除了一段没有意义的废话~~

## 如何开始

0. 保证本地有 nodejs 环境

1. 在 Exam/Exam3 中，在当前目录打开终端（确保当前目录是 Exam3）

2. 在终端中输入

    ```git clone https://github.com/CoopEdu2022-FrontendWeb/js-assessment```

3. 回车后，会在当前目录下出现 js-assessment 文件夹

4. 进入 js-assessment 文件夹，在当前目录打开终端，输入：

    ```npm install```
    
    这一步会让项目完成配置

5. 新建 vscode 窗口（new window），打开 js-assessment（保证 js-assessment 是根目录）


6. 安装 live-preview 插件

7. 此时进入项目，打开 tests/runner.html，通过右上方的预览按钮，可以显示出网页
    
    这时网页会有许多错误提示

8. 进入 app/，里面有 arrays.js 等 3 个 js 文件，这些文件就是需要完成的内容
    
    文件里包含了许多函数，完成函数内容后，右侧会自动识别是否成功

9. 例如，在 arrays.js 的第 5 行，添加如下代码：

    ```return arr.indexOf(item, 0);```

    右侧的预览就是出现一个成功的提示

    如果没有，就点一下刷新按钮