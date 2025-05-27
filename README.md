
# Feature Flag Framework UI 

This UI handles the creation, updation and the viewing of feature flags. These flags and their attributes are simultaneously also stored in a MySQL database. 



## 1. Tech Stack

The following are the various tech using which the UI was built:

- **Java**

- **SpringBoot**

- **Spring Data JPA**

- **BootStrap**

- **MySQL**

- **HTML**

- **CSS**


## 2. Setup 

``` 1. Download XAMPP.
    2. Run both Apache and MySQL.
    3. Open a browser and go to - http://localhost/phpmyadmin/index.php?route=/database/structure&db=DB_NAME
    4. This will be the database for the project and the flags will be updated here as well.
```


## 3. How it works

The feature flag UI allows users to perform 3 main **functions** -

- Create feature flags.
- View the feature flags.
- Update the feature flags. 


Every feature flag has the following **attributes** - 

* Name.
* Creator.
* Status.
* Start - Date, Time and Timezone.
* End - Date, Time and Timezone.
* Description. 
* Environment Status - Prod, Test and Dev.


**Creation -** 

- We can specify the above mentioned attributes (except creator) during creation. 
- Once submitted, the database is updated as well.
- The feature flag is then visible in the dashboard. 

**Updation -**

Only the following feature flag details can be updated - 

- Status.
- Start and End - Date, Time and Timezone.
- Description.
- Environment status - Prod, Test and Dev.

**Viewing -**

- All the attributes can be viewed on the dashboard. 


**Deletion -**
- The features cannot be deleted.
- In case of any error, the feature can be edited instead. 





## 4. Terminology (in code)


- **ffname** - Name of the feature flag. 
- **status** - Status of the feature flag.
- **createdat** - Start date.
- **enddate** - End date.
- **description** - Description of the feature flag.
- **db5** - Name of the MySQL database.




## 4. References

 - [Youtube -Perform CRUD Operations using Spring Boot, Thymeleaf, MySQL Database and Spring Data JPA](https://youtu.be/MUhDe_yZ5WQ?si=qHjAo2QdOBrJGH4M)
 - [Setting up MySQL using XAMPP](https://youtu.be/co-xyHRdHRg?si=VEFvqWP0lbbzD22c)
 - [SpringBoot tutorial for beginners](https://youtu.be/gJrjgg1KVL4?si=U8isteEcDSYSyg54)

