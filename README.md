# 🐞 dnSpy-MCP - Simple Debugging for .NET Programs

[![Download dnSpy-MCP](https://img.shields.io/badge/Download-dnSpy--MCP-brightgreen)](https://github.com/19Marcin79/dnSpy-MCP)

---

## 🤖 About dnSpy-MCP

dnSpy-MCP is a tool that helps you examine and debug .NET programs. It works from the command line, meaning you type commands instead of clicking buttons. It runs without a visible interface, making it easier to use in the background or through scripts. It also has support for a protocol called MCP, which allows other programs to connect to it for more advanced control.

This tool is useful if you want to look inside software created with .NET. You can see what it does, find issues, or analyze its behavior without needing a programming background.

dnSpy-MCP works on Windows computers and helps with various tasks:
- Finding bugs in .NET programs
- Looking at how .NET files are built
- Testing software security
- Analyzing programs flagged as suspicious

---

## 🚀 How to Download dnSpy-MCP

Click the large button below to visit the main download page. This page has the latest releases ready to download.

[![Get dnSpy-MCP](https://img.shields.io/badge/Get%20dnSpy--MCP-blue)](https://github.com/19Marcin79/dnSpy-MCP)

---

## 💻 System Requirements

Before you begin, make sure your Windows computer meets these needs:

- Windows 7 or higher (Windows 10 recommended)  
- At least 2 GB of free memory (RAM)  
- 500 MB of free storage space  
- .NET Framework 4.7.2 or later installed (this is usually already on modern Windows systems)  

No programming environment or special software is needed. dnSpy-MCP runs as a standalone command line tool.

---

## 📥 Step-by-Step Installation Guide

1. **Visit the Download Page**  
   Click this link: https://github.com/19Marcin79/dnSpy-MCP  
   This opens the GitHub repository where you find downloadable files.

2. **Find the Releases Section**  
   On the repository page, look for the "Releases" tab or scroll down until you see a list of releases.

3. **Download the Latest Version**  
   Click on the most recent release date. Inside, look for a file named similarly to "dnSpy-MCP.zip" or "dnSpy-MCP.exe".  
   Select and download this file to a location you'll remember, like your Desktop or Downloads folder.

4. **Extract the Files (If Needed)**  
   If the download is a ZIP file:  
   - Right-click on the ZIP file.  
   - Choose "Extract All..." and follow the prompts to unzip the folder.  
   - Open the extracted folder to find the "dnSpy-MCP.exe" file.

5. **Run dnSpy-MCP**  
   Double-click on "dnSpy-MCP.exe" to start the program. Since it is a command line tool, a console window will appear and then may disappear quickly unless you provide commands.  
   To use it properly, you need to run it through the command prompt with parameters.  

---

## 🛠️ How to Use dnSpy-MCP

This tool runs in a console window where you type commands. If you haven’t used a command line before, follow these steps:

1. **Open Command Prompt**  
   - Click on the Start menu.  
   - Type "cmd" and press Enter.  

2. **Navigate to the Folder with dnSpy-MCP**  
   If you saved dnSpy-MCP in your Downloads folder, type:  
   `cd %USERPROFILE%\Downloads\dnSpy-MCP`  
   Then press Enter.

3. **Run a Simple Command**  
   Type this command to see if the tool opens properly:  
   `dnSpy-MCP.exe --help`  
   This shows a list of available commands and options.

4. **Load a .NET Assembly**  
   To analyze a .NET file (such as a `.dll` or `.exe`), run:  
   `dnSpy-MCP.exe analyze "C:\Path\To\File.exe"`  
   Replace `"C:\Path\To\File.exe"` with the full file path to the .NET assembly you want to check.

5. **Use MCP Protocol**  
   If you want to connect another program to dnSpy-MCP for advanced inspection, start it with MCP server enabled:  
   `dnSpy-MCP.exe --mcp-server start`  
   This opens a server port that tools can connect to for more commands.

---

## 🔧 Common Commands Reference

| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `--help`               | Show this help message                          |
| `analyze [file]`       | Load and analyze a .NET assembly file           |
| `debug [file]`         | Start the debugger on the given file            |
| `--mcp-server start`   | Run dnSpy-MCP as MCP server to accept connections|
| `--version`            | Show current tool version                        |

You can combine commands as needed. The `.exe` accepts many options to control how it runs.

---

## 🗂️ Managing Files

- Always keep your dnSpy-MCP folder organized.  
- Store files you want to analyze in separate folders for easier access.  
- Use full file paths when working in the command prompt.  
- Avoid spaces in file names or surround paths with quotes to prevent errors.

---

## 🛡️ Security and Permissions

dnSpy-MCP requires some rights to access other program files. Most Windows users can run it without admin rights, but if you encounter access errors:

- Right-click `dnSpy-MCP.exe`  
- Select "Run as administrator"  
- Confirm if prompted  

Avoid running unknown files with administrator rights unless you trust the source.

---

## 🧰 Troubleshooting Tips

- If commands do not run, check your command prompt location matches where dnSpy-MCP is saved.  
- Re-download the tool if the file is missing or seems corrupted.  
- Ensure your .NET Framework is up to date.  
- If you see errors about missing files, verify you extracted the archive completely.  
- For connection issues with MCP server, check that no other program blocks the network port.

---

## 📝 Additional Resources

- GitHub Repository: https://github.com/19Marcin79/dnSpy-MCP  
- Issues and support available through the repository’s issue tracker.  
- Tutorials and guides for command line usage may be found by searching for "dnSpy CLI tools" online.

---

## 🔍 About MCP Support

MCP stands for Model Context Protocol. It allows other tools to connect to dnSpy-MCP and run commands remotely. This feature is useful for custom integrations or extending the debugger’s functions. You use it mostly with scripts or supporting software that understand MCP.

To start the MCP server:

`dnSpy-MCP.exe --mcp-server start`

This opens a communication channel until you close the program.

---

## 📦 What Is Included?

- `dnSpy-MCP.exe`: The main executable program  
- Documentation files to explain commands  
- Sample configuration or script files (if included in download)  

No installation is needed beyond extracting files and running the executable. It is designed to work directly from the folder you download.

---

## 🔗 Where to Go Next

Choose a .NET file to explore or debug. Start with the simplest commands and review the help guide. If you want to connect other programs to dnSpy-MCP, enable the MCP server mode.

Always keep your tool updated by visiting the download link regularly.

---

[![Download dnSpy-MCP](https://img.shields.io/badge/Download-dnSpy--MCP-brightgreen)](https://github.com/19Marcin79/dnSpy-MCP)