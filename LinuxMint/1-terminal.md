<div align="center">

# Terminal Linux (Shell)

</div>

- **Shell**: Software que roda dentro do terminal e interpreta os comandos que você digita.
- **Terminal**: Interface gráfica ou de texto que permite interagir com o Shell.
  
### Resumo

- **Terminal**: A janela onde você digita comandos.
- **Shell**: O programa que interpreta e executa os comandos no sistema.


## Conceitos Básicos


- **`~`**: Representa o diretório HOME do usuário.
- **`ROOT`**: Referência ao usuário administrador (superusuário).
- **`#`**: Usuário Root.
- **`$`**: Usuário comum.

---
<div align="center">

# Significado de Informações Basicas do Terminal

</div>

______________________________________________________________________________________________________________________________________________
| COMANDO                           | O QUE ELE FAZ                                                                                          |
| --------------------------------- | -------------------------------------------------------------------------------------------------------|
| `sudo`                            | Executa comandos como superusuário (modo ADM).                                                         |
| `$`                               | Indica que o comando é executado por um usuário comum, sem permissões elevadas.                        |
| `root`                            | Superusuário com permissões administrativas completas.                                                 |
| `#`                               | Representa o superusuário que pode executar qualquer comando no sistema.                               |
----------------------------------------------------------------------------------------------------------------------------------------------

<div align="center">

# Comandos Básicos do Linux

</div>

## Navegação, Listagem e Criação

______________________________________________________________________________________________________________________________________________
| COMANDO                           | O QUE ELE FAZ                                                                                          |
| --------------------------------- | -------------------------------------------------------------------------------------------------------|
| `ls`                              | Lista pastas e arquivos no diretório atual.                                                            |
| `ls -lh`                          | Lista pastas e arquivos no diretório atual e resume o tamanho ocupado                                  |
| `cd <diretorio>`                  | Muda para o diretório especificado. Exemplo: `cd /home/paulo`, `cd ~  `                                |
| `cd ..`                           | Volta um diretório acima.                                                                              |
| `cd -`                            | Volta um diretório e Mostra pra onde voltou.                                                           |
| `pwd`                             | Mostra o caminho completo do diretório atual(Sua Localização).                                         |
| `mkdir <nome_da_pasta>`           | Cria uma nova pasta.                                                                                   |
| `rmdir <nome_da_pasta>`           | Remove uma pasta (somente se estiver vazia).                                                           |
______________________________________________________________________________________________________________________________________________

<div align="center">

# Comandos de Atualização e Instalação

</div>

______________________________________________________________________________________________________________________________________________
| COMANDO                          | O QUE ELE FAZ                                                                                           |
| ---------------------------------|---------------------------------------------------------------------------------------------------------|
| `sudo apt install <pacote>`      | Instala um ou mais pacotes específicos. Exemplo: `sudo apt install vlc gimp`.                           |
| `sudo apt update`                | Atualiza a lista de pacotes disponíveis.                                                                |
| `sudo apt upgrade`               | Atualiza todos os pacotes instalados.                                                                   |
| `sudo apt full-upgrade`          | Força a atualização completa do sistema.                                                                |
| `sudo apt dist-upgrade`          | Atualiza o kernel (sistema operacional).                                                                |
| `sudo apt autoremove`            | Remove pacotes desnecessários do sistema.                                                               |
| `sudo apt autoclean`             | Limpa o cache do apt.                                                                                   |
| `sudo dpkg -i <pacote.deb>`      | Instala um pacote `.deb` baixado pelo navegador.                                                        |
----------------------------------------------------------------------------------------------------------------------------------------------

<div align="center">

# Comandos Úteis

</div>

