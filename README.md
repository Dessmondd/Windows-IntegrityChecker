# Windows-IntegrityChecker

The Windows-IntegrityChecker is a PowerShell script that allows you to monitor changes in files within a specified directory. It helps you detect new files, file modifications, and deleted files by comparing their current hash values with a stored baseline.

**Prerequisites**
PowerShell
Cloned or downloaded copy of this repository in your local machine.
Open a PowerShell terminal and navigate to the repository directory.
Customize the script by modifying the variables, paths, or algorithms to align with your specific needs.

**Option A: Collecting a New Baseline**
<ul>
<li>Ensure you have a folder named "Files" in the same directory as the PowerShell script.
<li>Place the files you want to monitor in the "Files" folder.</li>
<li>Run the script by executing .\file_monitoring.ps1 in the PowerShell terminal.</li>
<li>The script will calculate the hash for each file and store them in the baseline.txt file.</li> 
**Option B: Monitoring Files with Saved Baseline**
</ul>
<ul>
<li>Clone or download the repository containing the File Monitoring Tool.</li>
<li>Open a PowerShell terminal and navigate to the repository directory.</li>
<li>Execute the script by running .\file_monitoring.ps1 in the PowerShell terminal.</li>
<li>The script will continuously monitor the files in the specified directory for any changes.</li>
<li>Any new files created will be displayed with a green notification message.</li>
<li>Modified files will trigger a yellow notification message.</li>
<li>Deleted files will be highlighted with a red notification message.</li>
</ul>

![image](https://github.com/Dessmondd/Windows-IntegrityChecker/assets/97458634/e2e7ecee-04b7-4e4e-aed0-1bbfe412af31)

**Contributions**
Contributions are welcome! If you encounter any issues, have suggestions, or would like to add new features to the File Monitoring Tool, feel free to submit a pull request or open an issue in the GitHub repository.

**License**
This project is licensed under the MIT License.

