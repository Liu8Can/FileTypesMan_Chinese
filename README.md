# FileTypesMan v2.0 简体中文汉化版

**仓库地址:** [https://github.com/Liu8Can/FileTypesMan_Chinese](https://github.com/Liu8Can/FileTypesMan_Chinese)

## 简介

本仓库托管 **FileTypesMan v2.0** 的简体中文汉化版本。

FileTypesMan 是由 NirSoft 开发的一款强大的 Windows 文件类型管理工具。它允许用户查看系统中所有文件扩展名的详细信息，并轻松编辑它们的属性、关联的程序、动作、以及 **默认图标** 等。

你是否觉得某些软件（例如 7-Zip 或 NanaZip 安装后）关联的压缩包图标不够美观或辨识度低？想要手动更换成自己喜欢的图标样式？

虽然可以通过**手动修改 Windows 注册表**来实现，但这不仅操作繁琐，而且存在一定的风险，误操作可能导致系统问题。

**FileTypesMan** 提供了一个更安全、更直观的图形化界面来完成这些修改，是对系统自带的文件关联设置功能的一个极佳补充。

## 关于此汉化版本


*   **软件原作者：** Nir Sofer (NirSoft)
*   **官方网站 (英文原版)：** [https://www.nirsoft.net/utils/file_types_manager.html](https://www.nirsoft.net/utils/file_types_manager.html) (官方版本仅支持英文)
*   **汉化来源：** 本仓库提供的汉化版本来源于 **吾爱破解论坛用户** 的分享。原始分享帖地址：[https://www.52pojie.cn/thread-1947297-1-1.html](https://www.52pojie.cn/thread-1947297-1-1.html)。**我并非此软件的汉化作者，仅作搬运和整理分享。**
*   **版本信息：** 此为 FileTypesMan v2.0 版本 (截至 2025年4月14日 的 NirSoft 官网最新版本)。

## 为何使用 FileTypesMan 更改图标？

*   **安全便捷：** 相较于直接修改注册表，使用 FileTypesMan 可以避免误操作带来的风险。
*   **界面直观：** 图形化界面清晰展示文件类型信息，易于查找和修改。
*   **功能强大：** 除了修改图标，还可以管理文件类型的其他属性和动作。

## 如何使用 (以修改 NanaZip 关联图标为例)

![image](https://github.com/user-attachments/assets/594c3776-3d71-4b03-b549-38271a8aac86)

以将 `.zip` 或 `.7z` 等压缩文件的默认显示图标更改为 NanaZip 软件本身的图标为例：

1.  **获取目标图标：**
    *   NanaZip 软件本身的图标设计精美，辨识度高。
    *   你可以在 NanaZip 的官方 GitHub 仓库找到并下载其 `.ico` 图标文件：[https://github.com/M2Team/NanaZip/blob/main/Assets/NanaZip.ico](https://github.com/M2Team/NanaZip/blob/main/Assets/NanaZip.ico)
    *   **【推荐】** 将下载好的 `NanaZip.ico` 文件或其他你想要使用的 `.ico` 图标文件，直接放在与 `FileTypesMan.exe` 相同的文件夹下。这样在后续步骤中更容易找到它。

2.  **运行 FileTypesMan：**
    *   从本仓库下载并解压文件。
    *   双击运行 `FileTypesMan.exe`。
    *   程序启动后会扫描系统中的文件类型，请稍作等待。

3.  **查找并修改图标：**
    *   扫描完成后，在 FileTypesMan 窗口中按下 `Ctrl + F` 快捷键，打开搜索框。
    *   输入你想要修改图标的文件扩展名，例如输入 `.zip` 或 `.7z`，然后点击“查找下一个”。
    *   在搜索结果列表中，找到对应的文件类型条目（例如 `NanaZip.zip` 或 `NanaZip.7z`，具体名称取决于你的系统和 NanaZip 安装设置），双击该条目，或者右键点击选择“编辑选定文件类型”。
    *   在弹出的“编辑文件类型”窗口中，找到 **“默认图标”** (Default Icon) 这一行。
    *   点击该行末尾的 **“...”** 按钮。
    *   此时会弹出“更改图标”对话框。点击 **“浏览”** 按钮。
    *   因为你已将目标图标放在 FileTypesMan 文件夹下，文件选择对话框默认就会打开该文件夹。直接选中你准备好的图标文件（例如 `NanaZip.ico`）。
    *   如果你的图标文件是 `.exe` 或 `.dll`，选中后可能还需要在下方的列表中选择具体的图标。如果是 `.ico` 文件，则直接显示该图标。
    *   确认图标无误后，点击“确定”关闭“更改图标”对话框，再点击“确定”关闭“编辑文件类型”窗口。

4.  **查看效果：**
    *   修改通常不会立即在所有地方生效。你可以尝试：
        *   刷新桌面或打开的文件夹。
        *   重启 Windows 资源管理器（在任务管理器中找到“Windows 资源管理器”，右键选择“重新启动”）。
        *   注销或重新启动计算机。

重复以上步骤，你可以为所有希望更改图标的 NanaZip 关联文件类型（或其他任何文件类型）设置新的图标。

## 注意事项

*   修改文件类型关联和图标属于系统级别的更改，请了解操作含义后再进行。
*   对本汉化软件的任何疑问，请优先参考原版软件说明和汉化来源帖。

---

希望这个工具能帮助你更好地个性化你的 Windows 体验！
