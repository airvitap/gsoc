# Contributing to the Proposal Archive

Thank you for considering contributing to our archive of mentorship program proposals! Your contributions help other students learn and succeed.

## How to Contribute

1.  **Fork the Repository:** Start by forking the [main repository](https://github.com/airvitap/gsoc).
2.  **Clone Your Fork:** Clone your forked repository to your local machine.
    ```bash
    git clone https://github.com/airvitap/gsoc.git
    cd gsoc
    ```
3.  **Create a New Branch:** Create a branch for your contribution.
    ```bash
    git checkout -b add-proposal-YourName-ProgramYear
    ```
    (e.g., `add-proposal-JaneDoe-GSoC2025`)
4.  **Add Your Proposal:**
    *   Navigate to the appropriate year and program directory (e.g., `2025/GSoC`). If it doesn't exist, create it.
    *   Create a subdirectory named `OrganizationName-StudentName` (e.g., `Mozilla-JaneDoe`).
    *   Place your proposal file (preferably in PDF or Markdown format) inside this subdirectory.
5.  **Update README.md (Optional but Recommended):**
    *   If you're comfortable, you can add a link to your proposal in the "Proposals Archive" section of the main `README.md` file. Follow the existing format. If not, maintainers can help with this step.
6.  **Commit Your Changes:**
    ```bash
    git add .
    git commit -m "Add [Your Name]'s [Program] [Year] proposal for [Organization]"
    ```
    (e.g., `git commit -m "Add Jane Doe's GSoC 2024 proposal for Mozilla"`)
7.  **Push to Your Fork:**
    ```bash
    git push origin add-proposal-YourName-ProgramYear
    ```
8.  **Open a Pull Request:** Go to the original repository on GitHub and open a pull request from your forked branch.
    *   Provide a clear title and description for your pull request.
    *   Mention if your proposal was selected.

## Proposal Guidelines


*   **Anonymize if Necessary:** If your proposal contains sensitive personal information that you do not wish to share publicly, please anonymize it before submitting.
*   **Clear Formatting:** Ensure your proposal is easy to read. PDF or Markdown formats are preferred.

## Questions?

If you have any questions, feel free to open an issue in the repository.

Thank you for contributing!