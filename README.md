# MSU-IIT BSCS Thesis LaTeX Template

This repository contains the official LaTeX template for the Bachelor of Science in Computer Science (BSCS) thesis at Mindanao State University - Iligan Institute of Technology (MSU-IIT). It is designed to help students produce a well-formatted thesis document that complies with MSU-IIT formatting guidelines.

---

## Features

- Structured chapters including Abstract, Introduction, Review of Literature, Methodology, Results, and Conclusion  
- Formatted front matter: title page, approval sheet, acknowledgments, and dedication  
- Automated Table of Contents, List of Figures, and List of Tables  
- Supports bibliography management with BibTeX  
- Modular file organization for easy editing  
- Compatible with popular LaTeX distributions and editors (TeX Live, MiKTeX, Overleaf, TeXstudio)  

---

## Repository Structure

```
MSU-IIT-BSCS-Thesis-Template/
├── main.tex               # Primary LaTeX file to compile the thesis
├── preamble.tex           # Formatting setup and package imports
├── frontmatter/
│   ├── titlepage.tex
│   ├── approvalsheet.tex
│   ├── dedication.tex
│   └── acknowledgments.tex
├── chapters/
│   ├── abstract.tex
│   ├── introduction.tex
│   ├── review_of_literature.tex
│   ├── methodology.tex
│   ├── results.tex
│   ├── conclusion.tex
│   └── references.bib
├── images/                # Figures and graphs
└── tables/                # Tables and data visuals
```

---

## Getting Started

### Prerequisites

- LaTeX distribution installed (TeX Live, MiKTeX, or MacTeX)  
- LaTeX editor (e.g., Overleaf, TeXstudio, VS Code with LaTeX extension)  
- BibTeX for managing references  

### How to Use

1. Clone the repository: `git clone https://github.com/yourusername/MSU-IIT-BSCS-Thesis-Template.git`
2. Open `main.tex` in your LaTeX editor.  
3. Customize the front matter files with your personal and thesis details.  
4. Write your thesis content in the respective chapter files inside the `chapters/` folder.  
5. Compile the thesis document.  

---

## Compilation Instructions

For local compilation, run the following commands in your terminal:

pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex


On Overleaf or similar online editors, simply open `main.tex` and click the compile button.

---

## Customization

- Modify `preamble.tex` to adjust margins, fonts, or add new packages.  
- Add or remove chapters by creating `.tex` files in the `chapters/` folder and including them in `main.tex`.  
- Add images to the `images/` folder and reference them in your chapters using LaTeX commands like `\includegraphics{images/filename}`.  
- Manage your bibliography by editing the `references.bib` file with BibTeX entries.

---

## License

This template is released under the MIT License. Feel free to use, modify, and distribute this template with proper attribution.

---

## Acknowledgments

Thanks to the MSU-IIT Computer Science faculty and thesis advisers for the formatting guidelines that inspired this template. This project aims to simplify thesis writing for BSCS students.
