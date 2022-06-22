# myExtensions

//to create an extention List, install powershell, type pwsh in the a valid directory and type:
code --list-extensions | ForEach-Object {"code --install-extension $_"} > extensions.ps1
//This will create a PowerShell script file named extensions.ps1 in your chosen directory.

//Now for the final step, simply transfer the created script into a directory on the target machine.
//Navigate to the folder containing the script and run it using the following command:

''PowerShell''
.\extensions.ps1

**more:
https://www.codeproject.com/Tips/4121672/How-to-Export-VS-Code-Extensions-to-Another-Comput

