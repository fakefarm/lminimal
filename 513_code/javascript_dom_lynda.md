# Javascript

## Enhancing the DOM
### Querying with CSS Selectors

    querySelector(), querySelectorAll()

Notes through CSS selectors
Similar to jQuery


JavaScript has some gnarly syntax but it's very similar in that it is querying indexes, firstChildren, classes, etc.

Currently, I need to be aware of the methods.

    getElementById()
    getElementsByTagName()
    getElementsByClassName()
    querySelector() # Returns a node
    querySelectorAll() # Returns an array


## Thoughts about JavaScript
- Knowing why I'm writing JavaScript.
- Reasons, other than AJAX, that I would use JavaScrip (Opposed to JQuery)

## Forms

Forms have an attribute called **Name**

    document.forms

gives array of all forms

I can get to form directly by using the name attribute

    document.register.myname

change value with the values attribute

    document.register.myname.value

in the event you think there could be multiple name attributes w/ the same value, you can do it by an array

    document.getElementsByName('subscribe')[0]

getting the zeroth element will make sure it's the first one.