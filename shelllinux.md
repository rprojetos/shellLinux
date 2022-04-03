# Personalizando o shell bash:

Parâmetros para colocar no .bashrc:

\d – a data no formato “dia da semana mês data”
\h – o seu hostname sem o grupo de trabalho
\H – o seu hostname com o grupo de trabalho
\n – nova linha
\s – o nome do shell
\t – a hora no formato (24 horas) HH:MM:SS
\T – a hora no formato (12 horas) HH:MM:SS
\@ – a hora no formato (12 horas) AM / PM
\A – a hora no formato (24 horas) AM / PM
\u – o usuário que está usando o shell
\v – a versão do bash (ex. 4.4)
\V – a versão + patch do bash (ex. 4.4.12)
\w – o caminho completo do diretório atual, com $HOME abreviado com um ‘til’
\W – apenas o nome do diretório atual, com $HOME abreviado com um ‘til’
\$ – o simbolo # (caso root) ou $ (outros usuários)
\\ – uma barra invertida

Cor de fundo
40 - Preto
41 - Vermelho
42 - Verde
43 - Amarelo
44 - Azul
45 - Magenta (Rosa)
46 - Ciano (Azul Claro)
47 - Branco

Atributo da fonte
00 - Reset (Nenhum) 
01 - Negrito 
04 - Sublinhado 
05 - Piscante 
07 - Reverso 
08 - Oculto

Cor da fonte
30 - Preto
31 - Vermelho
32 - Verde
33 - Amarelo
34 - Azul
35 - Magenta (Rosa)
36 - Ciano (Azul Claro)
37 - Branco

Sintaxe:
'\e[COR_DE_FUNDO;ATRIBUTO_DA_FONTE;COR_DA_FONTEm \e[m'

Exemplo:
PS1="\e[40;00;32m\u@\h:\e[40;00;34m\W\$ \e[m"

Acrescentar no fim do arquivo .bashrc