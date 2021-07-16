# Separação de Patterns por tipo

Os detalhes dos padrões estão dentro de cada uma das pastas com seu nome.

Existe um README com a descrição completa do padrão, um (ou mais) diagrama(s) e um trecho de código.

***

## Intenções Oficiais por Patterns

Cada padrão está em sua categoria correspondente, são elas: creational (criacionais), behavioural (comportamentais) e structural (estruturais).

### Behavioural (Comportamentais)

#### Chain Of Responsibility

**PT:** Text.

**EN:** Text

***

#### Command

**PT:** Encapsular uma solicitação como um objeto, desta forma permitindo que você parametrize clientes com diferentes solicitações, enfileire ou registre (log) solicitações e suporte operações que podem ser desfeitas.

**EN:** Encapsulate a request as an object, thus allowing you to parameterize clients with different requests, queue or requests (log), and support undone operations.

***

#### Iterator

**PT:** Text.

**EN:** Text

***

#### Mediator

**PT:** Text.

**EN:** Text

***

#### Memento

**PT:** Text.

**EN:** Text

***

#### Observer

**PT:** Text.

**EN:** Text

***

#### State

**PT:** Text.

**EN:** Text

***

#### Strategy

**PT:** Definir uma família de algoritmos, encapsular cada um deles e fazê-los intercambiáveis. O Strategy permite que o algoritmo varie independentemente dos clientes que utilizam.

**EN:** Define a family of algorithms, encapsulate each of them, and make them interchangeable. Strategy allows the algorithm to vary independently of the clients they use.

***

#### Template

**PT:** Text.

**EN:** Text

***

#### Visitor

**PT:** Text.

**EN:** Text

***

### Creational (Criacionais)

#### Abstract Factory

**PT:** Fornecer uma interface para a criação de famílias de objetos relacionados ou dependentes sem especificar suas classes concretas.

**EN:** Provide an interface for creating families of related or dependent objects without specifying their concrete classes.

***

#### Builder

**PT:** Separar a construção de um objeto complexo da sua representação de modo que o mesmo processo de construção possa criar diferentes representações.

**EN:** Separate the construction of a complex object from its representation so that the same construction process can create different representations.

***

#### Factory

**PT:** Definir uma interface para criar um objeto, mas deixar as subclasses decidirem que classe instanciar. O Método Factory permite adiar a instanciação para as subclasses.

**EN:** Define an interface to create an object, but let the subclasses decide which class to instantiate. The Factory Method allows you to defer instantiation for subclasses.

***

#### Prototype

**PT:** Especificar os tipos de objetos a serem criados usando uma instância-protótipo e criar novos objetos pela cópia desse protótipo.

**EN:** Specify the types of objects to be created using a instance-prototype and create new objects by copying that prototype.

***

#### Singleton

**PT:** Garantir que uma classe tenha somente uma instância no programa e fornecer um ponto de acesso global para a mesma.

**EN:** Ensure that a class has only one instance in the program and provide a global access point for it.

***

### Structural (Estruturais)

#### Adapter

**PT:** Converter a interface esperada de uma classe em outra interface esperada pelos clientes. O Adapter permite que certas classes trabalhem em conjuntos, pois de outra forma seria impossível por causa de suas interfaces incompatíveis.

**EN:** Convert the expected interface of a class into another interface expected by clients. Adapter allows certain classes to work in sets that would otherwise be impossible because of their incompatible interfaces.

***

#### Bridge

**PT:** Bridge é um padrão de projeto estrutural que tem a intenção de desacoplar uma abstração da sua implementação, de modo que as duas possam variar e evoluir independentemente.

**EN:** Bridge is a structural design pattern that is intended to decouple an abstraction from its implementation so that the two can vary and evolve independently.

***

#### Composite

**PT:** Compor objetos em estruturas de árvore para representar hierarquias parte/todo. Composite permite aos clientes tratarem de maneira uniforme objetos individuais e composições de objetos.

**EN:** Compose objects into tree structures to represent part/whole hierarchies. Composite allows customers to uniformly handle individual objects and object compositions.

***

#### Decorator

**PT:** Agregar responsabilidades adicionais a um objeto dinamicamente. Os Decorators fornecem uma alternativa flexível ao uso de subclasses para extensão de funcionalidades.

**EN:** Add additional responsibilities to an object dynamically. Decorators provide a flexible alternative to using subclasses to extend functionality.

***

#### Façade

**PT:** Façade (Fachada) é um padrão de projeto estrutural que tem a intenção de fornecer uma interface para um conjunto de interfaces em um subsistema. Façade define uma interface de nível mais alto que torna o subsistema mais fácil de ser usado.

**EN:** Façade is a structural design pattern that is intended to provide an interface to a set of interfaces in a subsystem. Façade defines a higher-level interface that makes the subsystem easier to use.

***

#### Flyweight

**PT:** Flyweight é um padrão de projeto estrutural que tem a intenção de usar compartilhamento para suportar eficientemente grandes quantidades de objetos de forma granular.

**EN:** Flyweight is a structural design pattern that is intended to use sharing to efficiently support large numbers of objects in a granular form.

***

#### Proxy

**PT:** Proxy é um padrão de projeto que tem a intenção de fornecer um substituto ou marcador de localização para outro objeto para controlar o acesso a esse objeto.

**EN:** Proxy is a design pattern that is intended to provide a surrogate or location marker for another object to control access to that object.

***
