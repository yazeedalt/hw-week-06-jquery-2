# hw-week-06-jquery-2 

Here are some mini exercises to challenge your jQuery skills a bit. 

**Instructions:** 
- create index.html for the following exercise. 
- create main.js and link it to index.html and add the jquery link also 


## Exercise 1

HTML

```html
<button id="clicker">Click me to show a hidden secret!</button>
<div id="secret" style="display: none">I am a hidden secret.</div>
```

**Instructions:**

1. Add jQuery code that [fades in](http://api.jquery.com/fadein/) the text "I am a hidden secret" whenever the button is [clicked](https://api.jquery.com/click/).
2. Change your jQuery code so it [slides down](http://api.jquery.com/slidedown/) the text instead of fading it in.
3. Change the button text to say "Click me to toggle a hidden secret!" and make the text [toggle between fading in and out](http://api.jquery.com/fadetoggle/) each time it is clicked.


## Exercise 2

HTML

```html
<button id="clicker">Click me to hide the hidden secrets!</button>
<p class="secret">I am hidden secret #1.</p>
<p class="secret">I am hidden secret #2.</p>
<p class="secret">I am hidden secret #2.</p>
<p>I am <em>not</em> a hidden secret.</p>
```

**Instructions:**

Add jQuery code to modify the page so that when the user clicks the button, the paragraphs that start with the words "I am a hidden secret" slide up.

## Exercise 3

```html
<img src="http://hackasaurus.toolness.org/images/goggles/supergirl.png">
<p>
  <button id="clicker">Click me to change the picture</button>
</p>
```

**Instructions:**

Change the page with jQuery so that when the button is clicked, the image changes to this:

<img src="http://rs284.pbsrc.com/albums/ll36/Bigsteve87/Gifs/Liz_Lemon_High_Five.gif~c200">

**Hint:** Change the `src` [attribute](http://api.jquery.com/attr/) of the image.


