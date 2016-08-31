### Heyo! I'm BloxxiKola and this tutorial is about Variables and Functions in ROBLOX Lua.

A **Variable** is a changable _value_ with a corresponding _identifier_, or nickname.

For example: `local identifier = value`

You'll notice I used **"local"** at the front of the text. This tells the computer that _you're_ creating the variable, it's not built into ROBLOX Lua.

Let's try setting a variable to something in the `Workspace`, the player's world. First, let's insert a part by right clicking anywhere and selecting "Insert Part":

![](http://orig02.deviantart.net/129c/f/2016/244/f/f/insertpart_by_bloxxikola-dag4u3b.png "Insert a part.")

We now have a Part in the Workspace. Now, right click that part in your `Explorer` tab, and hover over "Insert Object", and click "Script".

![](http://orig02.deviantart.net/7a10/f/2016/244/f/b/insertscript_by_bloxxikola-dag4x42.png "Insert a script.")

Now we have a Part in the Workspace, and a Script in that part. Next, double-click the script to open the editor. 

In the editor, type `local part = game.Workspace.Part` to set a variable as the part. 

**Remember! Capitalization is very important, one mispelled or miscapitalized word can error the entire script!**

Now "part" is set as the Part we inserted into the Workspace. However, this is inefficient. If we need to put the part into something else, we'd have to change the code. and easier way to do this is:

`local part = script.Parent`

"script" is the current script we're editing. "Parent" refers to what the script is in. If we said `local workspace = part.Parent`, we'd be setting the variable as Workspace, the Part's parent, or what the part is in.
