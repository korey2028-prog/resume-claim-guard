# 导出排版

简历是文书，衬线字体读起来正式、像印刷品；无衬线留给界面类的东西。标签、页眉小字可以用无衬线，正文、标题、条目一律用衬线。

## 字体搭配

| 用途 | 字体 | 官方下载 |
|---|---|---|
| 英文、数字 | Source Serif 4（Adobe） | https://github.com/adobe-fonts/source-serif/releases |
| 中文 | Noto Serif SC / 思源宋体（Adobe × Google） | https://fonts.google.com/noto/specimen/Noto+Serif+SC 或 https://github.com/notofonts/noto-cjk |

两者许可都是 SIL OFL 1.1，可免费商用。本仓库不放字体文件，只给链接。

## 单页简历字号

- 姓名 20–22pt，节标题 11–12pt，正文 10–10.5pt，行距 1.3–1.4。
- 正文用深灰 `#1F1F1F`，不用纯黑。

## 导出方式

- **Word / WPS**：正文字体设为 Source Serif 4，中文字体设为 Noto Serif SC 或思源宋体。
- **PDF**：必须嵌入字体，否则对方电脑缺字体会回退成别的字体。
- **ChatGPT 生成 PDF / DOCX**：把两份字体文件上传到 GPT 的 Knowledge，或在对话里上传；明确让它用 Code Interpreter，并按文件路径注册字体。上传不了时，告诉用户回退到 Word 手动设置。
