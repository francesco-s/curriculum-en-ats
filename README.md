# Francesco Sannicola Resume

This repository contains a LaTeX-based resume template built using the [moderncv](https://www.ctan.org/pkg/moderncv) class. The template is tailored for a professional resume/CV with custom modifications that enhance the layout, design, and functionality.

## Overview

The LaTeX source code in this repository:

- **Defines Custom Colors:** Utilizes a custom dark blue color (`darkblue`/`customcolor`) to achieve a consistent and professional look.
- **Applies a Custom Layout:** Adopts the "classic" moderncv style with right-aligned details and incorporates header patches to adjust spacing and photo placement.
- **Uses a Variety of Packages:** Incorporates packages such as `geometry`, `babel`, `lmodern`, `gensymb`, `footmisc`, `xpatch`, `tikz`, and `tcolorbox` for enhanced typography, layout control, and decorative elements.
- **Redefines Key Commands:**
  - The `\cventry` command is redefined to support a two-column layout with flexible spacing for work experiences.
  - Custom commands like `\mycvitem` and `\cvtag` are provided to neatly display skills, technologies, and other bullet-point items in a visually appealing format.
  - Additional commands (e.g., `\jobdouble`) have been introduced for structuring entries that require side-by-side information.
- **Includes Detailed Personal Data:** The resume includes personal information such as name, professional title, contact details, social media links (LinkedIn and GitHub), and a placeholder for a profile photo.
- **Showcases Professional Experience, Education, Certifications, and Languages**

If you wish to use or customize this template, please review the prerequisites and instructions below.

## Prerequisites

Before compiling the resume, ensure you have the following installed:

- **TeX Distribution:** A modern TeX distribution (e.g., [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/)).
- **ModernCV Package:** The `moderncv` package, which is typically included in most distributions.
- **Required Packages:** Verify that you have installed:
  - `inputenc`
  - `geometry`
  - `babel`
  - `lmodern`
  - `gensymb`
  - `footmisc`
  - `xpatch`
  - `tikz`
  - `tcolorbox`

## Compilation

To compile the resume, follow these steps:

1. **Download the Repository:** Clone or download the repository to your local machine.
2. **Compile with LaTeX:** Use your preferred LaTeX editor or compile via the command line. For example, run:
   ```bash
   pdflatex resume.tex
   ```
   It is recommended to run the command twice to ensure all references and layout adjustments are correctly updated.

## Customization

You can easily modify several aspects of the template to fit your needs:

- **Personal Information:** Update your name, professional title, contact details, social media links, and the path to your profile photo.
- **Content Sections:** Customize sections such as Working Experience, Education, Certifications, and Languages to better match your background.
- **Design Elements:** Adjust colors, fonts, and overall layout by editing the color definitions and command redefinitions at the beginning of the document.
- **Commands:**
  - **`\cventry`:** Redesigned for a two-column format with adjustable spacing.
  - **`\mycvitem`:** Used for adding bullet-point items with controlled spacing.
  - **`\cvtag`:** Creates stylish tags for technologies and skills within decorative boxes.
  - **`\jobdouble`:** Supports side-by-side job descriptions for a more compact presentation.

## Directory Structure

A suggested directory structure for the project might be:

```
.
├── resume.tex         % Main LaTeX file
├── README.md          % This file
└── images/            % (Optional) Folder for images (e.g., profile photo)
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## Contact

For any inquiries or feedback, please reach out via:

- **Email:** [francescosannicola1997@gmail.com](mailto:francescosannicola1997@gmail.com)
- **LinkedIn:** [francesco-sannicola](https://www.linkedin.com/in/francesco-sannicola)
