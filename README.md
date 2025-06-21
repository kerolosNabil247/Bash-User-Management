# Bash-User-Management
A comprehensive bash script system for efficient Linux system and user management. This system provides an interactive menu to perform various administrative tasks, including viewing system information, managing user accounts, and ensuring data integrity through automatic backups.

---

## 📌 Features

### 🖥️ System Information

* View hostname, system uptime, kernel version, and disk usage.

### 👤 User Management

* List users with `/bin/bash` as their default shell.

* Search for users and verify their existence.

* Add new users with comprehensive input validation.

* Delete users with automatic backup of their home directories.

* View full user details (UID, GID, groups, shell, and home directory).

* Change user passwords securely.

* Lock and unlock user accounts.

### 📂 Backup on Deletion

* Automatically copies a user's home directory to `/tmp/username_backup` before account deletion, ensuring data preservation.

### 🧪 Validation

* Performs checks to confirm user existence before any operation.

* Provides friendly error messages and clear confirmations for each action, enhancing user experience.

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone (https://github.com/kerolosNabil247/Bash-User-Management.git)
   ```
2. **Navigate into the project directory:**
3. **Make all scripts executable:**
   ```bash
   chmod +x main user1 user2
   ```
   ---

## 🧪 Example Use Cases

| Feature | Description | 
| ----- | ----- | 
| Show System Info | Displays system statistics (hostname, uptime, disk usage, etc.). | 
| List Bash Users | Lists users configured with `/bin/bash` as their shell. | 
| Search User | Checks if a specified user exists on the system. | 
| Add User | Adds a new user account with `sudo` privileges and input validation. | 
| Delete User | Deletes a user account, backing up their home directory. | 
| Show User Details | Shows comprehensive user information (UID, GID, groups, home directory, and shell). | 
| Change Password | Securely resets a user's password. | 
| Lock/Unlock User | Enables or disables user account access. | 
| Exit Program | Safely exits the management script. | 

---

## 👥 Contributors

* [@abdelsalam101](https://github.com/abdelsalam101)

* [@kerolosNabil247](https://github.com/kerolosNabil247)
