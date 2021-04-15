# Clients
Database maintenance 
For this purpose, I used relational database management system (RDBMS) Microsoft SQL Server with the database ClientInfo
![image](https://user-images.githubusercontent.com/56975146/114936271-34f0f400-9e0a-11eb-9d21-7057cd94faca.png)

Before I started performing basic database maintenance, I had activated SQL Server Agent 
![image](https://user-images.githubusercontent.com/56975146/114936753-d8420900-9e0a-11eb-9dec-de1463d7428a.png)

All I need right now are Maintainance Plan Wizard and the toolbox with listed main database tasks.
For example Backup
![image](https://user-images.githubusercontent.com/56975146/114938035-9c0fa800-9e0c-11eb-9dcf-c58e2bbdac12.png)




 CLeanUp task and Check database Integrity task


![image](https://user-images.githubusercontent.com/56975146/114939040-e04f7800-9e0d-11eb-9d73-5da7b7c00da9.png)

The next step is the shrinking data. In this case I did not use Maintainance Plan Wizard

For instance, if the initial size which I manually set is too big (talking about number 20 MB)

![image](https://user-images.githubusercontent.com/56975146/114942447-8bfac700-9e12-11eb-84b9-4ef8536004dc.png)


I am going to shrink the menu and see that I have 82 % available space. Afterward, I chose shrink action: released unused space and click ok. 

![image](https://user-images.githubusercontent.com/56975146/114942624-cd8b7200-9e12-11eb-8a28-85c4f4228cb3.png)
![image](https://user-images.githubusercontent.com/56975146/114942773-062b4b80-9e13-11eb-8ee2-904f1ad9fbaa.png)


As a result, I have got reasonable allocated space (8 MB)

![image](https://user-images.githubusercontent.com/56975146/114943085-7934c200-9e13-11eb-9d9e-251442f55119.png)


The next logical step is reorganizing and rebuilding indexes.

![image](https://user-images.githubusercontent.com/56975146/114944732-24467b00-9e16-11eb-8c17-37a502d5a662.png)



And the last task is Updating database statistics

![image](https://user-images.githubusercontent.com/56975146/114945175-d8e09c80-9e16-11eb-8856-f50ba97c916c.png)








