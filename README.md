# TSV Content Visualizer

A modern, web-based tool for visualizing tab-delimited files with an intuitive table interface. Stop wrestling with broken columns in text editors and Excel import wizards — just upload and view your TSV data instantly!

## 🌟 Features

- **📋 Clean Table Display**: Organized columns with sticky headers, row numbers, and alternating row colors for easy reading
- **🔍 Powerful Search**: Filter across all columns with instant, case-insensitive results and match highlighting
- **🔃 Column Sorting**: Click any column header to sort alphabetically or numerically, ascending or descending
- **📄 Dual View Modes**: Switch between a formatted table view and a raw text view with visible tab markers
- **📈 Data Insights**: Real-time statistics showing total rows, columns, file size, and header detection
- **↔ Text Wrapping**: Toggle cell wrapping on and off to handle long content in narrow columns
- **💾 Export Functionality**: Download visible or filtered data as a new TSV file
- **🎨 Modern Design**: Professional interface with drag & drop upload and error handling
- **⚡ Client-Side Processing**: No server required — works entirely in your browser

## 🚀 Live Demo

**[Try it now!](https://andresromeroarcas.github.io/TSV-Visualizer/tsv-visualizer.html)**

## 🎯 Use Cases

- **Translators & Localization Engineers**: Inspect bilingual tab-separated text exports from CAT tools and TM files
- **Data Analysts**: Quick TSV inspection without opening Excel and dealing with delimiter misdetection
- **Developers**: Debug TSV exports from applications and validate data pipelines
- **Researchers & Students**: Explore tab-delimited datasets and present data in a readable format

## 💻 Getting Started

### Option 1: Use Online (Recommended)
Simply visit the [live demo](https://andresromeroarcas.github.io/TSV-Visualizer/tsv-visualizer.html) and start using it immediately!

### Option 2: Download and Run Locally
1. Download the `tsv-visualizer.html` file
2. Open it in any modern web browser
3. Upload your TSV or TXT file and start visualizing!

### Option 3: Clone Repository
```bash
git clone https://github.com/andresromeroarcas/TSV-Visualizer.git
cd TSV-Visualizer
# Open tsv-visualizer.html in your browser
```

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Main Interface
Drag & drop file upload with instant tab-delimiter validation and file information display.

### Table View
Professional table layout with sticky headers, row numbers, column sorting, and smooth scrolling for large datasets.

### Raw View
Original file content with line numbers and visible tab markers (→) for inspecting the raw structure.

### Search & Statistics
Real-time search across all columns with match count, plus a statistics dashboard showing rows, columns, file size, and header detection.

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** — No frameworks or dependencies
- **Client-side TSV parsing** with tab-character detection and line-ending normalization
- **CSS Grid and Flexbox layout** for responsive design
- **Modern ES6+ JavaScript** features
- **Secure processing** — Your data never leaves your device

## 📝 Supported Features

- [x] Tab-delimited parsing (.tsv, .txt, .tab)
- [x] Automatic tab-delimiter detection with user-friendly validation
- [x] Header row detection (named vs. numeric columns)
- [x] Column sorting (alphabetical and numeric)
- [x] Rows with mismatched column counts handled gracefully
- [x] Large file support (tested up to 10MB+)
- [x] Unicode/UTF-8 support
- [x] Windows, macOS, and Linux line-ending normalization (CRLF, LF, CR)

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
"# TSV-TXT_Visualizer" 
"# TSV-TXT_Visualizer" 
