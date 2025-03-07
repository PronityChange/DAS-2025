# DAS-2025

#dia 26/02

#https://engsoftmoderna.info/cap7.html
#Pacote



-O pacote ajuda na arquitetura de software deixando o projeto mais organizado, eficiênciente, com o objetivo de criar um software de mais alto nível

-Camada de apresentação (front) Camada de gerir informação (back) Camada de informação (bd,drivers, devices).

-anotação são tipos de componentes, são bibliotecas, feitas de antemão, e usadas para facilitar na programação
-No Java se refere como @, Httpserveletrequest (Java) ajuda a entender oq è o Java vindo da internet(Baixo nível)

-Em linguagens de programação, "componentes" referem-se a blocos de código reutilizáveis que encapsulam funcionalidades específicas. Eles são como peças de um quebra-cabeça, permitindo 
que os desenvolvedores construam aplicações complexas combinando componentes menores e mais simples.

-Características principais dos componentes:


-Reusabilidade: Podem ser utilizados em diferentes partes do mesmo programa ou em programas distintos, economizando tempo e esforço de desenvolvimento.
   -Encapsulamento: Ocultam a complexidade interna, expondo apenas uma interface bem definida para interação.
   -Modularidade: Promovem a divisão do código em módulos independentes, facilitando a manutenção e o teste.
   -Composição: Podem ser combinados para criar componentes mais complexos, seguindo o princípio de "construir a partir de blocos".
#Tipos de componentes:



#A definição exata de "componente" pode variar dependendo da linguagem de programação e do paradigma utilizado. No entanto, alguns exemplos comuns incluem:
   -Funções e procedimentos: Blocos de código que realizam tarefas específicas.
   -Classes e objetos: Unidades de código que combinam dados e comportamentos relacionados.
   -Bibliotecas e módulos: Coleções de funções, classes e outros componentes que fornecem funcionalidades específicas.
   -Controles de interface gráfica (UI): Elementos visuais como botões, caixas de texto e menus.
-Componentes de software: Unidades de software independentes que podem ser implantadas e executadas em diferentes ambientes.


#Benefícios do uso de componentes:
  -Aumento da produtividade: A reutilização de código reduz o tempo de desenvolvimento.
   -Melhora da qualidade do código: Componentes bem testados e documentados tendem a ser mais confiáveis.
   -Facilidade de manutenção: A modularidade facilita a identificação e correção de erros.
   -Promoção da colaboração: Componentes podem ser desenvolvidos e compartilhados por diferentes equipes.
-Em resumo, componentes são elementos fundamentais na programação moderna, permitindo a criação de aplicações mais eficientes, robustas e fáceis de manter.**

#Modulos

-Modulos separação do código 
-Exemplo: financeiro, logística, dois modulos diferentes

-API. Modulo chama a API para compartilhar informações entre modulos
-Cliente interface 
-Cliente interface.    Aplicação lógica do mercado 
-Cliente interface









#dia 27/2

#o objetivo dessa materia tem o missao de ensinar como qrquitetar um software de mais alto nivel

- padrao utilizado do molde do projeto/software/arquitetura é em camadas

-aruitetura amvc - model view-controler 

-arquitetura em camadas 
-as dua tem a missao de separar camadas (separar responsabilidade dento de uma aplicação)



   #mvn(Model-View-Controller): 

-Model: Representa os dados e a lógica de negócios da aplicação. É responsável por acessar e gerenciar os dados, 
assim como aplicar as regras de negócio.

-View: Responsável pela apresentação dos dados ao usuário. Esta camada renderiza a interface do usuário e exibe as 
-informações vindas do modelo

-Controller: Atua como intermediário entre o Model e o View. Recebe as entradas do usuário, processa-as (geralmente 
-invocando métodos no modelo), e seleciona a visão apropriada para retornar ao usuário.


   #arquiteturas em camadas: 

-Apresentação: Camada responsável pela interface do usuário e pela interação com o usuário final. Similar ao View no MVC.

-Aplicação: Gerencia a lógica de negócios e controle de fluxo da aplicação. Similar ao Controller no MVC.

-Domínio: Inclui as regras de negócios e a lógica específica da aplicação.

-Infraestrutura: Fornece serviços de suporte como persistência de dados, comunicação, etc.




#model(mvn): dados que vao aparecer na sua tela exemplo :fazer validaçoes,
#viwe :desenhar e mostrardados de tela 
#model:acessar e gerneciar dados
#controler:controla a tela

-oq a enttidade representa é uma os dados que vao para uma outra tela

-DTA: api faz a mesma coisa que o mvn (java)

   #diferença:
-Ambas as arquiteturas têm a missão de separação de responsabilidades.
-MVC foca em dividir a aplicação em três componentes principais.
-Arquitetura em Camadas pode ter várias camadas, proporcionando uma separação ainda mais detalhada e flexível.

