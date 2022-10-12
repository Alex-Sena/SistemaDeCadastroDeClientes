# 💻 Sistema de Cadastro de Clientes

<div>
  <a href="https://beacons.ai/Alex-Sena">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Alex-Sena&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alex-Sena&layout=compact&langs_count=16&theme=dark"/>
</div>

---
  
O sistema de cadastro de clientes customizado apresenta as seguintes características:
 
-   Armazena todos os cadastros das pessoas físicas e jurídicas;
-   O cadastro de pessoa física é feito com os seguintes dados: Nome, CPF e Data de nascimento;
-   O cadastro de pessoa jurídica é feito com os seguintes dados: Nome, CNPJ e razão social;
-   Ambos devem possuir um Rendimento,  Endereço e indicar se o endereço é comercial ou residencial;
-   Calcula o imposto baseado no Rendimento informado;
-   O sistema armazenar os registros em arquivos;
---
**Tecnologias utilizadas** 💻️

Esse projeto foi criado utilizando as tecnologias:

***Back-End***
- [.NET](https://dotnet.microsoft.com/download)
- [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)

***Editor***
- [VSCode](https://code.visualstudio.com/)

---
**Execução da aplicação**

Inicia com a tela de Boas Vindas:

-------------------------------------------------------------
           Bem vindo ao Sistema de Cadastro de                    
             Pessoas Físicas e Jurídicas                 
-------------------------------------------------------------

Após a Barra de carregamento, abre-se o seguinte menu:

-------------------------------------------------------------
              Escolha uma das opções a seguir:             

                   1- Pessoa Física                        
                   2- Pessoa Jurídica                      
                   0- Sair                                 
-------------------------------------------------------------
De acordo com a Opção selecionada, submenus são abertos.
Caso a *Opção 0* seja selecionada, uma barra de carregamento e finalização aparecem no Console



- Submenu da Opção 1 - Pessoa Física:
-------------------------------------------------------------
              Escolha uma das opções a seguir:            
                                                              
                1- Cadastar Pessoa Física                  
                2- Mostrar Pessoa Física                   
                0- Sair                                     
-------------------------------------------------------------

*Opção 1 - Cadastrar Pessoa Física:* Solicita informações como: Nome, CPF , Data de nascimento, Rendimento e Endereço.
E após o cadastramento, gera um arquivo .txt onde armazena algumas informações inseridas

*Opção 2 - Mostrar Pessoa Física:* Caso existam cadastros no arquivo .txt, ele retorna o  Nome, CPF , Data de nascimento e Taxa de Imposto a Pagar

*Opção 0 - Sair:* Retorna para o Menu anterior


- Submenu da Opção 2 - Pessoa Jurídica
-------------------------------------------------------------
              Escolha uma das opções a seguir:             
                                                               
                 1- Cadastar Pessoa Jurídica
                 2- Mostrar Pessoa Jurídica                  
                 0- Sair                                     
-------------------------------------------------------------
*Opção 1 - Cadastrar Pessoa Jurídica:* Solicita informações como: Nome, CNPJ , Razão Social, Rendimento e Endereço.
E após o cadastramento, gera um arquivo .csv onde armazena algumas informações inseridas

*Opção 2 - Mostrar Pessoa Jurídica:* Caso existam cadastros no arquivo .csv, ele retorna o  Nome, CNPJ , Razão Social e Taxa de Imposto a Pagar

*Opção 0 - Sair:* Retorna para o Menu Anterior
---
**Erros comuns**
- Se a lista estiver vazia uma mensagem será exibida e retornará para o submenu.
- O Cliente Pessoa Física deve ser maior de 18 anos
- O CNPJ deve ter o seguinte formato: "xx.xxx.xxx/0001-xx" ou "xxxxxxxx0001xx"
- Opção de Endereço Comercial só aceita as seguintes respostas:  "sim", "s", "não" e "n";
Caso esses parâmetros não sejam atendidos, retornará uma mensagem de Erro.
---
**Tutor**
Luiz Carlos Machi Lozano
