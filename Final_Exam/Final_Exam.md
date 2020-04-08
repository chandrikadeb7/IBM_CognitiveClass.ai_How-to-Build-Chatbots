### EXAM QUESTION 1
Text and audio are two common ways through which chatbots interact with the user.

True - correct 

### EXAM QUESTION 2
To be called a chatbot, a bot needs to converse with the user.

True - correct 

### EXAM QUESTION 3
Chatbots can help cut down the number of inquiries a business' customer care team needs to manually address.

True - correct 

### EXAM QUESTION 4
Watson Assistant is a chatbot building service hosted on IBM Cloud (formerly Bluemix).

True - correct 

### EXAM QUESTION 5
Chatbots can only be deployed on WordPress sites.

False - correct

### EXAM QUESTION 6
Which of these is a valid intent?

* @buy_product 
* #buy_product 
* #buy_product - correct 
* $buy_product 
* #buy product 
* @buy product

### EXAM QUESTION 7
Which of the following are valid system entities?

* @sys-date 
* #sys-date 
* #sys-person 
* @sys-person 
* @system-of-a-down

@sys-date, @sys-person, - correct

### EXAM QUESTION 8
The value of an entitity detected in the user input is automatically available for the entire duration of the conversation with the user.

False - correct

### EXAM QUESTION 9
We can use context variables to store (and later access) information collected from the user.

True - correct

### EXAM QUESTION 10
Slots allow us to collect information from the user and store it in context variables.

True - correct

### EXAM QUESTION 11
A dialog has the following nodes: Welcome (welcome condition), Greetings (#greetings intent condition), Thank you (#thank_you intent condition), Goodbyes (#goodbyes intent condition), Anything else (anything_else condition). Which of the following statements apply?

*	Welcome will be executed at the beginning of the conversation. - correct 
*	If no known intent is detected in the user input, the Anything else node will be executed. - correct
*	Greetings overshadows Goodbyes, and therefore Goodbyes is never executed. 
*	The order of Welcome and Anything else in the dialog will generally not matter. 
*	Rearranging the order to be Welcome, Thank You, Greetings, Goodbyes, Anything else would generally not cause any problems. - correct

### EXAM QUESTION 12
The evaluation of peer nodes proceeds top to bottom until a node with a matching condition is found. Child nodes are only considered for execution after their parent's condition is met (or if a jump is involved.)

True - correct

### EXAM QUESTION 13
Digressions allow users to divert the conversation away from a node while the slots are being processed (i.e., asking questions to the user).

True - correct

### EXAM QUESTION 14
Which of the following contains the user input?

* @sys-person 
* text.input 
* input.text - correct 
* user.text 
* None of the above

### EXAM QUESTION 15
A restaurant chatbot needs to collect the following information from the user: reservation name, party size, date, and time in order to book a reservation. Which of the following approaches works best?

*	Have four peer nodes, each asking one of the questions to the user. 
*	Have a node with multiple slots, each asking for the relevant information. System entities are not needed. 
*	Have a parent node asking for the reservation name, then a child node asking for party size, then a grandchild node asking for date, then a great-grandchild node asking for the time. 
*	Have a node with multiple slots, each asking for the relevant information. System entities should be enabled. Have a node with multiple slots, each asking for the relevant information. System entities should be enabled. - correct 
*	It's not possible to collect the information for four follow up questions.


