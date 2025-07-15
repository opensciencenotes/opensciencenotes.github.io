# OpenScienceNotes 🧬💻

**An open-source, community-driven collection of notes to make science accessible to everyone.**

#[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
#[![GitHub contributors](https://img.shields.io/github/contributors/opensciencenotes/opensciencenotes.svg)](https://GitHub.com/opensciencenotes/opensciencenotes/graphs/contributors/)

---

### 📚 Read the Live Website

The latest version of our notes is freely available online:

🔗 **[https://opensciencenotes.github.io/opensciencenotes/](https://opensciencenotes.github.io/opensciencenotes/)** *(Note: You will update this URL once the site is published)*

---

## Why We Created This

In a world where knowledge is abundant but often locked behind paywalls or buried in dense academic texts, we wanted to create something different. `OpenScienceNotes` was born from a simple idea: **high-quality scientific education should be free, collaborative, and accessible to all.**

We aim to break down barriers by creating a living resource that is:
* **Open:** Anyone can read, use, and contribute to the content.
* **Modern:** Kept up-to-date with the latest discoveries and includes multimedia resources.
* **Community-Built:** Written and vetted by a diverse group of students, researchers, and educators who are passionate about science.

## 🤝 How to Contribute

We are thrilled you're interested in contributing! This project is built by the community, for the community. No contribution is too small—from fixing a typo to authoring a new chapter.

To ensure a smooth and collaborative process, we have a specific workflow.

### Step 1: Join the `opensciencenotes` Organisation

To contribute directly, we ask that you first become a member of our GitHub Organisation. This helps us build a community of trusted contributors.

1.  Go to the [Issues tab](https://github.com/opensciencenotes/opensciencenotes/issues) of this repository.
2.  Create a **New Issue**.
3.  Use the title: `Request to join organisation`.
4.  In the body, briefly introduce yourself and your area of interest (e.g., "Hi, I'm a postgraduate student in microbiology and would love to contribute.").
5.  We will review your request and send you an invitation to join!

### Step 2: Choose a Topic or Task

Once you are a member of the organisation, you can start contributing.

1.  **Look at the Issues:** Check the [Issues tab](https://github.com/opensciencenotes/opensciencenotes/issues) for existing tasks, bugs, or content requests. This is the best place to start.
2.  **Propose a New Idea:** Have an idea for a new section, chapter, or blog post? Create a **New Issue** to propose it first. This helps us avoid duplicate work and discuss the new content.
3.  **Claim an Issue:** Comment on an existing issue to let us know you're working on it.

### Step 3: Create Your Contribution (The Git Workflow)

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/opensciencenotes/opensciencenotes.git](https://github.com/opensciencenotes/opensciencenotes.git)
    cd opensciencenotes
    ```
2.  **Create a New Branch:** Always work on a new branch, never on `main`. Name your branch descriptively.
    * For new features: `git checkout -b feat/add-mitosis-diagram`
    * For fixing bugs/typos: `git checkout -b fix/typo-in-genetics-intro`
3.  **Make Your Changes:** Edit or create the relevant `.qmd` files. Please follow the established style and formatting.
4.  **Commit and Push:** Commit your changes with a clear message and push them to your new branch on GitHub.
    ```bash
    git add .
    git commit -m "feat: Add detailed diagram of mitosis to biology chapter"
    git push -u origin feat/add-mitosis-diagram
    ```
5.  **Open a Pull Request:** Go to the repository on GitHub. You will see a prompt to create a Pull Request from your new branch. Please provide a clear description of your changes in the PR.

## 🛠️ Local Development

To preview the website on your own machine:

1.  **Install Quarto and R/RStudio.**
2.  **Clone the repository** (as described above).
3.  **Open the project** in RStudio.
4.  **Render the Website:** Open the **Terminal** tab in RStudio and run the following command to see a live preview:
    ```bash
    quarto preview
    ```

Thank you for being a part of our community!
