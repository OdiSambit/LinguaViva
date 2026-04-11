 
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

## 📅 Day 1 – Environment Setup & Debugging

### 🔴 Problems Faced

* Java incorrectly configured (`E:\bin\java.exe`)
* JDK 20 conflict
* PATH variable issues
* Maven not recognized

### 💡 Solutions

* Removed wrong Java path
* Deleted JDK 20 manually
* Cleaned environment variables
* Installed JDK 17 properly in:
  E:\Java\jdk-17

### 🎯 Outcome

* Clean Java setup
* System ready for backend development

### 🧠 Key Learning

* Importance of environment variables (PATH, JAVA_HOME)
* Always use LTS versions (JDK 17)
* Debugging setup issues is critical in development
