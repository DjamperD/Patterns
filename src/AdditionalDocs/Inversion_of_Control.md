# Инверсия управления (Голливудский принцип)

**Inversion of Control** - это некий абстрактный принцип, набор рекомендаций для написания слабо связанного кода. Суть которого в том, что каждый компонент системы должен быть **как можно более изолированным от других**, не полагаясь в своей работе на детали конкретной реализации других компонентов.
***

**Компоненты высокого уровня не должен зависеть от компонентов низкого уровня.**

Все подходы, основанные на инверсии управления, страдают от следующих **двух недостатков**:

 - Логика взаимодействия программы разбросана по отдельным обработчикам событий или классам;
 
 - Поток управления задан неявно и использует общее состояние (shared state) обработчиков событий.
 
 **Одной из реализаций IoC в применении к управлению зависимостями является [**внедрение зависимостей**][DIP]**. Внедрение зависимости используется во многих фреймворках, которые называются **IoC-контейнерами**.
 
 [DIP]: </src/AdditionalDocs/SOLID/Dependency_Inversion_principle.md>