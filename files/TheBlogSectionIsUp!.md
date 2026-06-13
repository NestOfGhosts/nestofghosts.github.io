## The blog section is up now
*May 22 2026 4:29pm*
I'm done coding the blog section (with help from claude). Currently the website is local, and due to the posts being stored in another folder, i have to run a local server in terminal, which is annoying af. Also, I need to manually add the post file to the post list (which i hope to automate somehow fingers crossed)

Building the Blog section really helped my learn some beginner javascript. Js is so hard to read lol all the functions look like files, but honestly I'm getting used to it.

The posts are markdown files, organized with a json list. Javascript in the HTML extracts the list, then extracts the files referenced in the list, then creates a new section square thing, and puts the post file into the square (omg saying it in plain english makes me realize this is so simple lol).

![The javascript code for the blog page](files/finalblogcode.png)