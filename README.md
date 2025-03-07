# Інсталяція

### Крок 1: Інсталювати chocolate
```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### Крок 2: Встановити залежності
```powershell
choco install php --version=8.1.27 symfony-cli composer postman
``` 

### Крок 3: Клонувати репозиторій
```git
git clone https://github.com/DmitriyShevchuk/api.git
```

### Крок 4: Встановити залежності копмозера
```powershell
cd api
```
```powershell
composer install
```

### Крок 5: Запустити сервер
```powershell
symfony serve
```

# Документація
[Нажми на мене](https://documenter.getpostman.com/view/42930052/2sAYdoE6uJ#intro)
