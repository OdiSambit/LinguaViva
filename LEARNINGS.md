 
## 📅 Day 0 – Git Setup & Debugging

### 🔴 Problems & Solutions

#### 1. Command Not Recognized (touch error)
- Problem: 'touch' command not working in Windows
- Reason: It is a Linux command not supported in Windows CMD
- Solution: Used alternative methods (echo / manual file creation)
- Learning: OS-specific command differences

#### 2. Git Not Initialized
- Problem: "not a git repository" error
- Reason: Git was not initialized in project folder
- Solution: Ran `git init` inside project directory
- Learning: Importance of initializing version control

#### 3. Authentication Failed
- Problem: GitHub rejected username/password
- Reason: Password authentication is deprecated
- Solution: Generated Personal Access Token and used it
- Learning: Secure authentication using tokens

#### 4. Repository Not Found
- Problem: Git push failed with repo not found
- Reason: Incorrect repository URL (case sensitivity issue)
- Solution: Corrected remote URL with proper casing
- Learning: GitHub URLs are case-sensitive