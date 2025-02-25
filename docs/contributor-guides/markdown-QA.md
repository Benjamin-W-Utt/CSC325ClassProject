# Vale and MarkdownLint
   Contributors to this repository should use **Vale** and **markdownlint-cli** to ensure that all Markdown files meet the highest quality standards before being pushed to the default branch. **Vale** helps by checking for style, grammar, and readability issues, ensuring that the language used in the documentation is clear, consistent, and free of errors. **markdownlint-cli** enforces formatting rules, catching common Markdown syntax issues such as improper headings, inconsistent lists, and misplaced code blocks. Contributors are encouraged to run both tools locally on their Markdown files before committing changes. Additionally, automated linting can be set up with pre-commit hooks or GitHub Actions to ensure that all Markdown files are automatically checked for compliance with the project's standards, preventing problematic files from being merged into the default branch.
# Using Vale
To use Vale to check the quality of your markdown files, first initialize Vale using the following bash command:
   ```bash
 vale sync
   ```
Then use this command to check your markdown files with Vale, printing any errors found.
   ```bash
 vale .
   ```
# Using MarkdownLint
To use Vale to check the quality of your markdown files, simply run this bash command to search markdown files and print any errors found. 
   ```bash
markdownlint .
   ```
