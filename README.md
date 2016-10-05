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


