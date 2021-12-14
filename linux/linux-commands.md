### Comandos relacionados aos diretórios do sistema

- `ls`: comando utilizado para listar (daí a singla `ls`) os arquivos que estão contidos no seu diretório atual.
- `ls -l`: lista os arquivos do diretório atual com mais informações, como data de modificação, usuário que modificou/criou o arquivo, dentre outras informações.
- `ls -a`: lista todos os arquivos, incluindo os arquivos ocultos (que iniciam com um ponto).
- `cd`: significa *change directory*, ou seja, é um comando para alterar o diretório em que você se encontra. Se executado sem um complemento, irá te levar para o diretório `/home`. O complemento desse comando pode ser qualquer caminho (path) para uma outra pasta do disco; ou apenas `..` para retornar para a pasta anterior à atual.
- `mkdir`: comando para criar uma pasta (*make directory*).
- `rmdir`: comando para remover uma pasta (*remove directory*). Funciona apenas se a pasta estiver vazia.
- `rm`: comando utilizado para remover pastas ou arquivos. Para remover uma pasta/diretório você deve utilizar o comando da seguinte forma: `rm -r nome_da_pasta`.
- `pwd`: comando para exibir o diretório (estrutura das pastas) atual. Vem do inglês, *print working directory.*

### Comandos relacionados à arquivos

- `touch`: comando para criar um arquivo qualquer. Por isso, você deve utilizar esse comando sempre acompanhado do nome do arquivo e a extensão dele. Por exemplo: o comando `touch exemplo.py` irá criar o arquivo `exemplo.py`.
- `nano`: comando utilizado para editar um arquivo dentro do próprio terminal. Sempre deve vir acompanhado do nome do arquivo, por exemplo: o comando `nano exemplo.py` irá abrir o arquivo `exemplo.py` no modo de edição.
- `cat`: comando utilizado para exibir no terminal o conteúdo do arquivo. Sempre deve vir acompanhado do nome do arquivo, por exemplo: o comando `cat exemplo.py` irá exibir o conteúdo do arquivo `exemplo.py`.
- `mv`: mover um arquivo de um diretório para outro diretório. Por exemplo, o comando `mv arquivo1.txt Documentos/` vai **mover** o *arquivo1.txt* para a pasta *Documentos*.
- `cp`: copiar um arquivo de um diretório para outro diretório. Por exemplo, o comando `cp arquivo1.txt Documentos/` vai **copiar** o *arquivo1.txt* para a pasta *Documentos*.
- `rm`: remover um arquivo. Por exemplo, para remover o arquivo `exemplo.py`, podemos utilizar o comando `rm exemplo.py`.

### Comandos para instalar/atualizar/remover programas

- `sudo apt update`: Comando utilizado para atualizar a lista de repositórios do sistema. O apt é o gerenciador de pacotes do Ubuntu e Debian. Esse comando irá atualizar a lista de repositórios para verificar se existem atualizações de softwares para serem feitas ou irá apenas manter a lista atualizada para que, quando você instalar um novo pacote, ele já esteja em sua versão mais recente.
- `apt list --upgradable`: esse comando irá listar os pacotes/softwares que estão disponíveis para atualizar.
- `man apt`: mostra um manual detalhado do gerenciador de pacotes `apt`.
- `apt --help`: mostra os principais comandos do `apt`, bem como uma breve descrição de cada um deles.
- `sudo apt upgrade`: atualiza o sistema instalando e/ou atualizando os pacotes/softwares.
- `sudo apt full-upgrade`: atualiza o sistema instalando, atualizando e/ou removendo os pacotes/softwares.
- `sudo apt install pacote`: comando para instalar um pacote/software no sistema. Para ver a lista de todos os pacotes disponíveis para instalação no `apt` você pode utilizar o comando `apt list`, ou pode pesquisar por um pacote específico com o comando `apt search pacote_desejado`.