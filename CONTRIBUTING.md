# Contributing to the RIVM Science Cookbook

Welcome, and thank you for your interest in contributing to the
FAIR Software for Research Guidance.  —a collaborative resource for
uniform research software practices.  This guidance is based on the best
practices and guidances at RIVM and the guidences for the quality of
Models, Datasets and Indicators of Wageningen University and Research.

This guide is intended for all data scientists, analysts, modellers,
and anyone else working with or interested in data science or research software.

Our aim is to foster open collaboration, promote research integrity, and
encourage the adoption of clear, reproducible, and robust data science,
modelling and research software engineering methods across and beyond the
consortium of LTER-Life.  Please read this document before contributing
or providing feedback.


## Code of Conduct

All contributors are expected to follow our [Code of
Conduct](CODE_OF_CONDUCT.md). We strive to maintain a welcoming,
respectful, and inclusive environment for everyone. Constructive
discussion, mutual support, and a willingness to learn from each other
are essential to the success of this project.

## How You Can Contribute

### Report Issues or Bugs

- Found a mistake, bug, or unclear section? Please let us know!
- Check the Issues tab to see if your concern is already reported.
- If not, open a new issue and include:
  - A clear description of the problem or suggestion.
  - Steps to reproduce, if applicable, or line number of parapgraph.
  - Screenshots or error messages, if helpful.
  - Details about your environment (e.g., R version, OS, browser).

### Suggest Improvements or Share Feedback

- Propose new recipes, guidelines, or sections to improve the clarity, usefulness, or completeness of our cookbook.
- Share your experiences or best practices to help us collectively raise our standards.
- External colleagues or stakeholders: Your feedback is valuable! Please create an issue or contact the autors of this document. See README for contact details.

### Contribute Content or Code

1. **Fork and Clone the Repository**  
   Fork this repository (on GitLab), then clone your fork to your local machine:
   ```sh
   git clone https://github.com/LTER-LIFE/FS4R
   cd project-name
   ```
   
2. **Set Up Your Development Environment**
  If you want to preview or render the book locally, ensure you have
  all the necessary R and python packages installed, especially quarto
  and its dependencies. In R you can do this by running:
  ```sh
  install.packages("bookdown")
  ```
  For most simple text changes (such as editing .qmd files), you do
  not need a specific environment, any good text editor will suffice.
  However, to view your changes as they will appear in the rendered book,
  or to check formatting and code output, having quarto and the required
  packages available is recommended.

4. **Create a New Branch**
  ```sh
  git checkout -b feature/your-topic
  ```

5. **Make Your Changes**

  Follow the the best practices as described in this book.
  Use clear, well-documented code and plain language explanations.
  Include examples, references, or links to relevant information when possible.
  Test and Review

6. **Ensure your contribution builds and renders correctly**
  Run any relevant tests or checks.
  Proofread your text for clarity and accuracy.

7. **Submit a Merge Request**
  Push your changes to your fork:
  ```sh
  git push origin feature/your-topic
  ```
  Open a Merge Request (MR) to the main repository.
  Clearly describe what you have added or changed, and why.

### Language- and Content-Specific Guidelines

  R Contributions: Follow the tidyverse style guide and document
  functions using roxygen2 where relevant. For Python contributions:
  Follow the PEP 8.  Documentation: Write clear, concise, and accessible
  explanations. Use examples to illustrate concepts.  Other Languages:
  Clearly specify dependencies and usage instructions; follow
  language-specific best practices.
