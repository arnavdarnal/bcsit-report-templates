# BCSIT Report Templates
This repository contains official LaTeX templates and build pipelines for student project documentation within the [BCSIT program](https://pu.edu.np/blog/program/bachelor-of-computer-system-and-information-technology-bcsit/) at Pokhara University and is designed to help you seamlessly draft, format, and compile your proposal and project reports using automated GitHub Actions, removing the need for a local LaTeX installation.

## 📁 Repository Structure & Branches
This repository uses a multibranch workflow to separate the different stages of your project life cycle.

* **`main` Branch:** Contains the global style file (`bcsitreport.sty`), the GitHub Actions workflow, the `.gitignore` file, the MIT License, and this README.
* **`proposal` Branch:** Contains the LaTeX templates required for drafting your proposal report, along with an `assets/` directory for project assets and a `references.bib` file for your references.
* **`project` Branch:** Contains the LaTeX templates required for drafting your project report, along with an `assets/` directory for project assets and a `references.bib` file for your references.

## 🌐 Compatible Colleges
These templates adhere to the standard university guidelines for the PRJ course and are compatible with students across the following affiliated colleges:

* [Ace Institute of Management](https://ace.edu.np/bcsit-pokhara-university/)
* [Apex College](https://apexcollege.edu.np/our-programs/bachelor-of-computer-system-and-information-technology)
* [Apollo International College](https://www.apollointcollege.edu.np/program/1/details)
* [Boston International College](https://bostoncollege.edu.np/bachelor-of-computer-system-and-information-technology-bcsit/)
* [Crimson College of Technology](https://cct.edu.np/bcsit/)
* [Excel Business College](https://excelcollege.edu.np/bcsit/)
* [Liberty College](https://libertycollege.edu.np/program/bachelor-of-computer-system-and-information-technology/)
* [Malpi International College](https://mic.edu.np/bcsit-programme/)
* [Medhavi College](https://medhavicollege.edu.np/bachelors-of-computer-science-and-information-technology)
* [Nobel College](https://nobelcollege.edu.np/academic-program/bachelor-of-computer-system-and-information-technology-bcsit)
* [Pokhara College of Management](https://www.pcm.edu.np/program-details/bachelor-in-computer-system-and-information-technology)
* [Quest International College](https://quest.edu.np/programs/bcsit-in-nepal)
* [Rajdhani Model College](https://rmccollege.edu.np/course/bcsit)
* [SAIM College](https://saim.edu.np/academic/bcsit)
* [Shubhashree College of Management](https://shubhashreecollege.edu.np/bachelor-of-computer-system-and-information-technology/)
* [Uniglobe College](https://uniglobe.edu.np/bcsit/)

> [!IMPORTANT]
> While these templates are designed to meet the general requirements of the PRJ course, **always check with your assigned project supervisor before submission** to confirm any specific departmental preferences or formatting add-ons.

## 🚀 Getting Started
> [!WARNING]
> Before you begin working with these templates, **make sure your copy of the repository is set to private**. Plagiarism checkers frequently crawl public GitHub repositories, so keeping your repository private ensures your write-ups remain secure and prevents accidental plagiarism flags.

### ✍️ Writing Your Report
You do not need to install complex LaTeX distributions or compilers on your local machine. Instead, you have two flexible options for writing your report:

#### Option A: Editing Directly on GitHub
If you are new to Git or simply prefer a web-based interface, you can edit the LaTeX files directly in your browser:

1. Navigate to the desired branch (`proposal` or `project`) in the repository.
2. Navigate to the specific `.tex` file you wish to edit.
3. Click the pencil icon on the top right corner of the file view to enter edit mode.
4. Make your changes and commit them directly to the branch.

#### Option B: Editing Locally & Pushing Changes
If you prefer to work on your local machine, you can clone the repository and edit the files using your preferred LaTeX editor:

1. Clone the repository to your local machine using Git:
    ```bash
    git clone <repository-url>
    ```
2. Open the cloned repository in your LaTeX editor and make your changes to the `.tex` files.
3. After making your changes, commit them to your local repository and push them back to GitHub:
    ```bash
    git add .
    git commit -m "Update report content"
    git push origin <branch-name>
    ```

### ⚙️ Automated PDF Compilation
Every time you push changes to your repository, GitHub Actions will automatically compile your LaTeX files into a PDF. This ensures that you always have an up-to-date version of your report available for review.

## 💡 Suggestions & Contributions
If you notice any bugs in these templates or want to suggest improvements, please feel free to open an issue or submit a pull request. Your suggestions and contributions are highly appreciated!
