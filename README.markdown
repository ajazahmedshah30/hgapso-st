# Hybrid GA-PSO with Segment Tree for Bin Packing Optimization

This repository contains the LaTeX Beamer source code for a presentation titled **"Hybrid GA-PSO with Segment Tree for Bin Packing Optimization: A Novel Framework for Industrial Efficiency Enhancement"**, prepared for the **16th International IEEE Conference on Computing, Communication & Networking Technologies (ICCCNT 2025)**.

## Overview

This presentation introduces a novel hybrid framework combining Genetic Algorithm (GA), Particle Swarm Optimization (PSO), and Segment Tree for optimizing the bin packing problem. It highlights the problem's significance in logistics, manufacturing, and cloud computing, proposes a triple-hybrid approach with O(log n) bin selection complexity, and presents experimental results demonstrating a 15.3% improvement over traditional methods. The presentation also includes an industrial case study and future research directions.

## Authors

- Ajaz Ahmed Shah
- Abhishek Kumar Rao
- Amitesh Pandey
- Divya Kumar

**Affiliation**: Department of Computer Science and Engineering, Motilal Nehru National Institute of Technology, Allahabad, India

**Contact**: ajaz.2024cs02@mnnit.ac.in

## Repository Structure

- `presentation.tex`: The main LaTeX source file for the Beamer presentation.
- `ieee_logo.png`: The IEEE logo image used on the title slide (not included in this repository due to copyright; see [Dependencies](#dependencies) for instructions).
- `README.md`: This file, providing an overview and instructions for the presentation.

## Dependencies

To compile the presentation, ensure you have the following:

1. **LaTeX Distribution**: A complete LaTeX distribution such as TeX Live (with `texlive-full` and `texlive-fonts-extra` collections) or MiKTeX.
2. **LaTeX Packages**: The presentation requires the following packages, which are typically included in a full LaTeX installation:
   - `beamer`
   - `tikz`
   - `xcolor`
   - `fontawesome5`
   - `pgfplots`
   - `multicol`
   - `booktabs`
   - `colortbl`
3. **IEEE Logo**: The title slide includes an IEEE logo (`ieee_logo.png`). You must obtain the official IEEE logo from the [IEEE Brand Experience website](https://brand-experience.ieee.org/) and place it in the same directory as `presentation.tex`. If you do not have the logo, comment out the line `\includegraphics[width=2.5cm]{ieee_logo.png}` in the `\setbeamertemplate{title page}` section to avoid compilation errors. Ensure compliance with IEEE branding guidelines.

## Compilation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ajazahmedshah30/hgapso-st.git
   cd hgapso-st
   ```

2. **Add IEEE Logo**:
   - Download the official IEEE logo (`ieee_logo.png`) from the IEEE Brand Experience website.
   - Place it in the same directory as `presentation.tex`.
   - Alternatively, comment out the logo inclusion line in `presentation.tex` if you do not have the logo:
     ```latex
     % \includegraphics[width=2.5cm]{ieee_logo.png}
     ```

3. **Compile the LaTeX File**:
   - Use `pdflatex` or `latexmk` to compile the presentation:
     ```bash
     pdflatex presentation.tex
     ```
     or
     ```bash
     latexmk -pdf presentation.tex
     ```
   - Ensure all required packages are installed. If using TeX Live, you can install missing packages with:
     ```bash
     tlmgr install beamer tikz xcolor fontawesome5 pgfplots multicol booktabs colortbl
     ```

4. **Output**:
   - The compiled output will be `presentation.pdf`, a PDF file containing the complete presentation.

## Presentation Structure

The presentation consists of the following slides:
1. **Title Slide**: Introduces the title, subtitle, authors, institution, and date, with the IEEE logo.
2. **Problem Statement and Motivation**: Describes the bin packing problem, its challenges, and research impact.
3. **Proposed Hybrid Framework**: Outlines the GA-PSO-Segment Tree integration and its innovations.
4. **Segment Tree Innovation**: Details the segment tree approach for O(log n) bin selection.
5. **Algorithm Architecture**: Explains the GA and PSO components and their integration.
6. **Experimental Methodology**: Covers datasets, baselines, and statistical tests.
7. **Performance Results**: Presents performance metrics and scalability results.
8. **Industrial Case Study**: Highlights a real-world e-commerce deployment.
9. **Contributions & Future Work**: Summarizes key contributions and future directions.
10. **Key References**: Lists relevant references for the research.
11. **Conclusion**: Summarizes achievements and includes a call to action.

## Usage

- **View the Presentation**: Open `presentation.pdf` in a PDF viewer to review the slides.
- **Customize**: Modify `presentation.tex` to adjust content, formatting, or styling as needed. Ensure you maintain compliance with IEEE presentation guidelines.
- **Present**: Use the PDF in a presentation software compatible with your conference setup (e.g., Adobe Acrobat, PowerPoint with PDF import).

## Notes

- **IEEE Branding**: Ensure you have permission to use the IEEE logo, as per IEEE's branding guidelines.
- **Font and Theme**: The presentation uses the Beamer `default` theme with a custom color scheme (`primary`, `secondary`, `accent`, `alert`) for a clean and professional look.
- **Contact**: For questions or collaboration opportunities, reach out to `ajaz.2024cs02@mnnit.ac.in`.

## License

This project is shared for academic and research purposes. Please respect IEEE copyright guidelines for the logo and any referenced content. The LaTeX code is provided as-is, with no warranty.