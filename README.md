# Padrão Composite

* Pattern Name and Classification
  - Name: Composite
  - Classification: Estrutural

* Intent
  - Facilitar a implementação de objetos que se comportam como estrutura em árvore.

* Motivation
  - O Composite é um objeto projetado como uma composição de um ou mais objetos semelhantes, Todos exibindo funcionalidade semelhante.

* Applicability
  - O Composite pode ser usado quando a aplicação possui alguma hierarquia e requeira funcionalidades genéricas por toda a estrutura.

* Structure

![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/Composite_UML_class_diagram_%28fixed%29.svg/600px-Composite_UML_class_diagram_%28fixed%29.svg.png)

* Paticipants
  - Component:
    - Declara uma interface para acessar e gerenciar componentes filho
    - Implementa comportamentos padrão comuns para todas as classes
    - Declara interface para objetos da composição
  - FrameworkClass:
    - Define o comportamento para objetos primitivos da composição
    - Representa objetos folha da consição que não tem filhos

* Sample Code
  - [Código](https://repl.it/repls/VirtualInnocentNetframework#Component.java)
  - Para demonstrar o composite foi usado o exercicio do professor João Cunha durante aula.
