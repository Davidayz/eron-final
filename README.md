# eron-final

# Atividade Avaliativa - Git Colaborativo com Portugol

## Integrantes do grupo
- Carlos Henrique Yudi Endo
- Arthur Daisuke Yamachita dos Santos
- Davi Daisuke Yazima da Silva

## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol que faz uma operação de soma

## Etapas realizadas por cada membro

### Davi Daisuke Yazima da Silva
- No github criei um repositório público com nome de "eron-final" adicionando o arquivo README, após isso convidei os colegas Carlos e Arthur e criei o arquivo portugol.por e dei commit.
- Adicionei usuário com código git config --global user.name "Seu Nome" > git config --global user.email "seuemail@example.com" > ssh-keygen -t rsa -b 4096 -C "seuemail@example.com" enter 3 vezes > eval "$(ssh-agent -s)" > ssh-add ~/.ssh/id_rsa > clip < ~/.ssh/id_rsa.pub > configurações > chave SSH > COLAR
- Criou o arquivo `portugol.por` com a estrutura inicial:
- Escrevi o código:
programa {
  funcao inicio() {
    real n1, n2
    escreva("digite dois números para somar: ")
    leia(n1,n2)
    escreva(n1+n2)
  }
}

### Carlos Henrique Yudi Endo
- Adicionei usuário com código git config --global user.name "Seu Nome" > git config --global user.email "seuemail@example.com" > ssh-keygen -t rsa -b 4096 -C "seuemail@example.com" enter 3 vezes > eval "$(ssh-agent -s)" > ssh-add ~/.ssh/id_rsa > clip < ~/.ssh/id_rsa.pub > configurações > chave SSH > COLAR
- Fez `git pull` após o commit de Arthur.
- Editou o README
 

### Arthur Daisuke Yamachita dos Santos 
- Adicionei usuário com código git config --global user.name "Seu Nome" > git config --global user.email "seuemail@example.com" > ssh-keygen -t rsa -b 4096 -C "seuemail@example.com" enter 3 vezes > eval "$(ssh-agent -s)" > ssh-add ~/.ssh/id_rsa > clip < ~/.ssh/id_rsa.pub > configurações > chave SSH > COLAR
- Fez `git pull` após o commit de Davi.
- Finalizou o algoritmo com lógica, acrescentou n3 na soma.


## Comandos utilizados
Todos os comandos foram executados via terminal utilizando chave SSH:
### Comandos de Davi
compuni@Lab6m51 MINGW64 ~
$ git config --global user.name "Davi"

compuni@Lab6m51 MINGW64 ~
$ git config --global user.email "davidaisuke@edu.unifil.br"

compuni@Lab6m51 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "davidaisuke@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase for "/c/Users/compuni/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:oUbepOmAJ8Jeh6AxVK20unH4Gk8gieNtFh2NneULDzQ davidaisuke@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
| ....  E .       |
|.  . .= =        |
|o.. oo.*o.       |
|++.+oo.*+..      |
|Bo=+oo* So       |
|+*++o+           |
| +==  .          |
| .*.             |
| ...             |
+----[SHA256]-----+

compuni@Lab6m51 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1107

compuni@Lab6m51 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (davidaisuke@edu.unifil.br)

compuni@Lab6m51 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m51 MINGW64 ~
$ ssh -T git@github.com
Hi Davidayz! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m51 MINGW64 ~
$ git clone https://github.com/Davidayz/eron-final.git
Cloning into 'eron-final'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

compuni@Lab6m51 MINGW64 ~
$ cd eron-final

