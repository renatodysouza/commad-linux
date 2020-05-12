## Comandos de manipulação de diretório
mkdir - Cria um diretório vazio exemplo: mkdir docs.

rmdir - Exclui um diretório (se estiver vazio).

rm -rf - Exclui um diretório e todo o seu conteúdo.

cd - Entra num diretório (exemplo: cd docs) ou retorna para HOME.

cd / - Muda para o diretório raiz.

cd ~ - vai direto para o diretório home do usuário logado.

cd - - volta ao último diretório acessado.

pwd - Exibe o local do diretório atual.

ls - Lista o conteúdo do diretório.

ls -alh - Mostra o conteúdo detalhado do diretório.

ls -a - Exibe os arquivos "ocultos" do determinado diretório.

ls -ltr - Mostra os arquivos no formado longo(l) em ordem inversa(r) de data (t).

df - Mostra a utilização dos sistemas de arquivos montados pelo usuário do computador.

du -ms - Mostra o tamanho do diretório em Megabytes.

whereis - Mostra onde se encontra determinado arquivo (binários) exemplo: whereis samba.


## Comandos para manipulação de arquivos

cat - Mostra o conteúdo de um arquivo binário ou texto

tac - Semelhante ao cat mas inverte a ordem

tail - Mostra as últimas linhas de um arquivo. Ex: tail -f <arquivo> Útil para visualizar arquivos de log continuamente.
  
head - Mostra as primeiras linhas de um arquivo. Ex: head -100 visualiza as 100 primeiras linhas do arquivo.

less - Mostra o conteúdo de um arquivo de texto com controle

vi - Editor de ficheiros de texto

vim - Versão melhorada do editor supracitado

rm - Remoção de arquivos (também remove diretórios, mas com o parâmetro -r, que significa recursividade)

cp - Copia diretórios 'cp -r' copia recursivamente

mv - Move ou renomeia arquivos e diretórios

chmod - Altera as permissões de arquivos ou directórios

chown - Altera o dono de arquivos ou directórios

cmd>txt - Cria um novo arquivo(txt) com o resultado do comando(cmd)

cmd>>txt - Adiciona o resultado do comando(cmd) ao fim do arquivo(txt)

touch foo.txt - Cria um arquivo foo.txt vazio; também altera data e hora de modificação para agora

> arquivo.txt - Mais rápido que o touch para criação de arquivos

split - Divide um arquivo

recode - Recodifica um arquivo ex: recode iso-8859-15..utf8 file_to_change.txt

## Comandos para administração

man - Mostra o manual do comando.

adduser - Adiciona usuários. O useradd pode também ser usado.

addgroup - Adiciona grupos. O groupadd pode também ser usado.

apropos - Realiza pesquisa por palavra ou string

dmesg - Exibe as mensagens da inicialização(log)

du - Exibe estado de ocupação dos discos/partições

find - Comando de busca ex: find ~/ -cmin -3

userdel - Remove usuários

usermod - Modifica informações de um determinado usuário.

groupmod - Modifica informações de um determinado grupo.

chfn - Altera informação relativa a um utilizador (usuário).

who - Informa quem está logado no sistema. Em algumas versões do Linux, o comando w pode ser usado, e retorna informações mais detalhadas, como o shell do usuário.

whoami - Informa com qual usuário você está logado

passwd - Modifica senha (password) de usuários

umask - Define padrões de criação de arquivos e diretórios

ps - Mostra os processos correntes

ps aux (ou ps -ef) - Mostra todos os processos correntes no sistema

kill - Mata um processo

killall - Mata todos os processos com o nome informado

su - Troca para o super-usuário root (é exigida a senha)

su user - Troca para o usuário especificado em 'user' (é exigida a senha)

chown - Altera o proprietário de arquivos e pastas (dono)


## Comandos para administração de rede

ifconfig - mostra as interfaces de redes ativas e as informações relacionadas a cada uma delas

route - Mostra as informações referentes as rotas

mtr - Mostra rota até determinado IP

netstat - Exibe as portas e protocolos abertos no sistema.

iptraf - Analisador de trafego da rede com interface gráfica baseada em diálogos

tcpdump - Sniffer muito popular. Sniffer é uma ferramenta que "ouve" os pacotes que estão passando pela rede.

traceroute Traça uma rota do host local até o destino mostrando os roteadores intermediários

nslookup - Consultas a serviços DNS

dig - Consultas a serviços DNS