______________________________________________________________________________________________________________________________________________
| COMANDO                          | O QUE ELE FAZ                                                                                           |
| ---------------------------------|---------------------------------------------------------------------------------------------------------|
| `sudo reboot`                    | Reinicia o computador.                                                                                  |
| `sudo poweroff`                  | Desliga o computador.                                                                                   |
| `whoami`                         | Exibe o nome do usuário atual.                                                                          |
| `clear`                          | Limpa a tela do terminal (ou `CTRL + L`).                                                               |
| `touch ''nome_do_arquivo''`      | Cria um arquivo vazio. Exemplo: `touch paulo.txt`.(Originalmente feito para alterar data e hora)        |
| `echo <nome_do_arquivo.txt>`     | Cria um arquivo . Exemplo: `echo <paulo.txt`.                                                           |
| `cat <nome_do_arquivo>`          | Exibe o conteúdo de um arquivo no terminal.                                                             |
| `<comando> --help`               | Exibe informações de ajuda sobre o comando. Exemplo: `sudo --help`.                                     |
| `man <comando>`                  | Exibe informações do Manual sobre o comando. Exemplo: `man sudo`.                                       |
| `history`                        | Mostra o histórico de comandos utilizados.                                                              |
| `<comando> && <comando>`         | Executa um comando apos o outro caso o 1 comando seja bem sucessido.`                                   |

----------------------------------------------------------------------------------------------------------------------------------------------

<div align="center">

# Atalhos do Linux

</div>

_____________________________________________________________________________________________________________________________________
| Atalhos                      | O QUE ELE FAZ                                                                                     |
| ---------------------------- | --------------------------------------------------------------------------------------------------|
| **`Shift + CTRL + V`**       | Copiar texto no terminal.                                                                         |
| **`Ctrl + Alt + F1`**        | Acessar TTY (Terminal de Texto) para usuários diferentes na mesma máquina ao mesmo tempo (F1-F12).|
| **`Ctrl + Alt + F7`**        | Retornar ao ambiente gráfico padrão.                                                              |
| **`Ctrl + D`**               | Sair de uma aplicação.                                                                            |
| **`Ctrl + C`**               | Cancela o Comando em Execução.                                                                    |
| **`Ctrl + Alt + Backspace`** | Reinicia apenas o ambiente gráfico.                                                               |
| **`Tab`**                    | Completa o restante do comando.                                                                   |
_____________________________________________________________________________________________________________________________________

<div align="center">

# Comandos GIT

</div>

____________________________________________________________________________________________________
| COMANDO                                 | O QUE ELE FAZ                                          |
| --------------------------------------- | -------------------------------------------------------|
| `git clone (link)`                      | Clonar Repositorio no github.                          |
| `git config --global user.name "NOME"`  | Para mostrar o nome de quem editou o arquivo           |
| `git config --global user.email "email"`| Para permitir que você ou alguem a editar o Github     |
| `git config --list`                     | Mostra lista de configurações aplicadas                |
____________________________________________________________________________________________________

<div align="center">



# Comandos de manipulação de arquivo
</div>


______________________________________________________________________________________________________________________________
| COMANDO                      | O QUE ELE FAZ                                                                   |
| --------------------------- | -------------------------------------------------------------------------------- |
| `head -n <número> <arquivo>`| Exibe as primeiras `n` linhas de um arquivo. Exemplo: `head -n 5 arquivo.txt`   |
| `tail -n <número> <arquivo>`| Exibe as últimas `n` linhas de um arquivo. Exemplo: `tail -n 10 arquivo.txt`    |
| `cat <arquivo>`             | Mostra o conteúdo de um arquivo. Exemplo: `cat arquivo.txt`                     |
| `cat -n <arquivo>`          | Mostra o conteúdo com número de linhas. Exemplo: `cat -n arquivo.txt`           |
| `echo "texto" > <arquivo>`  | Substitui o conteúdo do arquivo com o texto fornecido. Exemplo: `echo "Olá" > arquivo.txt` |
| `echo "texto" >> <arquivo>` | Anexa o texto fornecido ao final do arquivo. Exemplo: `echo "Mais uma linha" >> arquivo.txt` |
| `less <arquivo>`            | Permite visualizar o conteúdo de um arquivo em páginas, com navegação. Exemplo: `less arquivo.txt` |
| `cp <origem> <destino>`     | Copia arquivos ou diretórios de um local para outro. Exemplo: `cp arquivo.txt /pasta/` |
| `cp * <destino>`            | Copia todos os arquivos do diretório atual para o destino especificado. Exemplo: `cp * /pasta/` |
| `mv <origem> <destino>`     | Move ou renomeia arquivos ou diretórios. Exemplo: `mv arquivo.txt /pasta/`. Pode também sobrescrever arquivos existentes sem aviso. |
| `rm <nome_do_arquivo>`            | Remove arquivos.                                                                                       |
| `rm -r <nome_da_pasta>`           | Remove uma pasta e todo o seu conteúdo.                                                                |
| `nano <nome_do_arquivo>`         | Abre um arquivo para edição no editor de texto `nano`.                                                  |
______________________________________________________________________________________________________________________________


# Conhecimentos Do Terminal

</div>

# Entendendo as Cores e Permissões no Terminal Linux

No terminal Linux, diferentes cores são usadas para representar tipos de arquivos e diretórios:

- **Azul Escuro**: Representa um **diretório**.
- **Branco** (ou cinza): Geralmente representa um **arquivo comum**.
- **Azul Claro** : Link Simbolico (Atalho)
- **Marca Texto Verde** : PERIGO

## Sem Cores? Use o Comando `ls -lha`

Se as cores não estiverem habilitadas no terminal, você pode usar o comando `ls -lha` para identificar o tipo de arquivo e suas permissões.

### Explicando a Primeira Coluna do `ls -lha`

A primeira coluna da saída do comando `ls -lha` mostra informações detalhadas:

- **`d`**: Indica que é um **diretório**. Se não houver `d`, é um arquivo comum.
- **`r`**: Permissão de **leitura** (read) — pode visualizar o conteúdo.
- **`w`**: Permissão de **escrita** (write) — pode modificar o conteúdo.
- **`x`**: Permissão de **execução** (execute) — pode executar o arquivo como um programa ou script.

### Exemplo de Saída do Comando `ls -lha`

```
drwxr-xr-x  2 user user 4096 Oct 22 10:00 pasta/
-rw-r--r--  1 user user 1234 Oct 22 10:05 arquivo.txt
```
## Explicando a Saída

- **`drwxr-xr-x`**: O **`d`** indica que "pasta/" é um **diretório**. As permissões para o dono, grupo e outros usuários são exibidas em três grupos (`rwx` para leitura, escrita e execução).
- **`-rw-r--r--`**: O **`-`** indica que "arquivo.txt" é um **arquivo comum**. O dono tem permissões de leitura e escrita (`rw-`), enquanto o grupo e outros usuários têm apenas permissão de leitura (`r--`).

## Permissões de Arquivo

Cada conjunto de três caracteres após o tipo de arquivo (como `rwx` ou `rw-`) representa as permissões para:

1. **Proprietário** (primeiro trio de permissões)
2. **Grupo** (segundo trio de permissões)
3. **Outros** (terceiro trio de permissões)

### As permissões são:

- **`r`**: Leitura (*read*)
- **`w`**: Escrita (*write*)
- **`x`**: Execução (*execute*)

## Caminho Absoluto
- **Definição**: Indica a localização completa de um arquivo ou diretório a partir do diretório raiz do sistema de arquivos.
- **Formato**: Começa com uma barra (/) e fornece o caminho total.
- **Exemplo**: `/home/nome_usuario/documentos/relatorio.txt`
- **Uso**: Garantido para acessar arquivos de qualquer lugar no sistema.

## Caminho Relativo
- **Definição**: Indica a localização de um arquivo ou diretório em relação ao diretório atual.
- **Formato**: Não começa com uma barra (/) e pode usar `.` (diretório atual) ou `..` (diretório pai).
- **Exemplo**: `documentos/relatorio.txt`
- **Uso**: Prático para navegação em diretórios próximos e mais flexível.

## Resumo
- **Caminho Absoluto**: Começa com `/`, fornece o caminho completo, e é útil para acesso garantido a arquivos.
- **Caminho Relativo**: Baseado no diretório atual, mais curto e prático para navegação.
- **DICA**: para programação sempre usar o caminho absoluto para apontar um arquivo.
