# Adrian Ng – Curriculum Vitae

This repository contains my personal CV, which is automatically built and published as a PDF using GitHub Actions.  
You can fork, clone, and customize it for your own use—with no need to install dependencies locally!

---

## 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Adrian-Ng/cv.git
   cd cv
   ```

2. **Make your changes:**  
   Edit the LaTeX or other source files (e.g. `cv.tex`, `page1sidebar.tex`, etc.) as needed.

3. **Push your changes:**  
   ```bash
   git add .
   git commit -m "Update CV"
   git push
   ```

4. **Automatic PDF Generation:**  
   After you push, GitHub Actions will automatically build and generate a new PDF of your CV.
   Check the [Actions tab](https://github.com/Adrian-Ng/cv/actions) for build status.

---

## 📦 Releases & PDF Generation

When you publish a new release on this repository, a GitHub Action will:
- Build the CV PDF from the exact commit of the release.
- Upload the generated `cv.pdf` as a release asset.

You can always download the latest or any previous version of the CV from the [Releases page](https://github.com/Adrian-Ng/cv/releases).

[Download Latest CV (cv.pdf)](https://github.com/Adrian-Ng/cv/releases/latest/download/cv.pdf)

---

## 📂 Repository Structure

- `cv.tex`, `altacv.cls` – Main LaTeX CV files
- `page1sidebar.tex`, `page2sidebar.tex` – Sectioned content for the CV
- `requirements.txt` – (If you want to build locally, see requirements)
- `.github/workflows/` – GitHub Actions workflow files for automated builds
- `tex/` – (If present) Additional LaTeX resources

---

## 🛠️ Customization

- Fork or clone the repository.
- Replace content in the LaTeX source files with your own information.
- Push changes to trigger the automated PDF build and release process.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

Find me on [GitHub](https://github.com/Adrian-Ng) or via [LinkedIn](https://www.linkedin.com/in/adrian-ng/).