# LaTeX Scientific Writing Guide

**Author**: [Ivan Lejeune]  
**Version**: [0.0.1]  
**Contact**: [[My Github](https://github.com/Ivan23BG)]  

## 📦 Package Contents

### 📄 Main Files
- `latex_guide.pdf` - Complete PDF guide
- `latex_guide.tex` - Source file for the guide

### 📂 Content
1. The **Main File** is `latex_guide.pdf`, it contains the pdf version of the guide, which is the main file you will be working with.

2. The **Folders** are organised by purpose and order, each folder contains the main files used in that section of the guide:

3. Several **Templates** will be included in later versions of the guide

## ⚙️ System Requirements

### Recommended Setup
- **LaTeX Distribution**:
  - [TeX Live](https://www.tug.org/texlive/) (Recommended)
  - [MiKTeX](https://miktex.org/) (Windows)
  - [MacTeX](https://www.tug.org/mactex/) (macOS)

- **Editor**:
  - [VS Code](https://code.visualstudio.com/) + [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
  - [TeXstudio](https://www.texstudio.org/)
  - [Overleaf](https://www.overleaf.com) (Online)

### Recommended Packages
Ensure these packages are installed:
```bash
tlmgr install amsmath mathtools graphicx hyperref biblatex
```

## 📖 Usage
1. **Download** the repository.
2. **Open** the `latex_guide.pdf` file in your PDF viewer.
3. **Edit** the `latex_guide.tex` file in your LaTeX editor.
4. **Compile** the `.tex` file to generate the PDF with the command:
   ```bash
   latexmk Latex_guide.tex -pdf -output-directory=./output
   ```
5. **View** the generated PDF in the `output` folder.
6. **Explore** the folders for additional content and templates.

## Troubleshooting
- If you encounter issues with missing packages, install them using your LaTeX distribution's package manager.
- For compilation errors, check the log file for details. 
- Ensure your LaTeX editor is configured to use the correct distribution.

## Useful Links
- [LaTeX Documentation](https://www.latex-project.org/help/documentation/)
- [Overleaf Documentation](https://www.overleaf.com/learn)
- [TeX Stack Exchange](https://tex.stackexchange.com/)
- [CTAN](https://ctan.org/) (Comprehensive TeX Archive Network)
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)