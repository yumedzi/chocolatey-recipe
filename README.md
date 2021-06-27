# Chocolatey recipes
=================

Set of scripts / recipes for a new computer setup using:

* [Chocolatey](https://chocolatey.org/) - works with remote OK
* [Boxstarter](http://boxstarter.org/) - option that doesn't work well with remote

## Setups:

### Choco install

1. Install Chocolatey (run in *Admin Powershell*):
  * `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))`
2. Run [choco_install_all.bat](choco_install_all.bat) in cmd/powershell.

### Boxstarter

Use:
  1. Download and run [RunBoxstarterInstall.bat](RunBoxstarterInstall.bat).
  2. This will launch a download for an executable. 
  2. Run the executable it will download, install, and configure all programs in chocolatey-recipe.txt
