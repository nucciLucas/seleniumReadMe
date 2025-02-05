# seleniumReadMe
🛠 Step 1: Transfer Your Project Folder
- Copy your project folder to the other computer via:
- Once copied, place it in a convenient location (e.g., C:\Projects\SeleniumTest on Windows or ~/Projects/SeleniumTest on macOS/Linux).
---
🖥 Step 2: Install Node.js and npm
- Download Node.js (LTS version) from [nodejs.org](https://nodejs.org/).
- Install it by following the setup wizard.
- Verify the installation by running the following commands in Command Prompt/Terminal:
```bash
  node -v
  npm -v
```
- This should display Node.js and npm versions.
---
📦 Step 3: Install Project Dependencies
- Open Command Prompt/Terminal.
- Navigate to the project folder:
```bash
  cd path/to/your/project
```
- Install required dependencies using npm:
```bash
  npm install
```
---
▶️ Step 4: Run Your Selenium Script
- Once everything is set up, execute your script:
```bash
node main.js
```
--------
🛠 Troubleshooting
1. "chromedriver not found" or similar error
- Ensure chromedriver.exe (or geckodriver) is in the same folder as your script or added to PATH.
2. "npm not recognized"
- Restart the computer to apply the Node.js installation.
3. Browser does not open
- Check if the browser is installed.
