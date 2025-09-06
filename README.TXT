Project: better-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate conditional statements.
How to start this project: Create one or more TicketMachine objects.

Question 47) After experiment the new machine, even if there's an error
code, the balance does not change.

Question 48) If both value of amount and price are 0, no error code will be
printed and a ticket will be printed. But if the price is higher than 0 and the
inserted amount is 0, an error message will be printed.

Question 49)
 if(amount < 0) {
            System.out.println("Use a positive amount rather than: " + amount);
        }
        else {
              balance = balance + amount;
        }
        
        
Question 50)