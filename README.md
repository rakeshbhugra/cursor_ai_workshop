# Cursor AI Coding Workshop

Welcome to the Cursor AI Coding Workshop! This repository contains the starter code and resources you'll need to participate in the workshop.

## Pre-requisites for SaaS Workshop

Before attending the workshop, please ensure you have all the required software and tools installed on your machine.

### Required Software & Tools

#### 1. Cursor - AI Code Editor

Cursor is an AI-powered code editor that will be our primary development environment.

- **Official Download**: https://cursor.com/
- **Installation**: Available for Windows, macOS, and Linux
- **Setup**: Simply download and run the installer for your OS

#### 2. UV - Python Environment Management

UV is a fast Python package installer and resolver that will manage our Python environment.

- **Official Installation Guide**: https://docs.astral.sh/uv/getting-started/installation/
- **Quick Install**:
  - **macOS/Linux**:
    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```
  - **Windows**:
    ```powershell
    powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
    ```

- **Note**: UV will automatically handle Python installation
- **Required Python Version**: Python 3.11 or higher (UV will install this for you)

#### 3. NVM - Node Version Manager (for Node.js)

NVM allows you to manage multiple Node.js versions on your machine.

##### For macOS/Linux:
- **Official Installation**: https://github.com/nvm-sh/nvm
- **Install Command**:
  ```bash
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
  ```

##### For Windows:
- **NVM for Windows**: https://github.com/coreybutler/nvm-windows
- **Setup**: Download the installer from the releases page

##### After NVM Installation:
Install Node.js LTS version:
```bash
nvm install --lts
nvm use --lts
```

**Required Node.js Version**: Node 18+ or 20 LTS recommended

#### 4. OpenAI API Key - For LangGraph/LLM Functionality

You'll need an OpenAI API key to work with LLM functionality during the workshop.

- **Get Your API Key**: https://platform.openai.com/api-keys

**Steps to Get Your API Key**:
1. Sign up or log in at https://platform.openai.com/
2. Create a new project (if required)
3. Navigate to "API keys" in the dashboard
4. Click "Create new secret key"
5. **Important**: Copy and save the key immediately (you won't be able to see it again!)
6. Add usage limits to control costs (recommended for workshop use)

**Note**: You'll need to add credits/billing info to use the API. Consider setting a low spending limit for the workshop (e.g., $5-10).

#### 5. Google App Password - For Email Agent Functionality

You'll need a Google App Password to allow the email agent to send emails on your behalf.

- **Generate App Password**: https://myaccount.google.com/apppasswords

**Steps to Generate Your App Password**:
1. Sign in to your Google Account at https://myaccount.google.com/apppasswords
2. You must have 2-Step Verification enabled on your Google account (required for App Passwords)
3. Select "Mail" as the app and choose your device
4. Click "Generate"
5. **Important**: Copy the 16-character password immediately (you won't be able to see it again!)
6. Save this password securely - you'll use it instead of your regular Gmail password

**Note**: If you don't see the App Passwords option, make sure 2-Step Verification is enabled on your Google account first.
