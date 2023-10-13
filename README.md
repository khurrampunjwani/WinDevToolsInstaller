# WinDevToolsInstaller

This repository includes a script for installing common development tools for .NET developers on Windows 11. It uses Chocolatey ([Chocolatey](https://chocolatey.org/)) for downloading and installing packages.

## Setup

Run the following commands:

```pwsh
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://boxstarter.org/bootstrapper.ps1')); Get-Boxstarter -Force; Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/khurrampunjwani/WinDevToolsInstaller/main/WinDevTools.txt -DisableReboots
```

## Features

The script installs the following tools:

Set-WindowsExplorerOptions -EnableShowHiddenFilesFoldersDrives -EnableShowProtectedOSFiles -EnableShowFileExtensions

1. **General**
   - adobereader
   - 7zip.install

2. **Media**
   - vlc
   - spotify

3. **Image Editing**
   - paint.net

4. **Web Browsers**
   - googlechrome
   - firefox

5. **Chat**
   - microsoft-teams

6. **Git**
   - git
   - sourcetree
   - gh
   - oh-my-posh
   - poshgit

7. **Text Editors**
   - notepadplusplus
   - vscode
   - vim
   - nerd-fonts-hack
   - Powertoys

8. **VSCode Extensions**
   - vscode-terraform
   - vscode-azurerm-tools
   - vscode-prettier
   - vscode-icons
   - vscode-gitlens
   - vscode-docker
   - azurefunctions-vscode
   - vscode-markdownlint
   - vscode-powershell

9. **Network Tools**
   - postman
   - fiddler

10. **Dotnet**
    - dotnet-6.0-sdk
    - dotnet-sdk
    - dotpeek

11. **Node.js**
    - nodejs

12. **Azure**
    - azure-cli
    - bicep
    - azd
    - microsoftazurestorageexplorer
    - azure-functions-core-tools
    - azure-cosmosdb-emulator

13. **Terraform**
    - terraform
    - terraform-docs
    - tflint

14. **Security Tools**
    - tfsec
    - trivy

15. **SQL**
    - azure-data-studio
    - sql-server-management-studio

16. **Shells and Terminals**
    - powershell-core
    - pester
    - microsoft-windows-terminal
    - terminal-icons.powershell

17. **Container Tools**
    - docker-cli
    - docker-desktop

## Credits

I got the idea from my friend and colleague, Daniel Hack (<https://www.linkedin.com/in/danielhack/>), and his original script can be found here (<https://gitlab.com/-/snippets/1946822>).

## License

MIT © khurrampunjwani
