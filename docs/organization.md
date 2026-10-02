# 组织展示与维护

## 展示资料

| 位置 | 约定 |
|---|---|
| 组织名称 | SlayTheCircle |
| 组织简介 | Unofficial Genshin Impact-themed mods for Slay the Spire 2. 非官方原神主题《杀戮尖塔 2》模组与开发工具。 |
| 组织网站 | https://github.com/SlayTheCircle/STS2-Navia（当前主要作品入口；有独立网站后再替换） |
| .github 简介 | Organization profile and shared community guidelines. 组织主页与公共社区配置。 |
| Navia 简介 | Navia character mod for Slay the Spire 2. 娜维娅角色模组：装填、礼炮轰鸣、摩拉与支援构筑。Requires RitsuLib. |
| Charlotte 简介 | Charlotte character mod for Slay the Spire 2 (in development). 夏洛蒂角色模组，开发中，尚无公开发行。 |
| Template 简介 | Slay the Spire 2 mod template: dual-branch build, variant loader, audits and docs. 杀戮尖塔 2 模组开发模板。 |

Navia 的 Homepage 指向工坊；Charlotte 指向自身 README；Template 指向新仓上手文档；.github 指向组织主页。Topics 使用项目类型与生态关键词，角色模组和开发模板各自区分。组织头像采用 [assets/branding/avatar.png](../assets/branding/avatar.png)，来源与设计说明见[视觉资产说明](../assets/branding/README.md)；横幅另行设计。

## 上传组织头像

在 [组织设置](https://github.com/organizations/SlayTheCircle/settings/profile) 的头像区域点击 **Upload new picture**，选择本仓库的 `assets/branding/avatar-upload.jpg`（同图的压缩导出，小于 1 MB），确认裁切并保存。选定图为方形；预览时确认原石四个尖角和金色光环完整可见。

头像文件随 Git 提交不会自动替换组织账户的头像。上传后用未登录窗口检查组织主页；官方步骤见[自定义组织头像](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile#changing-your-organizations-profile-picture)。

## 公开仓库置顶

组织 Owner 在 [组织主页](https://github.com/SlayTheCircle) 选择 **View as: Public**，点击 **pin repositories / Customize pins**，按以下顺序选择并保存：

1. STS2-Navia：已发布作品。
2. STS2-Charlotte：开发中的作品。
3. STS2-Template：开发者入口。

只置顶这三个公开项目即可；.github 可由主页的帮助与贡献链接进入。保存后用未登录窗口核对展示。GitHub 允许最多六个公开置顶仓库，成员视图与公开视图可以不同；见[官方说明](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)。

## 默认社区文件的边界

- 组织默认文件存放在公开的 `.github` 仓库。
- CONTRIBUTING、SUPPORT、SECURITY、CODE_OF_CONDUCT 和 PR 模板供缺少对应文件的仓库使用；项目自有文件优先适用。
- Issue 表单与 config.yml 必须放在本仓库的 `.github/ISSUE_TEMPLATE/`，不是根目录的 `ISSUE_TEMPLATE/`。
- 目标仓库已有有效 Issue 模板或配置时，不继承组织整组 Issue 模板，不进行合并。
- Navia、Charlotte 与 Template 已有自己的社区文件与表单。修改这里不会同步更新它们；需要项目专用变更时，在目标仓库单独修改。
- 默认表单不预设 labels 或 assignees，避免新仓库缺少对应标签或人员时出现配置问题。
- LICENSE 不能作为组织默认许可继承；每个项目单独维护代码与素材的许可范围。

继承规则见[官方文档](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)。

## 安全报告入口

为各公开仓库启用 GitHub Private Vulnerability Reporting，在 **Security → Advisories** 确认存在私密报告入口；.github 作为组织公共配置及尚无入口项目的备用接收仓库。仅写入 SECURITY.md 不会开启此功能，新仓库仍需核对设置。

## 维护时机与验收

- **新增公开项目**：更新 profile/README.md 和 SUPPORT，核对 Description、Homepage、Topics、社区文件与安全报告入口。
- **首发或暂停开发**：更新主页中的状态；仅在对应包已发布后添加安装入口。
- **版本更新**：主页保持最新发行链接，具体版本和兼容说明在项目内维护。
- **提交本仓库内容后**：从公开视图核对主页、根 README 和 Issue 选择页，确认链接与表单显示正常。
- **验证继承**：使用没有自有社区配置的现有仓库（如有）查看入口；已有自有表单的三个项目不能用来证明继承。无需为此创建公开测试仓库。

组织设置与仓库元数据在 GitHub 中维护，不会由本仓库提交自动更新。按上面的约定修改后，应重新读取线上值核对；本页描述的是维护约定，不是自动部署脚本。
