# Codefinds
General information about coding the backend beginning with NODE.js

******Note about using require("path"); and path names in NODEjs (page 350 Eloquent Javascript)********
Node has to resolve the given string to an actual file to load. Pathnames that start with "/", "./", "../" are resolved relative to the current module's path, where:
./ stand for the current directory
../ stand for one directory up
/ stand for the root of the filesystem
the .js extension may be omitted.

When a string tha does not look like a relative or absolute path is given to require, it is assumed to refer to either:
a built-in module, or 
a module installed in a node_modules
For examples, require("fs") will give you Node's built-in filesytem module.

*******Resource********
https://visionmedia.github.io/masteringnode/



### **Resources**

http://www.nodebeginner.org/
i haven't read through this but it looks promising. the mastering node book above was over my head from the get go.

http://book.mixu.net/node/
haven't read this either but it's free

https://github.com/substack/stream-handbook
building node apps using streams, whatever that is

http://nodeguide.com/
the beginner guide looks to be a good resource

http://chimera.labs.oreilly.com/books/1234000001808/index.html
looks thorough.

http://nodeschool.io/
pretty cool resource


### **Practice**

this looks likea good resource for small projects to get a good feel for working with node:

http://nicholasjohnson.com/node/course/exercises/
