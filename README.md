FOR WINDOWS:

Steps beforehand:

[Install Scoop using their readme](https://github.com/ScoopInstaller/Install#readme)

Create document for $PROFILE: `New-Item -ItemType File -Path $PROFILE -Force`

Now, open it in notepad and copy content of other document: `notepad $PROFILE`, and save it.

Install necessary items with scoop: `scoop install file ripgrep zoxide bat less btop duf fzf` (and optionally git)

Now do `. $PROFILE` and you're ready.

FOR LINUX:

`sudo apt update && sudo apt upgrade -y`

`sudo apt install -y ripgrep fzf zoxide btop duf`

Download the provided bash_commands.txt file, move it to the directory you're in in the terminal, and run `cat bash_commands.txt >> ~/.bashrc`

Now do `source ~/.bashrc` and you're ready.
