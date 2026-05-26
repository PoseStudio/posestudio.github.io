# Contributing to PoseStudio.org

First off, thank you for considering contributing to PoseStudio! 

Community contributions are what make open-source projects thrive.

> **Note:** This repository is strictly for the PoseStudio website (posestudio.org) and documentation. If you want to contribute to the core 3D character and animation software, please visit our main **[PoseStudio Application Repository](https://github.com/PoseStudio/PoseStudio)**.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). We expect all contributors to maintain a respectful and welcoming environment.

## Repository Structure

All website content, HTML documents, and Markdown files are located inside the `/docs` directory. When making edits to pages, navigation, or styling, please ensure you are working within this folder. 

## How You Can Help

There are several ways you can contribute to the website:

* **Content & Documentation:** Fix typos, clarify confusing instructions, or write entirely new content about the PoseStudio project inside the `/docs` folder.
* **Site Architecture:** Improve our HTML accessibility, refine CSS/UI elements, or help optimize our technical SEO and structured data.

## Local Development Setup

To preview your changes locally before submitting them, you will need to run the site using Jekyll from within the `/docs` directory.

1. **Fork** the repository and clone your fork locally:
```bash
   git clone https://github.com/PoseStudio/posestudio.github.io.git

```

2. **Navigate** to the documentation directory:

```bash
   cd posestudio.github.io/docs

```

3. **Install dependencies** (Requires Ruby and Bundler):

```bash
   bundle install

```

4. **Serve the site:**

```bash
   bundle exec jekyll serve

```

5. Open `http://localhost:4000` in your browser. The site will automatically rebuild when you save changes to files.

## Pull Request Process

When you are ready to submit your changes, please follow these steps to ensure a smooth review process:

1. **Create a new branch** for your feature or fix:

```bash
   git checkout -b update/index-homepage

```

2. **Make your changes** and test them locally. Ensure all HTML/Markdown formatting renders correctly and no links are broken.
3. **Commit your changes** with a clear, descriptive commit message:

```bash
   git commit -m "Update hero section layout in index.html"

```

4. **Push** your branch to your fork on GitHub.
5. **Open a Pull Request (PR)** against the `main` branch of the official `PoseStudio/posestudio.github.io` repository.

### PR Requirements

* Provide a clear summary of what you changed in the PR description.
* If your PR fixes an open issue, link to it (e.g., "Closes #12").
* If you are adding a new section to a page, ensure it follows the formatting style of existing content.

## Reporting Bugs

If you find a broken link, a visual bug on mobile, or an SEO issue, please check the [Issue Tracker](https://www.google.com/search?q=https://github.com/PoseStudio/posestudio.github.io/issues) to see if it has already been reported. If not, open a new issue and include:

* The URL where the bug occurs.
* What you expected to see vs. what actually happened.
* Your browser and operating system.

*(Note: For security vulnerabilities, do not open a public issue. Please refer to our [SECURITY.md](SECURITY.md) for private reporting instructions).*

```
