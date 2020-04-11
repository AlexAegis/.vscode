# Generic VS Code workspace for Haskell

> Check out the other branches too

## How to use

Add as a git submodule:

> While in the root of the project repository

```sh
rm -rf .vscode # Remove existing setup
git submodule add https://github.com/AlexAegis/.vscode
cd .vscode
git switch haskell
cd ..
git commit -am "Added VS Code workspace submodule"
```

## When not to use

When you need some specific settings and your setup is not generic.
This happens most often when you need custom tasks, launch configs.

## But thats almost never the case

Then just download it as a starting point and customize it from there.
In this case, don't use submodules.
