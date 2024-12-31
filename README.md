Hello Tenno, and other brave explorers.

I have made this program for myself to take a weapon of my choosing and see what mods would yield the highest DPS. It has changed a lot during the time which it was just for my own usage. However recently I had the grand idea to give it a UI (I was previously using Debug Logs) and make it look somewhat presentable for an initial release!

You should be able to download the Zip from the release and extract and run the "Warframe Damage Calculator.exe"

How To Use:

- You put up to 3 weapon names into the "Weapon Info" inputs, and select the type of weapon via the drop-down menu.<br>
- While there are some default values you can further specify what the sim will use by setting the number of mod slots (up to 8) and the mod capacity (accounting for Forma) to help hone what mods will fit in your weapon.<br>
- For melee weapons you will want to put the combo rate of it (This number will be the average hit % of its normal combos, so if it on average is 400% per step of the move, such as 4 100% or just 1 400% hit you would put 4 into the box) Its not the most accurate, but it's close.<br>
- And if you have any sources of armour strip beyond the weapon you are trying to sim, put it in, what I have learned is all external strip is good. So if you have Corrosive Projection, that would be 18%. Got Calliban's death beam laser that strips armour that would be 50% or 100% I can't remember, mine has 200% strength and I can't remember the default value.<br>
- The toggle for "Include On Kill and Other mods with a Condition" means that you will try to meet the conditions of these mods, whether that's killing something every 9 seconds or quicker, or wall latch for 2 seconds here and there to keep the buff up. This way it can sim them as they tend to be more effective if one keeps them up. (This includes allowing Pre Set conditional mods)

- As of Version 1.1.0 users can now pre set mods for simmming.
<br>There is a new button on the top right area to open the panel, from there you can select the mods you want from the drop down menu.

- Once you are ready to sim, you can hit the "SIM TIME!" button, and have a good wait, stand up and walk around, boot up the next YouTube video, or something else while it does its thing. It will act as if it is frozen, but it is working and won't be interrupted till its finished 

- Once it has finished simming it will show your top mods on the right-hand side, each as a button. If you press any of these buttons you will mark that mod as "I do not have this" meaning in future sims it will not try and suggest it. If you get any of these mods or are unsure, you can hit the "Restore All Removed Mods" button to restore them.

- There is also a button to load in weapon data from the API, this is something you shouldn't need to press, however, if I just upload this and you find it useful, but I've abandoned it down the line that can be helpful to get any new weapons that get added. But with my plan of updating this "fairly" often which will include me updating the weapon data in the project, this button will rarely be used.

Somethings to note:
  - I have not included all weapons in the game yet, due to how some weapon attacks work I could potentially be making them far more powerful if I loaded them in.
  - I have not included all mods due to an ol' fashioned case of effort. Unlike the weapons which I load in via the API, I manually add them into a CSV file, due to how the mod API reads. It is not friendly to my code plans.
  - This is not an instant sim, and during this time it may display as frozen, but it is running.
    - All times are based on the latest update and how my computer takes to run the sim.
    - Small sims, such as the Dera with 7 mods and 70 capacity take 18.57 seconds.
    - Medium sim, such as the Dera with 8 mods and 80 capacity takes 58 seconds.
    - A Large sim, such as the Dera with 8 mods and 111 capacity takes a full 1 minutes and 17.31 seconds.
    - And a Full sim (all options), 3 weapons, 8 mods, max capacity can take nearly 15 minutes and 26.58 seconds.
    - This is because it is running nearly a Trillion (or more) possibilities without any of the checks (such as exceeding max capacity)
    - I worked on making it not freeze for the 1.1.0 update, and was succesful, however it would have taken 105 days for something that takes 30 seconds otherwise.

  - With any of these that you find an issue with, such as a weapon you want to sim, a mod, or some other "hey I want this in the tool" please let me know and I can make sure that it is added in, (as well as similar mods/weapons/others)

  - I also plan on adding in Arcanes, Incarnin form damage, Sniper zoom damage, and Modular weapon(maybe) as future goals. I also want to make it so you can reselect mods that you have marked as "don't have" individually instead of unmarking them all.
  - Accuracy of lower kill times may be inaccurate due to how the calculations are done where debuffs that would be inflicted AFTER a shot is calculated before the damage. (Should be minor and would require a major change for minor effects to fix I believe)
  - I would also suggest some way of supporting me, but that can be done later.

  This is also the first program I've shared with the world, outside of my game Phantom Asteroids (on Android), so I am new to all of the "setting things up so they look nice and make sense" stuff.
