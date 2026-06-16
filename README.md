steps beforehand:

[Install Scoop using their readme](https://github.com/ScoopInstaller/Install#readme)

Create document for $PROFILE: `New-Item -ItemType File -Path $PROFILE -Force`

Now, open it in notepad and copy content of other document: `notepad $PROFILE`

Save it, and do `. $PROFILE` in terminal to move into updated profile
