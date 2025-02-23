sdcv-dict README
#+BEGIN_SRC org

sdcv-dict - A Collection of Dictionaries for sdcv
** 简介

这个仓库提供了一系列适用于 sdcv（Stardict 命令行版本）的字典文件。sdcv 是一个轻量级的命令行工具，用于查询离线字典，而本项目旨在为用户提供方便的字典资源，支持多种语言和主题。

** 功能

提供多种语言的字典文件，兼容 sdcv。
易于安装和使用。
定期更新字典内容（如果适用）。
** 安装

确保已安装 sdcv:
#+BEGIN_SRC sh

对于 Debian/Ubuntu
sudo apt-get install sdcv

对于 macOS（通过 Homebrew）
brew install sdcv
#+END_SRC

克隆本仓库:
#+BEGIN_SRC sh
git clone https://github.com/boxmaking/sdcv-dict.git
#+END_SRC

将字典文件移动到 sdcv 的默认字典目录（通常是 ~/.stardict/dic）:
#+BEGIN_SRC sh
mkdir -p ~/.stardict/dic
cp -r sdcv-dict/dict/* ~/.stardict/dic/
#+END_SRC

** 使用方法

在终端中运行以下命令来查询单词：
#+BEGIN_SRC sh
sdcv <word>
#+END_SRC

例如：
#+BEGIN_SRC sh
sdcv hello
#+END_SRC

** 字典列表

目前包含以下字典（根据实际文件更新）：

目前我仅仅使用了
=stardict-cdict-gb-2.4.2=
这一个字典，其他的我没测试，也懒得去测试，感觉有的失效了。

** 贡献

欢迎提交 Pull Request 或 Issue 来添加新的字典文件或改进现有内容！请确保字典文件符合 Stardict 格式。

** 许可证

本项目未采用许可证 我也找不到原作者的许可证。

** 联系

有问题或建议？请通过 GitHub Issues 联系我！
#+END_SRC
