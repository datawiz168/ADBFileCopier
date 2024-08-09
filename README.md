# ADBFileCopier
ADB模式下海量手机图片文件迁移到电脑


要下载和安装 ADB（Android Debug Bridge），您可以使用以下官方链接。ADB 是一个命令行工具，用于与安卓设备进行通信，适用于多种操作系统。

### 官方下载链接
- **Windows**: [下载链接](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)
- **Mac**: [下载链接](https://dl.google.com/android/repository/platform-tools-latest-darwin.zip)
- **Linux**: [下载链接](https://dl.google.com/android/repository/platform-tools-latest-linux.zip)

### 下载和安装步骤
1. **下载**：
   - 点击上面的链接，下载适合您操作系统的压缩包。

2. **解压缩**：
   - 下载完成后，将压缩包解压缩到一个您容易找到的目录。例如，`C:\platform-tools`（Windows）或 `~/platform-tools`（Mac 和 Linux）。

3. **配置环境变量**：
   - **Windows**：
     1. 右键点击“计算机”或“此电脑”，选择“属性”。
     2. 点击“高级系统设置”。
     3. 点击“环境变量”。
     4. 在“系统变量”部分，找到并选择 `Path`，然后点击“编辑”。
     5. 点击“新建”，然后输入您解压缩的目录路径，例如 `C:\platform-tools`。
     6. 点击“确定”保存设置。
   - **Mac 和 Linux**：
     1. 打开终端。
     2. 编辑您的 `~/.bash_profile` 或 `~/.zshrc` 文件，添加以下行：
        ```sh
        export PATH=$PATH:/path/to/your/platform-tools
        ```
     3. 保存文件并运行 `source ~/.bash_profile` 或 `source ~/.zshrc` 以使更改生效。

4. **验证安装**：
   - 打开命令行终端（Windows 使用 `cmd`，Mac 和 Linux 使用终端）。
   - 输入以下命令并按回车：
     ```sh
     adb devices
     ```
   - 如果安装成功，您应该会看到已连接设备的列表。

### 连接设备
1. **启用 USB 调试**：
   - 在安卓设备上，进入“设置” > “关于手机”，连续点击“版本号”七次以启用开发者选项。
   - 返回“设置”，进入“开发者选项”，启用“USB 调试”。

2. **连接设备**：
   - 使用 USB 线将设备连接到电脑。
   - 在命令行终端中运行 `adb devices`，您应该会看到已连接设备的列表。

通过以上步骤，您就可以成功下载、安装和使用 ADB 进行安卓设备的调试和管理。

效果图
![image](https://github.com/user-attachments/assets/53ff5236-132d-4f25-b232-1fe585624cd1)


Citations:
[1] https://developer.android.com/tools/adb
[2] https://blog.csdn.net/weixin_44903147/article/details/104065844
[3] https://help.esper.io/hc/en-us/articles/12657625935761-Installing-the-Android-Debug-Bridge-ADB-Tool
[4] https://developer.android.com/tools/adb?hl=zh-cn
[5] https://play.google.com/store/apps/details?hl=en_US&id=com.htetznaing.adbotg
[6] https://developer.aliyun.com/article/306845
[7] https://www.cnblogs.com/soundcode/p/12682231.html
[8] https://pplx-res.cloudinary.com/image/upload/v1722939592/user_uploads/kmcphfukv/image.jpg
[9] https://pplx-res.cloudinary.com/image/upload/v1722937744/user_uploads/ysinugblw/image.jpg
[10] https://pplx-res.cloudinary.com/image/upload/v1722937793/user_uploads/plwrwaqjm/image.jpg
