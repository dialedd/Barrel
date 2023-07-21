# Barrel
this was a very specific skript someone requested me to make, so it probably won't be of much use.


# ok, so what is it?

I Made this skript for a friend of mine; basically, it is a loot box system (kinda)
Roughly what you do is create custom inventory inside an in-game editing GUI, by dragging and dropping items
then it saves that inventory, and when a player opens a barrel, it will choose a random gui you created and open it to the player

This was custom-made for a prison server, like a little looting system type thing

here's a quick video of some features:


https://www.youtube.com/watch?v=9AfsIWoft4k


Here are a couple of things you need to know:
  Any inventory you create is managed by something called its "key"
  every time you create an inventory, you must assign it a key
  this key is used to manage/check/delete that specific inventory
  you can get a list of all keys by doing /barrel-list

The general way it works is as follows:

1. Create an inventory using /barrel-create
2. barrel is automatically saved
3. get a loot box barrel by doing /barrel-give
4. place down the barrel
5. open the barrel, which will automatically generate a random gui from the ones
   you have created

Versions tested:
  1.19.4 + skript 2.7-beta3


message me if u need help
discord user: _dialed
