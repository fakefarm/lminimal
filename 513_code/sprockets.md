
# Benefits of sprockets
## 1. Reduces number of server requests to one per file type

## 2. Organizes in to 3 primary asset directories - App, Vendor, Lib

### Use of //= requre
Upon compiling, require is the location of where the other file contents will be moved into application.js
Example;

#### application.js
//= require jquery <- ... file contents into application.js
//= require_tree ./directives (sprockets will pull in contents from all 3 asset locations - app, vendor, lib)
//= require_self


sprockets looks in app/, vendor/, lib/
vendor/ for jquery
lib/ for code reuse
app/ specific to this application

### you can have a few different .js files a
- look  into cofig/appliction.rb
- to compile for different situations (like an admin section - admin.js)

##
assets pre:compile makes an MD5 hash to allow for caching but breaks the cache when a file is updated.
