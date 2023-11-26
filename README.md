# Tutorial de Instalação do `.vimrc` para Windows e MacBook

## Para Windows

### Download e Instalação do VIM
- Acesse o site oficial do VIM ([VIM Download](https://www.vim.org/download.php)) e faça o download da versão mais recente.
- Execute o instalador e siga as instruções, mantendo as configurações padrão.

### Download do Compilador MinGW
- Visite [MinGW](https://www.mingw-w64.org/) para baixar o compilador MinGW.
- Siga as instruções de instalação no site.

### Configuração do Sistema
- Acesse as configurações avançadas do sistema (Painel de Controle > Sistema > Configurações avançadas do sistema).
- Adicione o caminho da pasta `bin` do MinGW e a pasta de instalação do VIM às variáveis de ambiente do sistema.

### Configuração do `.vimrc`
- Abra o VIM e digite `:new` para criar um novo arquivo.
- Salve o arquivo na sua pasta de usuário com o comando `:w C:\Users\SeuUser\_vimrc`.
- Crie uma pasta chamada `projects` em `C:\Users\SeuUser`, e dentro dela, outra pasta chamada `vimfiles`.
- Acesse [CP-YouTube .vimrc](https://github.com/tmwilliamlin168/CP-YouTube/blob/master/.vimrc) e copie o conteúdo.
- Abra o arquivo `_vimrc` com o Bloco de Notas e cole o conteúdo copiado.
- Reinicie o VIM, abra o arquivo `_vimrc` com `:e _vimrc` e aplique as configurações com `:w` seguido de `:source %`.

## Para MacBook

### Download e Instalação do VIM
- Normalmente, o VIM já vem pré-instalado em macOS. Verifique a instalação abrindo o Terminal e digitando `vim`.
- Caso não esteja instalado, você pode instalar o VIM usando o Homebrew: `brew install vim`.

### Configuração do `.vimrc`
- Abra o Terminal e digite `vim` para iniciar o editor.
- Digite `:new` para criar um novo arquivo.
- Salve o arquivo na sua pasta de usuário com `:w ~/.vimrc`.
- Crie uma pasta chamada `vimfiles` no seu diretório de usuário.
- Acesse [CP-YouTube .vimrc](https://github.com/tmwilliamlin168/CP-YouTube/blob/master/.vimrc) e copie o conteúdo.
- Abra o arquivo `.vimrc` com um editor de texto e cole o conteúdo copiado.
- Para aplicar as configurações, reinicie o VIM e digite `:source %` após abrir o arquivo `.vimrc`.
