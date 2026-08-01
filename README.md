# BCSIT Project Report Templates

This branch contains the LaTeX templates required for drafting your project report, along with an `assets/` directory for project assets and a `references.bib` file for your references.

> [!IMPORTANT]
> While these templates are designed to meet the general requirements of the PRJ course, **always check with your assigned project supervisor before submission** to confirm any specific departmental preferences or formatting add-ons.

## 🚀 Getting Started

> [!WARNING]
> Before you begin working with these templates, **make sure your copy of the repository is set to private**. Plagiarism checkers frequently crawl public GitHub repositories, so keeping your repository private ensures your write-ups remain secure and prevents accidental plagiarism flags.

### ✍️ Writing Your Report

You do not need to install complex LaTeX distributions or compilers on your local machine. Instead, you have two flexible options for writing your report:

#### Option A: Editing Directly on GitHub

If you are new to Git or simply prefer a web-based interface, you can edit the LaTeX files directly in your browser:

1. Navigate to the specific `.tex` file you wish to edit.
2. Click the pencil icon on the top right corner of the file view to enter edit mode.
3. Make your changes and commit them directly to the branch.

#### Option B: Editing Locally & Pushing Changes

If you prefer to work on your local machine, you can clone the repository and edit the files using your preferred LaTeX editor:

1. Open the cloned repository in your LaTeX editor and make your changes to the `.tex` files.
2. After making your changes, commit them to your local repository and push them back to GitHub:

    ```bash
    git add .
    git commit -m "Update report content"
    git push origin project
    ```

### ⚙️ Automated PDF Compilation

Every time you push changes to your repository, GitHub Actions will automatically compile your LaTeX files into a PDF. This ensures that you always have an up-to-date version of your report available for review.

## 💡 Suggestions & Contributions

If you notice any bugs in these templates or want to suggest improvements, please feel free to open an issue or submit a pull request. Your suggestions and contributions are highly appreciated!
