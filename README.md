# 隐私政策页面 — 部署说明

本目录包含小纸船的隐私政策、用户协议等静态页面。应用内链接（`AppURLs.swift`）指向：

- **隐私政策**：https://giraffeee.github.io/paperboat/index.html
- **用户协议**：https://giraffeee.github.io/paperboat/terms.html
- **VIP 会员服务协议**：https://giraffeee.github.io/paperboat/membership.html
- **自动续费服务协议**：https://giraffeee.github.io/paperboat/auto-renewal.html
- **技术支持**：https://giraffeee.github.io/paperboat/support.html

## 如何更新 GitHub 上的文件

隐私页面部署在 **giraffeee/paperboat** 仓库的 GitHub Pages。

### 方式一：通过 GitHub 网页编辑

1. 打开 https://github.com/giraffeee/paperboat
2. 进入 `index.html`（隐私政策）或 `terms.html`、`support.html`
3. 点击铅笔图标「Edit this file」
4. 修改后点击「Commit changes」
5. 推送后 Pages 会在几分钟内自动更新

### 方式二：本地同步后推送

若 `giraffeee/paperboat` 仓库在本地已有 clone：

```bash
cd /path/to/paperboat   # 切换到 giraffeee/paperboat 仓库
cp /path/to/echosea/privacy-page/index.html .
# 若有 terms.html、support.html 也一并复制
git add index.html terms.html support.html
git commit -m "更新隐私政策：新增阿里云用户反馈说明"
git push origin main
```

### 访问地址

- 隐私政策：https://giraffeee.github.io/paperboat/index.html
- 用户协议：https://giraffeee.github.io/paperboat/terms.html
- VIP 会员服务协议：https://giraffeee.github.io/paperboat/membership.html
- 自动续费服务协议：https://giraffeee.github.io/paperboat/auto-renewal.html
- 技术支持：https://giraffeee.github.io/paperboat/support.html
