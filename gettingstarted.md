*This page was transcribed from Lemon's "Sandwich Handbook" with some extra commentary from Fires*

# Hi

If you've received this page via a link through Discord, you've probably just been hired as a "Sandwich Artist". Or not, you may just be looking at this. Whatever

This page is a guide to starting out as an Artist and learning what to do and what each command is.

~~**I highly advise you read the "System Breakdown" portion of it, it's more techy but really explains what's going on under the hood.**~~ M8, that page doesn't exist --- austinhuang

## Before you continue, a quick thank you to

* United Sandwich Republic and all its current and past admin/moderators. This bot would have been impossible without the support of the friends I have made there.

* Ruhe - Thanks for being a good admin.

* ShadowR3con - Does a great job managing Sandwich artists. also ps4 sucks

* Lemon - Thank you for your constant hard work and management of the bot, you've really kept this project alive for me with the great guide photos and all. Keep up the good stuff 👍 

* Melon - Thanks for doing all the management regarding keeping the Artists' in check

* Andrex and Chez - Thank you for being longtime Sandwich Artists, thank you for sticking around through all the buggy shit fest releases I have made.

* Auxesis - SQLite system

* JeuxJeux20 and LewisTehMinerz - Thank you for your lovely programming help, has kept things running smoothly :)

* All past members of the Sandwich Tavern, Sandwich Bar, Firecord, Casual Corps and all the other servers and renames we've had since August. Discord has been a wonderful thing and has kept me extremely busy these last few months, this all started as a small server to talk to people who were interested in my Source Film Maker posters but soon grew to a bigger, larger and more diverse community of people I couldn't thank enough for all their help.

## Alrighty, lets get into it

Here is all the information you need:

### What do I do?

Your goal as Sandwich Artist is accept, deliver and manage all orders our bot receives from users in our *300* servers.

The basic command flow goes like so:

*Accept order*

*Find or Photoshop their order using images*

*Deliver the order*

*Receive an invite*

*Join the server*

