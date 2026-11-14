# h5-stash

两个单文件、零外部依赖的 H5 作品，暂存在这里。

| 目录 | 作品 | 首屏 |
|---|---|---|
| [`wedding/`](wedding/) | 屿 · 晚 — 婚礼邀请函 | ![婚礼](wedding/preview-hero.jpg) |
| [`peppa-family/`](peppa-family/) | 小猪佩奇 · 我们这一家 | ![佩奇](peppa-family/preview-hero.jpg) |

## 预览

```bash
cd h5-stash
python3 -m http.server 8000
```

- 婚礼：http://localhost:8000/wedding/
- 佩奇：http://localhost:8000/peppa-family/

也可以直接双击各目录下的 `index.html`（`file://` 下分享/返回按钮行为可能不完整）。

## 说明

- `wedding/`、`peppa-family/` 各自保留了原始 README 与首屏/长图预览。
- 私有仓库，暂存用；GitHub Pages 对私有仓库需要付费计划，需要在线看再说。
