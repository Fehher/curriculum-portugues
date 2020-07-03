
# Cicero Oliveira
>Software Engineer, 38 anos, São Paulo, Perdizes - SP    
>Fehher@gmail.com  
>+55 (11) 99852-8195. 



### Perfil

Tenho atuado com desenvolvimento de software, em especial com a plataforma .NET e recentemente estou estudando Rust. Meu foco de atuacao tem sido construir sistemas distribuidos, Integrações entre sistemas, desenvolver sistemas que suportem e manipule grandes volume de dados, escrever codigo eficiente e de alta performance, paralelismo, concorrencia, implementando modelos arquiteturais (Hexagonal,Clean), cloud design patterns (Competing consumers, sidecars, batch-processing, cqrs), arquitetura orientanda a eventos, domain-driven-design e troubleshooting de aplicacoes (ETW, Perfview, dotnet-Benchmark e Pareto)

### Formação Acadêmica

- **Universidade Presbiteriana Mackenzie**, Bacharel em Sistemas de Informação (2008 - 2012)
- **ILAC English of School - Intercâmbio de idioma**, Canadá - Toronto (2017/09 - 2018/01)

### Experiência

---
- **Sovos - Tax Compliance & Regulatory Reporting**, Principal Developer VAT Product - *2018/03 até atual*

Projetos:

- **GVAT - Tax Compliance & Regulatory Reporting**: Sistema responsável por criar e gerar relatórios, analises, dados estatísticos e transmitir obrigações fiscais nos países europeus.
**Tecnologias do Projeto:** Arquitetura monolítica passando por reorganizacao estrutural. Principio de paretto, profile aplicado para identificar problemas no software, Domain Driven Design sendo utilizado para gerar separacao por contextos. Linguagem C#, API, React e SQL Server e Hangfire.

  *Desafios técnicos e patterns utilizados:*
     - Diagnosticar problemas de performance
     - Principio de Pareto
     - Identificar e Separação do projeto em contextos delimitados
     - Tipos de colaboração entre servicos
     - Integração com sistema europeu de Vatnumbers
     - Docker AWS Fairgate
    

- **GVAT - Importacao de Batches em Lote**: Processo de importação de transações, que consiste em ler arquivos excel com milhões de transações, processar, gerar analises sobre os dados, limpeza, e disponibilizar para geração de relatórios.
**Tecnologias do Projeto:** Arquitetura Hexagonal, Serviços distribuídos, Linguagem C#, Mongo, Docker, RabbitMq/Masstransit, API, Kibana, Elastic Search e logstash.

    *Desafios técnicos e patterns utilizados:*
     - Capacidade de Processar milhões de transações por dia e simultâneas
     - Work Queue system e Competing Consumers
     - Concorrência, Paralelismo, DDD e serviços distribuídos
     - Arquitetura Hexagonal
     - Docker AWS Fairgate

---
**LTM - Loyalty & Trade Management**, Líder Técnico do Time de Catálogo - *2015/04 até 2018/01*

Projeto:
- **Importação de Produtos**: Sistema que se conecta a vários parceiros na busca por informações de produtos.
O principal objetivo nesse processo, e se conectar através de protocolos especificos em um determinado parceiro e obter dados sobre os produtos e disponibilidade. Essas integrações ocorrem com grandes parceiros de mercado como Via Varejo, B2W, Magazine luiza entre outros.
**Tecnologias do Projeto:** Linguagem C#, SQL Server, SOLR, ELK, Cloud Patterns, Hangfire e API.

  *Desafios técnicos e patterns utilizados:*
   - Integração com diversos sistemas externos
   - Capacidade de importar e processar milhões de produtos

- **Catálogo de Produtos**:
Microserviço responsavél por exibir os catalogos de produtos, filtrar dados, exibir informações sobre disponibilidade, aplicar filtros personalizados por parceiros.
**Tecnologias do Projeto**: Linguagem C#, API, EF, CouchDB, Redis, Solr, Azure, API Management e AngularJS.

   *Desafios técnicos e patterns utilizados:*
     - Resiliência, Tolerancia a Falha e Alta Disponibilidade
     - SignarlR, Arquitetura Hexagonal
     - Concorrência, Assincronismo e Paralelismo
    
---
**CTIS Tecnologia**, Analista Desenvolvedor Sênior - *Junho, 2014 até Março, 2015*

*Atuando na definição de modelos de Arquitetura e Integrações de Serviços.*

Projeto:
- **SGF**: Sistema de gerenciamento de fiscalização e documentação sobre as Árvores.
Arquitetura de Serviços, baseado em um Gateway de troca de informações.
Sistema de Gestão e Fiscalização de dados sobre a saúde das árvores do estado de São Paulo. O software permite que um funcionário 
saia a campo munido de um Tablet, e que realize um cadastramento de cada árvore,e que agrupe essas informações sobre sua vida, sua 
saúde e etc. As informações são coletadas em modo off-line, assim não restrigindo o cadastramento por ausência de rede de dados e/ou qualquer interferência, essas informações, juntamente com histórico de saúde, são armazenadas em Banco Web SQL no navegador com HTML5.
**Tecnologias do Projeto:** ASP.NET API, Entity Framework, C#, Domain-Driven Design, Test-Driven Development, Azure Service Bus, SQL Server,Bootstrap Avant, MongoDB, Web SQL, AngularJs e Git*

    *Desafios técnicos e patterns utilizados:*
     - Persistência das informações no browser
     - SignarlR para comunicação em tempo real
     - Request/Reply
     - Polling Consumer

