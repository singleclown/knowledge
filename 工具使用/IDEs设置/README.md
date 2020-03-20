### IDEs' Setting

1. There is **WebStorm** settings. I exported `.jar` to make sure settings in my workplace and my PCs are the same.

    [webstorm.jar](https://raw.githubusercontent.com/realgeoffrey/knowledge/master/工具使用/IDEs设置/webstorm0320.jar)(PhpStorm can use too)
2. **Help -> Edit Custom VM Options** can change the memories for the IDE.

>Chinese Language Pack：please go to [jetbrains-in-chinese](https://github.com/pingfangx/jetbrains-in-chinese) (or [WebStorm-Chinese](https://github.com/ewen0930/WebStorm-Chinese), [PhpStorm-Chinese](https://github.com/ewen0930/PhpStorm-Chinese), or [PyCharm-Chinese](https://github.com/ewen0930/PyCharm-Chinese)).

3. （Windows）Terminal的vi乱码解决办法：

    在Git安装目录下的etc目录下的bash.bashrc文件（如：`C:\Program Files\Git\etc\bash.bashrc`），最后一行添加：

    ```text
    export LANG="zh_CN.UTF-8"
    export LC_ALL="zh_CN.UTF-8"
    ```
4. IDE错误（如：无法搜索文件等）的解决办法：

    点击File,选择Invalidate Caches/Restart...
