## 一 环境配置

### 1、git
#### 下载git
> 从（http://git-scm.com/download/）下载最新git版本即可。
####  安装
>按照提示安装即可。安装完成后，在终端中输入git --version,如果输入git版本，即说明按抓过成功。


### 2、node.js 
>安装node.js之前，我们先来安装nvm，这是一个能让我们在一台及其上安装和切换不同版本node的工具。
>我们打开https://github.com/creationix/nvm，找到它的cURL（目前最新地址是curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash ），然后坐等安装完成。完成后 ，不要着急，复制执行最后两行代码

    export NVM_DIR="$HOME/.nvm"
    [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

>配置好环境变量，就OK了。在终端中输入nvm，出现一堆东西，说nvm就安装好了。
#### nvm使用
##### nvm ls-remote 
>列出所有可用的node版本号。
##### nvm install 版本号
>安装制定版本号
##### nvm ls
>查看已经安装的版本号
##### nvm use 版本号
>切换版本号。注意切换效果是全局的。
##### nvm current
>查看当前正式使用的版本号

### npm 
>一般安装好node.js之后，也就安装好npm了。在终端中输入npm -v,查看当前npm版本。npm默认从国外的资源获取和下载安装包，有时候会速度比较慢。在命令行中允许
    npm config set registry https://registry.npm.taobao.org
即可设置从国内镜像获取资源。
>npm 安装完成后，即可愉快地安装所需的任意node.js的第三发包了。


## 编辑器的安装使用
>这里选择的编辑器是vscode。进入https://code.visualstudio.com下载安装即可。






