# O que é starter-jsf-ldnovaes?

Este é um projeto com intuito de ajudar alunos a conseguirem darem o primeiro "START" no mundo de JSF. Sabemos que a configuração de um projeto JSF é algo extremamente trabalhoso e em muitas vezes causam erros que deixam desenvolvedores sem os cabelos. Com o intuito de ajudar, criei esse repositório em que vocês vão poder startar o seu projeto JSF para construção do 0. Vale ressaltar que otimizações podem ser feitas e se você tem alguma sugestão e melhoria, você é bem-vindo!

## Quais as ferramentas utilizadas?
 * Spring Tool Suite 4
 * Tomcat 8.5.24 [Download](https://tomcat.apache.org/download-80.cgi)
 * JSF 2.3
 * CDI 2.0 (Weld Servlet 2.4.5)
 * Maven
  
## Como configurar o projeto?
Aqui não tem segredo! Vou te ajudar a chegar até o projeto estar rodando em sua máquina!

Antes de começarmos, é importante que você tenha feito o download do Tomcat 8.5.24 no link que disponibilizei. Extraia-o para uma pasta de sua preferência, mas guarde o caminho da extração. Usaremos ele durante a inicialização do nosso projeto!

1º Abra o seu terminal e digite:

> git clone link_aqui

 2º Abra o Projeto com Spring Tool Suite 4
 
 3º No menu superior, clique em `Project > Update Project` e selecione o projeto starter-jsf-ldnovaes e então clique em `Finish`.
 
 4º Ainda no menu superior, clique em `Windows > Show View > Other` e procure por Server. Isso deve aparecer uma aba `Servers` no canto Inferior da sua IDE. Clique em `No servers are available. Click this link to create a new server...`
 
 5º Na nova interface, expanda `Apache` até que você encontre a versão 8.5 do TomCat. Feito a escolha da versão correta, perceba que no campo `Server runtime environment` existe a opção de `add`. Clique ali.
 
 6º Clicado em `add` você deve clicar em `Browser` para procurar o pasta que você extraiu do TomCat. Selecione a pasta principal e pode dar `Finish` nesta tela. 
 
 7º Agora que você deu finish na tela de seleção de diretório, você voltou para a tela de seleção da versão do Apache TomCat. Não dê `Finish` nesse momento. Temos ainda que colocar o projeto para deploy no servidor. Para isso dê `Next` e adicione o projeto que está no lado esquerdo, para o lado direito. Clique em `Finish` e você pode dar start no servidor. Seu aplicativo deve estar em [http://localhost:8080/starter-jsf-ldnovaes/](http://localhost:8080/starter-jsf-ldnovaes/)
 
8º Hora das modificações! Entender como foi feito essa construção do JSF com TomCat pode ser importante para futuras implementações. 

## 
 
