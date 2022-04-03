# Shell zsh

## Breve descrição: 

"O Z-shell ou Zsh é um interpretador de comandos UNIX (shell) que, 
dos shells padrão, mais se assemelha ao Korn shell (ksh); sua compatibilidade 
com o shell Korn de 1988 vem aumentando gradualmente. Ele inclui vários tipos 
de aprimoramentos, principalmente no editor de linha de comando, opções para 
personalizar seu comportamento, globbing de nome de arquivo, recursos para fazer 
com que os usuários do C-shell (csh) se sintam mais à vontade e recursos extras 
extraídos do tcsh (outro shell personalizado)" 

##### ref.: https://pt.wikipedia.org/wiki/Z_shell
#


## 1-Instalação do shell zsh:

1.1-Instalação via terminal:

sudo apt install zsh

1.2-Usando o ZSH dentro do mesmo:

zsh

1.3-Para deixar o zsh como shell padrão:

chsh -s /bin/zsh

1.4-Para deixar o bash como shell padrão:

chsh -s /bin/bash

Obs:
Será necessário encerrar a sessão do seu sistema e logar-se novamente, 

podendo reiniciar também, mas isso provavelmente não será realmente 

necessário

#
## 2-Modificando tema do shell zsh

2.1-Instalando tema no zsh

ohmyzsh/ohmyzsh - GitHub

https://github.com/ohmyzsh/ohmyzsh

2.2-Se o git não estiver instalado:

sudo apt install git

2.3Instalando o ohmyzsh:

instalar via wget:

sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"


2.4-Editar o aquivo .zshrc:

(*digitar Ctrl+h) --> o arquivo esta oculto.

Para mudar o tema do shell zsh basta ir ate o arquivo .zshrc e na linha 
ZSH_THEME="robbyrussell" --> robbyrussell = tema padrão
inserir o tema escolhido.

ex:

ZSH_THEME="gnzh"

#
## 3-Diretorio com os temas oh-my-zsh
3.1
No diretório .oh-my-zsh/themes temos os temas do ohmyzsh

3.2
podemos ver os prints de temas em:
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

Exemplo de alguns temas.

bira

cloud

fox

gnzh