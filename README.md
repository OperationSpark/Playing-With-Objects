<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.


Playing With Objects
================
Let's make a website that lets us add people to a page with some information.
It should look like the following mockup:

![Text-based game](http://i.imgur.com/qjLIY4F.png)

We've provided you with the html, you just need to add some Javascript to make
everything work smoothly.

The idea is that the user will type in some information in the input boxes and
click the "Add" button. Then the information that they input will be transformed
into a sentence like: "Ben loves the color yellow." Since each person has multiple
pieces of information about themselves,
we will group them into a `person` object.  We will do this in the following steps:

1. 
Make a function that returns a `person` object which contains the information
entered inthe input boxes. 
2. 
Make a function that takes a `person` object and adds a sentence to the list.
3. 
Make a function that clears the input boxes so that another person can be entered.
4. 
Make a function that runs when the `Add` button is clicked and uses the other
functions to add a `person` to the list and clear the form.

Open up your website workspace and

```bash
os install playing-with-objects
```

Now open up the index.html file inside of the playing-with-objects folder,
this is where you will be working today.

1 - Get a Person
-------------------
Fill out the `getPerson` function, you can access the text that is typed into
the `name` input box with:

```js
name.val()
```

Try it out with `console.log()`.

Remember, this function should return an object that will have a `name` property
and a `color` property.