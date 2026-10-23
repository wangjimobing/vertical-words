# vertical-words
多语言竖排阅读器：智能混合分词，从右向左排版，支持 TXT/PDF 解析、精准翻页与大容量进度记忆。Multilingual vertical text reader with smart segmentation, RTL columns, PDF/TXT support, and IndexedDB progress saving.

📖 多语言竖排阅读器
一款纯前端、单文件的定制化排版工具，专为竖排阅读习惯打造。

· 智能混合排版：中日韩按单字（音节）竖排，英法德阿等外文按完整单词竖排，保留标点符号。
· 从右向左：符合传统竖排阅读习惯（列从右至左，字从上至下），支持自定义每页列数（1/3/5/6/7列）。
· 书籍式翻页：支持点击翻页、输入页码精准跳转。
· 强大解析能力：支持直接粘贴、上传 .txt 文件，以及解析文字版 .pdf 提取内容。
· 无感记忆：底层采用 IndexedDB，突破 5MB 限制，自动保存超大文本、阅读进度和排版设置，刷新不丢。
· 跨平台 PWA：支持添加到 iOS / 安卓主屏幕，像原生 App 一样全屏离线使用。
