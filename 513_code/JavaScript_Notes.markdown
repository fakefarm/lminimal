# JavaScript Notes

## Accessing the DOM

### 6 parts of successful DOM referencing.
There are 6 parts to a successful DOM reference. This is what the 6 parts look like;

    var myElement =  document.getElementByID("someId");


1. **var**
2.   **myElement**
3. **=**
4. **document**.
5. **getElementByID**
6. (**"someId"**);

**Breaking it down**

#### 1. The keyword 'var'
begin by declaring that you will be setting a variable using JavaScripts 'var' keyword.

#### 2. name your variable

This is whatever makes the most sense. Tendancy is to use something that refrecnes what you will be retreiving.

#### 3. assignment '='

Assign the variable to the retreiving statement.

#### 4. location to begin.

Give the browser a frame of reference. This can be things like _document_, _window_, or even a variable name.

#### 5. the method
Now that I have the variable and the starting point, what is it that I want to do? There are many built in methods to use like, _getElementByID_ or _getElementsByTagName_

#### 6. Target content
Once I have a variable, starting point, and method, then I can target the specific content I want to reference.


The end result will look like this;

    var myElement =  document.getElementByID("someId");

### getElementByID

    var myElement =  document.getElementByID("someId");

#### 2 parts


    var myElement

That is the variable 'handle' to use to reference the content that I want to grab.

    document.getElementByID("someId");

This is the code to grab whatever we are interested in, based on a css id.

### getElementsByTagName

    document.getElementsByTagName("a");

makes an array

### Combine uses

    var firstList = document.getElementByID("abc");

Then, use the new variable 'firstList' to access the specifics in that ID

    var limitedList = firstList.getElementsByTagName("li");


### getAttribute

    myElement.getAttribute("alignn");

### setAttribute

    myElement.setAttribute("align", "left")






































