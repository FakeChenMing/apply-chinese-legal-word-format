# 中文法律 Word 排版

为 Word 文档统一设置标题、章节标题、正文的中西文字体、字号、加粗和首行缩进。通用标题用华文中宋小二，章节标题用黑体小四加粗，正文用仿宋小四，西文和数字用 Times New Roman。

## 下载与安装

下载 [完整技能包](apply-chinese-legal-word-format.zip)，解压后把 `apply-chinese-legal-word-format` 文件夹放入技能目录。包内含技能说明、格式配置、Word 示例和排版校验脚本。运行脚本需要 Python 和 python-docx，显示效果取决于本机字体。

进入技能文件夹后，用以下命令生成并检查输出副本。

```sh
python scripts/apply_word_format.py apply input.docx output.docx --auto-classify
python scripts/apply_word_format.py verify output.docx
```

起草或修改民事起诉状时，优先使用[民事起诉状固定格式技能](https://github.com/FakeChenMing/civil-complaint-format)的专用字号和母版。通用脚本的结构检查完成后，仍应按实际显示或打印效果逐页核对。
