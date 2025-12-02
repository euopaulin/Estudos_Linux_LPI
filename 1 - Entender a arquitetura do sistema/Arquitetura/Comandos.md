**ls** - Listar
**ls-R** listar discursivo
**Discursivo** = As subpastas também
**cd** - Navegar entre diretorios

Usuários e grupos:
- **chown** - é usado para alterar o proprietário e/ou o grupo de um arquivo ou diretório
- **chgrp**: O comando `chgrp` é usado apenas para alterar o grupo de um arquivo ou diretório, não o proprietário.

- **chmod**: O comando `chmod` é usado para alterar as permissões de um arquivo ou diretório, não o proprietário ou o grupo.

- **chage**: O comando `chage` é usado para alterar os parâmetros de expiração de senha de um usuário, não para alterar o proprietário ou grupo de um arquivo.

**Caminhos absolutos** = Caminho completo
Ex: /home/paulo/Downloads

**Caminhos relativos** = Não completos
Ex: ~/.config

**head -n 10** - Lista as 10 primeiras linhas

**wc** - Conta o número de linhas de um arquivo

**mkdir** - Criar diretorios/pastas
**mkdir** -p O -p permite com que seja criados diretorios dentro de outros
Ex: dir1/dir2/dir3
**cp** - copiar
**tar** - Compactar
**gz** - Comprimir

**passwd** - Pode alterar a senha e bloquear usuário

**alias** - Cria comandos personalizados. Para executar variaveis preciso informar o $ antes, já no alias não é necessario

**;** - Serve para separar os comandos

**AND** e **OR**
```bash
&& e ||

Ex: "Sudo apt update && sudo apt upgrade -y"

&& - So será executado o segundo se o primeiro for executado
|| - Se o primeiro não der certo, execute o segundo
```

**uname -r** - Versão do Kernel

**Para ver o manual**

-h ou --help = informações sobre o seu uso
man - manual

**ip addr show** - é usado para exibir as interfaces de rede e suas respectivas configurações de endereço IP.

**sort** - classifica em ordem alfabética

**touch m** - Modifica o tempo de modificação do arquivo.

**which** - Mostra o caminho do comando. Ex: qual o caminho do comando ls

**whatis** - Descrição e finalidade de um comando.

**ls -h** - Mostra o tamanho dos arquivos de forma legível 

**--purge** - É para remover tudo, inclusive pacotes de configurações

**ps** - O comando `ps` (process status) é o comando básico para listar os processos atuais no sistema.

**/hidden** - O "/" dentro do comando man é utilizado para pesquisar por palavras-chave.

ls [A-Z]* = Lista todos os arquivos que possuem letras maiúsculas de A a Z