# 北玄宫 V2.0（独立测试版）

这是一个独立版本，不会覆盖旧版 V1.0。

## 文件
- `index.html`：虚拟主殿网页
- `ceiling-dragon-bagua.png`：参考图天花板贴图
- `README.md`：部署说明

## 部署建议
1. 在 GitHub 新建一个独立仓库，例如 `Bei-Xuan-Gong-V2`。
2. 将本 ZIP 解压。
3. 把 `index.html` 和 `ceiling-dragon-bagua.png` 一起上传到新仓库根目录。
4. 在 Cloudflare Pages 新建项目并连接这个新仓库。
5. 由于这是纯静态网页，Build command 留空，输出目录使用 `/`（仓库根目录）。

请勿将这两个运行文件只放在子文件夹，也不要覆盖旧版 V1.0。
