 🛠️ Contributing to mern-todo-list

First off, thank you for taking the time to contribute! 🎉

We appreciate your interest in improving \*\*mern-todo-list\*\*.

This document outlines the process for contributing code, opening issues, and submitting pull requests.

\---

 📋 Table of Contents

\- \[Code of Conduct\](#-code-of-conduct)

\- \[How to Contribute\](#-how-to-contribute)

\- \[Creating an Issue\](#-creating-an-issue)

\- \[Setting Up Your Local Environment\](#-setting-up-your-local-environment)

\- \[Making Changes\](#-making-changes)

\- \[Commit Guidelines\](#️-commit-guidelines)

\- \[Pull Request Process\](#-pull-request-process)

\- \[PR Template\](#-pr-template)

\- \[Issue Template\](#-issue-template)

\- \[❤️ Thank You\](#️-thank-you)

\---

\## 🧑‍💻 Code of Conduct

By participating in this project, you agree to uphold our Code of Conduct.

Please be respectful, inclusive, and constructive in all communications.

We’re all here to learn and grow together!

\---

\## 🚀 How to Contribute

We welcome:

\- 🐞 \*\*Bug reports\*\*

\- 💡 \*\*Feature requests\*\*

\- 🧹 \*\*Documentation improvements\*\*

\- 🧩 \*\*Code contributions\*\* (new features or fixes)

Before starting work, make sure there’s an open issue for your contribution.

If not, please create one first so we can discuss and align on the approach.

\---

\## 🐛 Creating an Issue

1\. Go to the \*\*Issues\*\* tab.

2\. Click \*\*“New Issue”\*\* and select the appropriate template:

\- 🧠 \*\*Feature Request\*\* – Suggest new functionality.

\- 🐞 \*\*Bug Report\*\* – Report a problem or error.

\- 📝 \*\*Documentation Issue\*\* – Flag an issue in docs or examples.

3\. Fill out all sections clearly and completely.

4\. Wait for maintainers to review and approve before starting work.

\---

\## ⚙️ Setting Up Your Local Environment

\*\*1. Fork the Repository\*\*

\`\`\`bash

git fork https://github.com//mern-todo-list.git

Or click the Fork button on GitHub.

2\. Clone Your Fork

bash

Copy code

git clone https://github.com//mern-todo-list.git

cd mern-todo-list

3\. Set Up the Upstream Remote

bash

Copy code

git remote add upstream https://github.com//mern-todo-list.git

4\. Install Dependencies

bash

Copy code

\# For both frontend and backend

cd frontend && npm install

cd ../backend && npm install

🌱 Making Changes

Always create a new branch for each change:

bash

Copy code

git checkout -b feature/

\# or

git checkout -b fix/

Example:

bash

Copy code

git checkout -b feature/add-dark-theme

After making changes, test them locally and keep your fork updated:

bash

Copy code

git fetch upstream

git rebase upstream/main

✍️ Commit Guidelines

Use clear, descriptive commit messages.

Use present tense and imperative mood (“Add feature”, not “Added feature”).

Reference related issues if applicable (e.g., Fixes #123).

Examples:

makefile

Copy code

feat(todo): add delete task button

fix(api): correct route for create task

docs: improve contributing guidelines

🚢 Pull Request Process

Push your branch to your fork:

bash

Copy code

git push origin feature/

Go to your fork on GitHub and click “Compare & Pull Request”.

Before submitting your PR:

Follow the PR Template below.

Reference related issues (e.g., Closes #45).

Ensure your changes pass all tests.

Avoid committing unrelated files.

Respond to review feedback constructively.

🧩 PR Template

🧾 Description

Please include a summary of the changes and related issue.

Fixes # (issue number)

✅ Type of Change

🐞 Bug fix

🚀 New feature

🧹 Code cleanup/refactor

📝 Documentation update

⚙️ CI/CD or configuration

🧪 How Has This Been Tested?

Describe the tests you ran:

Unit tests

Manual testing

Other (please describe):

📸 Screenshots (if applicable)

Add screenshots if UI changes were made.

🧠 Checklist

I have read the Contributing Guidelines

I have created an issue and discussed this change

My code follows the project style guidelines

I have tested my changes thoroughly

My PR references the relevant issue(s)

🐞 Issue Template

🧠 Summary

A clear and concise description of the issue.

🧩 Steps to Reproduce

Go to '...'

Click on '...'

Observe error '...'

📸 Expected Behavior

What did you expect to happen?

⚙️ Environment

OS:

Browser/Runtime:

Version:

💡 Additional Context

Add any other context, logs, or screenshots here.

❤️ Thank You

Your contributions make mern-todo-list better!

We’re grateful for your time, effort, and creativity in helping this open-source project grow. 🙌
