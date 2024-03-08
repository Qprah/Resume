---
layout: page
title: README
permalink: /readme/
---


# Hosting Your Resume on GitHub Pages: Inspired by Andrew Etter's  ***Modern Technical Writing***

___
## **Table of Contents**
1. [Introduction and Purpose](#intro)
3. [Prerequisites](#prerequisites)
4. [Instructions](#instructions)
    - [Step 1: Establishing Your GitHub Repository](#step-1)
    - [Step 2: Cloning Your Repository](#step-2)
    - [Step 3: Jekyll: Installation and Configuration](#step-3)
    - [Step 4: Create Your Markdown Resume](#step-4)
    - [Step 5: Local Testing](#step-5)
    - [Step 6: Publish Online](#step-6)
5. [Relating to Modern Technical Writing Principles](#relating)
6. [More Resources](#more-resources)
7. [Authors and Acknowledgements](#authors-and-acknowledgements)
8. [FAQs](#faqs)

___
## **Introduction and Purpose** <a name="intro"></a>
Welcome to the guide on hosting your resume on GitHub Pages using Jekyll! Here, I'll walk you through the process while incorporating the principles outlined in Andrew Etter's book, [*Modern Technical Writing*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). GitHub Pages, coupled with [Jekyll](https://jekyllrb.com/), offers an excellent platform for showcasing your resume online. By following the steps outlined in this guide, you'll not only learn how to set up your resume on [GitHub Pages](https://pages.github.com/) but also gain insights into applying modern technical writing principles to create clear and concise documentation.

___
## **Prerequisites** <a name="prerequisites"></a>

1. **A GitHub account:** Your resume will be hosted on GitHub Pages. Sign up for a free account on [GitHub](https://github.com/).
2. **Resume in Markdown:** Convert your resume to [Markdown](https://www.markdownguide.org/) for easy editing and publishing.
3. **Markdown editor:** Use Typora or Visual Studio Code with Markdown extensions for efficient editing.
4. **Ruby installed:** Jekyll, our static site generator, requires Ruby. Download Ruby from the [official website](https://www.ruby-lang.org/en/downloads/).
5. **Jekyll for Static Site Generation:** Install Jekyll via RubyGems. Follow the instructions on the [Jekyll installation page](https://jekyllrb.com/docs/installation/).

___
## **Instructions** <a name="instructions"></a>

### Step 1: Establishing Your GitHub Repository <a name="step-1"></a>

1. **Access GitHub:** Begin by logging in to your [GitHub](https://github.com/login) account.

1. **Create a New Repository:** Click on the "+" sign in the top right corner and select "New repository."

1. **Name Your Repository:** Choose a name in the format `yourusername.github.io`, ensuring to replace "yourusername" with your actual GitHub username.

1. **Set Repository Visibility:** Ensure your new repository is set to public to allow others to view it.

1. **Finalize Repository Creation:** Click "Create repository" to complete the setup.

___
### Step 2: Cloning Your Repository <a name="step-2"></a>
**Handling a Remote Repository**: Consider utilizing web-based interfaces such as Atlassian Bitbucket or GitHub for managing remote repositories. According to Etter, tools like Atlassian [SourceTree](https://www.sourcetreeapp.com/) and [GitHub Desktop](https://desktop.github.com/) provide user-friendly interfaces for repository management.

#### **Using Github Desktop**
1. **Access Your Repository:** Once your repository is created, navigate to its page on GitHub.

1. **Clone Repository:** Click on the green "Code" button and select "Open with GitHub Desktop."

1. **Open GitHub Desktop:** If you don't have GitHub Desktop installed, download and install it from [here](https://desktop.github.com/).

1. **Clone Repository:** In GitHub Desktop, you'll see your repository listed under "Recent repositories." Click on it to open.

1. **Choose Local Path:** Choose the local path where you want to clone your repository by clicking "Choose...".

1. **Clone Repository:** Click the "Clone" button to clone the repository to your local machine.


By following these steps, you'll successfully clone your GitHub repository to your local machine, enabling you to work on your project locally and synchronize changes with the remote repository on GitHub.

___

### Step 3: Jekyll: Installation and Configuration <a name="step-3"></a>

1. **Deploying Jekyll:** If Jekyll hasn’t been set up on your system, refer to the [official installation guide](https://jekyllrb.com/docs/installation/) provided for Windows users.
   
2. **Initialization of Jekyll within Your Repository:** Access your cloned repository directory in the Windows Command Prompt terminal and execute the command `jekyll new "Your Desired Folder Name"`.
   
3. **Config Setup:** Utilize your preferred text editor to open the `_config.yml` file. Within this file, you can customize various settings such as the site’s title, authorship details, description, and theme.

___
### Step 4: Create Your Markdown Resume <a name="step-4"></a>
As mentioned by Etter in his book, Markdown is the “most widely used lightweight markup language in the world and has the cleanest syntax”, therefore, adhering to the principle of simlicity and accessibility.

1. **Set Up Your Markdown Editor:**
   Choose a Markdown editor or use a text editor that supports Markdown formatting. Some popular options include Visual Studio Code, Atom, or Typora.

2. **Create a New Markdown File:**
   Open your Markdown editor and create a new file with a `.md` extension. Name it something like `resume.md`.

**Formatting Tips:**
- Etter suggests utilizing [GitHub Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) to enhance readability. Use headings for section titles, bullet points for lists, and links to showcase your professional work or profiles.

___
### Step 5: Local Testing <a name="step-5"></a>

1. **Launching Local Server:** Execute `bundle exec jekyll serve` in the Windows Command Prompt terminal within your project root directory. 
- This command hosts your site locally at `[http://localhost:4000]`. 
- `Ctrl + Left Mouse Click` on the provided URL to preview your resume.

___
### Step 6: Publish Online <a name="step-6"></a>

1. **Commit Changes:** Open Git Desktop, select your repository, stage your changes, add a brief commit message, and then commit.

1. **Push to GitHub:** After committing, push your changes to your GitHub repository by clicking the "Push origin" button.

1. **View Online:** Once pushed, visit `[https://yourusername.github.io]` in a web browser to see your updated resume live.

___
## **Relating to Modern Technical Writing Principles** <a name="relating"></a>
- **Use of Lightweight Markup Language:** Markdown is a lightweight markup language that allows for easy formatting of text without the complexities of HTML.

- **Format with Static Site Generator:** GitHub Pages, coupled with Jekyll, acts as a static site generator, providing a simple and efficient way to host and manage your resume website.

- **Share/Host on Distributed Version Control System:** By hosting your resume on GitHub Pages, you're utilizing a distributed version control system, enabling collaboration and version history tracking.

___
## **Demo**
 ![GIF](my.gif)

___
## **More Resources** <a name="more-resources"></a>
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll Documentation](https://jekyllrb.com/docs/)

___
## **Authors and Acknowledgements** <a name="authors-and-acknowledgements"></a>
This guide was authored by `Anmolpreet Singh` , edited by `Zander Apalit, Seyi Asoga` and adapted from the principles outlined in Andrew Etter's book, Modern Technical Writing.

___
## **FAQs** <a name="faqs"></a>
**Q: Why is Markdown better than a word processor?**

A: Markdown is lightweight, easy to learn, and platform-independent, making it ideal for creating and formatting text documents without the need for complex software.

**Q: Can I customize the design of my resume on GitHub Pages?**

A: Yes, GitHub Pages allows for customization using Jekyll themes and HTML/CSS modifications. Explore available themes or create your own to personalize the design of your resume according to your preferences.

**Q: Is it possible to include interactive elements like forms or JavaScript on my resume hosted on GitHub Pages?**

A: GitHub Pages has limitations on dynamic content and JavaScript execution for security reasons. While you can include basic HTML elements and forms, complex interactive features may not work as expected. Consider alternative platforms or hosting solutions if you require advanced interactivity.