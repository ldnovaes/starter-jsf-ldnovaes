# 👨‍🎓 O que é starter-jsf-ldnovaes?

Este é um projeto com intuito de ajudar alunos a conseguirem darem o primeiro "START" no mundo de JSF. Sabemos que a configuração de um projeto JSF é algo extremamente trabalhoso e em muitas vezes causam erros que deixam desenvolvedores sem os cabelos. Com o intuito de ajudar, criei esse repositório em que vocês vão poder startar o seu projeto JSF para construção do 0. Vale ressaltar que otimizações podem ser feitas e se você tem alguma sugestão e melhoria, você é bem-vindo!

## 🛠️ Quais as ferramentas utilizadas?
 * Spring Tool Suite 4
 * Tomcat 8.5.24 [Download](https://tomcat.apache.org/download-80.cgi)
 * JSF 2.3
 * CDI 2.0 (Weld Servlet 2.4.5)
 * Maven
  
## ⚙️ Como configurar o projeto?
Aqui não tem segredo! Vou te ajudar a chegar até o projeto estar rodando em sua máquina!

Antes de começarmos, é importante que você tenha feito o download do Tomcat 8.5.24 no link que disponibilizei. Extraia-o para uma pasta de sua preferência, mas guarde o caminho da extração. Usaremos ele durante a inicialização do nosso projeto!

1. Abra o seu terminal e digite:

```python
git clone https://github.com/ldnovaes/starter-jsf-ldnovaes.git
```

2. Abra o Projeto com Spring Tool Suite 4 ou Eclipse
 
3. No menu superior, clique em **_Project > Update Project_** e selecione o projeto starter-jsf-ldnovaes e então clique em **_Finish_**.
 
4. Ainda no menu superior, clique em **_Windows > Show View > Other_** e procure por Server. Isso deve aparecer uma aba **_Servers_** no canto Inferior da sua IDE. Clique em **_No servers are available. Click this link to create a new server..._**
 
5. Na nova interface, expanda **_Apache_** até que você encontre a versão 8.5 do TomCat. Feito a escolha da versão correta, perceba que no campo **_Server runtime environment_** existe a opção de **_add_**. Clique ali.
 
6. Clicado em **_add_** você deve clicar em **_Browser_** para procurar o pasta que você extraiu do TomCat. Selecione a pasta principal e pode dar **_Finish_** nesta tela. 
 
7. Agora que você deu finish na tela de seleção de diretório, você voltou para a tela de seleção da versão do Apache TomCat. Não dê **_Finish_** nesse momento. Temos ainda que colocar o projeto para deploy no servidor. Para isso dê **_Next_** e adicione o projeto que está no lado esquerdo, para o lado direito. Clique em **_Finish_** e você pode dar start no servidor. Seu aplicativo deve estar em [http://localhost:8080/starter-jsf-ldnovaes/](http://localhost:8080/starter-jsf-ldnovaes/)
 
8. Hora das modificações! Entender como foi feito essa construção do JSF com TomCat pode ser importante para futuras implementações. Ajuste o projeto ao seu gosto, esse repositório está livre de toda e qualquer licença.
 
 