-sub procedure: sub procedures são usadas para organizar e reutilizar o código de forma eficiente. 
-Elas permitem dividir um programa em partes menores e mais gerenciáveis, cada uma focada em uma função específica.


#teste de unidade

-um tipo de teste de software que verifica o funcionamento correto de pequenas partes isoladas de um programa

-Características dos Testes de Unidade:

-Automatização: Geralmente são automatizados para serem executados rapidamente e de forma consistente.

-Confiabilidade: Aumenta a confiabilidade do código, detectando e prevenindo bugs logo nas etapas iniciais de desenvolvimento.

-Reutilização: Facilita a refatoração e manutenção do código, pois qualquer alteração que quebre uma funcionalidade 
-existente será detectada imediatamente.

#exemplo em python

#def soma(a, b):
    #return a + b

#def teste_soma():
    #assert soma(1, 2) == 3
    #assert soma(0, 0) == 0
    3assert soma(-1, -1) == -2

# Executando o teste
#teste_soma()
#print("Todos os testes passaram!")





#selenium
Selenium, uma ferramenta amplamente utilizada para automação de navegadores web.

-Selenium WebDriver: Permite criar scripts de automação que interagem diretamente 
com o navegador, simulando ações de um usuário real.

-Selenium IDE: Um ambiente de desenvolvimento integrado que facilita a criação de 
scripts de teste através de gravação e reprodução de ações no navegador.

-Selenium Grid: Permite distribuir e executar testes em múltiplas máquinas e 
diferentes ambientes, facilitando a execução de testes em várias combinações de navegadores e sistemas operacionais.






#micro serviço:


-Micro serviços são uma abordagem de desenvolvimento de software na qual uma aplicação é dividida em pequenos 
-serviços independentes (pode ser um modulo)

-Independência: Cada micro serviço é independente e pode ser desenvolvido, implantado e escalado separadamente.

-Responsabilidade Única: Cada serviço executa uma única função ou um conjunto estreito de funções, seguindo 
o princípio da responsabilidade única.

-Comunicação via API: Os micro serviços se comunicam entre si através de APIs, geralmente usando protocolos 
HTTP/HTTPS, mensagens ou gRPC.

-Escalabilidade: É possível escalar serviços individuais de acordo com a demanda, em vez de escalar a aplicação inteira.
-Flexibilidade: Permite o uso de diferentes tecnologias e linguagens de programação para diferentes serviços.

-uma parte do meu software que faz um trabalha em especifico como registrar as transaçoes em um banco

-deve ter camadas 

-os metodos arquitetonicos poder ser todos usados/misturados


#caracteristicas do monolito:

-reposito unico de codigo, uso de uma unica tecnica padrao
-ele é compilado testado e gera um unico pacote
-deploy como um unico sistema (se for editar, ira ter que fazer o todo o processo de novo )
-executado como um unico processo no sistema operacional(geralmente)(se cair esse processo todo o sistema cai)
-unico banco de dados/repositario




#DIA 
06/03

Who Needs an Architect? https://martinfowler.com/ieeeSoftware/whoNeedsArchitect.pdf
So, perhaps an architecture is the
highest level concept that developers have of a
system in its environment

 What makes a component
Customers have a
different concept than developers. Customers do
not care at all about the structure of significant
components. So, perhaps an architecture is the
highest level concept that developers have of a
system in its environment.
It is significant 
because the 
expert developers 
say so

Who Needs an Architect?








      #O que é arquitetura?

      
   significant?

      
   a better definition would be “In most successful
   software projects, the expert developers working
   on that project have a shared understanding of the
   design


   This shared understanding
   is called ‘architecture.’ This understanding
   includes how the system is divided into
   components and how the components interact through interfaces.

      #Qual o comportamento do arquiteto da "Matrix"?

   Customers have a
   different concept than developers. Customers do
   not care at all about the structure of significant
   components. So, perhaps an architecture is the
   highest level concept that developers have of a
   system in its environment.
   Qual o comportamento do arquiteto ideal?

    guide, as in mountaineering. A
   guide is a more experienced and skillful
   team member who teaches other team
   members to better fend for themselves
   yet is always there for the really tricky
   stuff. 
   Architectus Oryzus is a different
   kind of animal (if you can’t guess, try
   www.nd.edu/~archives/latgramm.htm).
   This kind of architect must be very
   aware of what’s going on in the project,
   looking out for important issues and
   tackling them before they become a serious problem. When I see an architect
   like this, the most noticeable part of the
   work is the intense collaboration. In the
   morning, the architect programs with a
   developer, trying to harvest some common locking code. In the afternoon, the
   architect participates in a requirements
   session, helping explain to the requirements people the technical consequences of some of their ideas in nontechnical terms—such as development
   costs. 
   In many ways, the most important
   activity of Architectus Oryzus is to
   mentor the development team, to raise
   their level so that they can take on
   more complex issues




extreme progaming 

scrum


Rup : unified process
