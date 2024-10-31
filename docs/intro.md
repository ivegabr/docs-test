---
sidebar_position: 1
title: Introduction
---

# Devportal automation PoC

This is the Proof od Concept of the Devportal Automation Project.

From the documentation displayed on the Devportal for different projects, there are sections that can be static, not frequently updated, and there are sections that need to be frequently updated, and have to be aligned with the project's repository, like the readme, set up instructions, and other pieces of documentation.

## How it works

- A section is created for a specific project on the Devportal, with an intro page.
- Within that section, subsections can be added, that contain info about the project, instructions for the set up, etc.
- The subsections's content will be the same as the content that exists on the repository
- When there is an update on the documentation at the project's repository, the service will automatically open a Pull Request on the Devportal's repository with the changes
- The Devportal's owner will have then the opportunity to review the PR, accept it, or request changes to the owner of the project
- Once the PR is approved and merged, the updated documentation will be automatically deployed to production

Now, lets see how this works on a repository.