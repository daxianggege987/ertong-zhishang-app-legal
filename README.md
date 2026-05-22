# IQ智商测试-免费版 · 隐私政策与技术支持（静态页）

本仓库**仅**托管 App Store 所需的 **`privacy.html`** 与 **`support.html`**，通过 GitHub Pages 提供 HTTPS 链接。不包含 iOS 应用源代码。

## 多语言（方案 B）

两个页面顶部均有 **语言下拉选择**，支持与应用内一致的 9 种语言：

| 代码 | 语言 |
|------|------|
| `zh-Hans` | 简体中文 |
| `en` | English |
| `ja` | 日本語 |
| `ko` | 한국어 |
| `fr` | Français |
| `es` | Español |
| `de` | Deutsch |
| `pt-BR` | Português (Brasil) |
| `ar` | العربية（RTL） |

- 选择会保存到浏览器 `localStorage`，下次访问自动恢复。
- 也可通过 URL 指定：`?lang=ja`（例如 `privacy.html?lang=ja`）。
- 阿拉伯语自动切换 RTL 排版。

## 线上地址

- **隐私政策**：https://daxianggege987.github.io/ertong-zhishang-app-legal/privacy.html
- **技术支持**：https://daxianggege987.github.io/ertong-zhishang-app-legal/support.html

App Store Connect 各语言本地化可填写**同一 URL**；用户打开后自行切换语言。

## 文件

| 说明 | 路径 |
|------|------|
| 隐私政策 | `docs/privacy.html` |
| 技术支持 | `docs/support.html` |
| 商店文案草稿 | `docs/app-store-copy.md` |

## 更新

修改 `docs/` 后 `git push origin main`，Pages 通常数分钟内刷新。
