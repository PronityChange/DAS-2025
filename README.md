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

Aula 13/


Fundamentos da Arquitetura de Software

Pensamento Arquitetônico



Aula 19/03
Trade-offs
Tópicos
Filas
Fan out
Aula 02/04



Trabalho sobre tópicos (CHAT)



Aula 03/04

Filas


Aula 09/04



Características Arquiteturais
Criar um resumo

Imagine que uma empresa precisa de um software novo para resolver um problema. Primeiro, eles listam o que o software precisa fazer – essas são as funcionalidades, os requisitos do negócio. Mas, além disso, o software precisa ter outras qualidades importantes para funcionar bem, como ser rápido, seguro e fácil de usar.

A arquitetura de software é como o "esqueleto" e o "plano geral" do sistema. Ela define como as diferentes partes do software vão se organizar e se comunicar para atender tanto aos requisitos do negócio quanto a essas outras qualidades importantes.

O que diferencia a arquitetura da codificação e do design "comum"?



Codificação é escrever as linhas de código que fazem o software funcionar. É o nível mais baixo de detalhe.
Design (em um sentido mais restrito) pode se referir ao design das telas, da experiência do usuário ou de componentes específicos do software.
Arquitetura está em um nível mais alto. Ela define as características da arquitetura, que são aspectos cruciais para o sucesso do sistema, mas que não estão diretamente ligados ao que o software faz (a funcionalidade em si).


Uma característica da arquitetura tem três pontos chave:

Não é sobre o que o software faz diretamente (o domínio do problema): Por exemplo, "permitir que o usuário faça login" é um requisito do domínio. Já "o sistema precisa responder ao login em menos de 1 segundo" é uma característica da arquitetura (desempenho).
Afeta a estrutura do software: Se precisamos que o sistema seja muito seguro para pagamentos, talvez tenhamos que criar um módulo específico e isolado para essa função. Isso influencia a forma como o software é construído.
É essencial para o sucesso da aplicação: Se o sistema de um banco ficar fora do ar com frequência, mesmo que as funcionalidades de transferência funcionem bem, ele não terá sucesso. A disponibilidade (tempo que o sistema fica online) é uma característica da arquitetura essencial.



Operacionais: Como o sistema funciona em termos de velocidade (desempenho), capacidade de lidar com muitos usuários (escalabilidade), se manter online (disponibilidade), etc.
Estruturais: Como o código é organizado, se é fácil de mudar (manutenção), se pode ser usado em diferentes sistemas (reutilização), etc.
Transversais: Características que se aplicam a várias partes do sistema, como segurança (autenticação, autorização), acessibilidade (para pessoas com deficiência), privacidade, etc.





Aula 16/04


Fundamentos da Arquitetura de Software
Criar um resumo

Padrões Fundamentais: A Base de Tudo

Assim como na culinária existem técnicas básicas que são usadas em várias receitas, na arquitetura de software também existem padrões fundamentais que aparecem de diferentes formas em estilos mais complexos. Um exemplo clássico é o conceito de camadas, que separa o software em partes com responsabilidades diferentes (como a parte que mostra as coisas para o usuário e a parte que acessa o banco de dados). Essa ideia de camadas é bem antiga, mas continua sendo usada até hoje.

A Grande Bola de Lama: Quando a "Receita" Deu Errado

Imagine uma cozinha onde tudo está jogado, sem nenhuma organização. Os ingredientes estão misturados de qualquer jeito, os utensílios espalhados... O resultado provavelmente não será muito bom. Na arquitetura de software, quando não existe nenhuma estrutura clara, os arquitetos chamam isso de Grande Bola de Lama.

É um sistema confuso, cheio de código mal organizado, difícil de entender e de mudar. As informações ficam espalhadas por todo lado, como se tudo fosse "global". Geralmente, esses sistemas surgem quando a equipe está com muita pressa e não se preocupa em criar uma estrutura desde o início, ou quando a estrutura inicial se perde com o tempo.

É o tipo de arquitetura que todo mundo quer evitar, porque dificulta muito fazer qualquer alteração, testar o sistema, fazê-lo crescer (escalabilidade) e ter um bom desempenho. Infelizmente, é mais comum do que se imagina!

Arquitetura Unitária: Tudo em Um Só Lugar

