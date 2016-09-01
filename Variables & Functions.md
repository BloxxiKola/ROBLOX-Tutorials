### Heyo! I'm BloxxiKola and this tutorial is about Variables and Functions in ROBLOX Lua.
---
## _**VARIABLES**_

A **Variable** is a changable _value_ with a corresponding _identifier_, or nickname.

For example: `local identifier = value`

You'll notice I used **"local"** at the front of the text. This tells the computer that _you're_ creating the variable, it's not built into ROBLOX Lua.

Let's try setting a variable to something in the `Workspace`, the player's world. First, let's insert a part by right clicking anywhere and selecting "Insert Part":

![](http://orig02.deviantart.net/129c/f/2016/244/f/f/insertpart_by_bloxxikola-dag4u3b.png "i maked a parts?")

We now have a Part in the Workspace. Now, right click that part in your `Explorer` tab, and hover over "Insert Object", and click "Script".

![](http://orig02.deviantart.net/7a10/f/2016/244/f/b/insertscript_by_bloxxikola-dag4x42.png "i maked a scripts?")

Now we have a Part in the Workspace, and a Script in that part. Next, double-click the script to open the editor. 

In the editor, type `local part = game.Workspace.Part` to set a variable as the part. 

**Remember! Capitalization is very important, one mispelled or miscapitalized word can error the entire script!**

Now "part" is set as the Part we inserted into the Workspace. However, this is inefficient. If we need to put the part into something else, we'd have to change the code. and easier way to do this is:

`local part = script.Parent`

"script" is the current script we're editing. "Parent" refers to what the script is in. If we said `local workspace = part.Parent`, we'd be setting the variable as Workspace, the Part's parent, or what the part is in.

You should always name everything you make. It makes it easier to specify what your refering to when creating a variable.

Let's say I have the following group: 

![](http://orig14.deviantart.net/817f/f/2016/245/2/b/unspecific_by_bloxxikola-dag8vdp.png "The following group.")

Now, if I write in the script `local part = script.Parent.Folder.Part`, I get this back:

![](http://orig04.deviantart.net/bc03/f/2016/245/c/2/partnotvalid_by_bloxxikola-dag8vwy.png "Error 404")

That's because the computer doesn't know which folder I'm talking about, so it goes with the one with a sound inside it. To fix this, I'll just name the folders:

![](http://orig09.deviantart.net/4469/f/2016/245/e/b/specific_by_bloxxikola-dag8wkf.png "I hereby pronounce thee, sir folder.")

Boom! No errors, a programmer's dream. Everything I just showed you can be applied anywhere, go make some variables!

---
## _**FUNCTIONS**_
