# Computer Vision Q&A - Exam Preparation 🎓👁️

Welcome to the collaborative Q&A repository for the Computer Vision exam! 

The goal of this project is to build a comprehensive, high-quality PDF containing questions and answers covering all of our lectures (from Lecture 1 to Lecture ~26). 

Every time someone contributes, a GitHub Action will automatically compile a new PDF that everyone can download.

## 📄 How to download the latest PDF
You don't need to compile the code yourself! To get the latest PDF:
1. Go to the **Actions** tab.
2. Click on the latest successful workflow run (marked with a green checkmark).
3. Scroll down to the **Artifacts** section and click on `Computer-Vision-QA` to download the ZIP containing the PDF.

## 🤝 How to contribute

We use a simple workflow to keep things organized. Here is how you can add your questions:

### 1. Fork & Clone
1. Click the **Fork** button at the top right of this repository to create your own copy.
2. Clone your fork locally (`git clone https://github.com/YOUR-USERNAME/computer-vision-prep.git`) or edit the files directly within the GitHub web interface.

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
1. Commit and push your changes to your forked repository.
2. Go to the original repository and click **Compare & pull request**.
3. Add a brief title describing what you added (e.g., *Added 5 questions for Lecture 8*).

## 💬 Doubts or discussions?
If you hold a different opinion on an answer, spot a mistake, or just have a general doubt about a Computer Vision topic, please don't edit someone else's complex mathematical answer directly without checking! 
Instead, open an **Issue** or start a **Discussion** so we can figure out the right answer together.

Happy studying! 🚀
