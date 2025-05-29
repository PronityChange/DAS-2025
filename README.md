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

#Dia 28/05

-Resumo



# Topologia da Arquitetura Baseada em Serviços

A topologia básica da SBA consiste em:

- Interface de usuário (IU) separada: Implantada de forma independente.
- Serviços de domínio remotos e separados: São as "partes de uma aplicação", independentes e implantadas separadamente, geralmente como arquivos EAR, WAR ou assembly, sem a necessidade obrigatória de conteinerização.
- Banco de dados monolítico: Normalmente, os serviços compartilham um único banco de dados.

O número de serviços em um contexto de aplicação geralmente varia entre quatro e doze, com uma média de sete. Embora uma única instância de cada serviço de domínio seja comum, múltiplas instâncias podem existir para escalabilidade, tolerância a falhas e necessidades de taxa de transmissão, exigindo balanceamento de carga.

Os serviços são acessados remotamente pela IU usando protocolos como REST, mensageria, RPC ou SOAP. Em muitos casos, a IU acessa os serviços diretamente, embora uma camada de API (proxy ou gateway) possa ser usada para acesso externo ou para consolidar preocupações transversais.

Um aspecto crucial é o banco de dados compartilhado centralizado, que permite que os serviços utilizem consultas SQL e junções como em uma arquitetura monolítica. A principal preocupação nesse modelo são as alterações no esquema do banco de dados, que podem impactar múltiplos serviços se não forem gerenciadas corretamente.



#Variantes da Topologia

A SBA oferece grande flexibilidade de topologia:

- IU federada: A IU monolítica pode ser dividida em domínios de IU, correspondendo aos serviços de domínio.
- Bancos de dados particionados: O banco de dados monolítico pode ser dividido em bancos de dados separados, até o ponto de corresponder a cada serviço de domínio (similar a microsserviços). Nesses casos, é vital garantir que os dados de um banco de dados não sejam necessários por outro serviço para evitar comunicação interna e duplicação de dados.
- Camada de API: Um proxy ou gateway reverso pode ser adicionado entre a IU e os serviços para expor funcionalidades a sistemas externos ou consolidar preocupações transversais (métricas, segurança, auditoria, descoberta de serviço).



#Design do Serviço e Granularidade

Os serviços de domínio na SBA são granulares e tipicamente projetados com uma arquitetura em camadas (fachada da API, camada comercial e camada de persistência) ou por subdomínios, similar a monólitos modulares.

A fachada de acesso à API orquestra as requisições de negócio da IU. Por exemplo, um serviço `OrderService` pode orquestrar internamente a criação de um pedido, a aplicação de pagamento e a atualização de inventário. Essa orquestração no nível da classe interna é uma diferença chave em relação aos microsserviços, que orquestrariam vários serviços remotos menores para a mesma tarefa.

A granularidade dos serviços permite o uso de transações ACID (atomicidade, consistência, isolamento, durabilidade), garantindo 
-a integridade do banco de dados. Em contraste, arquiteturas altamente distribuídas como microsserviços frequentemente usam transações BASE (disponibilidade básica, estado suave, consistência eventual), que oferecem consistência eventual e menor nível de integridade de dados.

Embora a granularidade dos serviços na SBA proporcione melhor integridade de dados, uma alteração em um serviço pode exigir o teste de uma funcionalidade mais ampla (ex: processamento de pagamento dentro de um `OrderService` maior), o que pode aumentar o risco de quebrar outras funcionalidades em comparação com microsserviços.



#Particionamento do Banco de Dados

O compartilhamento de um banco de dados monolítico é comum na SBA. Para mitigar o impacto de alterações no esquema de banco de dados, é recomendável particioná-lo logicamente e manifestar esse particionamento através de bibliotecas compartilhadas federadas. Em vez de uma única biblioteca com todos os objetos de entidade, ter bibliotecas específicas para cada domínio lógico (ex: `invoice_entities_lib`) garante que alterações em um domínio afetem apenas os serviços que usam aquela biblioteca, reduzindo o esforço e a coordenação. Tabelas e objetos de entidade comuns devem ter acesso de alteração limitado para controlar mudanças que afetam todos os serviços.



