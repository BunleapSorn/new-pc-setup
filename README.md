# 🖥️ New PC Setup ⚙️
My choices of software, extensions and settings for **New Windows-10**. 

## 🍫 Getting Started
Install `Chocolatey` as the main software package manager.

1. #### 👮‍♂️ Administrator Powershell
   Paste the copied text into your shell and press Enter
   ```shell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
   ```
   If you don't see any errors, you are ready to use Chocolatey! Type `choco` or `choco -?`

2. #### ⬆️ Install Chocolatey GUI (for Software Updates)
   Paste the copied text into your shell and press Enter
   ```shell
   choco install chocolateygui
   ```

## 🍫 Software to Install via Chocolatey
#### 💻 Normal Uses
1. Google Chrome `choco install googlechrome`
2. Mozilla Firefox `choco install firefox`
3. Notepad++ `choco install notepadplusplus.install`
4. VLC Media Player `choco install vlc`
5. Winrar `choco install winrar`
6. Zoom `choco install zoom`

#### 🛠️ Development Uses
1. Visual Studio Code `choco install vscode`
2. Git `choco install git.install`

#### 🎥 Production Uses
1. Audacity `choco install audacity`

## Software to Install via Installer
#### 💻 Normal Uses
1. [Notepads](https://github.com/JasonStein/Notepads)

#### 🛠️ Development Uses
1. [NodeJS](https://nodejs.org/en/download/) 

#### 🎥 Production Uses
1. [Adobe Creative Cloud](https://www.adobe.com/creativecloud/desktop-app.html)
   - Adobe Photoshop
   - Adobe Illustrator
   - Adobe XD
   - Adobe Premiere Pro
   - Adobe After Effect
   - Adobe Media Encoder



