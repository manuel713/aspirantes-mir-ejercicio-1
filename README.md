Diana@DESKTOP-0KGDHV4 MINGW64 ~
$ git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


Diana@DESKTOP-0KGDHV4 MINGW64 ~
$ git config --global user.name "Daniel"

Diana@DESKTOP-0KGDHV4 MINGW64 ~
$ git config --global user.email "danielsanabria77@gmail.com"

Diana@DESKTOP-0KGDHV4 MINGW64 ~
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Daniel
user.email=danielsanabria77@gmail.com

Diana@DESKTOP-0KGDHV4 MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/Diana/.git/

Diana@DESKTOP-0KGDHV4 MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/Diana/.git/

nothing added to commit but untracked files present (use "git add" to track)

Diana@DESKTOP-0KGDHV4 MINGW64 ~ (master)
$ ls
'3D Objects'/
 AppData/
'Configuración local'@
 Contacts/
 Cookies@
'Datos de programa'@
 Desktop/
 Documents/
 Downloads/
 Dropbox/
'Entorno de red'@
 Favorites/
 Impresoras@
 IntelGraphicsProfiles/
 Links/
'Menú Inicio'@
 MicrosoftEdgeBackups/
'Mis documentos'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{1427d07a-f59d-11ea-abb9-c59245750222}.TM.blf
 NTUSER.DAT{1427d07a-f59d-11ea-abb9-c59245750222}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{1427d07a-f59d-11ea-abb9-c59245750222}.TMContainer00000000000000000002.regtrans-ms
 Nox_share/
 OneDrive/
 Pictures/
 Plantillas@
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
'VirtualBox VMs'/
 inittk.ini
 inst.ini
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 nuuid.ini
 rule.xml
 source/
 state.xml
 useruid.ini
 vmlogs/

Diana@DESKTOP-0KGDHV4 MINGW64 ~ (master)
$ cd Documents/

Diana@DESKTOP-0KGDHV4 MINGW64 ~/Documents (master)
$ cd Makeitreal/

Diana@DESKTOP-0KGDHV4 MINGW64 ~/Documents/Makeitreal (master)
$ cd EJERCICIOS/

Diana@DESKTOP-0KGDHV4 MINGW64 ~/Documents/Makeitreal/EJERCICIOS (master)
$ commit -m "Version Inicial"
bash: commit: command not found

Diana@DESKTOP-0KGDHV4 MINGW64 ~/Documents/Makeitreal/EJERCICIOS (master)
$ git init
Initialized empty Git repository in C:/Users/Diana/Documents/Makeitreal/EJERCICIOS/.git/

Diana@DESKTOP-0KGDHV4 MINGW64 ~/Documents/Makeitreal/EJERCICIOS (master)
$ git add ejercicio1

Diana@DESKTOP-0KGDHV4 MINGW64 ~/Documents/Makeitreal/EJERCICIOS (master)
$ git commit -m "Version Inicial"
[master (root-commit) 587db1b] Version Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md

Diana@DESKTOP-0KGDHV4 MINGW64 ~/Documents/Makeitreal/EJERCICIOS (master)
$ git commit -m "Agrega solucion primer ejercicio"
On branch master
nothing to commit, working tree clean

