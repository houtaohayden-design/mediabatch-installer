# 素材批量加工工具安装包

这里是 `素材批量加工工具` 的公开安装包与更新清单仓库。

## 下载

请到 Releases 下载最新版：

https://github.com/houtaohayden-design/mediabatch-installer/releases/latest

Windows 当前提供便携版 zip。下载后解压，双击目录里的 `素材批量加工工具.exe` 即可使用。

## 更新

工具左下角的 `检查更新` 按钮会读取本仓库根目录的 `latest.json`：

```json
{
  "version": "0.2.1",
  "release_url": "https://github.com/houtaohayden-design/mediabatch-installer/releases/tag/v0.2.1",
  "download_url": "https://github.com/houtaohayden-design/mediabatch-installer/releases/download/v0.2.1/mediabatch-v0.2.1-windows-portable.zip",
  "notes": "图片处理和压缩瘦身均支持 KB/MB 目标体积单位；左侧功能菜单新增图标。"
}
```

发布新版本时，只需要创建新 Release、上传新安装包，并同步更新这个文件。
