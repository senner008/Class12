
# Exercises

## Exercise 1
Create the card as depicted and center it on the page
![alt text](https://github.com/senner008/Class12/blob/master/HTMLCSSWeek_2/card_challenge.png "Card challenge")

- set width to 500px and a height of 200px
- card must be centered (try to use flexbox)
- must have rounded borders and a subtle shadow 
- bonus : make the card scale out slightly on hover
- bonus : add transition effect when scaling out and in


## Exercise 2

Create a nav section with horizontal links.

- use flexbox
- add a media query to align vertically on a smaller screen
- horizontal nav should have a max width of 600px
- to move the last li to the right, set the margoin-left : auto
- remember to add the subtle borders between the items 
- ul background : background: #444; 
- li font-family: 'Oswald', sans-serif;
- li color: ghostwhite;

```
<nav>
  <ul>
      <li class="li-item">Home</li>
      <li class="li-item">Blog</li>
      <li class="li-item">About</li>
      <li class="li-item">Admin</li>
      <li class="li-item">Contact</li>
  </ul>
</nav>
```

![alt text](https://github.com/senner008/Class12/blob/master/HTMLCSSWeek_2/horizontal_nav.png "horizontal nav")

![alt text](https://github.com/senner008/Class12/blob/master/HTMLCSSWeek_2/vertical_nav.png "vertical nav")


## Exercise 3

Recreate the depicted layout

![alt text](https://github.com/senner008/Class12/blob/master/HTMLCSSWeek_2/layout.png "layout")

- 1 header , 3 columns, 1 footer
- 3 columns always same height
- footer appears sticky at bottom. Don't add css to footer. Instead add overflow-y to #main 
- make it wrap underneath without using media queries. hint: flex-wrap: wrap; on #main
- section, aside fluid size
- section width significantly wider than the aside width
- set a max-width of #main to 1200px;
- add a media query to change the order of the items in #main. The #content should always be displayed first or left most when the items start to wrap
- set additional media queries depening on the content displayed. Perhaps use column-count property

This is the html markup : 

```
 <header>Header</header>
   <main id="main">
       <aside id="left-aside"><h1>Aside 1</h1>{ add some lorem ipsum here }</aside>
       <section id="content"><h1>Section</h1>{ add some lorem ipsum here }</section>
       <aside id="right-aside"><h1>Aside 2</h1>{ add some lorem ipsum here }</aside>
   </main>
   <footer>Footer</footer>
```

Good advice for programmers: Less is better!

## Exercise optional 1 

Stop fiddling with the mouse and avoid unnecessary typing:

- Learn the essential keyboard shortcuts in vscode : https://www.youtube.com/watch?v=uWP2n6xtYik
- Learn to use the emmet shorthand syntax: https://docs.emmet.io/cheat-sheet/

## Exercise optional 2

Enable hot reload to see your changes appear instantly in the browser. Right click on an html an select open with live server





