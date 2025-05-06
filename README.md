# CopyConsole
A secure and lightweight Windows Forms application built with VB.NET, designed for quick copying of folders, scripts, and text to the clipboard. It also offers efficient management of sensitive credentials such as usernames and passwords, securely storing them in an encrypted file using a custom structure.

---
## 🧑‍💻 Usage

The application consists of two tabs: **General** and **Sensitive**

### 🔹 General Tab

This tab is focused on quick copy actions and logoff functionality:

- **Folder Button** – Copies a specified folder to clipboard.
    
- **Script1 / Script2 Buttons** – Copies the content of respective script files to clipboard.
    
- **Text Areas with C/P Buttons** – Two quick-access text fields to paste custom content and copy it back out.
    
- **Logout Group**:
    
    - **Del Logout** – Copies the command to delete a folder and log out of the server.
        
    - **Logout** – Copies the logout command.
        
- **Open Button** – Opens the folder structure in File Explorer so you can manually interact with the folder or scripts.
    
- **On Top Button** – Toggles the application window to stay on top for multitasking convenience.
    

### 🔒 Sensitive Tab

This tab helps manage and protect your credentials:

- **Add Credential** – Use the "New" button to input a tag, username, and password.
    
- **Update Credential** – Select an existing tag and update its details.
    
- **Delete Credential** – Prompts before deletion to avoid accidental loss.
    
- **Copy Credential** – Copies the encrypted password to clipboard.
    
- **Show Credential** – Displays the username and decrypted password in a message box.
    
- **Refresh Button** – To refresh data once some modification is done
---

## ✨ Features

- ✅ **Store credentials** securely with tag, username, and password
    
- ✅ **AES encryption** for all sensitive data
    
- ✅ **Clipboard integration**:
    
    - Copy folder
        
    - Copy content of Script1 and Script2 files
        
    - Copy custom text via quick-access textboxes
        
    - Copy encrypted password for a selected tag
        
- ✅ **editing, deletion, and creation** of credentials via intuitive UI
    
- ✅ **"Stay on Top" toggle** for seamless multitasking

---
## 🔐 Security Model

- **AES encryption** 

---

## 🛡️ Note

All sensitive data is stored locally and encrypted. However, **use this tool for personal use only** and avoid storing highly critical credentials unless the environment is fully secure.

---

## ✅ Requirements

- .NET Framework (4.7.2+ recommended)
    
- Windows 10 or later

## 📄 License
This project is licensed under the MIT License.
