# cobol-crud
COBOL - CRUD

Título:
-
Projeto CRUD completo - COBOL Web - Sistema de cadastro e autenticação

1- Baixar Microsoft VSCode
https://code.visualstudio.com/download

2- Criar diretório em:
C:\Cobol\GnuCobol

3- Baixar o GNU COBOL
https://sourceforge.net/projects/gnucobol/files/gnucobol/3.2/gnucobol-3.2_win.zip/download

4- Criar a variável COBOL_HOME e apontar para o diretório principal do GNU COBOL:
-
- Editar as variáveis de ambiente do sistema > Avançado > Variáveis de Ambiente > Variáveis do sistema > Novo > Nova Variável de Sistema > Nome da variável: COBOL_HOME > Valor da variável: C:\Cobol\GnuCobol > OK

5- Apontar para o sub-diretório "bin" do GNU COBOL:
-
- Editar as variáveis de ambiente do sistema > Avançado > Variáveis de Ambiente > Variáveis do sistema > Novo > Nova Variável de Sistema > Nome da variável: COB_BIN_DIR > Valor da variável: %COBOL_HOME%\bin > OK

6- Apontar para o sub-diretório "config" do GNU COBOL:
-
- Editar as variáveis de ambiente do sistema > Avançado > Variáveis de Ambiente > Variáveis do sistema > Novo > Nova Variável de Sistema > Nome da variável: COB_CONFIG_DIR > Valor da variável: %COBOL_HOME%\config > OK

7- Apontar para o sub-diretório "copy" do GNU COBOL:
-
- Editar as variáveis de ambiente do sistema > Avançado > Variáveis de Ambiente > Variáveis do sistema > Novo > Nova Variável de Sistema > Nome da variável: COB_COPY_DIR > Valor da variável: %COBOL_HOME%\copy > OK

8- Apontar para o sub-diretório "lib" do GNU COBOL:
-
- Editar as variáveis de ambiente do sistema > Avançado > Variáveis de Ambiente > Variáveis do sistema > Novo > Nova Variável de Sistema > Nome da variável: COB_INCLUDE_PATH > Valor da variável: %COBOL_HOME%\lib > OK

9- Adicionar as variáveis de ambiente de sistema na variável "path" do sistema:
-
- Editar as variáveis de ambiente do sistema > Avançado > Variáveis de Ambiente > Variáveis do sistema > Path > Editar > Novo > %COB_BIN_DIR%, %COB_CONFIG_DIR%, %COB_COPY_DIR%, %COB_INCLUDE_PATH% > OK

10- Abrir um prompt de comando e testar a chamada com "cobc -v" 
-

11- Se der tudo certo, criar uma workspace e um diretório no VSCode e criar um arquivo .cob
-

12- Digitar um código COBOL básico para teste
-

13- Abrir um novo terminal no VS Code, acesar o diretório e compilar o código criado