
# Poliba Thesis LaTeX Class

This repository contains the `polibathesis.cls` LaTeX class, designed for preparing theses and dissertations at the **Politecnico di Bari (Poliba)**.

It is based on Lon Mitchell's `kuthesis.cls` but modified to fit Poliba’s formatting requirements.

## Features

* Supports both **Master’s theses** and **PhD dissertations**.
* Configurable **title page** with university logo, department, SSD, program, and supervisor/referee information.
* Handles **copyright**, **copyleft**, and **previous degrees**.
* Automatic **chapter, section, and subsection numbering**.
* Supports **tables, figures, captions**, and floating environments.
* Handles **appendices**, **table of contents**, and **front/back matter** formatting.
* Works for **single- and double-column layouts**, and **one- or two-sided documents**.
* Includes **date printing options** for defended/approved dates.
* Compatible with **A4, letter, and other common paper sizes**.

## Usage

1. Copy `polibathesis.cls` into your project directory.
2. In your main `.tex` file, use:

```latex
\documentclass[12pt,oneside,dissertation,titlepage]{polibathesis}
```

3. Fill in the required metadata:

```latex
\title{Your Thesis Title}
\author{Your Name}
\department{Department Name}
\programdept{Program Name}
\programlevel{PhD / Master}
\SSD{SSD Code}
\supervisorone{Supervisor Name}
\referees{Referee1}{Referee2}{Referee3}
```

4. Use `\frontmatter`, `\mainmatter`, and `\backmatter` to structure your document.

5. Compile with `pdflatex` (or `xelatex`/`lualatex` if you need Unicode support).

## License

This class is based on `kuthesis.cls`, which is under the **GNU Public License (GPL)**. You are free to distribute and modify it under GPL terms.

