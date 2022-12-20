# Astronaut API

Take small steps. Start with a canary test and one or two more tests.
List your tests in a file named tests.txt. Check them off with a x as you 
implement them. Remember to ask for a review each day. The earlier you start,
the earlier you finish, and less the risk. If you start late, you carry a 
bigger risk. Now to the assignment.
                                                                         
We will write a program that will print in the following example format the details about the ISS:

******************************
ISS location as 11:15PM CT flying over Baltimore, MD

There are 4 people on ISS at this time:
firstname1 lastname1
firstname2 lastname2
firstname3 lastname3
firstname4 lastname4
******************************

The names should appear in the sorted by lastname order.

A useful link: http://api.open-notify.org
                                                                         
Write the program in a way that it gracefully deals with network failures and also failure of the webservice. Also, write the program in such a way that if we decide to change the webservice that provides the information, the change will affect as little code as possible.
