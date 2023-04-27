### COMP 1073 – Client-Side JavaScript

# LAB 2
## Variables, Operators and Strings

#### DESCRIPTION
Using the code provided, re-create an HTML list by modifying the contents using JavaScript variables and string methods.

#### INSTRUCTIONS
We have the following information that has been output to an HTML list:
* Beijing Capital International, https://goo.gl/maps/iPe5fAqzq8C2 PEK
* John F Kennedy International, https://goo.gl/maps/JWwABmA3MBS2 JFK
* Lester B. Pearson International, https://goo.gl/maps/Ypu1dJLsnQu YYZ
* London Heathrow, https://goo.gl/maps/TFx8SrATdYr LHR
* Tokyo Haneda International, https://goo.gl/maps/5UxH2TxbRtT2 HND

We need the list to be re-arranged so that it appears in the following format, with the name of the airport and the airport code all being hyperlinked to the appropriate Google Maps location:

* [PEK - Beijing Capital International](https://goo.gl/maps/iPe5fAqzq8C2)

Build upon the provided JavaScript, and do the following things inside the loop as directed by the code comments:
1. Find the character index of the comma
2. Obtain the full name of the airport using the comma character index number as a reference point, and store it in a new variable
3. Capture the international airport code at the end of the string, and store it as a variable
4. Get the Google Maps short URL from the string, using the character index number of the comma, and store it as a variable
5. Build a new string that is a hyperlink, using the Google Maps URL as the href and set it as the value of the result variable
6. BONUS – Output the average number of characters of the airport names inside a paragraph after the list of airports

#### EVALUATION
#### Criteria                       | #### Mark
----------------------------------- | -------------
The above tasks have been completed | 5
#### TOTAL                          | 5
Bonus Challenge                     | 2
