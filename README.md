# Git Workshop Fortis
1. **Benötigte Software**
  * Git: https://gitforwindows.org/
  * Kommandozeile / Terminal: git-bash (enthalten im letzen Link) / cmd / gnome-terminal / etc.
  * Texteditor: Notepad++ / etc.
  * Browser: Chrome / etc.
2. **Git Konfiguration**
  * In der Kommandozeile ausführen:
    * git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --all --max-count=20"
3. **Setup für den Workshop**
  * Dieses Repository klonen - Kommandozeile öffnen und:
    * cd code
    * git clone https://github.com/cinocode/ws_git.git
    * cd ws_git
  * Im code Verzeichnis 'git lg' ausführen, wenn eine Zeile mit 'Initial commit' zu sehen ist, dann ist Git richtig eingerichtet. Wenn diese nicht zu sehen ist, bitte im Fortis Slack Channel zu diesem Workshop melden.
  * In ~/code/ws_git ist die Datei index.html
    * Im Browser öffnen
    * Im Texteditor öffnen
  * Ready to work and shop!
