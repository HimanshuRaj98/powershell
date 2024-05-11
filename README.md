# Folder Name Listing Script

The Folder Name Listing Script is a PowerShell tool designed to facilitate the extraction of folder names within a specified directory on your computer. This script streamlines the process, making it accessible to users regardless of their coding proficiency.

## Prerequisites

Ensure that PowerShell is installed on your computer. PowerShell comes pre-installed on Windows operating systems.

## Instructions

### 1. Download the Script

Download the `list_folder_names.ps1` PowerShell script from the repository.

### 2. Open PowerShell

Access PowerShell on your computer. Navigate to the Start menu, search for "PowerShell," and select "Windows PowerShell."

### 3. Navigate to the Script Directory

Using the `cd` command, navigate to the directory where you saved the `list_folder_names.ps1` script. For example:



### 4. Run the Script

Once in the correct directory, execute the script by typing its name and pressing Enter:


This command will initiate the script, generating a list of folder names within the specified directory.

### 5. View the Output

Upon script completion, locate the `folder_names.txt` file in the same directory where you executed the script. This file contains the names of all folders within the specified directory.

### 6. Open the Text File

Open the `folder_names.txt` file using any text editor (e.g., Notepad) to view the compiled list of folder names.

## Important Note

- **Folder Path:**  
  Ensure the correct directory path is specified for listing folder names. You can modify the `list_folder_names.ps1` script using a text editor to adjust the directory path as necessary.

---

- This command will initiate the script, generating a list of folder names within the specified directory.

Alternatively, you can use the following command directly in PowerShell to achieve the same result:
```powershell
Get-ChildItem -Path "Your Directory Folder" -Directory | ForEach-Object { $_.Name } > folder_names.txt
```
For further inquiries or assistance, feel free to reach out. Your feedback is valuable to us!