---
**Banco ABC Brasil**, Analista Desenvolvedor Sênior - *Setembro, 2012 até Junho, 2014*

*Responsável pela definição do modelo de Arquitetura e Integração.*

Alguns projetos:
- **Projeto de Boletagem**: Área responsável por iniciar cada operação de crédito no Banco.
O Sistema de Boletas é responsável por iniciar cada operação de crédito no banco, essas operações originam alguns tipos de créditos, como Swap, Debêntures e Opções. Tendo por consequência uma integração on line com o Banco Central
**Tecnologias do Projeto:** ASP.NET MVC, WCF, EntityFramework, SQL Server, RabbitMQ, TFS e AngularJs.


- **Back-Office**: Área responsável pelo batimento de operações de boletagem com o ERP da TOTVS.
Sistema que realiza os batimentos de cadas operação de crédito de origem da boleta com o ERP e distribuição dessas transações por toda a rede do banco, todas as transações são realizadas atráves de serviços WCF utilizando protocolo pipe, RabbitMQ como serviço de mensageria e Highcharts para composição de Dashboards, assim verificando se cada estágio da operação.
**Tecnologias do Projeto:** ASP.NET MVC, WCF, SQL Server, C#, RabbitMQ e Highcharts


---
**Porto Seguro Seguros**, Analista Desenvolvedor Pleno - *Novembro, 2011 até Junho, 2012*

*Atuando no desenvolvimento.*

- **Pronta Resposta da Porto**: Área responsável pelo rastreio de veículos roubados.
Sistema responsável por rastrear cada veículo roubado no estado de São Paulo, com base em seu rastreador,e que notifica a central de polícia,e notifica os agentes em campo atráves de um app, sobre as características do veículo, assim acionado agente mais proxímo.
**Tecnologias do Projeto:** ASP.NET WF, SQL Server, Oracle, NHibernate e WCF.

---
**Resource IT Solutions**, Analista Desenvolvedor Pleno - *Junho, 2010 até Novembro, 2011*

*Atuando no desenvolvimento.*


- **Itaú** Atendendo as áreas de Tesouraria, Cobranças, Back-Office e Câmbio. Áreas de produtos diversos.
Atuei em diversas áreas dentro do banco, levantamento, na correção de problemas, desenvolvimento de novas funcionalidades.
**Tecnologias do Projeto:** ASP.NET WF, DDD, SQL Server, Oracle, DB2, C#, JQuery, JS.

---
**Sof Informática e Consultoria**, Analista Desenvolvedor Pleno - *Abril, 2009 até Abril, 2010*

*Atuando no desenvolvimento.*

- **Plataforma de Relacionamento Carrefour**: Disponibilizar Cartão de Crédito na bandeira do Carrefour.
Plataforma de Relacionamento, responsável por prospectar novos clientes e geração de Private Label, esse sistema se comunica e troca informações com 4 grandes players do mercado relacionado a avaliação de crédito, fraude e geração do plástico. Um cliente, tenta se associar e adquirir um cartão de crédito, e todo esse processo no qual ele se cadastra como cliente, passa pela URA no chile, SantaElen e motor de créditos para validar seu histórico de créditos, todo esse processo de integração e feito via serviços WCF Rest, esse processo permite que um cliente consiga um crédito pré aprovado.
**Tecnologias do Projeto:** ASP.NET MVC, C#, Monorail, Castle Project, Windsor Container, Active Record, WCF Rest e JQuery.

    *Desafios técnicos e patterns utilizados:*
     -  Trafegar dados numa rede de 8k
     

---
### Habilidades e Conhecimentos.

Algumas Tecnologias, Bibliotecas, Ferramentas, Ambientes e Técnicas adquiridos, por experiência em Projetos, Estudos ou Cursos:

- *Arquitetura Distribuida*:
    - Microserviços, Arquitetura Orientada a Eventos, Programação Paralela e Distribuída, CQRS, Controle de Concorrência Optimistica, Programação Assíncrona, Cloud Patterns, Coreografia, Orchestracao, 2PC e Saga Pattern.
- *Padroes, Praticas e Abordagens*:
    - Domain Driven Design, Design Patterns, Arquitetura Onion, Hexagonal e Clean
- *Analise e Performance*: 
    - dotnet Benchamark, ETW Profiler, Perfview, Speedscope e Windbg.
- *Ambientes CI/ CD*:
    - Azure, Docker, AWS, GIT
- *Linguagens*:
    - C#, Rust
- *Services Bus*
    - RabbitMQ (Masstransit) e Azure Service Bus
- *NoSql e outros*:
    - MongoDB, CouchDB, Scarlyr e SQL Server
- *ORM e Frameworks*:
    - Entity Framework 6 e Core, Dapper, MediatR, Swagger e OAuth
- *FrontEnd*:
    - AngularJs, JQuery, React e HTML.
- *Frameworks de Testes e ambientes*:
    - Jasmines, Mocha, Xunit e Selenium
  
### Certificações
- Programming in C#

### Idiomas

- Inglês - Avançado

[Versão PDF](https://gitprint.com/Fehher/Curriculum/blob/master/README.md?download)
