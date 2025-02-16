
3## Elevated power-shell terminal Installation of  chocolatey
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### Installing a new laptop script from  GSN
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/dkalog/choco-scripts/refs/heads/main/new-laptop.ps1'))
```


### Installing chocolatey and software for a new laptop
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/dkalog/choco-scripts/refs/heads/main/install-choco-and-new-laptop-software.ps1'))

```

### Installing chocolatey and software for a school 1
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/dkalog/choco-scripts/refs/heads/main/school-1.ps1'))```
https://raw.githubusercontent.com/dkalog/choco-scripts/refs/heads/main/install-choco-and-new-laptop-software.ps1
```
### NON elevated power-shell terminal Installation of chocolatey via:


```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/dkalog/choco-scripts/refs/heads/main/chocolateyInstallNonAdmin.ps1'))
```

