# Sys-INTEG 

A system integration project. Aims to integrate master data.

This pom.xml is a "System" project. a shell/container maven file that references relevant project(s) required for system as a whole to function.

```xml
    <modules>
        <module>../muni-model</module> <!--Domain model that is common across SYS-INTEG -->
        <module>../m-lib-integ</module>
        <module>../m-lib-amanda</module>
        <module>../m-lib-hansen</module>
        <module>../m-app-rest</module>
        <module>../m-lib-amanda-soap</module>
        <module>../m-react-admin</module>
    </modules>
```

### muni-model
The 'domain objects' that are core to the business.

1. Edit structure of Person, Person::Address, Case ... 
2. Edit grpc service definition. If you are using non-grpc, ignore.

### lib-integ 

### lib-<subsystem>


### 