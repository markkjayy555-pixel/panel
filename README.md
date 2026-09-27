# 🖥️ Panel - Your All-in-One AI Research Workspace

[![Download Panel](https://img.shields.io/badge/Download-Panel-blue?style=for-the-badge&logo=github&color=4CAF50)](https://github.com/markkjayy555-pixel/panel)

## 👋 Welcome to Panel

Panel is a revolutionary research workspace that puts an AI agent right beside you. Imagine having a smart assistant that can chat with you, manage your files, read PDFs, and even create custom tools—all in one place. It's like having a brilliant colleague who never sleeps and is always ready to help you tackle complex problems.

This is an early test version for curious users. You might encounter some rough edges, but that's part of the adventure! If you find any issues, please let us know by creating a report on our GitHub page.

![Panel Screenshot](assets/panel_screenshot.jpg)

## ✨ What Makes Panel Special?

- **Smart Chat Assistant**: Talk to an AI that understands your projects and helps you think through problems
- **Unified File Management**: Keep all your documents, PDFs, and files organized in one dock
- **Interactive Notebooks**: Run code and take notes side-by-side with your AI assistant
- **Custom Viewers**: Let the AI create specialized tools and displays tailored to your needs
- **PDF Power**: Read, analyze, and extract information from your PDF documents effortlessly

## 🚀 Getting Started

Getting Panel up and running is easier than you might think. Below are the simple steps to get started.

### 📦 Step 1: Download Panel

**Visit this link to download the application**: [https://github.com/markkjayy555-pixel/panel](https://github.com/markkjayy555-pixel/panel)

Once you arrive at the GitHub page, you'll find everything you need to get Panel installed. The download page will guide you through the process of getting the application files onto your computer.

### 🛠️ Step 2: Prepare Your Computer

Before you can run Panel, your computer needs a few free tools installed. Don't worry—none of them require programming knowledge to install.

#### **Node.js** (Version 22.18 or newer)
This is a free program that helps Panel run. Visit the [Node.js website](https://nodejs.org/en/download) and download the installer for your computer. Just click through the installation wizard with the default settings.

#### **pnpm** (Package Manager)
Once Node.js is installed, we need one more helper tool called pnpm. You'll install this using the Command Prompt (we'll show you how):

1. Press `Windows Key + R` on your keyboard
2. Type `cmd` and press Enter
3. In the black window that opens, type: `npm install -g pnpm` and press Enter
4. Wait for the installation to finish

#### **uv** (Python Helper)
This small tool handles Python for us automatically. Visit the [uv installation page](https://docs.astral.sh/uv/getting-started/installation/) and download the Windows installer. Run it with the default settings.

#### **Claude Code** (AI Assistant)
Panel needs Claude Code to power its AI features. Visit the [Claude Code setup page](https://code.claude.com/docs/en/setup), download it, and follow their simple installation steps. After installing, run `claude` in that same Command Prompt window and log in with your account. This step is crucial—the AI won't work without it!

### 📁 Step 3: Install Panel

Now that all the helper tools are ready, you can install Panel itself:

1. Open Command Prompt (remember `Windows Key + R`, type `cmd`, press Enter)
2. Navigate to the Panel folder you downloaded (use the `cd` command, like: `cd C:\YourDownloads\panel`)
3. Type `pnpm install` and press Enter, then wait for it to finish
4. Type `uv sync` and press Enter, then wait for it to finish
5. Type `pnpm start` and press Enter

The first time you start Panel, it needs to build itself, which takes about a minute. Be patient! Once it's ready, a window will open showing details about your server.

### 🌐 Step 4: Open Panel

After starting, Panel automatically opens in your web browser at `http://localhost:4173`. You'll see your personal research workspace ready to use!

To stop Panel, go back to the Command Prompt window and press `Ctrl + C`. This safely closes everything.

## 📂 Where Your Data Lives

All your work in Panel is stored in a special database file located at `~/Panel/panel.db`. This file contains all your chats, notes, and project data. It's a good idea to back this up if you want to save your work.

## 🤔 Frequently Asked Questions

**Q: Do I need to be a programmer to use Panel?**
A: Absolutely not! While some setup steps use the Command Prompt, you're just typing a few simple commands. Think of it like following a recipe—no programming knowledge needed.

**Q: What if something goes wrong during install?**
A: Double-check that you completed each step in order. The most common issue is missing one of the helper tools. If problems persist, visit our GitHub page and create an issue report—we're happy to help!

**Q: Will Panel work on older computers?**
A: Panel needs a reasonably recent computer running Windows 10 or newer, with at least 8GB of RAM. If your computer is older, it may still work but could be slower.

## 🐛 Reporting Issues

Since this is an early test version, you might encounter some bugs. We'd love your feedback! Visit our GitHub page at [https://github.com/markkjayy555-pixel/panel](https://github.com/markkjayy555-pixel/panel) and click the "Issues" tab to report any problems you find.

## 📚 Tips for Success

- Always keep your helper tools updated for the best performance
- Save your work regularly by backing up the Panel folder
- Start with simple tasks to get familiar with how Panel works
- Take advantage of the AI assistant's ability to create custom viewers for your specific research needs

## 🌟 Ready to Start?

**Visit this link to download the application**: [https://github.com/markkjayy555-pixel/panel](https://github.com/markkjayy555-pixel/panel)

Panel is your gateway to a more efficient, AI-powered research workflow. Whether you're a student, professional, or curious learner, Panel will transform how you work with information. Download it today and experience the future of research assistance!

Keywords: research workspace, AI assistant, document management, PDF viewer, notebooks, productivity tool, artificial intelligence, file organization, data analysis, knowledge management