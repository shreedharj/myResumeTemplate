# Shreedhar's LaTeX Resume Template

A minimal, customizable resume template using LaTeX. 

## Main Packages
- **`geometry`**: Sets page margins and paper dimensions.  
- **`graphicx`**: Enables image inclusion (e.g., logos, icons).  
- **`xcolor`**: Provides color definitions (used for hyperlink colors).  
- **`hyperref`**: Turns text into clickable links (URLs, emails, citations).  
- **`fontawesome5`**: Adds icon support (LinkedIn, GitHub, external link icons).  
- **`amsmath` & `amssymb`**: Offers advanced math symbols (used for bullet symbols or custom lists).  
- **`multicol`**: Allows multi-column layouts (if you want side-by-side sections).  
- **`fancyhdr`**: Customizes headers/footers (can add page numbers or section titles).  

## Document Structure
- The preamble loads packages and defines custom commands.  
- `\begin{document}` ... `\end{document}` wraps the content.  
- Sections are divided by `\header{...}` for clean, styled headings.  

## Custom Commands (`\newcommand`)
- **`\contact{name}{address/phone/email}{links}`**  
  – Centers your name, contact info, and icons.  
- **`\header{Section Name}`**  
  – Inserts a styled section title with an underline.  
- **`\employer{Title}{Organization}{Dates}`**  
  – Formats your job/position entry (employer name, role, and timeframe).  
- **`\award{Award Name}{Date}`**  
  – Styles award/honor entries.  
- **`\paper{Title}{Link}`**  
  – Lists publications with a hyperlink icon.  
- **`\project{Title}{Date}`**  
  – Formats project entries and optional links.  
- **`\school{name}{degree/courses}{major/minor}{GPA or dates}`**  
  – Displays educational institutions and details.  
- **`achievements` environment**  
  – Creates a tight bullet list for responsibilities or results.  

Use these macros by replacing the placeholders (e.g., “Title”, “Organization”, “Month Year”) with your own information. You can add/remove bullets inside each environment or create your own custom commands to suit your needs.

## Usage
1. Clone/Download this repository.  
2. Create a new project in **[Overleaf](https://www.overleaf.com/)**, open `main.tex` and all `.png` files. Note: the premium version is often free for university students.  
4. Replace filler text with your own details, compile to PDF, and share!

## Resources
- [Overleaf Documentation](https://www.overleaf.com/learn)
- [ChatGPT](https://chat.openai.com/)

Feel free to customize any part of this template for your own use case.  
