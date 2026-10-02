# SlayTheCircle · 组织主页与公共配置

本仓库维护 [SlayTheCircle](https://github.com/SlayTheCircle) 的公开主页和默认社区文件。模组安装、开发和问题反馈请从[项目导航](SUPPORT.md)进入对应仓库。

## 内容入口

| 文件 | 用途 |
|---|---|
| [profile/README.md](profile/README.md) | 显示在组织 Overview 的公开主页 |
| [CONTRIBUTING.md](CONTRIBUTING.md) | 默认贡献指南 |
| [SUPPORT.md](SUPPORT.md) | 项目导航与默认支持指引 |
| [SECURITY.md](SECURITY.md) | 默认安全报告指引 |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | 默认社区行为准则 |
| [PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md) | 默认 PR 模板 |
| [.github/ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE) | 默认 Bug、建议表单与入口配置 |
| [assets/branding](assets/branding/README.md) | 选定的组织头像与来源说明 |
| [docs/organization.md](docs/organization.md) | 组织展示设置、文件继承与维护清单 |

## 修改与验证

主页维护项目定位、状态和入口；具体版本与兼容范围以各项目发行和文档为准。新增项目时同步检查 SUPPORT 的导航。选定的组织视觉资产在 assets/branding 维护，生成候选与提示词草稿放在被 Git 忽略的 output/。

修改后检查链接、事实与 Markdown 显示；Issue 表单检查 YAML 结构与字段。提交后在 GitHub 公开视图确认主页和本仓库 Issue 选择页；默认模板继承在没有自有模板的仓库中确认。

GitHub 的默认社区文件由公开 `.github` 仓库提供，在目标仓库没有对应文件时使用，不会写入其工作区。目标仓库已有有效 Issue 模板或配置时，不会与组织默认模板合并。具体规则见[官方文档](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)。

## English summary

This repository maintains SlayTheCircle's public organization profile and default community files. Use SUPPORT.md to find project-specific channels. Existing project policies and Issue templates take precedence. Organization display settings and maintenance steps are documented in docs/organization.md.
