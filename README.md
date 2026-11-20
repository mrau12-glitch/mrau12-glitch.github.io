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

## 水墨主题预览（`ink.html`）

`ink.html` 是用 Misha 自己的线稿做的水墨主题预览，内容和 `index.html` 一样。线稿是从照片转出来的矢量图，放在 `assets/ink/`（`misha.svg` 是签名）。确定要用的话，把 `ink.html` 改名成 `index.html` 就行。
