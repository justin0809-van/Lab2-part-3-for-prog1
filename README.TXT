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

Question 57)
public void affordable(int budget){
          if(price > budget) {
        // TODO: Write an if-statement that checks budget against price and prints
        System.out.println("Too expensive");
    }   
    else {
        System.out.println("Just right");
       // a message saying weather a ticket is affordable
    }
    
Question 58) i dont understand.

Question 59) The original returns the refund before even resetting 
the current balance,  where as the other version clears the balance first, resulting
in a refund amount of zero.

Question 60) An error code that is "unreachable statement" appears. 
A return statement ends the method so anything else written after that command wont work.

Question 61) Compiling works.
I created an object and set its value to 10 but when i click inspect, the field price is 0.
i believe int creates a new variable, price for this case, it isnt the object's own field so it stays 0

Question 62)
public int emptyMachine()
    {
       total = 0;
        
       return total;
    }
    
Question 63)
 int amountLeftToPay = price - balance;
        if(amountLeftToPay <= 0) {
            // Simulate the printing of a ticket.
            System.out.println("##################");
            System.out.println("# The BlueJ Line");
            System.out.println("# Ticket");
            System.out.println("# " + price + " cents.");
            System.out.println("##################");
            System.out.println();

            // Update the total collected with the price.
            total = total + price;
            // Reduce the balance by the price.
            balance = balance - price;
        }
        else {
            System.out.printf("You must insert at least %d more cents.%n",
                              price - balance);
                              
Question 64)

Created a discountedPrice method:
public void discountedPrice()
    {
         price = price / 2;
         discountedPrice = price;
    }
And added // Return to the original price for the next ticket.
            price = price * 2;
under the if statement of the method printTicket so that after the discounted ticket
printed, the next ticket will have the original price.
