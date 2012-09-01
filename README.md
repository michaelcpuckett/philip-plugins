Philip Plugins
==============

A few simple plugins for [the Philip IRC bot](http://github.com/epochblue/philip).


Admin
-----

Adds basic administrative functionality to the bot in the form of `!quit`, `!join`, and `!leave` commands.

1. `!quit <quit message>`: Tells the bot to quit the IRC server.

        Example usage:
             !quit ...aaand boom goes the dynamite.
 
2. `!join <channels>`: Tells the bot to join the given channel(s).

        Example usage:
             !join #example-room
             !join #example-room1 #example-room2
 
3. `!leave <channels>`: Tells the bot to leave the given channel(s).

        Example usage:
             !leave #example-room
             !leave #example-room1 #example-room2

These commands only work via private message and only if the issuer
is in the ops array in the bot's configuration.


SwearJar
--------

Adds a "swear jar" that listens to the conversation and keeps track of how many times
someone has used a "bad word" and how much money they owe as a result.
