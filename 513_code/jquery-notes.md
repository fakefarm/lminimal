# Jquery


## Document ready
Since the DOM is loaded top to bottom you need to have the javascript wait until the page. To make it ready in order to put code up top you need to wrap in document ready.

    $(document).ready(function(){
      // put code in here.
      });

### A shortcut to same thing

    $(funtion(){
      // put code in here
      });

css

    li:first-child

the jquery m

## Querying the DOM

### Children

    $('ul.emphasis').children('li')

Only 'li' that are direct children. Avoids the grandchildren.

### Find method

    $('ul.emphasis').find('li')

Grabs all the li's that are selected.

### Find just the first method

    $('ul.emphasis').find('li').first()

### Add Class

    $('ul.emphasis').find('li').addClass("emphasis")


### Find just the second, and add text

    $('ul.emphasis').children('li:nth-child(2)').text('added with jquery')


### eq method


    $('ul.emphasis').children('li').eq(0).text('added with jquery')

Select an item position with eq method. 0 based, becuase it's an array.

### next method

You can stack methods...

    $('ul.emphasis').children('li').eq(0).next.text('added with jquery')

chain methods, like 

    .next()

or 

    .prev()


### Actual way to write it

    $('ul.emphasis li:nth-child(3').text('added with jquery')


### user Parent method And, removeClass
to add something / or remove

    $('li').parent('ul').removeClass('emphasis');

If you want all parents, use;

    .parents


### Closest

# TODO

- use find, eq, children, last, first, parents, closest
Get specific elements out of each of those. 