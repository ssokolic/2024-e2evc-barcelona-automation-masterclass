General

Introduction

https://www.visualstudio.com/en-us/docs/git/create-a-readme

See TEMPLATE repository for templates you can use

A documentation is needed for the following objects:

    - Product
    - Project
    - Repositories within the master branch
    - Scripts
    - Bugs

It is important that commits are linked to respective Work Item in Azure DevOps.

Link commit in User Story when updating a repository

Link Commit in User Story after updating the repository (recommended when using GIT GUI for Commits)

Code Documentation Guidelines

Introduction

Code is typically not documented in office documents. A common way is the use of so-called markdown documents.

Storage Location Source Code

Source code is stored in Git. For this, there is an access for each developer at this time to https://dev.azure.com/XOSS/

Markdown

Markdown is the language used to create technical documentations. The syntax can be found on the following pages:

https://guides.github.com/features/mastering-markdown/
https://blog.ghost.org/markdown/

Documentation

All technical documentation has to be created with MarkDown and has to be pushed to the corresponding Git repository in Azure DevOps.

Every product, project, sub-project or script has to be documented with the following components located in the same folder:

    - README.md
    - CHANGELOG.md
    - CONTRIBUTE.md
    - BUGREPORTING.md

All of these templates can be found in the https://dev.azure.com/XOSS/templates/ project in Azure DevOps

    No commit without proper documentation!

How do I make a good changelog?

Guiding Principles

    - Changelogs are for humans, not machines.
    - There should be an entry for every single version.
    - The same types of changes should be grouped.
    - Versions and sections should be linkable.
    - The latest version comes first.
    - The release date of each version is displayed.
    - Mention whether you follow Semantic Versioning.

Types of changes

    - [Added] for new features.
    - [Changed] for changes in existing functionality.
    - [Deprecated] for soon-to-be removed features.
    - [Removed] for now removed features.
    - [Fixed] for any bug fixes.
    - [Security] in case of vulnerabilities.
