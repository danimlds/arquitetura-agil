# Arquitetura Ágil de Software

# O que é Arquitetura de Software?

"Arquitetura de software envolve a **descrição dos elementos** a partir dos quais o sistema é construído, as **interações entre esses elementos**, os **padrões que orietam sua composição** e as **restrições sobre esses padrões.**" (SHAW; GARLAN, 1996)

"Estrutura que fundamenta as **desisões de design de alto nível**, incluindo coisas como a **forma como o sistema é composto por partes que interagem**, quais são as **principais formas de interação e quais são as **principais propriedades das partes e do sistema** como um todo." (GARLAN, 2014)

*A arquitetura de software normalmente desempenha um papel fundamental como ponte entre requisitos e implementação*

A arquitetura de um sistema de software é a **forma dada a esse sistema por aqueles que o constroem. Essa forma é definida pela divisão do sistema em **componentes**, na **disposição desses componentes** e nas **maneiras como esses componentes comunicam entre si**.(MARTIN, 2018)

"A arquitetura de software de um sistema é o **conjunto de estruturas** necessárias para pensar sobre o sistema, que inclui **elementos de software, relações entre eles** e **propriedades de ambos**."(BASS; CLEMENTES; KAZMAN, 2014)

*A arquitetura tem o objetivo facilitar o desenvolvimento, a implantação, a operação e manutenção do software*.

"Arquitetura representa as *decisões significativas do projeto** que moldam o sistema, onde o **significativo é medido pelo custo da mudança**".(BOOCH, 2008)

"**Conceitos ou propriedades fundamentais de um sistema** em seu ambiente incorporado em seus **elementos, relacionamentos e nos princípios de seus design e evolução**."(ISO/IEC/IEEE, 2011)

*Toda arquitetura é um projeto, mas nem todo projeto é uma arquietura*.

A arquitetura de software consiste na **estrutura** do sistema, combinada com as **características** que o sistema deve suportar, **decisões** arquitutais e, finalmente, **princícios de design**(RICHARDS; FORD, 2020)

#Importância da Arquitetura de software

Se bem definida:

* Facilita o **gerenciamento** da **complexidade**;
* Auxilia a **evitar problemas** durante o processo de desenvolvimento;
* Contribui na **compreensão, reutilização, desenvolvimento, análise, evolução** e ** manutenção** de software;

**Fator crítico de sucesso** para o projeto de software.

Fundamental para **relacionar** as **características** do software com a sua **implementação**.

Ajuda a **satisfazer requisitos não funcionais** e de **qualidade**, como:

* Desempenho;
* Confiabilidade;
* Portabilidade;
* Escalabilidade e
* interoperabilidade;

É **comum** desenvolver **software sem uma arquitetura formal** ou com uma **arquitetura confusa e mal definida**

* Resultado:
   * Módulos e código-fonte desorganizados, sem papéis e responsabilidades definidas e com relacionamentos confusos entre si
   * Conhecido como **"Big ball of mud"**

Sem uma arquitetura formal **é difícil**:

* Determinar **características arquiteturais** de aplicação;

* **Responder perguntas básicas** sobre implantação e manutenção:
   * A arquitutura é dimensionada?
   * Quais são as características de desempenho de software?
   * Com que facilidade de software responderá à mudança?
   * Quais são as características de implantação do software?
   * Quão resposiva é a arquitetura?

**Se você acha** que uma **boa arquitetura é cara, experimente uma** arquitetura **ruim**

#Lei de Conway

Qualquer organização que projete um sistema produzirá um **design cuja estrutura** é uma **cópia da estrutura de comunicação da organização**

* Melvyn Conway, 1967

**Habilidades** de um arquiteto de software:

* Entender o processo de desenvolvimento
* Conhecer o domínio do negócio
* Conhecer diferentes metodologias e tecnologias
* Saber projetar e programar
* Saber negociar
* Comunicar - se muito bem(fala e escrita)

**Atividades** comuns na rotina de um arquiteto de software:
* Analizar trade-offs de possíveis soluções
* Tomar decisões:
   * Difícies em contextos ambíguos e incertos
   * que geram impactos de longa duração
   * que afetam diferentes aspectos (estruturais e implementação) do software
* Garatir o comprimento das decicões
* Analisar constantemente a arquitetura
* Mater - se atualizado

Quando um desenvolvedor **está com o chapéu de arquiteto**, é comum: 
* Estudar os requisistos do sistema e **retomá - los durante as decisões**
* Poderar a importância das demandas para **definir um roteiro** de implementação
* Rever as definições arquiteturais para **corrigir implementações** ou **redefinir arquitetura**
* Guiar discissões e **promover o conhecimento** do sistema pelos envolvidos

Acreditamos que o arquiteto de software:
* Não deve ser uma profissão, mas sim um papel
* Não trabalha sozinho, suas decisões dever ser **pautadas nas necessidades** de diferentes **stakeholders**

# Estilos Arquiteturais

[Arquitetura em Camada](https://www.oreilly.com/library/view/software-architecture-patterns/9781491971437/ch01.html)

[Arquitutura orientada à eventos](https://www.redhat.com/en/topics/integration/what-is-event-driven-architecture)

[Arquitetura Orientada à serviços](https://www.youtube.com/watch?v=jjv3Cati4NY)

[Microserviços](https://martinfowler.com/articles/microservices.html)

# Material Complementar

[o que são padrões?](https://pt.wikipedia.org/wiki/Padr%C3%A3o_de_projeto_de_software)
[part2](https://en.wikipedia.org/wiki/Pattern_language)

[CQRS](https://microservices.io/patterns/data/cqrs.html)

[Event Sourcing](https://microservices.io/patterns/data/event-sourcing.html)

[Asynchronous Messaging](https://microservices.io/patterns/communication-style/messaging.html)

[API Gateway & BFF](https://microservices.io/patterns/apigateway.html)

[Análise de Trade-offs](https://themicroservicesinfo.netlify.app/learn/trade-offs-method/)
[part2](https://dl.acm.org/doi/10.1145/3424771.3424809)

[Práticas Àgeis para Arquitetura de Software - Eduardo Guerra](https://www.youtube.com/watch?v=q-OHu0cENc4)

[Proposta de Arquitetura para o Sistema Boodle](https://www.youtube.com/watch?v=-tA-WW8eMOw&feature=youtu.be)

[Podcast Padrões de Projeto com Eduardo Guerra](https://open.spotify.com/episode/1swe5XIJL6iR6kQbVQJVdg)

[Canal Eduardo Guerra](https://www.youtube.com/user/eduardomg23)

# The benefits of the monolithic architecture

* Simple to develop - IDEs and other developer tools are focused on building single application;
* Easy to make radical changes to the application - You can change the code and the database schema, build, and deploy;
* Straightforward to test - The developers wrote end-to-end tests that launched the application, inveked the REST API, and tested the UI with Selenium;
* Straightforward to deploy - All a developed had to do was copy the WAR file to a server that had Tomcat installed;
* Easy to scale - RAN multiple instances of the application behind a load balancer;

# Escaping monolithic hell














