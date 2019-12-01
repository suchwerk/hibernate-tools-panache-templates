# hibernate-tools-panache-templates

Auto generate Panache entities from existing databases using hibernate tools.

## Usage

Edit `src/main/hibernate/hibernate.properties` for your needs

```
hibernate.dialect 
hibernate.connection.driver_class 
hibernate.connection.username 
hibernate.connection.password 
hibernate.connection.url 
hibernate.default_schema   
```

Calling maven 

```bash
mvn package
```

will genarate the packages in `target/generated-sources/`

Package name can be changed directly in the pom.
