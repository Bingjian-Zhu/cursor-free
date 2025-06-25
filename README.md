# Cursor Pro 自动化工具使用说明

## 功能说明
实现Cursor无限账号注册。

本项目基于 [@chengazhen/cursor-auto-free](https://github.com/chengazhen/cursor-auto-free) 开源项目进行二次开发，在此特别感谢原作者的无私分享和贡献！

## 下载安装
从 [GitHub Tags](https://github.com/Bingjian-Zhu/cursor-free/tags) 下载最新版本
### 根据你的系统选择对应的版本：
- Windows：直接下载 CursorPro.exe
- Mac（Intel）：选择 x64 版本
- Mac（M系列）：选择 ARM64(aarch64) 版本

## 按照下文配置环境文件，注册邮箱、下载人名数据、修改配置文件，然后运行
1. 前往 [注册邮箱](https://www.2925.com/login/) 注册账号， 完成邮箱注册流程。
2. 下载人名数据文件[names-dataset.txt](https://github.com/Bingjian-Zhu/cursor-free/blob/main/names-dataset.txt) 并放置在可执行文件同级目录下
3. 下载[.env](https://github.com/Bingjian-Zhu/cursor-free/blob/main/.env)配置文件并放置在可执行文件同级目录下
4. 修改.env文件中的IMAP_USER为注册的邮箱，IMAP_PASS为邮箱密码

#### Windows 用户
直接双击运行 CursorPro.exe

#### Mac 用户
在终端中运行：```./CursorPro```
或直接在访达（Finder）中双击运行

#### Mac 用户额外步骤
打开终端，进入应用所在目录
执行以下命令使文件可执行：
```
chmod +x ./CursorPro
```
如果遇到以下提示
![](./c29ea438-ee74-4ba1-bbf6-25e622cdfad5.png)

点击[这里查看解决方法](https://sysin.org/blog/macos-if-crashes-when-opening/)

#### 验证步骤
- 等待程序自动完成所有操作
- 看到"脚本执行完毕"提示后，重启你的编辑器
- 检查编辑器中显示的账号信息是否与脚本输出的日志账号一致

#### 使用注意事项
- 确保网络连接稳定
- 等待程序自动完成所有操作

## 许可证声明
本项目采用 [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) 许可证。
这意味着您可以：
- 分享 — 在任何媒介以任何形式复制、发行本作品
但必须遵守以下条件：
- 非商业性使用 — 您不得将本作品用于商业目的

## 声明
- 本项目仅供学习交流使用，请勿用于商业用途。
- 本项目不承担任何法律责任，使用本项目造成的任何后果，由使用者自行承担。

