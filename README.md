# GlimmerU | 微光育行

此项目仅用于备份数据到 Github。

如需在本地端调试或提交代码，请[下载](https://github.com/GlimmerU/GlimmerU.github.io/archive/refs/heads/main.zip)并解压本项目源代码后在**对应目录**下执行以下命令：

```bash
pip3 install -r requirements.txt
```

或者，你也可以选择完全在终端克隆并配置此项目（注意调用终端的目录z）：

```bash
git clone git@github.com:GlimmerU/GlimmerU.github.io.git
cd GlimmerU.github.io
pip3 install -r requirements.txt
```

**建议使用 Pycharm 和虚拟环境进行配置。**

```bash
python3 -m venv venv
source venv/bin/activate
```

配置好环境之后，可以在终端中执行以下命令：

```bash
mkdocs serve
```

即可在本地端( http://127.0.0.1:8000/ )调试和预览，默认端口为 8000。

如果需要构建静态网页，可以执行以下命令：

```bash
mkdocs build
```
生成的内容位于 `/site` 文件夹下
