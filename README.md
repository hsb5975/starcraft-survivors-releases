# StarCraft Survivors — downloads

Windows installers for **StarCraft Survivors**, an unofficial, non-profit Vampire Survivors-style fan game by BLUETAG.

> Not affiliated with or endorsed by Blizzard Entertainment. StarCraft is a trademark of Blizzard Entertainment, Inc.
> These downloads contain **no Blizzard files**: on first launch the game reads graphics and sounds from your own StarCraft: Remastered install.

This repository only hosts the installers under [Releases](https://github.com/hsb5975/starcraft-survivors-releases/releases). The game's source code is not published here.

## Requirements

- Windows 10 or later (64-bit)
- StarCraft: Remastered installed on the same PC (free on Battle.net)

## Install

1. Download `StarcraftSurvivors-Setup-<version>.exe` from the [latest release](https://github.com/hsb5975/starcraft-survivors-releases/releases/latest).
2. Optional but recommended: verify the file (below).
3. Run the installer. It installs for your Windows user only and needs no administrator rights.
4. The installer is not code-signed yet, so Windows SmartScreen may say "Windows protected your PC". Choose **More info** → **Run anyway**.

Saves and settings live in `%APPDATA%\StarcraftSurvivors`; uninstalling keeps them.

## Verify your download

Every release includes `SHA256SUMS.txt`. In PowerShell:

```powershell
Get-FileHash .\StarcraftSurvivors-Setup-1.0.0.exe -Algorithm SHA256
```

The hash must match the line for that file in `SHA256SUMS.txt`. If it does not, do not run the file and tell us on Discord.

## Help and feedback

- Website: https://www.bluetag.workers.dev/games/starcraft-survivors/
- Discord (support, feedback, update notes): https://discord.gg/EBjNH6QyDu

---

## 한국어 안내

BLUETAG이 만든 비공식·비영리 팬 게임 **스타크래프트 서바이버**의 Windows 설치 파일 저장소입니다. 블리자드 엔터테인먼트와 관계없으며, 설치 파일에 블리자드 데이터는 들어 있지 않습니다. 처음 실행할 때 PC에 설치된 스타크래프트: 리마스터(Battle.net 무료)에서 그래픽과 소리를 읽어 옵니다.

1. [최신 릴리스](https://github.com/hsb5975/starcraft-survivors-releases/releases/latest)에서 `StarcraftSurvivors-Setup-<버전>.exe`를 받습니다.
2. PowerShell에서 `Get-FileHash <파일> -Algorithm SHA256` 결과가 `SHA256SUMS.txt`와 같은지 확인합니다.
3. 설치 파일은 아직 코드 서명이 없어서 "Windows의 PC 보호" 창이 뜰 수 있습니다. **추가 정보** → **실행**을 누르면 됩니다. 관리자 권한 없이 사용자 폴더에 설치됩니다.

문의와 버그 제보는 [Discord](https://discord.gg/EBjNH6QyDu)로 해 주세요.
