--- /dev/null
+++ b/Users/alpha/github-dwdraju/ioenotes/CONTRIBUTING.md
@@ -0,0 +1,107 @@
+# Contributing to IOE Notes
+
+First off, thank you for considering contributing to IOE Notes! We're excited to have your help in making this a valuable resource for all IOE students. Your contributions, whether big or small, are greatly appreciated.
+
+This document provides guidelines for contributing to the project. Please take a moment to review it before submitting your contributions.
+
+## Table of Contents
+
+- [Code of Conduct](#code-of-conduct)
+- [How Can I Contribute?](#how-can-i-contribute)
+  - [Reporting Issues](#reporting-issues)
+  - [Requesting New Content](#requesting-new-content)
+  - [Submitting Changes (Pull Requests)](#submitting-changes-pull-requests)
+- [Contribution Workflow](#contribution-workflow)
+- [Content Guidelines](#content-guidelines)
+  - [For Notes](#for-notes)
+  - [For Syllabus Information](#for-syllabus-information)
+  - [For Past Papers](#for-past-papers)
+- [Style Guides](#style-guides)
+  - [Markdown Style](#markdown-style)
+  - [Commit Messages](#commit-messages)
+- [Setting Up Your Local Environment (Optional)](#setting-up-your-local-environment-optional)
+
+## Code of Conduct
+
+This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior. (Note: You'll need to create a `CODE_OF_CONDUCT.md` file if you don't have one. You can adapt a standard one like the Contributor Covenant.)
+
+## How Can I Contribute?
+
+### Reporting Issues
+
+If you find a bug, a typo, a broken link, or incorrect information on the IOE Notes website, please let us know!
+
+- **Search existing issues:** Before creating a new issue, please check if a similar one has already been reported.
+- **Use the correct template:** We have an Issue Report Template to guide you. Please provide as much detail as possible.
+
+### Requesting New Content
+
+Want to see notes for a subject that's not yet covered, or a syllabus for a specific program?
+
+- **Syllabus Requests:** Use our Syllabus Request Template.
+- **Notes Requests:** Use our Notes Request Template.
+- **Other Content:** For other types of content (e.g., past papers, resources), feel free to open a general issue or a feature request.
+
+### Submitting Changes (Pull Requests)
+
+We welcome contributions to add new content, fix errors, or improve the website!
+
+1.  **Fork the repository:** Create your own copy of the `ioenotes/ioenotes` repository.
2.  **Create a new branch:** For your changes (e.g., `git checkout -b fix-syllabus-typo` or `git checkout -b add-thermo-notes`).
3.  **Make your changes:** Add or edit content. Please follow the Content Guidelines and Style Guides.
4.  **Test your changes:** If possible, build the site locally to ensure everything looks correct and links work.
5.  **Commit your changes:** Write clear and concise commit messages.
6.  **Push to your branch:** `git push origin your-branch-name`.
7.  **Open a Pull Request (PR):** Submit a PR from your forked repository to the `main` branch of `ioenotes/ioenotes`.
+    -   Use our Pull Request Template (it should populate automatically).
+    -   Clearly describe the changes you've made and link to any relevant issues.
+
+## Contribution Workflow
+
+- **Clarity is key:** Ensure your PR description clearly explains the "what" and "why" of your changes.
+- **Review:** Project maintainers will review your PR. We may ask for changes or provide feedback.
+- **Collaboration:** Be open to discussion and collaboration during the review process.
+
+## Content Guidelines
+
+Our goal is to provide accurate, well-organized, and helpful content.
+
+### For Notes
+
+- **Accuracy:** Ensure the information is correct and up-to-date with the IOE curriculum.
+- **Clarity:** Write in clear, understandable language. Use headings, lists, and formatting to improve readability.
+- **Completeness:** Try to cover the relevant topics comprehensively.
+- **Originality/Attribution:** If you are transcribing or summarizing notes, ensure you have the right to share them. If using external resources, provide proper attribution where appropriate.
+- **File Naming:** Use clear and consistent file names (e.g., `subject-name-chapter-1.md`).
+
+### For Syllabus Information
+
+- **Official Sources:** Whenever possible, refer to official IOE syllabus documents.
+- **Accuracy:** Double-check course codes, credit hours, and subject names.
+
+### For Past Papers
+
+- **Legibility:** Ensure scanned documents are clear and readable.
+- **Organization:** Group papers by faculty, year, and subject.
+
+## Style Guides
+
+### Markdown Style
+
+- Use standard Markdown syntax.
+- Keep lines reasonably short (e.g., 80-100 characters) for better readability in raw text format.
+- Use consistent formatting for headings, lists, and code blocks.
+
+### Commit Messages
+
+- Start with a capital letter.
+- Use the imperative mood (e.g., "Fix typo in calculus notes" instead of "Fixed typo..." or "Fixes typo...").
+- Briefly describe the change. For more complex changes, provide more detail in the commit body.
+
+## Setting Up Your Local Environment (Optional)
+
+If you plan to make significant changes or want to preview the site locally, you'll need to set up Hugo. Refer to the project's `README.md` for instructions on how to build and run the site locally.
+
+---
+
+Thank you again for your interest in contributing to IOE Notes!
