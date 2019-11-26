# Design Patterns :
    Creational Design Patterns
        Abstract Factory - Allows the creation objects without specifying their concrete type
        Builder - Uses to create complex types
        Singelton - Ensures only single instance of an object is created
        Prototype - Creates a new object from existing object
        Factory Method - Creates objects without specifying the exact class to create
    Structural Design Patterns
        Adapter
        Decorator
        Composite
        Proxy -  a class is used to represent the functionality of another class, example: AOP
    Behaviour Design Patterns
        Chain of responsibility
        Template Method
        Strategy
        Observer
    
# Design patterns in Spring:

Dependency injection or Inversion of control:
DI is a design pattern where an object provides dependencies of another object this is called service. 
IOC is a design prinicple through which custom written code receives control flows from a framework.
Spring has IOC container which manages the objects, wiring them up , configuring them and managing the lyfe cycle.
The container has the Dependency Injection (DI) which is used to manage the components present in an application. Such objects are known as Spring Beans
Bean is a component of the IOC container which provides the dependencies of another object.

Factory Design Pattern:
Spring BeanFactory Container: It is the simplest container present in the spring framework which provides the basic support for DI (Dependency Injection). 
We use the following interface to work with this container.[org.springframework.beans.factory.BeanFactory].

Spring ApplicationContext Container: It is another container present in spring container which adds extra enterprise-specific functionality. 
These functionalities include the capability to resolve textual messages from a properties file and publishing application events to the attentive event listeners.
We use the following interface to work with this container. [org.springframework.context.ApplicationContext]. 
    FileSystemXmlApplicationContext (need to provide the full path of the XML bean configuration file to the constructor). 
    ClassPathXmlApplicationContext (need to set CLASSPATH of the bean configuration XML file in order to load the metadata of the beans from an XML file).
    WebXmlApplicationContext (the container loads the XML file within a web application which has metadata of all beans).

Proxy Design Pattern:
In the proxy design pattern, a class is used to represent the functionality of another class. It is an example of a structural pattern. 
Here, an object is created that has an original object to interface its functionality to the outer world. 
Proxy design pattern is widely used in AOP, and remoting

Model View Controller (MVC):
Spring MVC is known to be a lightweight implementation as controllers are POJOs against traditional servlets which makes the testing of controllers very comprehensive. 
A controller returns a logical view name and the view selection with the help of a separate ViewResolver. 
Therefore, Spring MVC controllers can be used along with different view technologies such as JSP, etc.

Template method:
Spring framework provides a number of templates to kick start work and complete that piece of work as the best programming practice such as opening and closing connection for JDBC or JMS, etc.
 E.g., JdbcTemplate, JmsTemplate, and JpaTemplate.
