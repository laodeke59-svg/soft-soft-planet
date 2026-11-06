# 软软星球 · Windows 桌面软件项目

这是把原来的史莱姆 ASMR 网页小游戏封装成 Windows 桌面应用的项目文件。
运行后是独立窗口，不需要输入网址；游戏页面和交互资源都在本地，运行游戏时不需要联网。

## 最终会生成什么
- `软软星球 Setup 1.0.0.exe`：Windows 安装程序
- `软软星球 1.0.0.exe`（portable）：便携版，下载后双击运行，不需要安装

## 最简单的生成 EXE 方法（使用 GitHub 云端 Windows 编译）
1. 登录 GitHub，创建一个新的空仓库，例如 `soft-soft-planet`。
2. 将本文件夹里的全部文件上传到仓库根目录（包括 `.github` 文件夹）。
3. 打开仓库的 **Actions** 页面，选择 **Build Windows App**。
4. 点击 **Run workflow**，再点击绿色的 **Run workflow**。
5. 等待运行完成，点开成功的任务，在页面底部的 **Artifacts** 下载 `soft-soft-planet-windows`。
6. 解压下载的 Artifact，即可看到 `.exe` 文件。

## 注意
- 这是 Windows x64 桌面程序。
- 首次运行未签名的个人作业程序时，Windows 可能显示 SmartScreen 提示；只有确认文件来自自己的项目构建后再选择继续运行。
- 生成的 EXE 尚未经过微软代码签名，不代表恶意软件。
- 如果只需要提交项目源码，可直接提交本文件夹 ZIP；如果老师要求可运行软件，请提交构建后得到的 EXE。
