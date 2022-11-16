# INTRODUÇÃO AO GIT E AO GITHUB  :computer:



### Introdução ao Git

​	O Git é um sistema de versionamento de código distribuído, ou seja, é um _software_ que ajuda a criar e monitorar diferentes versões de um código. Foi inicialmente projetado e desenvolvido por Linus Torvalds para o desenvolvimento do Kernel Linux, já que nenhum dos sistemas disponíveis na época atendia suas necessidades.



### Navegação via Command Line Interface (CLI)

​	Em vez de possuir uma interface gráfica do usuário (_Graphical User Interface_ - GUI), o Git utiliza uma interface de linha de comandos.

​	Alguns dos comandos mais utilizados:

dir - abre uma lista de diretórios contidos na pasta em que está situado

mkdir - cria um diretório

rmdir - remove um diretório com todos seus arquivos dentro

cd - navega entre diretórios

cd .. - volta a um diretório

cls - limpa o terminal

echo - imprime de volta um texto no terminal

del - deleta arquivos de um diretório



### Tópicos fundamentais para entender o funcionamento do Git

##### SHA1

​	A sigla SHA significa _Secure Hash Algorithm_ (Algoritmo de Hash Seguro). É um conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA).

​	Um algoritmo de encriptação gera um conjunto de caracteres de 40 dígitos. Esse conjunto é único, pois serve para identificar o objeto de encriptação.

##### Objetos internos do Git

- _Blobs_

  O Git manipula através de objetos. Os arquivos ficam guardados dentro desse objeto chamado _blob_, que contém metadados. Ele possui as seguintes informações:

  - O tipo de objeto (_blob_);
  - O tamanho da _string_;
  - \0;
  - O conteúdo desse arquivo.

- _Trees_

  As _trees_ (na tradução, árvores) armazenam _blobs_. Elas são responsáveis por montar a estrutura de onde estão localizados os arquivos. Podem apontar para _blobs_ ou outras _trees_.

- _Commit_

  É o objeto que junta tudo. Ele aponta para uma árvore, um parente (último _commit_ realizado), um autor, e uma mensagem.



### Chave SSH e _Token_

##### Chave SSH

​	É uma forma de estabelecer uma conexão segura e encriptada entre duas máquinas. Cada máquina gera duas chaves, sendo uma privada e uma pública.



##### _Token_ de acesso pessoal

​	Se assemelha à senha comum e é solicitado ao clonar um repositório a partir de uma URL HTTPS.



### Primeiros comandos com Git

ls - lista os diretórios

mv - move o arquivo para outro diretório

git init - inicializa repositório Git

git add - move arquivos para a _staging area_

git commit -m "<mensagem>" - cria um commit



### Ciclo de vida dos arquivos no Git

​	Os arquivos rastreados pelo Git são denominados _tracked_. Podem se subdividir em três estágios diferentes: _unmodified_, _modified_, e _staged_. Há também os arquivos ainda não rastreados, _untracked_.

_untracked_ - arquivos de um diretório onde ainda não aconteceu a inicialização do repositório Git

_unmodified_ - arquivos que ainda não sofreram alteração após terem sido "commitados"

_modified_ - arquivos que já sofreram modificação

_staged_ - arquivos que estão preparados para fazer parte de um _commit_



### Introdução ao GitHub

git remote add origin <link> - cadastra um repositório remoto

git remote -v - lista os repositórios remotos cadastrados

git push origin master - empurra para o repositório remoto



### Resolvendo conflitos

​	Caso o repositório remoto estiver mais atualizado que o repositório local, basta utilizar o comando "git pull origin master", e resolver manualmente os conflitos de _merger_ se houver diferenças na mesma linha.

​	Para clonar repositórios, usar o comando "git clone <link>".



