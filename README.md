# esm-ified
This is a repository for hosting misc. ports of JavaScript modules, with ESM compatible imports/exports.

## Why?
In an era where ESM is basically the only *sane* way to deal with the hell that is JavaScript
modules, it's important that projects adhere to this standard as much as possible.

Unfortunately, some modules - either due to incompetence, or neglect on behalf of the developer(s) -
have not bothered to allow for ESM compatibility. 

So, in order to mitigate this problem, we're letting probably the most qualified group of people 
to help fix this problem as much as they can: The community.

## Uploading a module.
Assuming you've already gotten done porting the module, and want to upload it here:

0. *Make sure* that the file you've edited it in is a directory,
   of the same name as the module you've ported.
1. *Rename* the `.js` file to `mod.js`. `mod` indicates the file is a
   module.
2. Either *download the original license and put it in the directory*,
   or *put it in the header of the .js file*. This is so we
   follow the license conditions, and also don't get sued.
3. *Keep* the README.  
4. *Submit a pull request*, with the directory, and ported module.

Here's an example of a tree of what a proper port's directory should look like:

```
port-name
  ├── LICENSE
  ├── mod.js
  └── README.me
```

<!-- We'll add the original link to ported module, when PR is accepted -->
## Projects ported:
* [fuzzysort](https://github.com/farzher/fuzzysort) 
* [he](https://github.com/mathiasbynens/he) 
