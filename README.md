# trabajo-dsw-303
Trabajo - Desarrollo de Software- Comision 3k03-Facundo Quiñonez,Enzo Ferrari, Ignacio Ruiz, Tommy Szalich

git log --graph --pretty=format:'%C(yellow)%h%Creset -%C(cyan)%d%Creset %s %C(green)(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative

git log --graph --pretty=format:'%C(yellow)%h%Creset -%C(cyan)%d%Creset %s %C(green)(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative

git log --all --graph --pretty=format:'%C(bold yellow)%h%Creset %C(bold cyan)%d%Creset %C(auto)%s%Creset %C(bold green)(%cr)%Creset %C(bold blue)<%an>%Creset' --date=relative --stat --color=always

git log --all --graph --pretty=format:'%C(bold yellow)%h%Creset %C(bold cyan)%d%Creset %C(auto)%s%Creset %C(bold green)(%cr)%Creset %C(bold blue)<%an>%Creset' --date=relative --stat --color=always

git log --all --graph --pretty=format:'%C(bold yellow)%h%Creset %C(bold cyan)%d%Creset %C(auto)%s%Creset %C(bold green)(%cr)%Creset %C(bold blue)<%an>%Creset' --date=relative --stat --color=always

git log --all --graph --pretty=format:'%C(bold yellow)%h%Creset %C(bold cyan)%d%Creset %C(auto)%s%Creset %C(bold green)("Fecha: %ad", "Commit del día: %n")%Creset %C(bold blue)<%an>%Creset' --date=format:'%d/%m/%y' --stat

git log --all --graph --pretty=format:'%C(bold yellow)%h%Creset %C(bold cyan)%d%Creset %C(auto)%s%Creset %C(bold green)(%ad, Nro. Commit: %N)%Creset %C(bold blue)<%an>%Creset' --date=format:'%d/%m/%y' --stat | awk -v RS='\0' '{gsub(/%N/, NR-1); print}'
