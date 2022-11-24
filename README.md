# SQL Data Analysis Exercises – Stack Exchange
This SQL exercise is a part of a section dedicated for data analysts, providing data analysis tasks that require both business understanding and technical skills.

 **About this Exercise**
Stack Exchange Is a network of sites, allowing different communities learn and share their knowledge.
Movies & TV Stack Exchange – is one of these sites, focused entirely on questions and answers regarding movies and series. The following database is built according to its structure, and simulates some of the data it has.

 
The following exercises are constructed in ascending difficulty order. First ones are pretty easy, made for warm-up. The advanced exercises, on the other hand, can be quite challenging.


**ERD General Description**
============
![image](https://user-images.githubusercontent.com/65993041/203769784-7b741f93-8123-40a2-a3b6-55ffc571e409.png)




This database consists of 4 tables

* posts – Each post can have different comments, each post can be voted by different users (in order to improve its ranking)
* votes – Each vote consists of a voting ID, user number (FK), post number (FK), and a date of creation
* comments – The details regarding the various posts comments
* users – The details of the users who commented / wrote a post / voted
