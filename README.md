# project-startup-cursor

![Project Startup Cursor](https://img.shields.io/badge/Version-1.0.0-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg)

Welcome to the **project-startup-cursor** repository! This repository serves as a management tool for upstream documentation related to Project as Code using Cursor. Here, you will find a structured approach to generate documents based on input information stored in the `/input-docs` directory. The goal is to create documents in Markdown format that align with detailed design and implementation processes.

For more information on Project as Code, please refer to the [Qiita article](https://qiita.com/kumai_yu/items/0aa2fc294f8e1347e36c).

## Table of Contents

- [Repository Structure](#repository-structure)
- [How to Use This Repository](#how-to-use-this-repository)
  - [Step 1: Enter Basic Project Information](#step-1-enter-basic-project-information)
  - [Step 2: Store Project Information in Input Docs](#step-2-store-project-information-in-input-docs)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Repository Structure

Here’s a brief overview of the directory structure in this repository:

```
project-startup-cursor
├── .cursor/
│   └── rules/
│       └── project-design.mdc   // Rules
├── input-docs/                  // Input information storage
├── project-docs/                // Document templates
│   ├── 00_project_management/   // Project management
│   ├── 01_requirements/         // Requirements definition
│   ├── 02_design/               // Design
│   ├── 03_development/          // Development
│   └── 04_operations/           // Operations
├── directory-structure.md       // Directory structure definition
└── project-config.yaml          // Project definition
```

### .cursor/rules

This directory contains rules for generating documents. The `project-design.mdc` file outlines the guidelines to follow.

### input-docs

This is where you will store raw input information relevant to your project.

### project-docs

This folder contains various templates for documentation, organized by category:

- **00_project_management**: Documentation related to project management.
- **01_requirements**: Requirements definition documents.
- **02_design**: Design-related documents.
- **03_development**: Development documentation.
- **04_operations**: Operational documentation.

### directory-structure.md

This file defines the overall directory structure of the repository.

### project-config.yaml

This file is crucial for defining the basic project information.

## How to Use This Repository

### Step 1: Enter Basic Project Information

To start, you need to input your project’s basic information into the `project-config.yaml` file. Here’s a template to guide you:

```yaml
project:
  name: "Project Name"
  created_date: "2025-06-01"

user:
  name: "User Name"
```

### Step 2: Store Project Information in Input Docs

After entering the basic project information, you should store the relevant project data in the `input-docs` directory. This raw data will serve as the foundation for generating your documents.

## Contributing

We welcome contributions from the community. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes.
4. Submit a pull request detailing your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest updates and downloads, visit the [Releases section](https://github.com/MAHMOUDWALID77/project-startup-cursor/releases). You can download the necessary files and execute them as needed.

---

Thank you for your interest in the **project-startup-cursor** repository! We hope you find it useful for your documentation needs. If you have any questions or feedback, feel free to reach out.