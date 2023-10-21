# Chocolatey Scaffold

This repository contains a PowerShell script that utilizes Chocolatey, a package manager for Windows, to automate the installation of multiple applications listed in a text file.

## Requirements

- PowerShell
- [Chocolatey](https://chocolatey.org/install)

## Files

- `install-apps.ps1`: PowerShell script to install applications using Chocolatey.
- `apps.txt`: Text file containing the list of applications to be installed.

## Usage

1. Ensure that Chocolatey is installed on your machine. If not, follow the [installation instructions](https://chocolatey.org/install).

2. Clone or download this repository to your local machine.

3. Edit `apps.txt` to include the names of the applications you want to install. Each application name should be on a new line. For example:

```
googlechrome
notepadplusplus
vlc
```

4. Open PowerShell and navigate to the directory containing `install-apps.ps1`.

5. Run the script with the following command:

```powershell
.\install-apps.ps1 -filePath "path\to\apps.txt"
```

Replace `path\to\apps.txt` with the actual path to your `apps.txt` file.

6. Confirm the installation when prompted. The script will then proceed to install the applications listed in `apps.txt` using Chocolatey.