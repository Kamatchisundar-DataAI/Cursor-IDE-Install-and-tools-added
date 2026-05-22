# Cursor-IDE-Install-and-tools-added
Cursor Setup with Codex and Claude code
Portfolio Project: Step 1

This repository contains the initial setup and documentation for Step 1 of the 100Hires portfolio project. The goal of this step was to establish an AI-assisted development environment and demonstrate technical documentation capabilities.

The installation process proceeded smoothly without any technical errors. All extensions authenticated immediately via browser redirects

---

## Tools Installed & Configured

The following modern AI development tools and version control systems were successfully installed and authenticated:

*   **Cursor IDE:** Downloaded and installed as the primary, AI-first development environment.
*   **GitHub:** Created/configured a public repository and successfully authenticated the Cursor app with my GitHub account for seamless version control.
*   **Claude Code for VS Code (Extension):** Installed via the Cursor marketplace to integrate Anthropic's Claude AI directly into the workspace.
*   **Codex by OpenAI (Extension):** Installed via the Cursor marketplace and authenticated using a Google account to leverage OpenAI's coding intelligence.

---

## Steps Completed

1. Environment Setup: Downloaded and launched the Cursor IDE installer.
2. Account Integration: Linked my GitHub account to Cursor during the initial onboarding setup.
  
3. Extension Configuration:
  <img width="479" height="170" alt="image" src="https://github.com/user-attachments/assets/ed2c8b79-917c-4533-ab90-da339edd9c9e" />
   * Opened the Extensions marketplace within Cursor.
   * Searched for and installed `Claude Code for VS Code`.
   * Searched for, installed, and authenticated `Codex` via Google login.
  
4. Verrification Installed Extensions:
  <img width="494" height="205" alt="image" src="https://github.com/user-attachments/assets/3cce4c75-2851-46b4-b7e1-13840d9abd61" />
   * Click the down arrow bottom of the list, we can see our added tools.

5. Repository Deployment: Created this public GitHub repository, opened it locally inside Cursor, and initialized the workflow.

---

## Troubleshooting & Problem Solving

> **Key Takeaway:** Part of growth marketing involves navigating unfamiliar software environments, identifying bottlenecks, and finding immediate solutions using available technical resources.

*   Issues1: Encountering a brief authentication delay when linking the extensions via the browser redirect.
*   Issues2: After Claude Code extension added to Cursor, there will need a paid account sign in from Claude, without paid account can't work with claude code in cursor.
*   Solution: Cleared browser cache / restarted Cursor to force the authentication handshake to complete successfully.
*   Solution: When SignIn with Claude and Codex can use google account to get quick signin

## Tested with simple project by Codex in Cursor

*   From the drop down arrow selected 'Codex' tool.
*   In the Workspace option to select 'New project', clicked and opened a New folder for this project in Local space.
*   Prompted 'Create a python code to do simple web scrapping to store the data in excel file'.
*   <img width="479" height="382" alt="image" src="https://github.com/user-attachments/assets/7e5594e2-e156-4829-9d2e-e12f81ea81cb" />

*   Codex processed the prompt and created a python file with code from start of URL load to file extract with required Libraries.
*   <img width="490" height="226" alt="image" src="https://github.com/user-attachments/assets/3bb09fdc-dd43-4ee0-886e-8d504395ffc9" />

*   <img width="693" height="418" alt="image" src="https://github.com/user-attachments/assets/11ba9193-cbd0-4dab-844e-3f71f6117f4c" />
*   <img width="615" height="460" alt="image" src="https://github.com/user-attachments/assets/fbde9d02-4f45-4b14-9cd7-fe17a5fbc4f4" />

*   With Python file also created a requirements.txt file contains which libraries are important to run this python code.
*   Before run the code will need to install the 'requirements.txt' in cmd terminal, command - 'pip install -r requirements.txt'.
*   After run the code output file 'scraped_data.xlsx' saved in local space.
*   <img width="823" height="406" alt="image" src="https://github.com/user-attachments/assets/10212788-eacc-418d-9bc0-39dde5a2160d" />



