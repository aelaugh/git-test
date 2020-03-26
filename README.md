# PicknDrop
“Pick n Drop” is a new VIP cab service that lets customers book cab services through and online web app. It is as simple as picking up the pick up and drop off location from a map. Drivers who wish to provide the service can also register with the company.

## SETUP

### Instructions

1. Clone the source code from the repo : https://github.com/aelaugh/PicknDrop.git

2. Create a new database using the folowing configuration

#### Database Configuration
```
Database: JavaDB (Apache Derby)
Port: 1527
DB Name: pickndropDB
username: root
password: toor
Connection URL: jdbc:derby://localhost:1527/pickndropDB
```
*Note: If you need to change the DB configuration do edit the changes in the deployment descriptor (web.xml) in the sourcecode; PicknDrop\web\WEB-INF\web.xml*

3. Populate the Database using the SQL file 'pickndropDB.sql' in PicknDrop\pickndropDB.sql (use execute command)

4. Deploy the webservice; PicknDrop/webserviceCal/CalculatorWSApplication

5. Build and run the project 'PicknDrop'

*Note: If Netbeans shows an error saying missing library file, click ‘Resolve’ and navigate to the ‘javaLib’ folder inside the repo and select the missing JSON library file; PicknDrop/javaLib/json-20190722 (1).jar*


### Default Logins
Use the folowing logins to gain acces to the system

Admin
```
username: admin
password: admin
```

Customer
```
username: thab
password: thab
```
Driver
```
username: elaaf
password: elaaf
```
## Collaborators
Abdulla Elaaf  
Hassan Zayyan  
Ismail Muizzu Nizam  
Ibrahim Bin Ahmed  


## Collaborators
⋅⋅* Abdulla Elaaf
⋅⋅* Hassan Zayyan
⋅⋅* Ismail Muizzu Nizam
⋅⋅* Ibrahim Bin Ahmed
