 Open an elevated power-shell terminal to install choco package manager

## Installing chocolatey
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### Installing a new laptop script from  GSN
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://gitlab.com/dkalog/chocolatey-scripts/-/raw/main/new-laptop.ps1'))
```


### Installing chocolatey and software for a new laptop
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://gitlab.com/dkalog/chocolatey-scripts/-/raw/main/install-choco-and-new-laptop-software.ps1'))

```

### Installing chocolatey and software for a school 1
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://gitlab.com/dkalog/chocolatey-scripts/-/raw/main/install-choco-and-school1-software.ps1'))
```
