Dependency Injection Using Spring Annotations

Dependency Injection (DI) is a design pattern used to achieve Inversion of Control (IoC) between classes and their dependencies. Spring Framework provides a robust way to implement DI using annotations, which reduces the need for XML configuration and enhances code readability and maintainability.

Key Annotations Used for Dependency Injection

1. @Autowired

Used to automatically inject dependencies by type.
Can be applied to constructors, fields, or setter methods.

2. @Component

Marks a class as a Spring-managed bean.
Automatically detected during classpath scanning.

3. @ComponentScan

Specifies the base packages to scan for annotated components.
