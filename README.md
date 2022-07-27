# ATMapp
## React ATM Machine app

### What Is It?
In this MITxPro challenge, we were tasked with creating an ATM Machine app. The app includes the options to deposit or withdraw money, and it provides an account balance. The `submit` button is only available if "Deposit" is selected or the "Cash Back" `input` is less than the account balance. 

### How I Improved It?
When the dropdown menu is selected, I chose to assign the blank choice a state of "isBlank". This allows me to target this state in my code. I originally included an `alert` when a "cash back" amount was greater than the balance, but decided to leave it out and make the `submit` button `disabled` instead. 

### What I Would Do Differently Next Time
I enjoyed this activity but I found the program cluttered. I would split the file into two reusable components which would allow for easier use. I struggled with the `submit` button because I wasn't familiar with the `disabled` HTML attribute, but once I researched it, I understood how it is used and how to apply it to my program.

![Alt text](/ATMmachine.png "ATM Machine App Image")