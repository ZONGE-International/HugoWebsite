# Zonge International Website

Welcome to the **Zonge International Website** repository! This is a static marketing site built using [Hugo](https://gohugo.io/) and the [Ananke theme](https://github.com/theNewDynamic/gohugo-theme-ananke). The site is designed for fast performance, easy content updates, and is deployed using **GitHub Pages**.

---

## 🚀 **Project Overview**

This website showcases the services, expertise, and legacy of **Zonge International**, a leader in geophysics. Built as a static site, it ensures:

- **High performance** and **security** by serving static files.
- **Easy content updates** using Markdown (`.md`) files.
- **Automatic deployment** through GitHub Actions and GitHub Pages.

---

## 🔧 **Technologies Used**

- **Hugo**: Static site generator.
- **Markdown (`.md`)**: For writing content.
- **Ananke Theme**: Clean and modern theme for Hugo.
- **GitHub Actions**: Continuous deployment pipeline.
- **GitHub Pages**: Hosting the website.

---

## 📂 **Project Structure**

```
HugoWebsite/
├── archetypes/       # Templates for new content
├── assets/           # CSS, JavaScript, and images
├── config/           # Configuration for Hugo
├── content/          # Markdown files for pages and posts
│   ├── en/           # English content
│   └── fr/           # French content
├── static/           # Static assets (e.g., images, videos)
└── themes/           # Hugo theme (Ananke)
```

---

## 🚀 **Editing Directly on GitHub**

You can easily edit content directly in the GitHub repository without installing Hugo locally. This is ideal for quick updates or non-technical users.

### **1. Navigate to the Content Directory**

- Go to the GitHub repository and navigate to the `content/en/` folder.
- You will find Markdown (`.md`) files for each page.

### **2. Edit a Page**

- Click on the file you want to edit (e.g., `about.md`).
- Click the pencil icon in the top right corner to edit the file.
- Make your changes using Markdown syntax.

### **3. Preview and Commit Changes**

- Scroll down to the bottom of the page.
- You can preview your changes using the built-in GitHub Markdown preview.
- Write a short description of your change and click **Commit changes**.
- You can either commit directly to the `main` branch or create a new branch and open a Pull Request for review.

### **4. GitHub Actions Deployment**

- Once committed, the site will be automatically rebuilt and deployed using GitHub Actions.
- The updated content will be visible at: https://zonge-international.github.io/HugoWebsite/

---

## 🚀 **Running the Site Locally (Advanced Users)**

If you prefer to preview changes locally or are an advanced user, you can install Hugo and run the site on your machine.

### **1. Install Hugo**

Make sure Hugo is installed on your system:

**macOS (Homebrew)**:

```sh
brew install hugo
```

**Windows (Chocolatey)**:

```sh
choco install hugo
```

**Check the version**:

```sh
hugo version
```

### **2. Start the Local Development Server**

```sh
hugo server -D
```

- `-D`: Includes draft content.
- Open your browser and go to: [http://localhost:1313](http://localhost:1313)

---

## 📦 **Deployment**

This website is deployed using **GitHub Pages** and **GitHub Actions**.

### **How It Works**:

- When you push changes to the `main` branch, GitHub Actions automatically builds and deploys the site to:
  ```
  https://zonge-international.github.io/HugoWebsite/
  ```

---

## 🔗 **Useful Links**

- [Hugo Documentation](https://gohugo.io/documentation/)
- [Ananke Theme Documentation](https://github.com/theNewDynamic/gohugo-theme-ananke)
- [Markdown Guide](https://www.markdownguide.org/)

---

## 💬 **Contributing**

Contributions are welcome! If you find a bug or want to suggest a new feature:

1. **Fork** this repository.
2. **Create a new branch** (`feature/your-feature-name`).
3. **Commit your changes**.
4. **Push to your branch**.
5. **Create a Pull Request**.

---

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

## 🤝 **Contact**

For questions or support, please contact the maintainer at:

- **Email**: marc.benoit@zonge.com
- **LinkedIn**: [Zonge International](https://www.linkedin.com/company/zonge-international/)
