# Teximlr

是一個基於 Python 和 Rust 的多功能文本處理工具。
它提供了兩個核心功能：提取圖片中的純文字（支持多語言）和從複製貼上的內容中剔除 HTML 標籤。
此外，本棧庫將會計劃支持 React (web) 和 Flutter (iOS or Android) 的集成。
Teximlr is a modern toolkit built with **Rust**, **Python**, and **Machine Learning** for ultra-convenient text extraction.


## Features

- 🖼️ **Image to Text (OCR)**
  - Extracts multilingual plain text from images with advanced ML models.
- 🧹 **HTML to Text**
  - Instantly strips all HTML tags, leaving only pure, clean text.

## How Teximlr become?

現代網站經常使複製貼上內容變得困難，這可能是因為元素不可選擇或 HTML 混亂。 Teximlr 只需單擊即可解決此問題 - 將任何圖像或 HTML 轉換為可用文字。
Modern sites often make copy-pasting content difficult, either due to non-selectable elements or messy HTML. Teximlr solves this with one click—turn any image or HTML into usable text.

## Tech Stack

- Core: **Rust** & **Python**
- Intelligence: **Machine Learning** (OCR, text clean-up)
- UI: **React** (web), **Flutter** (mobile, optional)

## Quick Start

```bash
pip install teximlr
```

## Usage

1. Image to Text: Upload or drag an image, Teximlr returns the extracted text.
2. HTML to Text: Paste HTML content, Teximlr cleans it to pure text.

## License
MIT