- Classificações das Características da Arquitetura

A SBA é particionada por domínio, o que significa que a estrutura é orientada pelo domínio de negócio, não por considerações técnicas. Isso resulta em:

Agilidade (4 estrelas): Capacidade de responder rapidamente a mudanças.
Testabilidade (4 estrelas): Fácil e completa testagem devido ao escopo limitado do domínio.
Implementabilidade (4 estrelas): Implementações mais frequentes com menor risco.

Essas características contribuem para um melhor tempo de lançamento no mercado.

- Tolerância a Falhas e Disponibilidade (4 estrelas): Devido à independência dos serviços, a falha de um serviço geralmente não impacta os outros.
- Escalabilidade (3 estrelas) e Elasticidade (2 estrelas):** Embora possíveis, a replicação de mais funcionalidade em serviços mais granulares torna-a menos eficiente em termos de recursos de máquina em comparação com microsserviços.
- Simplicidade e Custo Geral (altos): A SBA é a arquitetura distribuída mais fácil e econômica de implementar, tornando-a atraente para muitas empresas.
- Confiabilidade (alta): Serviços maiores resultam em menos tráfego de rede e menos transações distribuídas, aumentando a confiabilidade geral da rede.

O número de quanta (unidades independentes de implantação) em uma SBA pode ser um ou mais. Mesmo com vários serviços implantados separadamente, se eles compartilham o mesmo banco de dados ou IU, o sistema inteiro pode ser considerado um único quantum. No entanto, com IU e banco de dados federados, pode haver múltiplos quanta.



#Quando Usar Este Estilo de Arquitetura

A flexibilidade e as classificações de três e quatro estrelas em diversas características tornam a SBA um dos estilos mais pragmáticos. É ideal para:

- Design Orientado a Domínios: Como os serviços são granulares e no escopo do domínio, cada domínio se encaixa bem em um serviço de domínio implantado separadamente, facilitando a aplicação de alterações.
- Preservação de Transações ACID: A SBA preserva melhor as transações ACID do que outras arquiteturas distribuídas, pois a maioria das transações fica no escopo de um único serviço de domínio. Em casos de orquestração de múltiplos serviços, podem ser necessárias sagas e transações BASE.
- Modularidade Arquitetural sem Complexidade Excessiva: Oferece um bom nível de modularidade sem as complexidades e armadilhas da granularidade fina, como a necessidade de orquestração e coreografia extensivas encontradas em microsserviços.

Em resumo, a arquitetura baseada em serviços oferece um equilíbrio sólido entre os benefícios das arquiteturas distribuídas e a simplicidade de implementação, tornando-a uma opção robusta e acessível para muitas aplicações comerciais.



# Topologia e Filosofia

A topologia de microsserviços é caracterizada por:

-Serviços Distribuídos: Cada serviço roda em seu próprio processo, tipicamente em contêineres ou máquinas virtuais. Isso permite isolamento operacional e facilita o gerenciamento de recursos. No entanto, a natureza distribuída pode impactar a performance devido a chamadas de rede e verificações de segurança adicionais.
- Contexto Delimitado:** A essência dos microsserviços é que cada serviço modela um domínio ou fluxo de trabalho específico, incluindo tudo o que precisa para operar independentemente (classes, subcomponentes e esquemas de banco de dados). Isso leva a um extremo desacoplamento em níveis lógicos e operacionais.
- Granularidade: O termo "microsserviço" é um rótulo, não uma descrição de tamanho. A granularidade ideal busca capturar um domínio ou fluxo de trabalho funcionalmente coeso. Erros comuns incluem tornar os serviços pequenos demais, o que leva a uma comunicação excessiva entre eles. A iteração no design é crucial para encontrar a granularidade certa.
Isolamento dos Dados: Cada microsserviço possui seu banco de dados contido (contained database), evitando esquemas e bancos de dados compartilhados para eliminar pontos de acoplamento. Embora isso crie desafios de coordenação de dados, permite que cada serviço escolha a tecnologia de persistência mais adequada para suas necessidades, aumentando a flexibilidade.
- Camada da API (Opcional):** Geralmente presente entre os consumidores (IUs, outros sistemas) e os microsserviços. É um local estratégico para tarefas operacionais como descoberta de serviços e gerenciamento de tráfego, mas não deve ser usada para orquestração de lógica de negócio, pois isso violaria a filosofia de contexto delimitado.
- Reutilização Operacional: Em vez de compartilhar funcionalidades operacionais no código (o que geraria acoplamento), microsserviços utilizam o padrão sidecar. Componentes sidecar separados, próximos a cada microsserviço, lidam com preocupações transversais (monitoramento, log, circuit breakers). Esses sidecars podem se conectar para formar uma malha de serviços, proporcionando controle unificado e visibilidade global sobre os aspectos operacionais.
- Descoberta de Serviços:** Essencial para a elasticidade, permite que as requisições encontrem instâncias de serviços disponíveis, monitorando o número e a frequência das requisições para ativar novas instâncias conforme a necessidade.



