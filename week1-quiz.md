#WDI-18 Week 1 Quiz 

Name:_____________________

```bash
$ pwd
/Users/Me/GeneralAssembly/Quizes

$ ls
Quiz1   Quiz2

$ ls Quiz1
questions answers

$
```

1. Refer to the sample command line session above (all directory names are 

Capitalized). Which of the following commands would display the entire answers file for 

quiz 1?

    A) cat Quiz1/answers
    
    B) grep answers
    
    C) less answers
    
    D) answers > show
    
    E) head Quiz1/answers

2. Which of the following is a reference type in JavaScript?

    A) id
    
    B) number
    
    C) string
    
    D) object
    
    E) class

3. Which of the following expressions will evaluate to false?
    
    A) 1+"1" === "11"
    
    B) null == undefined
    
    C) 1 == 1.000001
    
    D) "Hello, world!"

    E) a === a

4. Which of the following statements is false?

    A) Algorithms are abstractions of behavior
    
    B) Algorithms are a concrete implementations of functions
    
    C) Functions encapsulate behavior
    
    D) Everything in computer science boils down to data structures and algorithms


  ```
  for (var i = 3; i >= 0; i--){
  
      console.log(i && "Superclap!");
  
  }
  ```

    The for loop above should count down and superclap in the console. Here's the desired console output:
    
    ```
    3
    
    2
    
    1
    
    Superclap!
    ```

5. Which change would produce the desired output?

    A) Change i-- to i++
    
    B) Change i >= 0 to i > 0
    
    C) Change && to ||
    
    D) Add return Superclap at the end
    
    E) None of the above.
  
  ```
  var hungry = "super";
  
  while (hungry > "kinda"){
  
    eat();
  
  }
  
  function eat() {
  
    // insert code here
  
  }
  ```

6. Replacing // insert code here, which line will ensure the while loop ends?

    A) hungry--;
    
    B) hungry = hungry[3];
    
    C) return "break";
    
    D) hungry = "not at all";
    
    E) None of the above.

7. Which of the following is NOT a compelling reason to introduce functions into a computer language?

    A) Name association
    
    B) Modularity
    
    C) Repetition reduction
    
    D) Faster execution

    ```
    var city = "San Francisco"
    
    var sing = function() {
    
     console.log(city);
    
     city = "New York";
    
     return "If you're going to " + city +
    
    " be sure to wear some flowers in your hair";
    
    }
    ```

8. If we call sing() what will happen?

    A) "San Francisco" is printed, then "If you're going to New York be sure to wear some 
    
    flowers in your hair" is returned
    
    B) "San Francisco" is returned, then "If you're going to New York be sure to wear some 
    
    flowers in your hair" is printed
    
    C) "New York" is printed, then "If you're going to San Francisco be sure to wear some 
    
    flowers in your hair" is returned
    
    D) "New York" is returned, then "If you're going to San Francisco be sure to wear some 
    
    flowers in your hair" is printed

    ```
    var theNumbers = [15,8,4,23,42,16]; 
    
    var ascending = function(a, b) {
    
     return a - b;
    
    }
    
    var descending = function(a, b) {
    
     return b - a;
    
    }
    
    theNumbers.sort(ascending);
    ```

9. Which statement is true?

    A) sort is a first-class function
    
    B) ascending & descending are first-class functions
    
    C) sort is a callback
    
    D) ascending is a callback
    
    E) Only A & D
    
    F) Only B & C

10. Write a function that takes a variable number of arguments, and iterates through each one, console.log-ing each.   

  ```
    
       
         
          
            
             
            
  ```

11.  The DOM's data structured as _________.

  A) A linked list
  
  B) An array
  
  C) A tree
  
  D) A queue

12. Which of the following is NOT an event?

  A) submit
  
  B) script
  
  C) load
  
  D) click

13. In the context of the DOM, three of the following four terms are used interchangeably. Which one doesn't belong?

  A) object
  
  B) parent
  
  C) element
  
  D) node

14. Which of the following is an example of an HTML element attribute?

  A) font
  
  B) img
  
  C) style
  
  D) input

 For questions 15 and 16, assume the following HTML document:
    
    ```
    <!DOCTYPE html>
    
    <html>
    
     <head>
    
       <title>My Awesome Web Page</title>
    
     </head>
    
     <body>
    
       <header>
    
         <ul id="list">
    
           <li><a href="/">Home</a></li>
    
           <li><a href="/about">About</a></li>
    
           <li><a href="/contact">Contact</a></li>
    
         </ul>
    
       </header>
    
       <section>  
    
         <h1>Welcome to my site!</h1>
    
         <img id="image" src="/static/say_cheese.jpg">
    
         <p>Words and <a href="/">links</a></p>
    
       </section>
    
       <footer>
    
         <small>Copyright 2015 Jon Doe.</small>
    
       </footer>
    
     </body>
    
    </html>
    ```

15. To select the unordered list:

    A) var el = document.querySelector(".ul");
    
    B) var el = document.querySelector("#ul");
    
    C) var el = document.querySelector("#list")
    
    D) var el = document.querySelector("list");

15. How would you change the image to the file at /static/say_bologna.jpg?

    A) document.querySelector("img").setAttribute("src", "/static/say_bologna.jpg");
    
    B) document.querySelector("img").src = "/static/say_bologna.jpg";
    
    C) document.querySelector("#image")["src"] = "/static/say_bologna.jpg";
    
    D) All of the above

16. Which HTML tag is used to define an internal style sheet?

    A) css
    
    B) style
    
    C) script
    
    D) head

17. Starting with least specific and ending with most specific, which of the following is in the correct order?

    A) tag, class, id, inline
    
    B) class, tag, id, inline
    
    C) class, tag, inline, id
    
    D) tag, id, inline, class

18. Which of the following is a block-level element?
      
    A) span
    
    B) p
    
    C) a
    
    D) img

19. Which is correct?
    
    A) border: dashed 1px black;
    
    B) border: red 5px solid;
    
    C) border: 3px solid yellow;
    
    D) border: dotted 10x green;

20. How do you display a border like this:
  
      top border = 10 pixels bottom border = 5 pixels
      
      left border = 20 pixels right border = 1 pixel
    
    A) border-width: 5px 20px 10px 1px;
    
    B) border-width: 10px 5px 20px 1px;
    
    C) border-width: 10px 20px 5px 1px;
    
    D) border-width: 10px 1px 5px 20px;

`<h2 id= “my_heading” class= “heading”>Which font wins?</h2>`

21. Given the CSS below, which font-family does the browser use to display the above header? Circle your answer.

```
#my_heading {

    font-family: cursive;

 }

 html body h2 {

    font-family: serif;

 }

 h2.heading {

    font-family: fantasy;

 }

 h2#my_heading.heading {

    font-family: monospace;

 }
```
