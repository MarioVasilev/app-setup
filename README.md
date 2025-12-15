### Usage:
```powershell
iwr "https://raw.githubusercontent.com/MarioVasilev/app-setup/refs/heads/main/app.json" -OutFile "$env:TEMP\winget.json"; winget import -i "$env:TEMP\winget.json" --accept-source-agreements --accept-package-agreements
