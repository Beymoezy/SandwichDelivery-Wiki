# Guide to 4.0

**4.0 is the updaterino coming to Sandwich Delivery September 1st. The testing version will be live for a short amount of time on August 30th and 31st**

# Note: Your stats will be missing as the user database is being wiped.

If you want to keep your stats, join our Discord and talk to an Artist Manager.

## Things to knooooow

* Orders will now go through an extra stage before being delivered.
* * A "cashier" will now give the order a cost and charge the customer from their own chat.
* * After customer has been charged it is redirected to the Sandwich Artist team for creation and delivery.

## Other things to know

* User database no longer tracks a few stats.
* * Removed Rank
* * Removed Type
* * Removed TimesKilledByRoulette
* * Removed IsBlacklisted
* * Added Level
* Sandwich Artists and Cashiers will earn an equal weekly wage based on the amount of orders done to incite work.
* Recolored embeds


## Sandwich Artist Section

**Starting August 29th we'll be accepting applications for Cashiers**

* Yes, you can switch from Artist to Cashier if you'd like.
* No, you do not earn more credits then cashiers.

### How Ordering Works Now(aka how different your job is)

Here's how an order will go.

Customer types `;order item`

Message is sent in cashier chat pinging cashiers notifying them of an order.

Order is either confirmed (;confirmorder <id> <cost>) or denied (;denyorder <id> <reason>)**NOTE, SANDWICH ARTISTS CAN NO LONGER DENY ORDERS**

If order is confirmed it is moved to the kitchen chat where sandwich artists are pinged.

Sandwich artists have the option to accept the order or ignore it completely.

From there it is what you're used to, ;ao id and ;d id

## Admin section 

A few new commands:

* ;artist iscashier @user - Changes user to Trainee Cashier
* ;artist isartist @user (**USERS ARE AUTOMATICALLY ARTISTS WHEN YOU ;artist new @THEM**)
* ;artist pay - Pay's artists their cut of the paycheck. **TALK TO OTHER MANAGES AND CHECK THE BALANCE BEFORE DOING THIS, SHOULD ONLY BE DONE ONCE A WEEK**
* ;artist bank - Check how much money can be delivered
* * Artists are paid like this: Grab list of artists who have accepted an order in the last 7 days, Take the amount of money earned this week and divide it by the amount of artists in the list mentioned previously, Give each artist the quotient.

## Things that need updating.

`;getallorders` is not sorted. Oops.

