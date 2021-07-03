
## MongoDB - CRUD  with Spring Boot


## How it works:
### **1. mongoDB. First, you need to install mongodb**
* Download MongoDB [Here](https://www.mongodb.com/try/download) ( MongoDB Community Server available for developers ) ;

       *Mongo — download*

### **2. Spring boot app**
* Clone the repository:
```bash
git clone https://github.com/ibrahimcatakli/spring-boot-mongodb-crud.git

```

* Check the application.properties file

      1.  spring.data.mongodb.database=mongodb
      2.  spring.data.mongodb.port=27017
      3.  spring.jpa.generate-ddl = true
      4.  spring.datasource.initialization-mode=always
      5.  spring.datasource.initialize=true
      6.  spring.datasource.continue-on-error=true
    

*application.properties*

* Build the maven project:

mvn clean install

* POST request to `/api/tutorials/` with a tutorials object as JSON creates a new tutorials;
![Screenshot postman](/images/post.png)

  *Post Request*



* View the results on MongoDB Compass

![Screenshot](/images/result.png)

*View the results*





