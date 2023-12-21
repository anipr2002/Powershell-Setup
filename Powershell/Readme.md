# STEPS FOR SETTING UP YOUR POWERSHELL

## Requirements (Follow docs for installation)
> Powershell (Microsoft Store) <br>
> Scoop / Winget <br>
> NerdFonts (https://www.nerdfonts.com/font-downloads) <br>
> oh-my-posh (https://ohmyposh.dev/docs/installation/windows) <br>
> WSL 


**After installing the requirements mentioned above, please change the font in the Powershell settings. Powershell > Appearance**

Check if Powershell profile file exists:
```
echo $PROFILE
```
You should get something like this back
> C:\Users\<user-name>\Documents\PowerShell\Microsoft.PowerShell_profile.ps1

Confirm it by checking it inside the File Explorer.If there is not PowerShell folder present inside Documents:
```
mkdir PowerShell
cd PowerShell
$null > Microsoft.PowerShell_profile.ps1
code .
```

Then paste the code provided inside the Microsoft.PowerShell_profile.ps1 file and Restart the terminal. 

Installing Modules

1. Terminal Icons
   ```
   Install-Module -Name Terminal-Icons -RequiredVersion 0.9.0
   ```
2. PSReadline
   ```
   Install-Module -Name PSReadLine -RequiredVersion 2.2.6
   ```
3. Z (Directory jumper)
   ```
   Install-Module -Name z
   ```
4. PSFzf (Fuzzy Finder)
   ```
   Install-Module -Name PSFzf -AllowPrerelease
   ```

### Oh my posh with terminal icons
![Imgur](https://i.imgur.com/SYI08SX.png)

### Auto Complete suggestions
![Imgur](https://i.imgur.com/sbFXQQ6.png)

### Fuzzy Finder ( f + ↵ )
![Imgur](https://i.imgur.com/LXGtOlI.png)
