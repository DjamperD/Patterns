# Patterns of c programming java

## Принципы проектирования: 

* **Изменяемые аспекты** приложения должны быть **отделенны** от постоянных;

* Программировать на уровне **интерфейсов**, а не на уровне реализаций;

* [**Композиция**][Composition]* лучше наследования;

* Стремиться к [**слабой связанности**][LowCoupling]* взаимодействующих объектов;
  - Выделять уровень абстракции, чтобы работать с **супер типом** (Полиморфизм);
  
* Классы открыты для расширения, но закрыты для изменения([Open/closed][OCP]).



[LowCoupling]: </src/AdditionalDocs/LowCoupling.md>
[Composition]: </src/AdditionalDocs/Composition.md>
[OCP]: </src/AdditionalDocs/SOLID/Open-Closed_principle.md>
[DIP]: </src/AdditionalDocs/SOLID/Dependency_Inversion_principle.md>


[Abstract_Factory]: </src/Creational/Factorys/Abstract_Factory/Abstract_Factory.md>
[Abstract_Factory]: </src/Creational/Factorys/Factory_Method/Factory_Method.md>
[Builder]: </src/Creational/Builder/Builder.md>
[Prototype]: </src/Creational/Prototype/Prototype.md>
[Singleton]: </src/Creational/Singleton/Singleton.md>

[Adapter]: </src/Structural/Adapter/Adapter.md>
[Bridge]: </src/Structural/Bridge/Bridge.md>
[Composite]: </src/Structural/Composite/Composite.md>
[Decorator]: </src/Structural/Decorator/Decorator.md>
[Facade]: </src/Structural/Facade/Facade.md>
[Flyweight]: </src/Structural/Flyweight/Flyweight.md>
[Proxy]: </src/Structural/Proxy/Proxy.md>

[Chain_of_Responsibility]: </src/Behavioral/Chain_of_Responsibility/Chain_of_Responsibility.md>
[Command]: </src/Behavioral/Command/Command.md>
[Iterator]: </src/Behavioral/Iterator/Iterator.md>
[Mediator]: </src/Behavioral/Mediator/Mediator.md>
[Memento]: </src/Behavioral/Memento/Memento.md>
[Observer]: </src/Behavioral/Observer/Observer.md>
[State]: </src/Behavioral/State/State.md>
[Strategy]: </src/Behavioral/Strategy/Strategy.md>
[Template_Method]: </src/Behavioral/Template_Method/Template_Method.md>
[Visitor]: </src/Behavioral/Visitor/Visitor.md>