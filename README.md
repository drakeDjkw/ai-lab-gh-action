# ai-lab-gh-action
# AI Lab GitHub Action

This repository contains the code and configuration for the AI Lab project, which utilizes GitHub Actions for continuous integration and deployment, and GitHub Pages for hosting the live website.

## Table of Contents
- [Repository URL](#repository-url)
- [Live Site](#live-site)
- [Project Structure](#project-structure)
- [GitHub Actions Setup](#github-actions-setup)
- [Challenges Faced](#challenges-faced)
- [License](#license)

## Repository URL
- [GitHub Repository](https://github.com/drakeDjkw/ai-lab-gh-action)

## Live Site
- [Live GitHub Pages Site](https://drakedjkw.github.io/ai-lab-gh-action/)

## Project Structure
The project follows a standard web application structure, organized as follows:

/ai-lab-gh-action
├── .github/
│   └── workflows/
│       └── <workflow-files>.yml
├── src/
│   └── <source-code>
├── docs/
│   └── <documentation-files>
├── assets/
│   └── <static-resources>
└── index.html

### Description of Directories
- **/.github/workflows/**: Contains YAML files defining the GitHub Actions workflows.
- **/src/**: Includes the source code for the application (HTML, CSS, JavaScript).
- **/docs/**: Documentation files with additional information about the project.
- **/assets/**: Static resources like images and stylesheets.
- **index.html**: The main entry point for the application.

## GitHub Actions Setup
The setup process for GitHub Actions involves the following steps:

1. **Creating Workflow Files**:
- Created a `.github/workflows/` directory and defined YAML files for workflows.

2. **Defining Steps in YAML**:
- Configured jobs and steps including code checkout, environment setup, dependency installation, testing, and deployment.

3. **Testing Workflows**:
- Committed changes and monitored the Actions tab for successful runs, iterating on configurations as needed.

## Challenges Faced
Encountered several challenges during the setup, including:

1. **YAML Syntax Errors**: Utilized validators to ensure correct syntax and indentation.
2. **Workflow Triggers Not Working**: Reviewed configuration to ensure correct events were specified.
3. **Dependencies and Environment Setup**: Added necessary setup steps in workflow YAML files.
4. **Debugging Failed Workflows**: Enabled detailed logging to identify points of failure.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.