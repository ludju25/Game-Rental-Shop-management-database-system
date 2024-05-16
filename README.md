This system was created a few years ago as a group project for the "Databases II" course at the Faculty of Computer Science in Pula. It was an extremely large and complex project, especially considering the time when we worked on it (second year of college). Although there is room for improvement and some oversights, I am still proud of it today considering the level of knowledge at that time and the amount of work and effort that was put into it. For this reason, I am sharing it with others in the hope that it will help someone in the future with a similar idea or problem they may encounter in their education or business.

The project's goal was to create a database and a suitable application for managing a "Game Shop". The basic idea, or business model, for the Game Shop was to rent video games for consoles of the then-current generation (PS4, Nintendo Switch, Xbox One), and sell older titles at significantly lower prices.

For the purpose of managing the database, a simple C++ application was created within CLion, while the database itself was created in MySQL using Oracle SQL Developer and MySQL Workbench.

Since the entire "Databases II" course was in Croatian, the database was also created in Croatian, but below I will translate the name of each table within the database into English to make it easier for anyone who might take over this project:

Kupac - Customer,
Adresa - Address,
Poslovnica - Branch,
Režije - Expenses,
Poslovođa - Manager,
Zaposlenik - Employee,
Proizvod - Product,
Posuđeno - Borrowed,
Prodano - Sold,
Račun - Bill,
Vraćene igre - Returned games,
Stanje poslovnica Nintendo - Nintendo branch status,
Stanje poslovnica PS4 - PS4 branch status,
Stanje poslovnica Xbox- Xbox branch status,
Narudžbenice - Orders,

*each particular table is divided from the other with ",", each table originally in their names and contents don't have č,ž,š signs, names above are just for documentation purposes - original names are "rezije, poslovoda, vracene igre, etc."

Ultimately, our database consisted of:

15 tables with a total of 103 columns

Approximately 6800 arbitrary/example entries in the database

10 views

12 procedures

11 functions

6 triggers

2 transactions

Fully functional applications of approximately 1700 lines of code

**Along with the database and application, an ER diagram of the entire database, as well as a PowerPoint presentation and PDF documentation (in Croatian) with a detailed explanation of the entire process of creating the database and application, were provided inside Documentation folder.

Finally, I must extend special thanks to my former colleagues and collaborators on this project, who are:

Mia Rovis
Karlo Tušek
Mihael Cukon
Mateo Pakter
Marko Cunj
Matija Hamer
Mateo Brajković

I hope it will be helpful to someone :)