*Send order, while mentioning (@Example#0517) the user and including a nice note*

*Leave the server*

*Repeat*

It's fairly straight forward. Please see **Guideline** for further information and also see **How to deliver** for even more.

### Commands:

* ;acceptorder `id` - Accept order(**;ao for short**) Claims an order, once claimed, other artists cannot claim it, you must then continue and use:

* ;deliver `id` - Sends you an invite to deliver(**;d for short**). Acceptorder **must** be ran beforehand.

* ;getallorders - (**;gao for short**) Returns a list of all orders, including previously accepted orders. **This will be changed soon to show separate sections for untouched, and accepted orders very soon.**

* ;orderinfo `id` - (**;oi for short**) Returns information on the given order.

* ;denyorder `id` `reason can include spaces` - (**;do for short**) Denies an order, removes it from the system and gives a message to the customer on why it was deleted.

### Other commands:

* ;order `order` - I hope to God you know what the hell this does.

* ;messagekitchen `message` - Allows users to message the Kitchen staff directly. Still WIP

* ;respond `id` `message` - Allows Kitchen Staff to respond directly to an order. Still WIP

* ;help - Self explanatory

* ;server - Gives you a link to our server.

* ;invite - Run this command and copy the link and spam your friends with it.

* ;getordercount - Gets total orders we have served (in 2.0).

* ;delorder - Deletes your `;order`.

* ;caniblacklist - Returns whether or not you can blacklist users. Typically not enabled for...anyone

* ;feedback `feedback message` - Sends a message to our feedback channel, telling us what you thought.

* ;motd - Returns the message you got when the bot first joined.

* ;blacklist `user` - Blacklists a user, requires the permissions to do so. 

* ;blacklist `id` **OVERLOAD** - Same as above, but takes an id instead.

* ;unblacklist `user` - Removes a user from the blacklist, requires the permissions to do so.

* ;unblacklist `id` **OVERLOAD** - Same as above, but takes an id instead.

* ;totalorders - I think this command already exists lol.

* ;credits - Returns an outdated credits text.

### Should I accept?

If the order asks for something simple like "ham", it is safe to assume they are asking for a **ham sandwich**.

If the customer is using the ;order command incorrectly, including swears, trying to communicate (Deny and tell them to use ;messagekitchen) to the kitchen, NSFW orders or non sandwich items, you should deny the order and give them a warning if they continue.

Is `blank` an item I can deliver?

Anything that includes one object, in between two of the same object **is a sandwich.** So if they ask for a *glass sandwich with a baked potato inside*, its a valid sandwich. 2 pieces of glass and a baked potato. (If you can't find it/photoshop it, deny it saying you can't find it.) Drinks are allowed, ice cream sandwiches(duh), **hamburgers and hot dogs included**. 

Food items that are "sides" such as salads are allowed.

### Guideline

* Proper grammar **IS A MUST**
* * Artists that flake on proper grammar will be removed.

* Inactivity will result in a removal, possibly without warning.
* * Please inform someone in the **CONTACTS** list if you are going away for a while. Tell us before or you might risk "nice excuse bro" and getting removed.

* Be polite.
* * Chat a bit, make small talk and **be nice** to the customer. If they treat you with disrespect, just notify someone off the **CONTACTS** list.

* Don't be weird and stay in servers.
* * Once you join a server, deliver the sandwich, maybe hang around a bit if they are talking to you, or if you are explaining something, but **unless they ask, do NOT stay in a server**. If they give you a "Sandwich" related role, ask someone of power if you can stay (if you want) then go from there.

* Common sense
* * Yes, the bot is down if you can't see it in the servers list. NO don't spam Fires' DM. Just send it in our report-error chat and go on with your life.

* Search up an order beforehand
* * If you get an order that says `BLT` and you think "huh, what the heck is a BLT?", **GOOGLE IT**, If you find something, accept the order and go through with the order. **If you find nothing use the `;respond` command**.

**When you are delivering an order, you are representing Sandwich Delivery Bot, our server and all our admins. Being rude or immature is NOT acceptable.**

### How to deliver 101

* Accept the order
* * Make sure you have time to deliver, no one else can accept that order after you claim it.

* Finding what was requested
* * Find an image of what was requested, if multiple items were requested (sandwich with a soda), sending multiple images is perfectly fine. Bonus points if you use an image editor and combine the two. Links or direct images are fine, but try to not use direct `copy image url` from Google Images. It does **not** come out well.
Example:
NO
https://cn.bing.com/images/search?view=detailV2&ccid=478u2vPK&id=C7BE342549D08FB94EEADBB8AD8FA5E2469A8839&thid=OIP.478u2vPKrrKEkQCzcNnOxQDcEs&q=cat&simid=608051926205205752&selectedIndex=1&ajaxhist=0
YES
https://cattamboo.com/wp-content/uploads/2013/05/creme-puff-oldest-cat.jpg

* Delivering
* * After you've located what is requested, use your `;deliver` command and join the server. Ping them, give it a nice message and make sure to ask for feedback(`;feedback`).
* * Be sure to use proper grammar, or at least use capitalization. 

### In progress features

* ;gao order sorting

* JSON to SQLite system.

* Embeds on ;artist info

## I got an error, what do I do????

Errors have been plaguing Sandwich Artists since 2.0 was released, here's what you can do

### Command Syntax Errors

* **Error:** The input text has too few parameters.
* * This happens when you are missing an argument inside a command, say you go to deny and error and you type `;denyorder 5` and include no reason. This error will occur. This happens on any command that takes arguments.

* **Error:** Failed to parse Int32
* * *Attention: This error will soon be much less common when 3.0 rolls around, Id's will be moved from the `Integer32` type to `string`. 
* * This typically occurs when you fail to give a correct number when using a command that needs an id.

### Code Errors

Code errors, albeit a bit less common, are much more serious and **must be reported immediately**.

Errors sometimes have the `:ghost` emoji with them and they usually look something like this:

http://i.imgur.com/WhaXZgz.png

The message included is incredibly important to me(Fires) and shouldn't be disregarded. Report it in our `report-error` chat, and also immediately mention a high power user(Preferably look at **CONTACTS**) and notify them. 

**Failure to report errors will result in server warnings, and possible removal from position.**

### Contacts

* Fires#1043
* * Bot Creator, Server Owner
* * Usually playing video games, listening to music and NOT WATCHING ANIME SINCE IM NOT A WEEB (I love anime!!!)
* * **ONLY PING IF:** Reporting bugs, bot downtime(please do this `report-error`, check for existing pings), to annoy Fires

* Lemon#8973
* * Bot and Server Administrator, incredibly helpful (I LIKE ANIME TOO)
* * Stares at computer all day
* * **ONLY PING IF:** Bugs/errors, general help, blacklisting, hug.

* Irizu#7270
* * Bot and Server Administrator, Lemon's ~~assistant~~ minion. (SHE LIKES ANIME AS WELL)
* * **ONLY PING IF:** General help, blacklisting, cold glare, sass.

* Ruhe#0653
* * Bot and Server Administrator, Fires' Mom (anime succ)
* * **ONLY PING IF:** Bugs/errors, general help, blacklisting, anything.
### Closing

This is still a work in progress, if you feel anything is missing, please add Fires#1043 on Discord and tell him.

I'd again like to thank Lemon and Irizu for all their help. :)

Good luck delivering all those sandwiches!
