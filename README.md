Hello Tenno, and other brave exploreres.

I have made this program for myself to be able to take a weapon of my choosing and see what mods would yeild the highest DPS. It has changed a lot during the time where it was just for my own usage. However recently I had the grand idea to give it a UI (I was previously just using Debug Logs) and make it look somewhat presentable for an inital release!

Somethings to note:
  I have not included all weapons in the game yet, due to how some weapon attacks work I could potentially be making them far more powerful if I loaded them in.
  I have not included all mods due to a ol' fashioned case of effort. As unlike the weapons which I load in via the API, I manually add them into a CSV file, due to how the mod API reads. It is not friendly to my code plans.
  This is not an instant sim, 
    Small sims, such as the Dera with 7 mods and 70 capacity takes 30 seconds, 
    Medium sim, such as the Dera with 8 mods and 80 capacity takes 1 minute and 50 seconds.
    A Large sim, such as the Dera with 8 mods and 111 capacity takes a full 2 minutes and 44.4 seconds
    And a Full sim, 3 weapons, 8 mods, max needed capacity (I just use 111 for testing) can take nearly 8 minutes and 19 seconds.
    This is due to the fact that it is running nearly a billion (or more) possibilities without any of the checks (such as exceeding max capacity)

  With any of these that you find an issue with, such as a weapon you want to sim, a mod, or some other "hey I want this in the tool" please let me know and I can make sure thats its added in, (as well as similar mods/weapons/others)

  I also plan on adding in Arcanes, Incarnin form damage, Sniper zoom damage, Modular weapon(maybe) as future goals.

  I would also should suggest some way of supporting me, but that can be done later.
  This is also the first program I've shared with the world, outside of my game Phantom Asteroids (on android), so I am new to all of the "setting things up so they look nice and make sense" stuff.