#Comunicação

A comunicação entre microsserviços pode ser:

- Síncrona: Geralmente por protocolos reconhecidos (ex: REST), onde o solicitante aguarda uma resposta. Os microsserviços favorecem a interoperabilidade heterogênea com reconhecimento de protocolo, permitindo que diferentes serviços usem diferentes stacks tecnológicas e se comuniquem por meio de protocolos padronizados.
 Assíncrona: Comumente através de eventos e mensagens, utilizando padrões de coreografia ou orquestração.

#Coreografia e Orquestração

- Coreografia: Não há um coordenador central. Os serviços se comunicam diretamente através de eventos, respeitando a filosofia de desacoplamento do contexto delimitado. Isso é vantajoso para a filosofia da arquitetura, mas pode tornar a coordenação e o tratamento de erros mais complexos em fluxos de trabalho complexos.
- Orquestração: Um serviço mediador central coordena as chamadas entre múltiplos serviços para um fluxo de trabalho complexo. Embora crie algum acoplamento, centraliza a lógica de coordenação e simplifica o tratamento de erros em cenários mais intrincados. A escolha entre coreografia e orquestração depende da complexidade do fluxo de trabalho e do equilíbrio entre desacoplamento e facilidade de coordenação.



#Transações e Sagas

Em microsserviços, criar transações que abrangem vários serviços é desencorajado, pois viola o princípio fundamental do desacoplamento. O ideal é corrigir a granularidade dos serviços para que as transações ocorram dentro de um único serviço (transações ACID).

Quando transações distribuídas são inevitáveis (devido a requisitos de arquitetura muito diferentes), o padrão Saga é uma solução popular. Uma saga coordena uma sequência de transações locais, onde cada transação atualiza os dados em um único serviço. Se uma parte da transação falha, a saga executa transações de compensação para desfazer as operações bem-sucedidas anteriores, restaurando a consistência do sistema. No entanto, o padrão saga adiciona complexidade e tráfego de rede, e seu uso deve ser parcimonioso.


#Classificações das Características da Arquitetura

Microsserviços se destacam em:

- Escalabilidade (5 estrelas): Permite escalar serviços individualmente.
- Elasticidade (5 estrelas): Alta capacidade de adaptação à demanda, suportada por automação e descoberta de serviços.
- Evolutibilidade (5 estrelas): Favorece a alteração evolutiva no nível da arquitetura devido às unidades de implementação pequenas e altamente desacopladas.
- Agilidade, Testabilidade, Implementabilidade (Altas): Beneficiadas pelo desacoplamento e automação.

Pontos que podem ser desafiadores:

- Performance (2 estrelas): Devido ao overhead de chamadas de rede e verificações de segurança.
- Confiabilidade e Tolerância a Falhas (impactadas por muita comunicação entre serviços):** Embora tendam a ser altas devido à independência dos serviços, dependem da minimização da comunicação entre eles.

Em essência, a arquitetura de microsserviços, com sua filosofia de desacoplamento extremo e foco no domínio, oferece imensos benefícios em escalabilidade e agilidade, mas requer um gerenciamento cuidadoso da granularidade, isolamento de dados e comunicação para mitigar suas complexidades inerentes.








