## Thanks for 100+ stars

```
 _   _____   __   ____  ___  ___   _  ________                
| | / / _ | / /  / __ \/ _ \/ _ | / |/ /_  __/__________  ____
| |/ / __ |/ /__/ /_/ / , _/ __ |/    / / / /___/ __/ _ \/ __/
|___/_/ |_/____/\____/_/|_/_/ |_/_/|_/ /_/     /_/ / .__/\__/ 
                                                  /_/         
```

> Show your Valorant match info on Discord Rich Presence!

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![GitHub License](https://img.shields.io/github/license/colinhartigan/valorant-rpc)](https://github.com/colinhartigan/valorant-rpc/blob/master/LICENSE)
[![Discord](https://img.shields.io/badge/discord-join-7389D8?style=flat&logo=discord)](https://discord.gg/uGuswsZwAT)
[![GitHub issues](https://img.shields.io/github/issues/colinhartigan/valorant-rpc)](https://github.com/colinhartigan/valorant-rpc/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/colinhartigan/valorant-rpc)](https://github.com/colinhartigan/valorant-rpc/pulls)
![GitHub Repo stars](https://img.shields.io/github/stars/colinhartigan/valorant-rpc?style=social)
[![BetterREADME Verified](https://img.shields.io/badge/BetterREADME-Verified-grey?logo=github&labelColor=white&logoColor=grey)](https://github.com/better-readme)


### Table of Contents
1. [Demo](#demo)
2. [Getting Started](#getting-started)
3. [Current Features](#current-features)
4. [FAQ](#faq)
5. [What's next](#whats-next)
6. [Contribute](#contribute)
7. [Dependencies](#dependencies)
8. [Legal](#legal)

<br/>

## Demo
![Demo 1](https://cdn.discordapp.com/attachments/751830529409810576/878766647798812692/Demo1.png)
![Demo 2](https://media.discordapp.net/attachments/751830529409810576/878766648935464980/Demo2.png)

<br/>

## Getting Started
### Setup

**Download the `.exe` from [here](https://github.com/colinhartigan/valorant-rpc/releases/latest)**

> __NOTE__: Your antivirus might mark the executable as malware, but this is a side effect of building the executable with PyInstaller. Check [FAQ](#faq) for further information and steps to get back your file.
> _I've rebuilt the executables with Python 3.7 and it seems they aren't being marked as malware anymore!_

If you'd rather build the executable yourself, download the release `.zip` file and run `build.bat`, or `run.bat` to execute the script directly. To test the latest features, [join the Discord server and download the latest beta](https://discord.gg/uGuswsZwAT).

### Usage
- Run the program instead of launching VALORANT
     - If VALORANT is not running, the program will launch it for you
- If VALORANT is already running, launch the program and the presence will start

<br/>

## Current Features
* Show game mode and party size
* Show if you are in Menu or In-game

<br/>

## FAQ
**Q: Why does windows defender say it's a virus?**
A: [@markhank:](https://medium.com/@markhank/how-to-stop-your-python-programs-being-seen-as-malware-bfd7eb407a7)
>Code compiled using pyinstaller or py2exe is often incorrectly to be malware or a virus or a trojan by various antivirus programs. It can often have scary names like Trojan:Win32/Wacatac.C!ml.
This is most likely what is known in the virus industry as a “false positive”. Your code might not be doing anything malicious, but because it was compiled in a way that looks a bit like other code which might do malicious things antivirus judges it to be a virus.

To recover the `.exe` from Windows Defender:
1. Open Windows Defender
2. Select  **Virus & threat protection**  and then click  **Protection history**
3. In the list of all recent items, filter on  **Quarantined Items**
4. Select the `.exe`, press the **Actions** button, and press Restore

To prevent Windows Defender from quarantining the file again:
1. Open Windows Defender
2. Select  **Virus & threat protection**  and under  **Virus & threat protection setting** click **Manage settings**
3. Scroll down to **Exclusions** and click **Add or remove exclusions**
4. Click **Add an exclusion**, click **File** and then select the downloaded`.exe`file

<br/>

## What's next
- [ ] TBD

<br/>

## Contribute
Have an idea or a suggestion? Drop an issue or create a pull request!

<br/>

## Dependencies
Check [requirements.txt](https://github.com/colinhartigan/valorant-rpc/blob/master/requirements.txt) for updated infomation!
```
requests
valclient
Flask
cursor
pystray
Flask_Cors
psutil
urllib3
pypresence
pyperclip
iso8601
InquirerPy
Pillow
```

<br/>

## Legal
This project is not affiliated with Riot Games or any of its employees and therefore does not reflect the views of said parties. This is purely a fan-made project to enhance VALORANT's skin inventory management.

Riot Games does not endorse or sponsor this project. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc. 
