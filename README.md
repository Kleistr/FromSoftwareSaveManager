# FromSoftwareSaveManager


一个基于 PyQt6 的存档管理工具，专门用于管理 FromSoftware 游戏的存档文件。

<a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg" alt="996.icu" /></a>
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

![eldenring_screenshot](screenShot/screenshot_er.png)
![darksouls3_screenshot](screenShot/screenshot_ds3.png)
![sekiro_screenshot](screenShot/screenshot_sk.png)

## 功能特性

- 直观的图形用户界面 (GUI)
- 备份和恢复游戏存档
- 自动检测游戏存档位置
- 支持多个存档版本管理
- 自定义备份名称和描述
- 快速切换不同存档
- 支持删除旧备份

## 系统需求

- Python 3.8 或更高版本
- PyQt6
- qt_material

## 安装步骤（从代码运行）

1. 克隆本仓库：
   ```bash
   git clone https://gitea.ixuan.org/kleist/FromSoftwareSaveManager.git
   ```
2. 安装依赖：

    ```bash
    pip install -r requirements.txt
    ```
## 安装步骤（直接下載exe）

下載 [FromSoftwareSaveManager v0.9.0](http://fn.ixuan.org:8418/kleist/FromSoftwareSaveManager/releases/download/V0.9.0/FS%E7%A4%BE%E6%B8%B8%E6%88%8F%E5%AD%98%E6%A1%A3%E5%A4%87%E4%BB%BD%E5%B7%A5%E5%85%B7.exe)

## 使用方法
1. 运行程序：

    ```bash
    python saveManager.py
    ```
2. 主界面将显示当前存档信息和备份列表

3. 使用按钮进行操作：

- "备份"：创建当前存档的备份
- "恢复"：选择并恢复备份
- "删除"：删除选中的备份
- "设置"：配置存档路径和其他选項

