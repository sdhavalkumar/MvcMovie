2024-05-16
Dhavalkumar Parmar
1730 UTC

 

Part 1
1730 UTC

Created a project name MVC Movies and added a controller

1745 UTC
Ran the program, Confirmed the default works:
https://localhost:7064/
Modified the index.cshtml title to MVC MOVIE by replacing the default title WELCOME
Created README.in the MVC Movies
Was able to confirm the default page

1810
I confirmed Part1 of the tutorial is complete, The started with part2

Part2 - Add a Controller

1830 UTC

Commented the default index method which is returning to class view()
Then added new index method and changed the content to "This is my default action..."
Was running when i ran the program

https://localhost:7064/Helloworld

1845  UTC
Added another method called welcome with the content of "This is the Welcome action method..."
Confirmed it was running

https://localhost:7064/Helloworld/welcome

1855 UTC

Change the Welcome method to include two parameters(name,numtimes)
Ran the program, Confirmed the changes works:

https://localhost:7064/helloworld/welcome?name=yash&numTimes=6


2024-05-23
Dhavalkumar Parmar
1730 UTC

Part 3 
Worked on Add a View and edited the Views/Shared/_Layout.cshtml then edited the  HelloWorldController file present in controller and
ran the program, was able to see the local host was able to take the command where i gave the name yash and runtime 100 
and was able see my name in 100 lines respectively
https://localhost:7064/helloworld/welcome?name=yash&numTimes=6


Part 4 
1802 UTC
Started adding a model for which I created a file name movie.cs in models folder and in controller Scaffold movie pages.
and created a new item with the name moviescontroller.cs

1820
Migration was done 
20240523183621_initialCreate.cs

1825 UTC
Updated the database for the testing purpose

1850 UTC
Edited the movies name with title genre price and release date

1913 UTC

Testing and was successful 
https://localhost:7064/Movies

2024-05-30

1441 UTC

I was facing problemn with "Add-Migration InitialCreate"
that will indicate that I have to the database agian for the project

I will have to do part 4 and 5 again to ensure this.

After that 

2024-06-06

1204 UTC

I did all the steps from 1 to 10 agian to ensure that all of things that I made which working well.
Time consume for that procedure is about 1 hour.
final link of working well = https://localhost:7064/
New Mitigation 20240606152346_InitialCreate.cs

After adding rating
20240606154359_Rating.cs

1310 UTC3

Creating github account and linking to the project