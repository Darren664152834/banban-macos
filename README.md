# 伴伴 Mac · 源码与 App 备份

此私有仓库存放 1.4.1 版基础源码和可运行 Mac App 的干净分发包。

## 下载

- [基础源码 ZIP](Banban-Source-v1.4.1.zip)
- [Mac App ZIP](Banban-Mac-v1.4.1.zip)
- [SHA-256 校验值](SHA256SUMS.txt)
- [完整上传清单](upload-manifest.json)
- [隐私检查说明](PRIVACY-CHECK.md)

Mac App 适用于 Apple Silicon，最低 macOS 13；本机自动抠图需要 macOS 14。解压 App ZIP 后可得到 `伴伴.app`。这是临时签名构建，没有 Apple Developer ID 公证。

## 使用源码

下载并解压源码 ZIP，进入其中的 `banban-macos` 文件夹。安装 Xcode Command Line Tools 后运行：

```sh
./build.sh
```

执行自动检查：

```sh
./test.sh
```

源码包含默认人物素材管理、20 个表情动作、角色与场景、AI 接口配置、独立桌宠、照片／视频自适应展示和悬浮退出入口。源码包内 README 说明详细用法。

## 不含个人运行数据

源码和 App 不包含个人 API Key、用户导入照片／视频、聊天记录、已保存的人设或本机配置。API Key、照片和设定由使用者运行 App 后自行填写／导入，保存在本机用户资料目录。

源码中的测试值为虚拟值，唯一测试视频为无人物、无音轨的合成色彩图案；程序图标为系统爱心符号。分发包未附带本地工作截图、日志、编译缓存或用户资料文件。
