### `CONTRIBUTING.md`

```markdown
# Contributing to This Project

## Legal Notice

By submitting any contributions (e.g., code, documentation, issues, feature requests, etc.) to this project, you acknowledge and agree to the following:

- You assign the copyrights of your contributions to Milestone A/S.
- You warrant that your contributions are your own original work and that you have the legal right to assign the copyright.
- You understand that your contributions may be used, modified, and redistributed under this project’s license.

---

## Contributing To The Project

Before you report an issue, it is best to go through the documentation and similar existing issues. If you need further clarification, you can raise an issue on GitHub.
 
When reporting bugs or suggesting new features:

- **Create a new GitHub Issue** using the Issues tab.
- **Mention the sample/module name** (e.g., `Component Integration/Audio Export`).
- For bug reports, include:
  - A **clear and concise description** of the issue.
  - **Steps to reproduce** the issue.
  - **Expected vs. actual behavior**.
  - **Screenshots, logs**, or any supporting material.

- For feature requests:
  - Explain the **need** for the feature.
  - Describe its **advantage or use case**.

Once submitted, the issue will be reviewed by the **owning team** and labeled accordingly (e.g., `bug`, `new feature`, `documentation`).

---

## Forking & Contributing Code

1. **Fork the repository** to your GitHub account.
2. **Create a new branch** with a clear name based on the related issue (e.g., `issue-123-audio-export`).
3. **Make your changes**:
   - Fix the bug or add the feature.
   - Include **code comments** explaining new or changed behavior.
   - **Update any relevant documentation**.

4. **Commit messages**:
   - Start each commit message with the `issue_id` (e.g., `#123-Fix-null-reference-on-Audio-Export`).
   
5. **Pull Request (PR)**:
   - Reference the issue in your PR description (e.g., `Closes #123`).
   - Provide a **detailed explanation** of the change (what, why, how).
   - The PR will be reviewed by the owning team. Reviewers may:
     - Request changes
     - Accept and merge
     - Close with feedback

---

## Code Style & Best Practices

Follow these conventions to ensure clean and maintainable code:

### General Guidelines
- Use **PascalCase** for class, method, and property names.
- Use **camelCase** for local variables and parameters.
- Ensure method and variable names are clear and desctriptive of their function.
- Name the boolean property with an affirmative phrase e.g. Enabled instead of Disabled.
- Empty lines should be used to separate the methods. Use only one empty line.
- Always surround statement by operator brackets even if it's one-line.
- In .Net Core, its is possible to have a appsettings.[environment].json. Any setting in the environment file will overwrite the settings in the normal appsettings.json file. Use these files when developing.
- Ensure **null-checks** and **exception handling**.
- Follow DRY and SOLID
- All switch-statements should have a default case.

---
```

