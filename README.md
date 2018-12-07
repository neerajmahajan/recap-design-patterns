# recap-design-patterns
Repository to revise and document design patterns.

#### Command Pattern
* decouple what from who
* decouple what from when
* undo
* redo

#### Strategy and Template 
* solve same problem
* Replace condiional logic with different strateries.
* Apply the strategy based on key. Eg Map(key,value) will contain set of strategies based on the key. when client pass the key, look up the strategy based on client passed key.

##### Static Factory Method

##### Factory Method
* A Factory Method is a nonstatic method that returns a base class or interface type and that is implemented in a hierarchy to enable polymorphic creation.
* A Factory Method must be defined/implemented by a class and one or more subclasses of the class. The class and subclasses each act as Factories. However, we don't say that a Factory Method is a Factory.
* A Factory Method is useful for polymorphic creation.
* A class that is a Factory is one that implements one or more Creation Methods.
* Prefer creation methods instead of multiple constructors.
* Factory Method is a Creation Method but not necessarily the reverse

##### Abstract Factory
* An Abstract Factory is "an interface for creating families of related or dependent objects without specifying their concrete classes"
* Abstract Factories are designed to be substitutable at runtime, so a system may be configured to use a specific, concrete implementor of an Abstract Factory.
* 
