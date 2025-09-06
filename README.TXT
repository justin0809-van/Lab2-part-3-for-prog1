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
        
        
Question 50)The boolean feature was to make the class visible. Yes it is
well suited since the circle only has 2 states: true or false. In other words,
true(visible) or false(not visible)

Question 51)The better-ticket-machine is obviously more accurate
because the printTicket machine has one big difference with the naive machine:
the better-ticket-machine has an "if else" statement. That means if the amount 
inserted is higher than the price, the ticket will print and the total will be updated

But for Naive-machine, it prints 0 instead even if the inserted Amount is greater
than the price.

Question 52) The terminal windows doesn't show up which means nothing happened

Question 53)Nope. Because of the code, deduction only happens if the amount inserted
is > or = than the price.

Question 54) * for multiplication and / for division

Question 55) saving = price * discount;

Question 56) mean = total / count;
