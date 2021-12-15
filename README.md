# ventoy #一键式安装系统
我的ventoy配置文件,当前适配 ventoy-1.0.24

# 使用方法
首先 [安装ventoy](https://www.ventoy.net/cn/doc_start.html "安装ventoy")

然后 在 ventoy U盘 第一分区执行
```
git clone --depth 1 https://github.com/ghostry/ventoy.git
mkdir iso
```
iso文件都放在iso目录中

# 定制内容
* 主题
* 只在iso目录中搜索镜像文件
* 集成 [ventoy_vhdboot.img](https://www.ventoy.net/cn/plugin_vhdboot.html "ventoy_vhdboot.img")
* 集成 [ventoy_wimboot.img](https://www.ventoy.net/cn/plugin_wimboot.html "ventoy_wimboot.img")
* 自定义菜单
 1. 查找并启动系统(EFI)
 2. 进入UEFI配置
