# Merge Conflicts

In this page we'll cover how to resolve **merge conflicts** in your codebase.

Merge conficts occur when parallel commit histories that both have changes to the same piece of code are merged. This can occur (for example) when you and a teammate both commit changes to the same piece of code at the same time, and they push their changes before you push yours.

Merge conflicts can be somewhat tricky to resolve, as there may be incompatible changes made.

The basic process for resolving conflicts is:

1. Find the conflict.
2. Fix the code manually using either your version of the code, their version, or some hybrid version as appropriate.
3. Repeat for any other conflicts that exist.

You can see what files have merge conflicts by running `git status` and looking at the files listed under "both modified".

Individual merge conflicts are shown in your files like this:

```
shared code
...
<<<<<<<
some code
======
some different code
>>>>>>>
...
more shared code
```

Where everything between the `<<<<<<` and `======` is your code, and everything between `======` and `>>>>>>` is the code on GitHub.
