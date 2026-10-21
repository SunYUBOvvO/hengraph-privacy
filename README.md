# 衡绘 Hengraph — 官方隐私与支持站点

本仓库是 **衡绘 Hengraph**（HarmonyOS 科学数据分析与可视化应用，包名 `com.sunyubo.sciviz`）的官方公开文档站点，
仅用于发布应用上架所需的隐私文档与支持信息。

## 页面

| 路径 | 内容 |
| --- | --- |
| `/` | 首页：产品定位与能力概览 |
| `/privacy/` | 隐私政策（15 节，基于当前版本源码审计） |
| `/rights/` | 隐私权利：查看、删除与删除范围说明 |
| `/contact/` | 联系与支持 |

## 结构

```text
.
├── index.html
├── privacy/index.html
├── rights/index.html
├── contact/index.html
├── assets/style.css
├── README.md
└── .nojekyll
```

纯静态 HTML + CSS，无框架、无构建步骤、无 JavaScript、无外部字体、无统计脚本。
所有链接均为相对路径，可直接在 GitHub Pages 的项目子路径下工作。

## 本地预览

```bash
python -m http.server 8000
# 打开 http://localhost:8000/
```

## 部署

GitHub Pages → Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `/ (root)`。

## 内容边界

本仓库**不包含**衡绘应用的源代码、签名材料、证书、密钥、用户数据集或调试日志。
站点内容只涉及公开的产品说明与隐私文档。

## 联系

支持邮箱见 `/contact/` 页面。
