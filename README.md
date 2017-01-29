# teach
teaching notes etc.

## topics

### terminal

1. find the terminal
2. add terminal to task bar
3. open terminal
2. which directory are you in? (pwd)
2. look at your home directory (ls)
3. make a src directory (mkdir src)
4. make a project directory (cd src; mkdir first)
5. add an html file to your project directory (cd first; touch index.html)

#### you learned

- how to open terminal
- your home directory (/Users/yourname)
- terminal (shell) commands: pwd, ls, mkdir, cd, touch

#### next

- [TextEdit](#textedit)

### TextEdit

1. find TextEdit
2. add TextEdit to task bar
3. open TextEdit
4. set preferences (TextEdit > Preferences)
   - un-check "Smart quotes" and "Smart dashes"
   - Open and Save tab: check "Display HTML files as HTML ..."
   
#### you learned

- how to set up TextEdit for writing code

#### next

- [first project](#first-project)

### first project

1. open the index.html file (open terminal, cd src/first, open -e index.html)
2. copy/paste in basic html file from here: [index.html](index.html)
3. save
4. Open in browser (from terminal: open index.html)
2. customize your file
   - html (replace Friend with your name, save file, refresh browser)
   - css (change gray to blue, save file, refresh browser)
   - javascript (remove // from before document.get[... etc], save file, refresh browser)
   
#### you learned

- how to copy and paste code
- how to open an html file in a browser
- how to edit, save, and refresh an html file to see your changes
- that // in front of a line of javascript means the browser will ignore it
- the browser interprets html, css and javascript to display a web page


#### next

- [functions and events](#functions-and-events)
- [html](#html)
- [css](#css)
- [github-account](#github-account)

### functions and events

- rename the function showTime to showtime (inside the script tag, save, refresh browser)
- change onload="showTime()" to onload="showtime()" (inside the body tag, save, refresh browser)
- change both instances of showtime to something silly like sandwiches (in both places, save, refresh browser)

#### you learned

- to change the name of a function
- a function is executed by its name followed by ()
- uppercase and lowercase letters in a function name make a difference 
- onload is a browser event you can subscribe to in the html body tag

#### next

- [variables and objects](#variables-and-objects)

### variables and objects

- replace the single line of javascript inside { and } with:

```js
//hold a reference to the html paragraphs
var paragraphs = document.querySelector('p');

//hold a reference to a Date object
var rightNow = new Date(Date.now());

//use the two variables above to change the paragraph text
paragraphs.innerHTML = `It is ${rightNow.toTimeString()}`;
```
- save, refresh the browser

### html

### css

### github account
