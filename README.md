# esm-ified

This is a repository for hosting misc. ports of JavaScript modules, with ESM
compatible imports/exports.

## Why?

In an era where ESM is basically the only _sane_ way to deal with the hell that
is JavaScript modules, it's important that projects adhere to this standard as
much as possible.

Unfortunately, some modules - either due to incompetence, or neglect on behalf
of the developer(s) - have not bothered to allow for ESM compatibility.

So, in order to mitigate this problem, we're letting probably the most qualified
group of people to help fix this problem as much as they can: The community.

## Uploading a module.

Assuming you've already gotten done porting the module, and want to upload it
here:

0. _Make sure_ that the file you've edited it in is a directory, of the same
   name as the module you've ported.
1. _Rename_ the `.js` file to `mod.js`. `mod` indicates the file is a module.
2. Either _download the original license and put it in the directory_, or _put
   it in the header of the .js file_. This is so we follow the license
   conditions, and also don't get sued.
3. Add a README, using the following template:

<pre>
# PROJECT NAME
Original author: (author)[github.com/author]
Project repository: ()
## Usage
Deno:
```
import { module } from "module.js"
```
</pre>

4. *Submit a pull request*, with the directory, and ported module.

Here's an example of a tree of what a proper port's directory should look like:

```
module-name
   ├── LICENSE
   ├── mod.js
   └── README.md
```

<!-- We'll add the original link to ported module, when PR is accepted -->
## Projects ported:
* [balanced-match](https://github.com/juliangruber/balanced-match)
* [brace-expansion](https://github.com/juliangruber/brace-expansion)
* [fuzzysort](https://github.com/farzher/fuzzysort)
* [he](https://github.com/mathiasbynens/he)
