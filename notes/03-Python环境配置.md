# Python 开发环境配置

## 日期
2026-07-01

## 一、安装 Python 3.11.8

1. 从官网下载 Python 3.11.8 安装包
   - 官网地址：https://www.python.org/downloads/
   - 下载文件：python-3.11.8-amd64.exe

2. 安装 Python
   - 运行安装程序
   - **关键步骤：务必勾选 "Add Python to PATH"**
   - 点击 "Install Now"，等待安装完成

3. 验证安装
   - 打开新的终端（CMD 或 PowerShell）
   - 执行命令：`python --version`
   - 输出结果：`Python 3.11.8`

## 二、安装 VS Code Python 扩展

1. 打开 VS Code
2. 点击左侧 "扩展" 图标（Ctrl+Shift+X）
3. 搜索 "Python"
4. 选择微软官方发布的 Python 扩展
5. 点击 "安装"

## 三、配置 Python 解释器

1. 在 VS Code 中按 Ctrl+Shift+P
2. 输入 "Python: Select Interpreter"
3. 选择 Python 3.11.8（系统会自动检测到）

## 四、验证开发环境

在 VS Code 终端中执行：
```powershell
python --version