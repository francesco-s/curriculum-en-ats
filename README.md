# ATS-Optimized LaTeX Resume Template

This repository contains a one-page, ATS-friendly LaTeX resume template. It prioritizes clean, parsable content over complex visual design to ensure maximum compatibility with modern Applicant Tracking Systems (ATS).

## Core Features

- **Simple, Single-Column Layout**: Built using LaTeX's standard `article` class with traditional sections (`Work Experience`, `Education`, `Skills`) to ensure ATS can correctly identify and categorize information.
- **Clean Hyperlinks**: Uses the `hyperref` package to embed links directly into text (e.g., company names, email addresses) without disruptive colors or boxes, preventing common parsing failures.
- **Standard Fonts**: Employs T1 encoding with Latin Modern fonts to guarantee high-quality PDF rendering and reliable text extraction by automated systems.

## Getting Started

1.  Ensure you have a modern LaTeX distribution installed (e.g., TeX Live, MiKTeX).
2.  Clone the repository and edit the `resume.tex` file with your information.
3.  Compile the document twice using `pdflatex` to ensure all cross-references and spacing are correctly rendered.

<!-- end list -->

The output will be a single-page PDF named `resume.pdf`.

## ATS-Compatibility Principles

This template was designed around principles known to improve parsing accuracy:

- **No Visual Clutter**: It deliberately avoids tables, multiple columns, text boxes, images, and other graphical elements that frequently confuse ATS parsers and can lead to dropped content.
- **Consistent Formatting**: It uses unambiguous section headers and a consistent `Month YYYY – Month YYYY` date format to help systems accurately calculate work experience and filter candidates.
- **Linear Structure**: The content flows logically from top to bottom, using standard `itemize` bullet points to prevent text fragmentation during automated processing.

## Customization

- **Section Order**: While section titles should remain standard for parsability, you can reorder them (e.g., move `Skills` higher) to better align with the keywords in a specific job description.
- **Spacing**: Adjust vertical spacing using the `titlesec` and `enumitem` package settings in the preamble to ensure the content fits perfectly on a single page without resorting to fragile formatting.
- **Links**: Anchor hyperlinks to descriptive text (e.g., a company or university name). Only add a visible URL in parentheses if you know a specific application portal strips embedded link data.

## Human-Friendly vs. ATS-Friendly Versions

This template is engineered for passing through automated screening. For direct engagement with human recruiters, portfolios, or networking, a visually richer resume is often more effective.

- **Paired Design**: A companion resume, built with the `moderncv` class for visual appeal, is available in the **[curriculum-en](https://github.com/francesco-s/curriculum-en)** repository.
- **Content Sync**: It is critical to keep the content of both the ATS-optimized and the human-readable versions synchronized to avoid presenting conflicting information.
