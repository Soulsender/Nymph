# Nymph

<img src="assets/logo.png">

Bash script that will rice, and install various tools in the theme of the [Saints](https://saintssec.com).

**ONLY EXECUTE `main.sh`.** The other files are meant to run off `main.sh`, and are not supposed to be executed manually.

Please see `-h` for available options when installing.

### Important Notes
 - When the installer asks if you would like to use `sddm` or any other option (usually `lightdm` or `gdm`) choose whichever one you like. On ParrotOS, `lightdm` is the default login manager. `sddm` is the default login manager for Plasma. `gdm` is the login manager for Gnome (Ubuntu).
 - When you clone the script, **please use the URL or the link generated by github. DO NOT CLONE BY MANUALLY TYPING OUT.** There is a problem that I will fix sometime in the future where it will clone the repository as `nymph` and NOT `Nymph` which will cause some path issues in the script.

### Installation and Usage
Clone the script via:
```
git clone https://github.com/Soulsender/Nymph
```
change directory and execute:
```
cd Nymph/
sudo chmod +x main.sh
sudo ./main.sh
```
and respond to the prompts that will appear. See `-h` for options.

### Credit
 - [Template plasma theme](https://github.com/yeyushengfan258/LyraS-kde)
 - [Saints icons](https://github.com/itsjustshepherd)
