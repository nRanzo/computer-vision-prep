# Computer Vision Q&A - Exam Preparation 🎓

Welcome to the collaborative Q&A repository for the Computer Vision exam! 

The goal of this project is to build a comprehensive, high-quality PDF containing questions and answers covering all of our lectures (from Lecture 1 to Lecture ~26). 

Every time someone contributes, a GitHub Action will automatically compile a new PDF that everyone can download.

## 📄 How to download the latest PDF
You don't need to compile the code yourself!

👉 **[DOWNLOAD THE LATEST PDF HERE](../../raw/pdf-build/Computer-Vision-QA.pdf)** 👈

*(The PDF is automatically generated and updated every time a new change is integrated into the `main` branch).*

If the upper link shows 404, there probably is a pending action building the pdf. Just wait a minute.

## 🤝 How to contribute

We use a simple workflow to keep things organized. Here is how you can add your questions:

### 1. Fork & Clone
*If you are an external contributor, you cannot push directly to this repository.*
1. Click the **Fork** button at the top right of this repository to create your own copy.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/computer-vision-prep.git
   cd computer-vision-prep
   ```
3. Create a new branch for your edits (e.g., to add questions for lecture x):
   ```bash
   git checkout -b add-lecture-x
   ```

*(Note for Maintainers: You don't need to fork. Just clone the repo and always create a new branch `git checkout -b my-branch` before making changes, then push your branch.)*

### 2. Add your Questions
Open the specific file for the lecture you are working on (e.g., `Lecture5.tex`). Do not edit `main.tex` unless you are adding a new lecture file.

To add a question and an answer, use our custom LaTeX command `\qa{Question}{Answer}`. 

**Example:**
```latex
\qa{What is an image histogram?}{
A histogram is a graphical representation of the distribution of pixel intensities in an image.
}
```
*Note: Using `\qa` will automatically add your question to the clickable Table of Contents of the final PDF!*

### 3. Test your changes (Optional but recommended)
If you want to make sure your LaTeX syntax is correct before submitting:
- Upload your modified `.tex` file to [Overleaf](https://www.overleaf.com/).
- Or rely on the GitHub Action (it will fail and warn you if there's a syntax error in your Pull Request).

### 4. Open a Pull Request (PR)
1. Commit your changes and push your branch to your forked repository:
   ```bash
   git add .
   git commit -m "Added 2 questions for Lecture x"
   git push origin add-lecture-x
   ```
2. Go to the original repository and you will see a banner to **Compare & pull request**. Click it.
3. Fill out the provided **Pull Request Template** (check the boxes and write a short description).
4. Click **Create pull request** and wait for the GitHub Action to compile your LaTeX code. If it passes (turns green), a Maintainer will merge it! If there is a typo or a doubt about an answer, we can easily fix it together in the PR comments.

## 💬 Doubts or discussions?
If you hold a different opinion on an answer, spot a mistake, or just have a general doubt about a Computer Vision topic, please don't edit someone else's complex mathematical answer directly without checking! 
Instead, open an **Issue** or start a **Discussion** so we can figure out the right answer together.

## 📄 License
This project is licensed under the **[CC BY-NC 4.0 License](LICENSE)** (Creative Commons Attribution-NonCommercial 4.0). You are free to share and adapt the material as long as you give appropriate credit and do not use it for commercial purposes.

Happy studying! 🚀 Start this if helps!