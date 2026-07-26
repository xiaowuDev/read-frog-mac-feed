# Read Frog Mac 0.4.0

- 增加 PDF、Word DOCX 和 Markdown 文档翻译工作台。
- 支持左右精读与原文在上、译文在下的双语阅读模式。
- 文字 PDF 使用 PDFKit；扫描 PDF 使用本机 Vision OCR。
- 段落批量并发发送给 DeepSeek，失败批次自动拆分重试。
- 使用 SQLite 翻译记忆跨文档复用相同段落，人工修订也会进入记忆。
- 支持项目术语表、暂停恢复、断点续译和最近项目。
- 支持导出双语 PDF 与 Markdown。
- 延续 Sparkle 自动更新、划词翻译、中文表达和 Edge Neural TTS。
