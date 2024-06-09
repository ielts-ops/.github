# Welcome to the IELTS Team GitHub Repository

## Introduction

Welcome to the IELTS Operations team GitHub! This platform serves as the central hub for collaboration, version control, and code sharing within our team. This guide will help you get started with the basics, and with setting up Git and GitHub access using Anaconda.

## Table of Contents

1. [What is Git and Github?](#what-is-git-and-github)
2. [Installing Git with Anaconda](#installing-git-with-anaconda)
3. [Configuring Git](#configuring-git)

## What is Git and GitHub?

**Git** is a distributed version control system that enables multiple contributors to work on a project simultaneously, tracking changes and managing collaboration efficiently. It allows developers to create branches, merge changes, and maintain a complete history of project modifications. It is installed and used through the Command Line, though there is a graphic interface edition available.

**GitHub**, on the other hand, is a web-based platform built around Git. It provides a centralized location for hosting Git repositories, offering collaboration features such as pull requests, issues, and project management tools. GitHub simplifies team workflows, facilitating seamless collaboration, code review, and integration into continuous integration / continuous delivery pipelines (CI/CD). It serves as a hub for open-source projects and a secure space for version-controlled code repositories.

The IELTS Operations Github is entirely private, only visible to invited members of our team.

## Getting Started with Git and GitHub

**GitHub** is a key platform for collaborative software development using Git. Before setting up Git, ensure you have a GitHub account. If you don't have one, you can create an account on [GitHub's Sign Up page](https://github.com/signup). Having a GitHub account allows you to host repositories, contribute to projects, and benefit from the collaborative features GitHub provides, such as pull requests, issues, and discussions.

Once your GitHub account is ready, you can proceed to set up Git on your local machine and start contributing to projects hosted on GitHub.

## Installing Git with Anaconda

To install Git using Anaconda, follow these steps:

1. Open the Anaconda Command Line or Anaconda Navigator.
2. Make sure that your Conda is up to date by running the command `conda update -n base conda`
3. Install Git: ` conda install anaconda::git`

This will install Git globally on your system.

## Configuring Git

After installing Git, you need to configure it with your name and email. Open the Anaconda Command Line and run the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

This doesn't necessarily need to be your GitHub username and email - you will be prompted for your credentials later in the process.

## Getting Started

There's a Wiki here which should cover many of the basics you need to get started. We would recommend taking a look at the following articles in order:

- [Introduction: How Git & GitHub Work](https://github.com/ielts-ops/.github/wiki/How-Git-and-Github-Work)
- [Git Basics: Terms and Commands](https://github.com/ielts-ops/.github/wiki/Git-Basics:-Terms-and-Commands)
- [How to Create Your First Repository](https://github.com/ielts-ops/.github/wiki/How-to-Create-Your-First-Repository)
- [Everyday Working with Git: Cheatsheet](https://github.com/ielts-ops/.github/wiki/Working-with-Git:-Cheatsheet)
- [Pull Requests](https://github.com/ielts-ops/.github/wiki/Pull-Requests)
- [Good Practices with Git and GitHub](https://github.com/ielts-ops/.github/wiki/Good-Practices-with-Git-and-Github)

For more information and support, Percipio offers a course on Git and GitHub. You can also find more resouses on the [Additional Resources] page, and many tutorials on YouTube which provide a good intro to Git, GitHub and version control.
