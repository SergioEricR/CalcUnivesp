Tutorial: Configurando Ambiente de Desenvolvimento para Executar Código Python e HTML

Neste tutorial, vou guiá-lo através do processo de configuração de um ambiente de desenvolvimento para executar um código Python que utiliza o framework Flask e um arquivo HTML relacionado.

Passo 1: Instalação do Visual Studio Code (VSCode)

1. Se você ainda não tiver o Visual Studio Code instalado em seu computador, baixe-o e instale-o no site oficial: [Visual Studio Code](https://code.visualstudio.com/).
2. Após a instalação, abra o VSCode para prosseguir.

Passo 2: Estrutura de Arquivos

1. No VSCode, crie uma pasta onde deseja armazenar seus arquivos Python e HTML.
2. Dentro desta pasta, crie uma subpasta chamada "templates" para armazenar seu arquivo HTML.
   Isso garantirá que sua estrutura de arquivos esteja organizada de forma adequada para o desenvolvimento e execução do seu projeto.

Passo 3: Instalação do Python

1. Abra o terminal no Visual Studio Code ou no prompt de comando do seu sistema operacional.
2. Caso ainda não tenha o Python instalado em seu computador, siga as instruções no site oficial do Python: [Python.org](https://www.python.org/).
3. Verifique se o Python foi instalado corretamente digitando `python --version` no terminal. Isso deve exibir a versão do Python instalada.

Passo 4: Instale as Dependências do Python

1. No terminal do VSCode ou prompt de comando, navegue até a pasta onde você criou seus arquivos Python.
2. Instale as dependências necessárias executando o seguinte comando:
   ```
   pip install Flask
   ```
   Isso instalará o framework Flask, necessário para executar o código Python.

Passo 5: Copiando os Arquivos

1. Copie seu arquivo Python (com extensão `.py`) para a pasta que você criou.
2. Copie seu arquivo HTML (com extensão `.html`) para a subpasta "templates" que você criou.

Passo 6: Executando o Servidor Flask

1. No terminal do VSCode ou prompt de comando, navegue até a pasta onde você salvou o arquivo Python.
2. Execute o seguinte comando para iniciar o servidor Flask:
   ```
   python nome_do_arquivo.py
   ```
   Isso iniciará o servidor Flask. Certifique-se de que o terminal está exibindo mensagens indicando que o servidor está em execução sem erros.

Passo 7: Acessando o Aplicativo no Navegador

1. Abra um navegador da web.
2. Na barra de endereços, digite `http://localhost:5000/` e pressione Enter.
   Isso deve abrir a calculadora de média de notas no navegador.

Com isso, você configurou com sucesso um ambiente de desenvolvimento para executar código Python e HTML no seu computador usando o Visual Studio Code. Se precisar de mais alguma orientação, estou à disposição para ajudar!
