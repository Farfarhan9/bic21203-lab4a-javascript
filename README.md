Name : Muhammad Farhan bin Mad.Zin
Matric ID: AI240053

Question 1:
**1) Interactive Text Changer :**
- Brief Explanation :
- Created a javascript function named changeMessage().
- This functions change the text inside paragraph with and id = "message"
- And then an addEventListener is added to a button with and id "changeBtn" that will activate on click and it will call the changeMessage() function

Screenshot :

<img width="233" height="120" alt="image" src="https://github.com/user-attachments/assets/591698ef-0d4f-4b32-b20e-9badc88f6677" />

<img width="227" height="111" alt="image" src="https://github.com/user-attachments/assets/1cfce421-e8bd-451f-888c-ed1bdaa84d2b" />

**2) books.json :**
- Brief Explanation :
- Created a json object with a key named "books" and it's value is an array of 2 json objects which are book 1 and book 2
- Both json objects inside the array contain the properties "title","author", "publicationYear" and "genres"
- and each properties are filled with it's respective value based on the task lab 4b.

Screenshot : 

<img width="485" height="416" alt="image" src="https://github.com/user-attachments/assets/60f96859-2b5d-4973-beee-9d0a4d35c05b" />

Question 2:
**1) Smart Number Validator :**
- Brief Explanation :
- Created a javascript function named checkInput().
- This functions validate the input entered by a user.
- This functions uses a variable called userInput and resultElement that will store user input, and resultElement will store the output of the validation
- This function also uses and if,else-if statements to determine the user input according to the validation rules stated in the lab4a
- And then an addEventListener is added to a button with and id "checkBtn" that will activate on click and it will call the checkInput() function

Screenshot :
Higher than 10

<img width="440" height="101" alt="image" src="https://github.com/user-attachments/assets/515360d1-420b-4c4d-914f-e4c5251d3b8f" />


Lower than 10

<img width="431" height="85" alt="image" src="https://github.com/user-attachments/assets/6b9a8095-be2d-4dd8-938f-e48ce499ff6b" />

equal to 10

<img width="441" height="91" alt="image" src="https://github.com/user-attachments/assets/46b814b7-c992-4e2d-9074-8399ff5a81c3" />

abc

<img width="430" height="85" alt="image" src="https://github.com/user-attachments/assets/ae8d0a99-68b7-49e3-bb52-b6f640ee3ada" />

empty input

<img width="440" height="92" alt="image" src="https://github.com/user-attachments/assets/f1d896f3-d3a7-4950-a350-799e4b199144" />

Decimal numbers

<img width="432" height="90" alt="image" src="https://github.com/user-attachments/assets/4b606960-f13f-4695-bc08-bec20cd1fdf1" />


**2) books.html :**
- Brief Explanation :
- Created async funcion loadTitle()
- Uses a try catch block to cover for error when json file failed to load
- In the try block, book.json is fetch from Q1 folder inside the project root directory and then stored inside a const info variable. and then an if condition is used to check the status of info variable, if it fails to fetch an error is thrown.
- And then the stored JSON object is parsed to javascript object (because javascript cannot read a JSON object directly) using .json() method.
- Finally the info are displayed using appropriate property name to move throughout the nested JSON file. 
  

Screenshot : 

<img width="593" height="171" alt="image" src="https://github.com/user-attachments/assets/85c2893e-d06c-4fcc-aa10-5b9c1513b680" />





Question 3:
**1) Dynamic Number Generator :**
- Brief Explanation :
  Created a javascript function named generateNumbers().
- This functions add a list by using appendChild to the ordered list
- A variable numberList is defined with the value of the order list with the id "numberList"
- Before a for loop that will add the items for the ordered list, the list is cleared using the innerHTML = "".
- And then a for loop will execute 5 loops that will append the number to the list.
- And then an addEventListener is added to a button with and id "generateBtn" that will activate on click and it will call the generateNumbers() function

Screenshot :

<img width="342" height="146" alt="image" src="https://github.com/user-attachments/assets/4eb1d85d-f76e-4c4d-8bec-f51f4fe29414" />

<img width="347" height="268" alt="image" src="https://github.com/user-attachments/assets/aa4b200e-6d99-467d-9d42-beed63442fe6" />



**2) jquery-dom.html :**
- Brief Explanation :
  Created a separate <script> tag to incude this as a source https://code.jquery.com/jquery-4.0.0.min.js.
- Used the given HTML elements and CSS
- Duplicate the given HTML elements and CSS and add 2 to the id. To show the difference between native JavaScript and JQuery
- Create a jQuery equivalent from the given javascript
- Advantage of Native JavaScript: Maximum execution speed and absolute efficiency, running directly inside the browser's V8 or native execution engine without needing to download, parse, and process an external ~30KB library block.
- • Situation for jQuery Maintenance: Legacy codebase retention. Rewriting highly stable enterprise codebases, complex intranet portals, or massive setups closely tied to older plugins or systems (like WordPress) often incurs high testing risks and heavy resource costs that outweigh performance gains.


Screenshot : 

<img width="550" height="547" alt="image" src="https://github.com/user-attachments/assets/a74a22e2-4a34-4417-878a-50ed519e9779" />
