# starter-website
Starter website code for Git workshop. (this guide assumes you are using MacOS)

## Basical terminal commands
The terminal executes any commands you input. Try typing `pwd` and then pressing
Enter. This will **print** your **working directory**, the folder you are currently
working in. Input `ls` to list all of the files in the current folder.

You can use <pre><code>cd <i>folder-name</i></code></pre> to change your working
directory to *folder-name*. For example, if your current working directory is
`/Users/reeceyang` and the folder `my-code-project` is in that directory, use
`cd my-code-project` to move into that folder.

To learn more, check out
(this tutorial)[https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line]. 

## Installing Git
Installing [homebrew](https://brew.sh/) if you don't have it already is recommended.
Then you can install Git by running ```brew install git``` in your terminal.

## Setting up a GitHub repository
Make a GitHub account, then go to [https://github.com/new](https://github.com/new)
to make a new repository. Name it *[your-username-here]*.github.io (for example,
reeceyang.github.io). Select the "Add a README file" checkbox.

## Cloning your repo to your computer
Click the green "Code" button and copy the HTTPS link to your clipboard. Then run
<pre><code>git clone <i>your-link</i></code></pre> in your terminal. This creates
a local copy of the repository on your computer.

## Making changes
`cd` into your new repository, then run ```touch index.html``` to make a new
file called ```index.html```. You can then open ```index.html``` with a text editor
using ```nano index.html``` and use CMD + V to paste
[this code](https://github.com/HotchkissCP/starter-website/blob/main/index.html)
into the file. Press CTRL + X to exit, and Y to save.

## Tracking changes
Use ```git add .``` (with the period) to add all changes to your commit.

## Committing changes
Use ```git commit -m "Initial commit"``` (with the period) to commit your changes.
The ```-m``` tag indicates you are passing your commit message "Inital commit" as
an argument. A commit is essentially a "snapshot" of your code at this point in
time, given all of the changes you have added.

## Pushing your commit
Finally, use ```git push -u``` to "push" your commit to GitHub.

## Making your website public
To see your website live on the web, click the Settings tab on your repository
page on GitHub, scroll down to GitHub Pages, and select "main" in the Source
dropdown menu. Press "Save" and go to the resulting link.

## Learning more about Git
There are many free resources online for learning more Git. Check out
[try.github.io](https://try.github.io/) as a good starting place.

## Customizing your website
Check out the [w3schools.com](https://www.w3schools.com/) website to get started
with learning HTML. The sample biography in our starter website has a few suggestions
for possible modifications you can make.
