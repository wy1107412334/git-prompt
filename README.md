GIT Prompt for BASH
===================


屏幕截图和文档位于: http://volnitsky.com/project/git-prompt






安装教程
-------

1. 克隆本仓库
    $ git clone https://github.com/wy1107412334/git-prompt.git ~/.git-prompt

2. 启用 git-prompt
    $ vim ~/.profile \
    在里面添加这样的内容： .  ~/.git-prompt/git-prompt.sh

3. 运行 git-prompt
    $ . ~/.profile





git-prompt的配置
---------------

git-prompt.sh 默认会在三个地方寻找配置文件：
```
~/git-prompt.conf
/etc/git-prompt.conf
~/.git-prompt/git-prompt.conf
```


按照上面 **安装教程** 的步骤克隆本仓库的话，那么配置文件就是 `~/.git-prompt/git-prompt.conf`


配置文件中对配置项有详细的描述，看配置文件就可以了





