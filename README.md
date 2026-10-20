ScopeLock

Make targeted code changes. Preserve everything else.

ScopeLock is an AI coding skill designed to prevent unwanted modifications when an AI assistant fixes bugs, updates scripts, or modifies existing features.

It instructs AI coding assistants to focus strictly on the user's requested changes while preserving unrelated functions, existing features, project structure, and established behavior.

Instead of rewriting entire files or refactoring working code, ScopeLock prioritizes minimal, targeted patches that reduce the risk of regressions.

Why ScopeLock?

AI coding assistants can sometimes make unnecessary changes while fixing a specific problem. A simple bug fix may result in rewritten functions, modified UI components, removed features, or unexpected changes to other parts of a project.

ScopeLock establishes strict boundaries around code modifications to reduce these problems.

With ScopeLock, your AI coding assistant is instructed to:

- Fix only the specific bug or feature you request.
- Preserve unrelated functions and existing functionality.
- Avoid unnecessary rewrites and refactoring.
- Keep the original project architecture and file structure.
- Avoid changing UI designs when fixing backend logic.
- Avoid changing application logic when modifying UI styling.
- Preserve existing APIs, database structures, and integrations.
- Avoid adding or removing features without permission.
- Inspect potential side effects before making changes.
- Review modifications for potential regressions.
- Provide complete source files when explicitly requested, without omitting existing code.
- Report which files were modified and what was actually verified.

What Is ScopeLock For?

ScopeLock is intended for developers who use AI assistants to maintain existing projects, fix bugs, and update scripts without unintentionally affecting unrelated functionality.

It is suitable for:

- HTML, CSS, and JavaScript projects.
- React, Next.js, Vue, and other frontend applications.
- Node.js and backend scripts.
- Firebase applications and database integrations.
- API integrations and automation scripts.
- Discord bots and other bot projects.
- Payment systems, checkout flows, and invoice applications.
- Admin dashboards and management panels.
- Existing websites that need targeted fixes.
- Large codebases with interconnected functions and components.

ScopeLock is especially useful when working with existing projects where preserving working functionality is more important than rewriting code.

How It Works

ScopeLock establishes a strict workflow for AI-assisted code modifications.

1. Understand the request

The AI identifies the exact bug, feature, function, or component that needs to change.

2. Inspect the original code

The AI examines the relevant implementation and its dependencies before editing.

3. Identify protected functionality

The AI determines which unrelated features, functions, configurations, and integrations must remain unchanged.

4. Apply a minimal patch

The AI modifies only the necessary code instead of rewriting the entire project.

5. Review potential regressions

The AI checks whether the change could affect other functions or introduce unintended side effects.

6. Verify and report

The AI performs available checks and explains the changes, verification results, and remaining limitations.

Installation

Install ScopeLock using the Skills CLI:

npx skills add zaaneecodingmulu/ScopeLock

Follow the CLI prompts to select the appropriate agent or installation scope if prompted.

Usage

After installing ScopeLock, use your AI coding assistant as usual.

For example:

Bug fixing

Fix the login button because it does not work.
Do not modify any unrelated features or functions.

UI updates

Change the primary button color to blue.
Preserve the existing layout, animations, spacing, and functionality.

Script maintenance

Fix the error in this JavaScript function.
Make the smallest possible change and preserve the rest of the script.

Full-file output

Return the complete updated file.
Apply only the requested fix.
Do not omit, replace, or rewrite unrelated functions.

ScopeLock reinforces these requirements so the assistant has explicit instructions to follow when modifying existing code.

Core Principles

Principle| Description
Strict scope| Modify only what the user requests.
Minimal changes| Prefer targeted patches over rewrites.
Feature preservation| Protect unrelated functionality.
No unauthorized refactoring| Do not refactor without permission.
No silent removals| Preserve existing code unless removal is necessary and authorized.
Regression awareness| Check for unintended side effects.
Honest verification| Never claim tests passed if they were not performed.
User control| Ask before making potentially destructive changes outside the authorized scope.

Important Limitations

ScopeLock provides instructions for AI coding assistants; it does not technically lock files or prevent an AI from making every possible mistake.

Its effectiveness depends on whether the selected AI agent loads and follows the skill.

The skill cannot guarantee that every modification is bug-free, that all existing features remain functional, or that every regression will be detected.

For important projects, use Git, review diffs, run tests, and maintain backups before applying changes.

License

Choose a license appropriate for your intended use and distribution before publishing this repository.

---

ScopeLock — Fix what is broken. Preserve what works.

---

Copy paste to agent ai

```bash npx skills add zaaneecodingmulu/ScopeLock```
