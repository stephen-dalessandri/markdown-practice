# markdown-practice
A repo to hold my examples of markdown docs. This is a useful reference for me.

## A place to store samples
I am using this repo to store examples of markdown so that I don't need to rely on Google for the answers. I find that doing a Google search pulls me out of a *focused* state and into a _distracted_ condition.

## Things you can find here
There are all sorts of **handy** things to find here:

### Lists
What's a document without some lists? Let me share them with you!

#### Unordered List

- eggs
- milk
- nintendo eshop gift card
- stationery

#### Ordered List

1. Create the repo on GitHub
1. Clone the repo to my local machine
1. Edit the code on the repo
1. commit my changes locally
1. push changes up to GitHub
1. Repeat steps 1-5 forever! (`while(true) { //keep coding }`)

#### Checklist (GitHub-flavor)

- [ ] Have you committed code today?
- [x] Indigo is my favorite color
- [ ] Enable dark mode

### Code Blocks (GitHub-flavor)

```
// Without syntax highlighting this code is a little hard
// to read
Console.WriteLine("Hello, World!");
Console.Write("Press ENTER to close the application");
Console.ReadLine();
```

#### Code Blocks with Syntax Highlighting (GitHub-flavor)

C# Example:
```C#
// With syntax highlighting, this C# code is more readable
Console.WriteLine("Hello, World!");
Console.Write("Press ENTER to close the application");
Console.ReadLine();
```
JavaScript Example:
```JavaScript
// Even with syntax highlighting, you still don't know what
// type this variable is.
const couldBeAnything = document.querySelector('#theThing');
console.log(`The value of the variable is: ${couldBeAnything}`);
```

### Misc GitHub-flavor Markdown Features

#### SHA References
This is a bit specific, but you can put in a commit's SHA-1 hash, and it will automatically be converted into a link to that commit on GitHub. Example: eb76bcd9ae2764a106586bd4861fe03ffb3936ec

#### Issue References within a repository
Numbers formatted like this: #1 :exploding_head: will automatically link to the issue numbered that in the repository. If you click on the one then you will be taken to the first issue in this repository.

#### Strikethrough

You can do ~~strikethroughs~~ GitHub-flavored markdown.

You should definitely ~~watch~~ miss the game on Sunday.

#### Emoji!!

You can write emojis easily :smiley:.

:hankey: :japanese_ogre: :no_mouth: :upside_down_face:

#### Tables

Tables are easy on GitHub.

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | content in the second column
I like | Vanilla coca-cola
