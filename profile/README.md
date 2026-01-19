# Course Experiments Guide

## Table of Contents
- [Course Materials](#course-materials)
- [Assignment Structure & Grading](#assignment-structure--grading)
- [Submission Requirements](#submission-requirements)
- [Experiment Guides](#experiment-guides)
  - [Experiment-1 Guide](#experiment-1-guide)
  - [Experiment-2 Guide](#experiment-2-guide)

---

## Course Materials

All source materials for the course are available at: [github.com/cu-fs1](https://github.com/cu-fs1)

## Assignment Structure & Grading

Each experiment consists of three parts with different difficulty levels:

### Part A - Easy (In-Class)
- **Total Points**: 15
  - Code: 12 points
  - Viva: 3 points
- Completed during class time

### Part B - Medium (Take-Home)
- **Total Points**: 9
  - Code: 5 points
  - Viva: 4 points
- Take-home assignment with deadline

### Part C - Hard (Demonstration)
- **Total Points**: 3
  - Viva: 3 points
- Demonstrated by instructor

**Total Viva Points**: 10 (3 + 4 + 3)

## Submission Requirements

### For Part B (Medium) Assignments

You must submit:

1. **Deployment Link**: Host your code on Vercel or Netlify. {uid}-1a-name. If your uid is 24BDA70021, experiment number is 1b, and your name is Navkaran Singh. The link will be 24bda70021-1a-navkaran-singh.vercel.app
2. **README.md File**: Equivalent to what you write in your practical file
   - Include code snippets
   - Add explanations
   - Document your implementation

### Code Availability

- **Part A & Part B**: Code will remain private until the deadline
- **README.md files**: Available for reference

### Example: Experiment Structure

Let's say **Experiment 1** covers the following topics:

- **Flexbox**
  - README.md file with code snippets and explanations
  - CodeSandbox/Vercel deployment link
  - Source code
- **Grids**
- **Positioning**
- **JavaScript**

---

## Experiment Guides

## Experiment-1 Guide

### Installation and Setup
1. Download and install VSCode.
2. Install Five Server Extension in VSCode. It is a better version of Live Server.

### Resources
1. [flexbox](https://github.com/cu-fs1/flexbox)
2. [positioning](https://github.com/cu-fs1/positioning)
3. [grid](https://github.com/cu-fs1/grid)

---

## Experiment-2 Guide

### Installation and Setup
1. Download and install Node.js from the official website (this also installs npm, the Node package manager).
   - **Node.js**: JavaScript runtime built on Chrome's V8 engine, used to run JavaScript outside the browser.
   - **npm**: Stands for *Node Package Manager*; it manages JavaScript libraries and tools.

2. Open PowerShell or Command Prompt and install pnpm globally using `npm i -g pnpm`.
   - `npm i -g pnpm`
     - `npm`: Node Package Manager CLI.
     - `i`: Short for `install`; tells npm to install a package.
     - `-g`: Short for `--global`; installs the package globally so it can be used from any folder.
     - `pnpm`: Stands for *Performant NPM* (pnpm), an alternative fast package manager that uses a content-addressable store to save disk space.

3. If you encounter an execution policy error on Windows, open PowerShell **as current user** and run `Set-ExecutionPolicy Unrestricted -Scope CurrentUser`.
   - `Set-ExecutionPolicy Unrestricted -Scope CurrentUser`
     - `Set-ExecutionPolicy`: PowerShell command that changes the script execution policy.
     - `Unrestricted`: Allows all scripts to run, but shows a warning before running scripts from the internet.
     - `-Scope CurrentUser`: Applies this policy only to the current user, not system-wide.

### Project Setup
1. Create a folder named `exp-2a` for this experiment.
2. Open the `exp-2a` folder in VSCode so that all commands run in this project directory.
3. Open the terminal in VSCode and run `pnpm create next-app@latest .` to initialize a Next.js app in the current folder.
   - `pnpm create next-app@latest .`
     - `pnpm`: The pnpm CLI, your package manager.
     - `create`: Tells pnpm to run a project scaffolding tool (a "create" script).
     - `next-app@latest`: Uses the *create-next-app* initializer at its latest version to generate a Next.js app.
     - `.`: Dot means "current directory", so the app is created inside `exp-2a` instead of a new subfolder.

### Resources
1. [flexbox](https://github.com/cu-fs1/flexbox)
2. [positioning](https://github.com/cu-fs1/positioning)
3. [grid](https://github.com/cu-fs1/grid)
