Demonstration of work with Spring framework:

Demo#1: Project's creation & Application context configuration
1 - Create Intellij IDEA's project with Spring framework template
2 - Creation resources folder for storing module's configuration
3 - Create 'application-context.xml' file (Create -> Spring configuration)

Demo#2: First injection wiring-up
1 - Create CurrentDateService interface with implementation
2 - Configure bean definition for the service
3 - Use ClassPathXmlApplication class to create ApplicationContext instance
4 - Use ApplicationContext to access service instances

Demo#3: Bean's dependency handling
1 - Add TomorrowDateService interface with implementation
2 - Update the service so it would use CurrentDateService for dates calculation
3 - Setup dependency injection by using @Required annotation
4 - Update 'application-context.xml' to include new service with required dependency

Demo#4: Working with constructions
Demo#5: Working with post-init methods
Demo#6: Working with application properties
