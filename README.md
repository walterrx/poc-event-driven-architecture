# Event-Driven Architecture (EDA)

"*O estilo de arquitetura orientada a eventos (event-driven) é um estilo de arquitetura assíncrona distribuída, popular, usada para produzir aplicações altamente escaláveis e de alto desempenho. Também é altamente adaptável e pode ser usada para aplicações pequenas e tão grandes quanto as complexas. A arquitetura orientada a eventos é composta de componentes de processamento de eventos dissociados que recebem e processam eventos de forma assíncrona. Ela pode ser utilizada como um estilo de arquitetura independente ou incorporada a outros estilos de arquitetura (como uma arquitetura de micro-services orientada a eventos).*" (Fundamentals of Software Architect, O'Really - 2020 pág. 179)

Neste guia você encontrará todo fundamento da orientação a eventos, desde uma rápida iniciação, os motivadores do uso deste estilo arquitetural, trade-offs, exemplos nas maiores empresas, ferramentas, governança, DevOps e como utiliza-la.

## Overview e Procedimentos

* [Introdução](intro)

* [Casos de Uso/ Exemplos](uso)
  * [Event Broker x Message Broker](brokersconfusion)

* [Anti-Patterns](antipatterns)

* [Topologias]()

  * [Mediator](mediator) 
      * Casos de Uso
      * Vantagens e Desvantagens
      * Ferramentas
        * [Apache Camel](camel-home) 

  * [Broker](broker)
       * Casos de Uso
       * Vantagens e Desvantagens
       * Ferramentas
         * [Apache Kafka](kafka-home)
         * [Rabbit MQ](rabbit-home) 

* [Estilos Processamento de Evento](eventstyles)
  * [Simple Event](simpleevent)
  * [Event Stream](eventstream) 
  * [Complex Event (CEP)](complexevent) 
  * [On line Event](onlineevent) 

* [Padrões](eventpatterns)
  * [Event Notification](eventnotification)
  * [Event Carried State Transfer](eventcarried) 
  * [Event Source](eventsource) 

* [Governança](xxx.md)
  * [Eventos Inter Domínio](governanca-eventosinter)
  * [Eventos Entre Domínio](governanca-eventosentredominio)
    * [Event Storming](governanca-eventstorming)
    * [Catálogo de Eventos](governanca-catalogo)
    * [Schema Registry](governanca-schema)

* [Gestão de Acessos](acessos)

* [Circuito DevOps](devops)
  * [Automação para Criar Fila](devops-fila)
  * [Automação para Criar Tópico](devops-topico)
  * [Validadores Schema Registry](devops-schemaregustry)

* [Referências](references)

---
Contato:
```
Email xxxxx
```
