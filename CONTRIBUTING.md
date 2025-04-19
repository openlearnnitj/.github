# Contributing to OpenLearn NITJ Projects

Hey there! 👋 We're stoked you're interested in contributing to projects under the OpenLearn NITJ banner. Whether it's fixing a bug, adding a feature, improving documentation, or sharing an idea, your help is valuable!

This document provides some guidelines to make contributing smooth for everyone.

## Code of Conduct

First things first: all participation in OpenLearn NITJ projects is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it to understand the expectations for respectful and inclusive collaboration.

## How Can I Contribute?

There are many ways to contribute:

*   **Reporting Bugs:** Find something broken? Let us know!
*   **Suggesting Enhancements:** Have an idea to make a project better? Share it!
*   **Writing Code:** Help fix bugs or implement new features.
*   **Improving Documentation:** Clear docs are crucial! Fix typos, clarify steps, add examples.
*   **Helping Others:** Answer questions on Discord or in GitHub Issues.

## Getting Started

*   **Find Something to Work On:** Check the `issues` tab on individual project repositories. Look for issues tagged `good first issue` or `help wanted`.
*   **Ask Questions:** Not sure where to start? Hop onto our [Discord Server](discord.gg/) and ask in the relevant project channel or a general help channel!

## Reporting Bugs

*   **Check Existing Issues:** Before creating a new bug report, please search the existing issues to see if someone else has already reported it.
*   **Use the Bug Report Template:** When you create a new issue, select the "Bug Report" template if available. Provide as much detail as possible:
    *   Clear steps to reproduce the bug.
    *   What you expected to happen vs. what actually happened.
    *   Your environment (OS, browser, tool versions, etc.).
    *   Screenshots if applicable.

## Suggesting Enhancements

*   **Check Existing Issues:** Search existing issues first to see if your idea has already been suggested.
*   **Use the Feature Request Template:** If available, use the "Feature Request" template when creating a new issue. Explain:
    *   The problem your enhancement solves.
    *   A clear description of the feature you'd like.
    *   Any alternative solutions you considered.

## Submitting Changes (Pull Requests)

Ready to contribute code or documentation? Awesome! Here’s the general workflow:

1.  **Fork the Repository:** Create your own copy of the project repository on GitHub.
2.  **Create a Branch:** Make a new branch in *your fork* for your changes. Use a descriptive name (e.g., `fix-login-bug`, `add-user-profile-feature`). Don't work directly on the `main` branch.
    ```bash
    git checkout -b your-branch-name
    ```
3.  **Make Your Changes:** Write your code or update documentation.
4.  **Test Your Changes:** Make sure your changes work as expected and don't break anything else. (Add tests if applicable!)
5.  **Commit Your Changes:** Write clear, concise commit messages explaining *what* you changed and *why*.
    ```bash
    git commit -m "Fix: Correct calculation in user summary"
    # or for multiple changes
    git add .
    git commit -m "Feat: Add user profile editing functionality"
    ```
6.  **Push to Your Fork:** Push your branch to your fork on GitHub.
    ```bash
    git push origin your-branch-name
    ```
7.  **Open a Pull Request (PR):** Go to the original OpenLearn NITJ repository on GitHub. You should see a prompt to create a Pull Request from your new branch.
    *   Use the Pull Request template if provided.
    *   Clearly explain the changes you made.
    *   Link any relevant issues (e.g., "Closes #123").
    *   Request reviews from project maintainers if needed.

## Coding Style (If Applicable)

Some projects might have specific coding style guidelines or use linters/formatters (like Prettier, ESLint, Black). Please try to follow the existing style in the codebase or check for a project-specific `CONTRIBUTING.md` or style guide file. Consistency makes the code easier to read and maintain!

---

Thanks for contributing! Your efforts help make OpenLearn NITJ a great place to learn and build together. 