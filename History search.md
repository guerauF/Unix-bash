Here are some tricks to make your life easier when dealing with commands you already had typed:

**1. Last element of the previous command**

Esc.

**2. Previuos command**

If you need e.g. to sudo your last command

sudo !!

**3. History search with Page Up and Page Down**

How to search your terminal history starting the command you had previously used and completing it with Page Up or Page Down.

First you create the file .inputrc in your ~ directory and write in it:

"\e[5~": history-search-backward

"\e[6~": history-search-forward
