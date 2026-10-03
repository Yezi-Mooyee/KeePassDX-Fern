# Android KeePassDX Fern

[English](README.md) | 简体中文

<img alt="KeePassDX Icon" src="https://cdn.jsdelivr.net/gh/Yezi-Mooyee/KeePassDX-Fern@master/art/icon.png"> <strong>轻量级 Android 密码保险箱与管理器</strong>，KeePassDX Fern 让你在 KeePass 格式的单一文件中编辑加密数据，并以安全的方式填充表单。

<img alt="KeePassDX Screenshot" src="https://cdn.jsdelivr.net/gh/Yezi-Mooyee/KeePassDX-Fern@master/art/screen.jpg" width="220">

## Fork 声明

KeePassDX Fern 是 [Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX) 的非官方 fork，基于上游 tag 4.5.5（commit `2db52c5`），并持续跟进上游版本。
修改部分的版权归 Yezi Mooyee 所有（2026），与上游一样以 GPLv3 发布。
请勿把本 fork 的问题反馈给上游 KeePassDX 项目；本项目的问题与需求请提交到[本仓库的 issues](https://github.com/Yezi-Mooyee/KeePassDX-Fern/issues)。

### 计划中的功能

 - <strong>可编排的填充键序列</strong>：把魔法键盘的填充从固定动作改为可自定义的键序列，例如 `{USERNAME}{TAB}{PASSWORD}{KEYBOARD_BACK}`，实现自定义魔法键盘自动填充的行为。
 - <strong>可配置的填充按键</strong>，填写用户名和填写密码的按钮，各自填充什么、填充后做什么，都可以自由配置。

### 功能

 - <strong>通行密钥（Passkeys）</strong>，用于身份验证，并<strong>在本地存储私钥</strong>。
 - <strong>生物识别</strong>快速解锁（指纹 / 人脸 / …）。
 - <strong>一次性密码</strong>（HOTP / TOTP）管理，用于双因素认证（2FA）。
 - <strong>自动填充</strong>，轻松用密码填写表单。
 - <strong>魔法键盘</strong>，高效填充任意输入框。
 - 创建<strong>加密数据库文件</strong>。
 - 以<strong>条目</strong>与<strong>群组</strong>树组织凭据。
 - 支持快速打开与<strong>复制 URI / URL 字段</strong>。
 - 每种条目类型都有动态<strong>模板</strong>。
 - 每个条目都有<strong>历史记录</strong>。
 - 精细的<strong>设置</strong>管理。
 - Material 设计与<strong>主题</strong>支持。
 - 支持 <strong>.kdb</strong> 与 <strong>.kdbx</strong> 文件（版本 1 至 4），采用 AES - Twofish - ChaCha20 - Argon2 算法。
 - 与绝大多数同类程序<strong>兼容</strong>（KeePass、KeePassXC、KeeWeb 等）。
 - 代码以<strong>原生语言</strong>编写（Kotlin / Java / JNI / C）。

KeePassDX Fern 是<strong>开源</strong>且<strong>无广告</strong>的。

## KeePassDX Fern 是什么？

与其把一长串密码硬背下来，不如交给它保管。麻烦在于，<strong>每个账号都该用不同的密码</strong>，光靠脑子记根本不现实。可要是图省事，到处用同一个密码，那么只要有一处泄露，你的邮箱、各类网站账号就可能一并被人拿走，而你往往浑然不觉，等到发现时已经晚了。

KeePassDX Fern 是<strong>面向 Android 的本地密码与通行密钥管理器</strong>，帮助你<strong>以安全的方式管理密码</strong>。你可以把所有密码放进一个数据库，用<strong>主密码</strong>和／或<strong>密钥文件（keyfile）</strong>加锁。你<strong>只需记住一个主密码和／或选中密钥文件</strong>，就能解锁整个数据库。数据库使用当前已知最强、<strong>最安全的加密算法</strong>加密。

## 小字条款

KeePassDX Fern 以<strong>开源 GPL3 许可证</strong>发布，这意味着你可以随意使用、研究、修改和分享它。Copyleft 确保它一直如此。
凭借完整源码，任何人都可以构建、fork，并检查例如加密算法是否被正确实现。
该软件<strong>没有广告</strong>。

## 参与贡献

* <strong>反馈 issue</strong>：本 fork 只接受界面、易用性等不涉及底层安全实现的 issue；加密算法、KDBX 解析等上游问题请提交给[上游项目](https://github.com/Kunzisoft/KeePassDX/issues)。如果你不确定该提交给谁，<strong>优先提交给[本项目](https://github.com/Yezi-Mooyee/KeePassDX-Fern/issues)</strong>。
* <strong>提交代码</strong>：通过 <strong>[pull request](https://github.com/Yezi-Mooyee/KeePassDX-Fern/pulls)</strong> 添加功能。fork 自己的改动会尽量保持在外层（界面 / 输入法 / 偏好），避免触碰加密实现。
* <strong>翻译</strong>：本 fork 直接复用上游的翻译成果，界面上绝大多数语言的译文来自[上游 Weblate 项目](https://hosted.weblate.org/projects/keepass-dx/)——<strong>想翻译通用界面，请去上游贡献</strong>。本 fork 新增字符串的翻译，目前请通过 [issue](https://github.com/Yezi-Mooyee/KeePassDX-Fern/issues) 提出。
* <strong>支持原作者</strong>：本 fork 的代码几乎全部来自上游。如果你想支持这个项目的开发，请直接支持上游作者：[Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX)（[捐款页](https://www.keepassdx.com/#donation)）。

## 下载

通过 [GitHub releases](https://github.com/Yezi-Mooyee/KeePassDX-Fern/releases/latest) 下载。

本项目目前尚未发布任何 release，需要自行编译，或等待第一个版本发布。

本 fork 目前只提供 <strong>libre</strong> 版本（不含 Google Play 依赖），暂不提供上游的 free 版与 Pro 版。关于 libre 与 free 的区别，见上游 wiki 的[说明](https://github.com/Kunzisoft/KeePassDX/wiki/FAQ#why-a-libre-and-free-version)。

## 常见问题

该项目还没有FAQ，你可以先参考上游的 [FAQ](https://github.com/Kunzisoft/KeePassDX/wiki/FAQ)

## 其他平台

- [KeePass](https://keepass.info/)（https://keepass.info/）是面向桌面的原始官方项目，提供标准化数据库文件的技术文档。它由活跃维护持续更新（以 C# 编写）。

- [KeePassXC](https://keepassxc.org/)（https://keepassxc.org/）是用 C++ 编写的另一套 KeePass 实现。

- [KeeWeb](https://keeweb.info/)（https://keeweb.info/）是同样兼容 KeePass 文件的网页版。

## 许可证

  Copyright © 2026 Jeremy Jamet / [Kunzisoft](https://www.kunzisoft.com).

  This file is part of KeePassDX.

  [KeePassDX](https://www.keepassdx.com) is free software: you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation, either version 3 of the License, or
  (at your option) any later version.

  KeePassDX is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with KeePassDX.  If not, see <http://www.gnu.org/licenses/>.

  *This project is a fork of [KeePassDroid](https://github.com/bpellin/keepassdroid) by bpellin.*
