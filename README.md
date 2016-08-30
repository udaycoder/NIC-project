# NIC-project
I worked on this project during my 1 month training at NIC Agartala in summer of the year 2016.
I made a intuitive web portal to manage students in a school. Students and sections are recieved as input by database can be added to 
desired section. 
It is possible to create a new section if need be and students can be added to the new section .The admin can also remove a student from 
the section .
if need be and keep them in an unassigned group from where they can be added to proper sections later. If a section is not required anymore
it can be removed too.

The tools i used for this project are-

> Html5
> CSS
> Bootstrap
> JSP
> Jquery
> AJAX
> Postgres SQL

Instructions to get the project running on a system :

OS-Windows 10,8,7 
   Linux(Yet to be tested)

* Netbeans EE IDE is required to be installed on the system.
* Import the .zip project .
* Build a postgres sql database with name NIC on port 5432.
 *Add two tables - one named Groups and another Student. Inside group add a text colum named group as primary key and add the already 
  present group in it. Inside the Student table add a column for Sl  as integer and as priamry key, a character column of size 100 
  called Name,a charcter column of size 100 as Email and finally another charcter column of size 10 names as Group.
*Input the required informations at each of the columns.
*Run the project using your favourite web browser.
  
  NOTE- The username, password that is given for the database NIC needs to be changed in the jsp files during connection with 
        databse using jdbc.
        Keep an eye on the column names if they are written properly,check with the jsp files.
