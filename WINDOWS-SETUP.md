# BeautyLink Windows Setup Guide 🪟

## 🎯 Quick Start for Windows

### Step 1: Download Node.js
1. Go to: https://nodejs.org
2. Download the LTS version for Windows
3. Run the installer and follow the setup wizard
4. Make sure "Add to PATH" is checked ✅

### Step 2: Verify Installation
1. Press `Windows Key + R`
2. Type `cmd` and press Enter
3. Type: `node --version` (should show v18+ or v20+)
4. Type: `npm --version` (should show version number)

### Step 3: Extract This Project
1. Extract the BeautyLink zip file to your desired location
2. Example: `C:\Users\YourName\Desktop\BeautyLink\`

### Step 4: Open Command Prompt in Project Folder
1. Navigate to the extracted BeautyLink folder
2. Click in the address bar and type `cmd`
3. Press Enter (this opens Command Prompt in the right location)

### Step 5: Install Dependencies
```bash
npm install
```
Wait for installation to complete (2-3 minutes)

### Step 6: Start the App
```bash
npm run dev
```

### Step 7: Open in Browser
Go to: http://localhost:5173

## 🎉 You Should See:
- Beautiful BeautyLink landing page
- Service marketplace with Hair, Nails, Massage, etc.
- Demo navigation to test User and Provider dashboards

## 🔧 Troubleshooting

**Error: "npm is not recognized"**
- Node.js wasn't installed properly
- Restart Command Prompt after installing Node.js

**Error: "Cannot find package.json"**
- You're in the wrong folder
- Make sure you're in the folder that contains package.json

**Port already in use:**
- The app will automatically use the next available port
- Check the terminal output for the correct URL

## 📞 Need Help?
If you encounter any issues, note down:
1. The exact error message
2. Which step you're on
3. What you see in Command Prompt

Happy coding! 🚀
