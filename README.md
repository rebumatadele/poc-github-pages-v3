# GitHub Pages PR Preview POC

This repository demonstrates a CI/CD workflow that automatically builds and deploys a preview for pull requests using **GitHub Pages** and **GitHub Actions**.

## 📌 Repository
[GitHub Repository](https://github.com/rebumatadele/poc-github-pages-v3)

## 🚀 How to Use

Follow these steps to contribute and see your changes live before merging.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/rebumatadele/poc-github-pages-v3.git
cd poc-github-pages-v3
```

### 2️⃣ Create a New Branch
```bash
git checkout -b your-feature-branch
```

### 3️⃣ Make Changes
Modify `src/index.js` as needed. For example, update the displayed message to verify the build and deployment process.

### 4️⃣ Commit and Push
```bash
git add src/index.js
git commit -m "Update index.js with new feature"
git push origin your-feature-branch
```

### 5️⃣ Open a Pull Request
1. Go to the repository on GitHub.
2. Navigate to the **Pull Requests** section.
3. Click **New Pull Request** and select your branch.
4. Submit the pull request.

## 🎯 View Your Deployment

Once you submit the pull request, **GitHub Actions** will automatically:
- Build and bundle your changes using Webpack.
- Deploy a **preview link** for your PR.

🔗 **To view your changes**, go to the **PR's Checks section** → **GitHub Actions job summary**.  
There, you'll find a **deployment link** where you can preview your changes live before merging.

---

### 🛠 Technologies Used
- **Webpack** for bundling assets
- **GitHub Actions** for CI/CD
- **GitHub Pages** for hosting previews
- **Node.js** for dependency management

---

## 🤝 Contributing
Feel free to fork the repository, create a feature branch, and submit a pull request. If you encounter any issues, open an **issue** in the repository.

---

## 📜 License
This project is licensed under the **MIT License**.

---

Happy coding! 🚀
