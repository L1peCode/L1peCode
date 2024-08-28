1 - Baixando o zip do repositório GitHub
Link do repositório: [Repositório] (https://github.com/everthonmanoell/AluguelChromejsp.git)

1.1 - Clique em "<> Code" e baixe o o projeto zipado.




2 - Instalação da IDE que roda a aplicação
2.1 - Instalar o NetBeans:
2.2 - Link Escolha a versão que é compatível com o seu sistema operacional: Downloading Apache NetBeans 18
(https://netbeans.apache.org/front/main/download/nb18/index.html)

2.3 - Siga clicando em 'Next' até instalar a IDE.




3 - Escolha do servidor que roda a aplicação
3.1 - Clique no o ícone "New Project"
exemplo

3.2 - Selecione o na barra de "'Categorias' - Java with Maven" e depois na barra de 'Projects:' Selecione o 'Web Aplpication'" e clique em 'Next"
exemplo

3.3 - Escolha o nome do seu projeto e depois clique em 'Next'
exemplo

3.4 - O campo 'Server' estará '', com isso clique no botão da direita 'Add...'
exemplo

3.5 - Selecione o Server 'GlassFish Server' e logo ems seguida clique no botão 'Next >'
exemplo

3.6 - Marque a caixa com o texto 'I have read and accpt the license agreement... (click)', depois clique no botão 'Download Now...', espere baixar e em seguida, clique no botão 'Next >'
exemplo

3.7 - Depois de instalado selecione o Server: GlassFish Server e clique em Finish.
exemplo



4 - Importando o zip no NetBeans
4.1 - Com o Apache Netbeans ainda aberto depois de você ter escolhido e instalado o GlassFish server clique em 'file' selecione o 'import project' e clique em 'From ZIP...'
exemplo

4.2 - Na janela seguinte clique no 1º botão 'Browse..' e procure o arquivo zip que você baixou do projeto.
exemplo

4.3 - Quando achar o arquivo zip 'AluguelChromejsp-main' clique nele e depois no botão 'Open'
exemplo

4.4 - Agora escolha o lugar onde sera importado seu projeto, clique no 2º 'Browse..' e clique na pasta destino.
exemplo

4.5 - Ao selecionar a pasta clique no botão 'Save'
exemplo

4.6 - Na tela seguinte clique em 'Import'
exemplo

4.7 - Aguarde o Netbeans carregar e você terá a seguinte tela, depois disso instale o banco antes de rodar a aplicação.
exemplo





5 - Como usar o banco de dados do projeto
Obs, caso tenha instalado o xampp vá para o passo 5.
5.1- Baixe a versão mais recentes do xampp ex:
https://www.apachefriends.org/pt_br/download.html

5.2- Escolha o sistema operacional e clique em 'Baixar (64bit)'
exemplo

5.3- Se o arquivo não for baixado clique no botão 'click aqui...'
exemplo


5.4- Click no arquivo do instalador que você acabou de baixar e instale o xampp no seu computador, seguindo os proximos passos.
5.4.1- Se aparecer esse aviso clique em 'sim'.
exemplo


5.4.2- Se aparecer esse aviso clique em 'ok'.
exemplo


5.4.3- Nessa tela click em 'Next'
exemplo


5.4.4- Nessa tela click em 'Next'
exemplo


5.4.5- Nessa tela click em 'Next'
exemplo


5.4.6- Nessa tela click em 'Next'
exemplo


5.4.7- Nessa tela click em 'Next'
exemplo


5.4.8- Aguarde o XAMPP terminar de instalar
exemplo


5.4.9- Deixe marcado o quandro 'Do you want to start the Control Painel now?' e clique em Finish
exemplo


5.5 - Assim que abrir o XAMPP aperte no start do "Apache" e do "MySQL"
exemplo


5.5.1 - O XAMPP tem que ficar dessa forma, com essas respectivas portas:
exemplo


5.5.2 - Caso o XAMPP não inicie os dois servidores tente desistalar, apagar a pasta c:/xampp, reiniciar o pc e reinstalar o XAMPP conforme passos 4.

5.6 - Do lado do botão 'stop' do MySQL tem um botão chamado admin que te leva para o phpmyadmin onde você pode criar o banco de dados.
exemplo


5.6.1 - Ao abrir o PHPMYADMIN uma pagina de internet abrira com o endereço 'localhost/phpmyadmin/' clique no botão 'novo' para criarmos o banco.
exemplo


5.6.2 - Insrina o nome do banco no nosso caso 'aluguelchromebook' no campo 'nome do banco de dados'
exemplo


5.6.3 - Após inserido clique em 'criar'
exemplo


5.6.4 - Depois de criado vamos importar o banco de acordo com o arquivo, clicando em importar
exemplo


5.6.5 - Clique em 'escolher o arquivo'
exemplo


5.6.6 - Navegue até o arquivo que deve estar na pasta '..\AluguelChromejsp\Banco\ModeloFisico' clique no arquivo e depois em 'Abrir'
exemplo


5.6.7 - Role a barra de rolagem até o fim e clique em 'importar' no lado esquerdo da tela
exemplo


5.6.8 - Ao fazer a importação o PHPMYADMIN mostrará uma tela com as querys executadas.
exemplo





6 - Como usar a aplicação
Após a instalação do XAMPP e do NetBeans, é possível iniciar as páginas para utilizar a aplicação.

A primeira página consiste no processo de login, permitindo o cadastro e acesso para entrar na página inicial do projeto.

Na página inicial, há uma breve explicação sobre o projeto, bem como botões que direcionam para as seções de cadastro, aluguel e relatório de todos os itens da aplicação.

Na tela de cadastro, oferece-se a opção de registrar informações sobre alunos, coordenadores e Chromebooks para a aplicação.

A página de aluguel possibilita o aluguel de Chromebooks, exigindo a prévia inclusão da matrícula do aluno, do coordenador e o tombamento do Chromebook para efetuar a locação.

Além disso, há a funcionalidade de devolução do Chromebook na seção de aluguel, onde é possível registrar a data e hora de retorno, mantendo essas informações armazenadas no relatório.

O relatório é a seção da aplicação destinada à visualização de dados sobre alunos, coordenadores e Chromebooks. Nesta página, um submenu permite a escolha específica entre essas opções.

7 - Rodando o sistema
 - Passo 1 - Procure o ícone de "Run Project" no menu de ferramentas do NetBeans.
 - Passo 2 - Clique e espere abrir no navegador.
