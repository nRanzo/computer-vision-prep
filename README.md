# Computer Vision Q&A - Exam Preparation 🎓

A GitHub Action automatically compiles and updates the PDF whenever changes are merged into `main`.
---

👉 **[DOWNLOAD PDF](../../raw/pdf-build/Computer-Vision-QA.pdf)** 👈
The file is regenerated automatically on each update. If you get a 404, the build is likely in progress; wait a minute and retry.
---
## 🤝 How to contribute
We follow a simple workflow.
### 1. Fork & clone (external contributors)
1. Fork the repository.
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/computer-vision-prep.git
   cd computer-vision-prep

3. Create a branch:

`git checkout -b add-lecture-x`

Maintainers can work directly on the repo but should still use feature branches.

⸻

2. Add questions

Edit the relevant lecture file (e.g., Lecture5.tex).
Do not modify main.tex unless adding a new lecture.

Use:

`\qa{Question}{Answer}`

Example:

`\qa{What is an image histogram?}{
A histogram represents the distribution of pixel intensities in an image.
}`

This automatically integrates into the final PDF table of contents.

You can test locally, use Overleaf, or rely on the GitHub Action (it will fail if LaTeX has errors).

⸻

4. Submit a Pull Request

`git add .`

`git commit -m "Add questions for Lecture X"`

`git push origin add-lecture-x`

Then open a PR from GitHub and complete the template.
A CI check will compile the PDF automatically.

⸻

💬 Questions & discussions

For disagreements, uncertainties, or conceptual doubts, feel free to open an issue.

⸻

📄 License

Licensed under CC BY-NC 4.0: free to use and adapt for non-commercial purposes with attribution.

⸻

Happy studying 🚀