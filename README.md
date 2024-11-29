# Baned-by-GFW

## 项目简介

Baned-by-GFW 是一个每日自动构建的工具，旨在分析被中国大陆的防火墙（GFW）拦截的网站。它能够分析网站的主要用途，并根据用户需求提供相应的解决方案或替代网站。

## 功能

- **每日自动构建**：每次触发后，会自动构建和更新 `Baned-by-GFW` 项目，确保工具能够分析最新的被拦截网站。
- **分析网站用途**：分析被GFW拦截的网站，提供网站的主要用途和服务。
- **满足用户需求**：为用户提供网站的替代方案或解决方法，帮助绕过GFW的限制。

## 使用方式

### 触发方式

1. **自动触发**：每次推送到 `main` 分支时，GitHub Actions 会自动构建和更新项目。
2. **定时触发**：GitHub Actions 每天00:00会定时执行一次构建任务。
3. **手动触发**：你也可以手动触发 GitHub Actions 工作流，进行即时构建和更新。

### 运行脚本

在仓库中包含了一个 `release.sh` 脚本，该脚本会自动执行以下操作：

1. 克隆当前仓库。
2. 运行构建脚本。
3. 提交更改并推送到 GitHub 仓库。

## 开发者

- **用户名**：XiaomingX
- **电子邮件**：support@xxxx.com

## 许可证

此项目采用 [MIT 许可证](LICENSE)。
