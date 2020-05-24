# lzhp.github.io

## 初始化

1. 安装npm。

    到 [nodejs网站](https://nodejs.org/en/download/) 下载nodejs安装文件，选择合适版本进行安装，安装完毕后，可以执行`npm -v`，确认安装是否成功。

2. 安装hexo。

    执行`npm install -g hexo-cli`，安装hexo。

3. clone 本项目。

    `git clone git@github.com:lzhp/hexo.git`

4. 安装 Next 主题。

    ``` shell
    cd hexo
    git clone https://github.com/next-theme/hexo-theme-next themes/next
    ```

    如果忘记执行本步骤，会导致页面空白，没有任何内容。

5. 初始化项目。

    目录下，执行`npm install`，执行完毕后，即可执行下边操作。

## Quick Start

### Create a new post

``` bash
 hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
 hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
 hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
 hexo deploy
```

## 引入Next主题

### 下载及使用

Next使用说明：<https://theme-next.iissnan.com/getting-started.html>

### 修改next的设置

项目的配置文件位置：`source\_data\next.yml`，会覆盖`theme\Next`目录下的配置文件

More info: [Deployment](https://hexo.io/docs/deployment.html)
