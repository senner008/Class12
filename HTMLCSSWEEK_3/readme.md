
# Exercises

## Exercise 1 Absolute vs Relative positioning:

- Add this markup and see the effect.
- Explain what is going on with relative and absolute positioning
- Comment out 'position: relative;' in the #parent selector
- Explain what happens

Html : 
```
  <div id="parent">
    <div>One</div>
    <div>Two</div>
    <div>Three</div>
    <div>Four</div>
  </div>
```

Css:

```
  body {
      border: 1px solid #000;
      margin: 0;
  }

  #parent {
      margin-top: 200px;
      border: 2px dotted red;
      position : relative;
      /* comment out the above line */
  }

  #parent div {
      border: 1px solid #000;
      display : block;
      width: 200px;
      height: 100px;
      font-weight: bold;
      font-size: 20px;
  }

  #parent div:nth-child(2) {
      position : absolute;
      margin-left: 500px;
      border: 2px dotted red;
      bottom : 0;
  }
  
```
![alt text](https://github.com/senner007/temp/blob/master/classwork_3/positioning.png "horizontal nav")


## Exercise 2

Create a basic HTML5 form and add some appropriate styling:

Read about HTML forms here:

https://www.w3schools.com/html/html_forms.asp

Add this basic form to your index.html:

```
<form action="/action_page.php">
  <fieldset>
    <legend>Personal information:</legend>
    First name:<br>
    <input type="text" name="firstname" value="Mickey"><br>
    Last name:<br>
    <input type="text" name="lastname" value="Mouse"><br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>
```

- explain what the action property does and what happens when you press the submit button
- replace the input text values with a placeholder text instead
- add label elements that point to the input text elements. What does the label element do?
- add required the required attribute. Add the * to the labels of the required fields 
- remove the br tags and add appropriate css instead

## Exercise 3

Understand the checkbox hack for the homework assignment:

https://css-tricks.com/the-checkbox-hack/

- add a checkbox to the above form
- demonstrate how to hide and show elements

When you are done. Begin working on the homework assignment

## Exercise optional 1 

Improve your keyboard ninja skills

Do the following without touching the mouse:

- [ctrl + æ] open the terminal
- [touch index.html && touch main.css] create and index.html and a main.css
- [ctrl + `] switch back to main view
- [ctrl + p] type i to go to index.html
- [! + tab] add basic html5 template
- [ul>li{List item $}*5 + tab] add 5 list items
- [ctrl + p] type m to go to main.css
- add styling to the list
- open index.html in the browser 