Pense no primeiro computador, onde o software e o hardware eram quase uma coisa só. A arquitetura unitária é parecida: todo o software roda em um único lugar, como um único programa no seu computador.

Hoje em dia, essa arquitetura é rara fora de sistemas muito específicos (como os que rodam dentro de equipamentos eletrônicos). A maioria dos softwares precisa crescer e lidar com mais coisas, então é melhor separar as responsabilidades.

Cliente/Servidor: A Divisão de Tarefas

Com o tempo, percebeu-se que era melhor dividir o trabalho. A arquitetura cliente/servidor faz exatamente isso: separa a parte que o usuário vê e interage (o "cliente") da parte que processa os dados e faz o trabalho pesado (o "servidor"). Existem diferentes tipos dessa arquitetura, dependendo de como essa divisão é feita:

Desktop + servidor de banco de dados: O programa rodava no seu computador (desktop) e pegava os dados de um servidor de banco de dados separado.
Navegador + servidor web: O que a gente mais usa hoje em dia! O navegador (Chrome, Firefox) é o cliente e o servidor web (onde o site está hospedado) é o servidor. Mesmo que o servidor web use um banco de dados separado, ainda é considerado uma arquitetura de duas camadas.
Três camadas: Aqui, aparece uma camada intermediária entre o cliente e o banco de dados, geralmente um servidor de aplicação. Isso ajuda a organizar melhor o sistema e facilita a manutenção.
Monolíticas Versus Distribuídas: Uma Grande Divisão

Agora chegamos a uma das principais formas de classificar os estilos de arquitetura:

Monolíticas: Todo o código do sistema é empacotado e rodado como uma única unidade. Pense em um bolo inteiro.
Distribuídas: O sistema é dividido em várias partes independentes que rodam separadamente e se comunicam através da rede. Pense em vários docinhos diferentes que juntos formam a sobremesa.
O texto vai detalhar vários estilos dentro dessas categorias, mas já adianta que as arquiteturas distribuídas, apesar de serem mais poderosas em termos de desempenho, escalabilidade e disponibilidade, trazem consigo novos desafios.

As "Oito Falácias da Computação Distribuída": As Ciladas da Rede

Quem trabalha com sistemas distribuídos precisa ter em mente que a rede não é perfeita. Existem algumas "ilusões" comuns que arquitetos e desenvolvedores têm sobre a rede, mas que não são verdade:

A rede é confiável: Não é! Ela pode falhar, ter problemas de conexão, etc.
A latência é zero: Leva tempo para a informação ir de um lugar para outro na rede.
A largura de banda é infinita: A quantidade de dados que pode ser transmitida pela rede em um certo tempo é limitada.
A rede é segura: A comunicação pela rede pode ser interceptada e atacada.
A topologia nunca muda: A estrutura da rede (roteadores, etc.) muda o tempo todo.
Existe apenas um administrador: Em empresas grandes, existem vários administradores de rede.
O custo do transporte é zero: Usar a rede tem custos (infraestrutura, etc.).
A rede é homogênea: A rede é feita de equipamentos de diferentes fabricantes, que nem sempre funcionam perfeitamente juntos.
Entender essas "falácias" é crucial para projetar sistemas distribuídos que funcionem de forma confiável e eficiente.

Outras Considerações em Sistemas Distribuídos:

Além das falácias, existem outros desafios em arquiteturas distribuídas que não existem em sistemas monolíticos:

Log distribuído: Acompanhar o que aconteceu em diferentes partes do sistema para encontrar um erro é muito mais difícil.
Transações distribuídas: Garantir que várias operações em diferentes partes do sistema aconteçam de forma consistente (tudo ou nada) é mais complexo do que em um sistema único.
Manutenção e versionamento de contrato: Definir e manter as regras de comunicação entre as diferentes partes do sistema (os "contratos") e lidar com diferentes versões desses contratos é um desafio.









Aula 24/04


Estilo de Arquitetura em Camadas

#Dia 24/04



4 principais camadas

sistema ditribuido pode usar camadas: semapraçao de responsabilidades por isso nos usamos camadas esse é o o motivo para que consiga isolar ua parte aalgo que so essa camada é responsalvel

cada camada conversa com quem esta abixo dela 

copartilhamento de componentes 

pulo de camadas tambem é possivel





