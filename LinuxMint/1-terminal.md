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

---
<div align="center">

# Comandos Padrões do Terminal

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

## Navegação e Listagem

______________________________________________________________________________________________________________________________________________
| COMANDO                          | O QUE ELE FAZ                                                                                           |
| --------------------------------- | -------------------------------------------------------------------------------------------------------|
| `ls`                              | Lista pastas e arquivos no diretório atual.                                                            |
| `cd <pasta>`                      | Muda para o diretório especificado. Exemplo: `cd /home/paulo`.                                         |
| `cd ..`                           | Volta um diretório acima.                                                                              |
______________________________________________________________________________________________________________________________________________

<div align="center">

# Comandos de Administração

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
| `mkdir <nome_da_pasta>`          | Cria uma nova pasta.                                                                                    |
| `rmdir <nome_da_pasta>`          | Remove uma pasta (somente se estiver vazia).                                                            |
| `rm <nome_do_arquivo>`           | Remove arquivos.                                                                                        |
| `rm -r <nome_da_pasta>`          | Remove uma pasta e todo o seu conteúdo.                                                                 |
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
| `pwd`                            | Mostra o caminho completo do diretório atual.                                                           |
| `touch <nome_do_arquivo>`        | Cria um arquivo vazio. Exemplo: `touch paulo.txt`.                                                      |
| `nano <nome_do_arquivo>`         | Abre um arquivo para edição no editor de texto `nano`.                                                  |
| `cat <nome_do_arquivo>`          | Exibe o conteúdo de um arquivo no terminal.                                                             |
| `<comando> --help`               | Exibe informações de ajuda sobre o comando. Exemplo: `sudo --help`.                                     |
| `history`                        | Mostra o histórico de comandos utilizados.                                                              |
----------------------------------------------------------------------------------------------------------------------------------------------

<div align="center">

# Atalhos do Linux

</div>

___________________________________________________________________________________________________________________________________________________
| Atalhos                           | O QUE ELE FAZ                                                                                               | 
| ------------------------------------------- |---------------------------------------------------------------------------------------------------|                                                                            
| **`Shift + CTRL + V`**                      | Copiar texto no terminal.                                                                         |
| **`Ctrl + Alt + F1`**                       | Acessar TTY (Terminal de Texto) para usuários diferentes na mesma máquina ao mesmo tempo(F1-F12). |
| **`Ctrl + Alt + F7`**:                      | Retornar ao ambiente gráfico padrão.                                                              |
| **`Ctrl + D`**                              |  Sair de uma aplicação.                                                                           |
| **`Ctrl + alt + Backspace`**                | Reinicia apenas o ambiente grafico.                                                               |
| **`Tab`**                                   | Completa o restante do comando.                                                                   |
---------------------------------------------------------------------------------------------------------------------------------------------------
