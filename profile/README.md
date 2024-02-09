# Welcome to the IELTS Team GitHub Repository

## Introduction

Welcome to the IELTS Operations team GitHub! This platform serves as the central hub for collaboration, version control, and code sharing within our team. This guide will help you get started with the basics, and with setting up Git and GitHub access using Anaconda.

## Table of Contents

1. [What is Git and Github?](#what-is-git-and-github)
2. [Installing Git with Anaconda](#installing-git-with-anaconda)
3. [Configuring Git](#configuring-git)

## What is Git and GitHub?

**Git** is a distributed version control system that enables multiple contributors to work on a project simultaneously, tracking changes and managing collaboration efficiently. It allows developers to create branches, merge changes, and maintain a complete history of project modifications.

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

There's a Wiki here which should cover many of the basics you need to get started. We would recommend taking a look at the following articles:

- [Introduction: How Git & GitHub Work]
- [How to Create Your First Repository](https://github.com/ielts-ops/.github/wiki/How-to-Create-Your-First-Repository)
- [Git Basics: Terms and Commands](https://github.com/ielts-ops/.github/wiki/Git-Basics:-Terms-and-Commands)
- [Committing, Pulling and Pushing: How to Save and Upload Changes]
- [Working on an Existing Repository: Cloning](
- [Creating and Managing Branches]
- [Good Practices with Git and GitHub](https://github.com/ielts-ops/.github/wiki/Good-Practices-with-Git-and-Github)

For more information and support, Percipio offers a course on Git and GitHub. You can also find more resouses on the [Additional Resources] page.

## Cloning a Repository

How do you download a repository to your local system? To fetch a respository remotely stored on GitHub, navigate to the folder you want to store it in and `clone` the repository using the following command:

```bash
git clone git@github.com:organization/repository.git
```

Replace "organization/repository" with the actual organization and repository name. This creates a copy of this repository on your computer. You can now make changes locally and save them to GitHub.

There is a lot of terminology to get used to with Git and GitHub. A save is called a `commit` - think of it like committing something to memory - and to upload that change you `push` it from your local computer to the online repository.