compuni@Lab6m51 MINGW64 ~/eron-final (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

compuni@Lab6m51 MINGW64 ~/eron-final (main)
$ git add .

compuni@Lab6m51 MINGW64 ~/eron-final (main)
$ git commit -m "Preenchendo o por vazio"
[main 888defd] Preenchendo o por vazio
 1 file changed, 8 insertions(+), 1 deletion(-)

compuni@Lab6m51 MINGW64 ~/eron-final (main)
$ git push
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 397 bytes | 397.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Davidayz/eron-final.git
   1d61955..888defd  main -> main

compuni@Lab6m51 MINGW64 ~/eron-final (main)
$

### Comandos de Carlos
compuni@Lab6m40 MINGW64 ~
$ git config --global user.name

compuni@Lab6m40 MINGW64 ~
$ git config --global user.email

compuni@Lab6m40 MINGW64 ~
$ git config --global --unset user.name

compuni@Lab6m40 MINGW64 ~
$ git config --global --unset user.email

compuni@Lab6m40 MINGW64 ~
$ ls -al ~/.ssh
total 21
drwxr-xr-x 1 compuni 1049089   0 Mar 28 20:55 ./
drwxr-xr-x 1 compuni 1049089   0 Apr 11 19:16 ../
-rw-r--r-- 1 compuni 1049089 828 Mar 28 19:49 known_hosts
-rw-r--r-- 1 compuni 1049089  92 Mar 28 19:49 known_hosts.old

compuni@Lab6m40 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m40 MINGW64 ~
$ git config --global user.name "Carlos"

compuni@Lab6m40 MINGW64 ~
$ git config --global user.email "carlosyudi@edu.unifil.br"

compuni@Lab6m40 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "carlosyudi@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase for "/c/Users/compuni/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:/VQ3Z9U/ycgAukfia9yhcNn/FcgbwUQYRhy+7fNCZq8 carlosyudi@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|         .+==o  o|
|        . o+o   o|
|       o . .oo+.*|
|      . *.  ++o*+|
|     . =S+...= ..|
|      + = oo.+o .|
|       = . .=+.. |
|      .     ..+. |
|             Eo. |
+----[SHA256]-----+

compuni@Lab6m40 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 338

compuni@Lab6m40 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (carlosyudi@edu.unifil.br)

compuni@Lab6m40 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m40 MINGW64 ~
$ ssh -T git@github.com
Hi CarlosHenriqueYudi! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m40 MINGW64 ~
$ git clone git@github.com:Davidayz/eron-final.git
Cloning into 'eron-final'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@Lab6m40 MINGW64 ~
$ cd eron-final

compuni@Lab6m40 MINGW64 ~/eron-final (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 377 bytes | 3.00 KiB/s, done.
From github.com:Davidayz/eron-final
   1d61955..888defd  main       -> origin/main
Updating 1d61955..888defd
Fast-forward
 portugol.por | 9 ++++++++-
 1 file changed, 8 insertions(+), 1 deletion(-)

compuni@Lab6m40 MINGW64 ~/eron-final (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 3 (delta 1), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 336 bytes | 2.00 KiB/s, done.
From github.com:Davidayz/eron-final
   888defd..038f751  main       -> origin/main
Updating 888defd..038f751
Fast-forward
 portugol.por | 6 +++---
 1 file changed, 3 insertions(+), 3 deletions(-)

### Comandos de Arthur
daisu@Notebook MINGW64 ~
$ git config
error: no action specified

daisu@Notebook MINGW64 ~
$ git config --global user.name
ArthurDaisuke10

daisu@Notebook MINGW64 ~
$ ssh -T git@github.com
Hi ArthurDaisuke10! You've successfully authenticated, but GitHub does not provide shell access.

daisu@Notebook MINGW64 ~
$ git clone git@github.com:Davidayz/eron-final.git
Cloning into 'eron-final'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

daisu@Notebook MINGW64 ~
$ cd repositorio
bash: cd: repositorio: No such file or directory

daisu@Notebook MINGW64 ~
$ git clone –hhttps://github.com/Davidayz/eron-final.git
fatal: destination path 'eron-final' already exists and is not an empty directory.

daisu@Notebook MINGW64 ~
$ cd eron-final/
bash: cd: eron-final/: No such file or directory

daisu@Notebook MINGW64 ~
$ git pull
fatal: not a git repository (or any of the parent directories): .git

daisu@Notebook MINGW64 ~
$ cd eron-final
bash: cd: eron-final: No such file or directory

daisu@Notebook MINGW64 ~
$ git clone git@github.com:Davidayz/eron-final.git
Cloning into 'eron-final'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 9 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (9/9), done.

daisu@Notebook MINGW64 ~
$ cd eron-final/

daisu@Notebook MINGW64 ~/eron-final (main)
$ git pull
Already up to date.

daisu@Notebook MINGW64 ~/eron-final (main)
$
daisu@Notebook MINGW64 ~
$ git clone git@github.com:Davidayz/eron-final.git
Cloning into 'eron-final'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 9 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (9/9), done.

daisu@Notebook MINGW64 ~
$ cd
.bash_history
.gitconfig
.node_repl_history
.ssh/
.vscode/
Ambiente de Impressão/
Ambiente de Rede/
AppData/
Configurações Locais/
Contacts/
Cookies/
Dados de Aplicativos/
Desktop/
Documents/
Downloads/
Favorites/
IdeaProjects/
Links/
Menu Iniciar/
Meus Documentos/
Modelos/
Music/
NTUSER.DAT

daisu@Notebook MINGW64 ~
$ cd eron-final/

daisu@Notebook MINGW64 ~/eron-final (main)
$ git pull
Already up to date.

daisu@Notebook MINGW64 ~/eron-final (main)
$ git add .

daisu@Notebook MINGW64 ~/eron-final (main)
$ git commit -m"Alteração no por"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

daisu@Notebook MINGW64 ~/eron-final (main)
$ git add .

daisu@Notebook MINGW64 ~/eron-final (main)
$ git commit -m"Alteração do por"
[main 038f751] Alteração do por
 1 file changed, 3 insertions(+), 3 deletions(-)

daisu@Notebook MINGW64 ~/eron-final (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 356 bytes | 356.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:Davidayz/eron-final.git
   888defd..038f751  main -> main

daisu@Notebook MINGW64 ~/eron-final (main)
$

## Observações
Cada etapa foi realizada por apenas um integrante por vez, respeitando a ordem de commits e a integridade do código.