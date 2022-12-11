- 👋 Hi, I’m @HerryLT
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git version
git version 2.38.1.windows.1
?? app.js
?? ejemplo.java
?? ejemplo1.py
?? estilos.css
?? index.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
A  index.html
?? app.js
?? ejemplo.java
?? estilos.css
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add estilos.css
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
?? ejemplo.java
?? ejemplo1.py
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "Index1 enviado y estilos"
[master (root-commit) 1216063] Index1 enviado y estilos
 2 files changed, 9 insertions(+)
 create mode 100644 estilos.css
 create mode 100644 index.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
?? app.js
?? ejemplo1.py
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git config --global user.name "DummarCharles"
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git config --global user.email "charles.camasca.upn@gma.com
        ejemplo.java
nothing added to commit but untracked files present (use "git add" to track)
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "Index1 enviado y estilos1"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        app.js
        ejemplo.java
nothing added to commit but untracked files present (use "git add" to track)
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add ejemplo1.py
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "envio python"
 1 file changed, 1 insertion(+)
 create mode 100644 ejemplo1.py
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
?? app.js
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add index.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "envio nuevo index"
On branch master
Untracked files:
        ejemplo.java

nothing added to commit but untracked files present (use "git add" to track)
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add index2.html
 1 file changed, 9 insertions(+)
 create mode 100644 index2.html
f85ff88 envio python
1216063 Index1 enviado y estilosPS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add .
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "se agrego todo y un cambio en index2"   
[master dbe019e] se agrego todo y un cambio en index2
 create mode 100644 app.js
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
dbe019e (HEAD -> master) se agrego todo y un cambio en index2
bf8e61d envio nuevo index 2
f85ff88 envio python
1216063 Index1 enviado y estilos
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add .                                              
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "solo se agrego un h4"                   
[master 18c7178] solo se agrego un h4
 1 file changed, 1 insertion(+)
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git log --oneline                                      
18c7178 (HEAD -> master) solo se agrego un h4
dbe019e se agrego todo y un cambio en index2
bf8e61d envio nuevo index 2
f85ff88 envio python
1216063 Index1 enviado y estilos
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git reset --hard bf8e61d
HEAD is now at bf8e61d envio nuevo index 2
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git reset --hard dbe019e
HEAD is now at dbe019e se agrego todo y un cambio en index2
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git reset --hard 18c7178
HEAD is now at 18c7178 solo se agrego un h4
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> 
 *  Historial restaurado 

nothing to commit, working tree clean
unknown option: -version
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git config --global user.name "HerryHL"
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git config --global user.email "PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git version
git version 2.38.1.windows.1
?? app.js
?? ejemplo.java
?? ejemplo1.py
?? estilos.css
?? index.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
A  index.html
?? app.js
?? ejemplo.java
?? estilos.css
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add estilos.css
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
?? ejemplo.java
?? ejemplo1.py
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "Index1 enviado y estilos"
[master (root-commit) 1216063] Index1 enviado y estilos
 2 files changed, 9 insertions(+)
 create mode 100644 estilos.css
 create mode 100644 index.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
?? app.js
?? ejemplo1.py
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git config --global user.name "DummarCharles"
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git config --global user.email "charles.camasca.upn@gma.com
        ejemplo.java
nothing added to commit but untracked files present (use "git add" to track)
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "Index1 enviado y estilos1"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        app.js
        ejemplo.java
nothing added to commit but untracked files present (use "git add" to track)
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add ejemplo1.py
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "envio python"
 1 file changed, 1 insertion(+)
 create mode 100644 ejemplo1.py
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
?? app.js
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add index.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "envio nuevo index"
On branch master
Untracked files:
        ejemplo.java

nothing added to commit but untracked files present (use "git add" to track)
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add index2.html
 1 file changed, 9 insertions(+)
 create mode 100644 index2.html
f85ff88 envio python
1216063 Index1 enviado y estilosPS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add .
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "se agrego todo y un cambio en index2"   
[master dbe019e] se agrego todo y un cambio en index2
 create mode 100644 app.js
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
dbe019e (HEAD -> master) se agrego todo y un cambio en index2
bf8e61d envio nuevo index 2
f85ff88 envio python
1216063 Index1 enviado y estilos
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add .                                              
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git commit -m "solo se agrego un h4"                   
[master 18c7178] solo se agrego un h4
 1 file changed, 1 insertion(+)
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git log --oneline                                      
18c7178 (HEAD -> master) solo se agrego un h4
dbe019e se agrego todo y un cambio en index2
bf8e61d envio nuevo index 2
f85ff88 envio python
1216063 Index1 enviado y estilos
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git reset --hard bf8e61d
HEAD is now at bf8e61d envio nuevo index 2
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git reset --hard dbe019e
HEAD is now at dbe019e se agrego todo y un cambio en index2
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git reset --hard 18c7178
HEAD is now at 18c7178 solo se agrego un h4
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> 
 *  Historial restaurado 

nothing to commit, working tree clean
unknown option: -version
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git config --global user.name "DummarCharles"
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git config --global user.email "yerico8@gmail.com"
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add index2.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git reset --hard
HEAD is now at 18c7178 solo se agrego un h4
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git version
git version 2.38.1.windows.1
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
 M index2.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git log --oneline
18c7178 (HEAD -> master) solo se agrego un h4
dbe019e se agrego todo y un cambio en index2
bf8e61d envio nuevo index 2
f85ff88 envio python
1216063 Index1 enviado y estilos
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> "
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git add index2.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git reset --hard
HEAD is now at 18c7178 solo se agrego un h4
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git version
git version 2.38.1.windows.1
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git status -s
 M index2.html
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> git log --oneline
18c7178 (HEAD -> master) solo se agrego un h4
dbe019e se agrego todo y un cambio en index2
bf8e61d envio nuevo index 2
f85ff88 envio python
1216063 Index1 enviado y estilos
PS K:\CURSOS_2020\UNALM\PBI-01\TallerBigData\AD021> 
