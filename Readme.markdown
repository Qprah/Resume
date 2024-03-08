---
layout: page
title: Readme
permalink: /readme/
---


# Hosting Your Resume on GitHub Pages: A Guide

## Table of Contents
1. [Introduction](#introduction)
2. [Purpose](#purpose)
3. [Prerequisites](#prerequisites)
4. [Instructions](#instructions)
    - [Step 1: Setting Up Your GitHub Repository](#step-1-setting-up-your-github-repository)
    - [Step 2: Creating Your Resume in Markdown](#step-2-creating-your-resume-in-markdown)
    - [Step 3: Setting Up Your GitHub Pages](#step-3-setting-up-your-github-pages)
    - [Step 4: Uploading Your Resume](#step-4-uploading-your-resume)
    - [Step 5: Customizing Your GitHub Pages](#step-5-customizing-your-github-pages)
5. [Relating to Modern Technical Writing Principles](#relating-to-modern-technical-writing-principles)
6. [More Resources](#more-resources)
7. [Authors and Acknowledgements](#authors-and-acknowledgements)
8. [FAQs](#faqs)

## Introduction <a name="introduction"></a>
Welcome to the guide on hosting your resume on GitHub Pages using Jekyll! In this README, I'll walk you through the steps required to create and host your resume online using GitHub Pages, adhering to the principles outlined in Andrew Etter's book, *Modern Technical Writing.*

## Purpose <a name="purpose"></a>
The purpose of this guide is to help you set up and host your resume on GitHub Pages while also introducing and demonstrating key principles of Modern Technical Writing as advocated by Etter.

## Prerequisites <a name="prerequisites"></a>

Before diving into the process, let's ensure you have everything you need:

- **GitHub account:** This is where your resume will be hosted using [GitHub Pages](https://pages.github.com/). If you don't have one, you can easily create an account for free on [GitHub's website](https://github.com/).

- **Resume formatted in Markdown:** [Markdown](https://www.markdownguide.org/) is a lightweight markup language that allows you to format plain text documents with simple syntax. Having your resume in Markdown format will make it easy to edit and publish online.

- **Markdown editor:** While you can use any text editor to write Markdown, a dedicated Markdown editor like [Typora](https://typora.io/) or [Visual Studio Code](https://code.visualstudio.com/) with Markdown extensions can provide syntax highlighting and other helpful features to streamline the editing process.

- **Ruby installed:** Jekyll, the static site generator we'll be using, is built with Ruby. Make sure you have Ruby installed on your system to run Jekyll locally and build your site. You can download Ruby from the [official website](https://www.ruby-lang.org/en/downloads/).

- **Jekyll for Static Site Generation:** [Jekyll](https://jekyllrb.com/) is a popular static site generator that simplifies the process of building websites. It will convert your Markdown resume into a static HTML website that can be hosted on GitHub Pages. You can install Jekyll via RubyGems by following the instructions on the [Jekyll installation page](https://jekyllrb.com/docs/installation/).

## Instructions <a name="instructions"></a>

### Step 1: Setting Up Your GitHub Repository <a name="step-1-setting-up-your-github-repository"></a>
1. Log in to your GitHub account.
2. Click on the "+" sign in the top right corner and select "New repository."
3. Name your repository `*yourusername*.github.io`. 
4. Choose your repository to be public.
5. Click "Create repository."
![Your username](username.png)

### Step 2: Creating Your Resume in Markdown <a name="step-2-creating-your-resume-in-markdown"></a>
1. Open your favorite Markdown editor.
2. Create a new Markdown file and name it "resume.md."
3. Write or copy and paste your resume content into the Markdown file.
4. Format your resume using Markdown syntax.

### Step 3: Setting Up Your GitHub Pages <a name="step-3-setting-up-your-github-pages"></a>
1. Go to your repository settings.
2. Scroll down to the "GitHub Pages" section.
3. Under "Source," select the branch where your resume Markdown file is located (usually "main" or "master").
4. Choose a theme for your GitHub Pages site (optional).
5. Click "Save."

### Step 4: Uploading Your Resume <a name="step-4-uploading-your-resume"></a>
1. Go back to your repository.
2. Upload your resume Markdown file if you haven't already done so.
3. Commit your changes.

### Step 5: Customizing Your GitHub Pages <a name="step-5-customizing-your-github-pages"></a>
1. Navigate to your GitHub Pages site (usually `username.github.io/repository-name`).
2. Customize your site by editing the `_config.yml` file or directly modifying your Markdown files.
3. Commit your changes.

## Relating to Modern Technical Writing Principles <a name="relating-to-modern-technical-writing-principles"></a>
- **Use of Lightweight Markup Language:** Markdown is a lightweight markup language that allows for easy formatting of text without the complexities of HTML.
- **Format with Static Site Generator:** GitHub Pages, coupled with Jekyll, acts as a static site generator, providing a simple and efficient way to host and manage your resume website.
- **Share/Host on Distributed Version Control System:** By hosting your resume on GitHub Pages, you're utilizing a distributed version control system, enabling collaboration and version history tracking.

## DEMONSTRATION
 ![GIF](my.gif)

## More Resources <a name="more-resources"></a>
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll Documentation](https://jekyllrb.com/docs/)

## Authors and Acknowledgements <a name="authors-and-acknowledgements"></a>
This guide was authored by `Anmolpreet Singh` and adapted from the principles outlined in Andrew Etter's book, Modern Technical Writing.

## FAQs <a name="faqs"></a>
**Q: Why is Markdown better than a word processor?**
A: Markdown is lightweight, easy to learn, and platform-independent, making it ideal for creating and formatting text documents without the need for complex software.

**Q: Why is my resume not showing up on GitHub Pages?**
A: Ensure that your resume Markdown file is properly formatted and located in the correct branch specified in your GitHub Pages settings. Additionally, check for any typos or errors in your Markdown syntax that may be causing rendering issues.