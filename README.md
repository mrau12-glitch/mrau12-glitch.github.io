# Mu Shan (Misha) Rau — Portfolio

Live site: https://mrau12-glitch.github.io

## 你可以往这里放的东西

| 文件夹 | 放什么 | 命名建议 |
| --- | --- | --- |
| `assets/images/projects/` | 项目截图、流程图、团队照片 | `cstar-1.png`、`bitazone-flow.png` |
| `assets/images/art/` | 插画、贴纸、角色设计 | `sticker-01.png` |
| `assets/resume/` | 简历 PDF | `Mu-Shan-Rau-Resume.pdf` |

图片建议：宽度 1600px 左右，单张小于 1 MB，用 PNG 或 JPG。

## 旧 portfolio 的内容

旧网站（misharau.myportfolio.com）的图片和文字已经按作品分好文件夹放在 `assets/images/art/`、`assets/images/projects/` 和 `assets/images/about/`，总目录见 [`assets/images/README.md`](assets/images/README.md)。

## 网站内容在哪里改

打开 `index.html`，搜索 `const PROJECTS=[`（项目）或 `const ART=[`（作品），每一项的标题、简介、段落、图片和链接都在那里。

- 图片原图在 `assets/images/<分类>/<作品>/`，点开大图时显示的就是原图。
- 网页上直接显示的是压缩版 `assets/thumbs/…/*.webp`（最长边 1200px）。新加图片后，也要放一份压缩版进去。


## 网站风格（水墨主题）

整站是米白纸加黑墨线，配色在 `index.html` 最后一段 `INK THEME` 里（`--paper` 纸色、`--ink` 墨色、`--accent` 朱红）。
线稿是从 Misha 的手绘照片转出来的矢量图，在 `assets/ink/`：`misha.svg` 是签名（Logo 和页脚），`butterfly.svg` 是首页那只蝴蝶，其他几张先留着备用。
