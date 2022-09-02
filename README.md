# MOB PROGRAMMING: THE ROLE PLAYING GAME 
## by Willem Larsen CC-BY-SA-NC 2016 
## [Powered by the Apocalypse](https://en.wikipedia.org/wiki/Powered_by_the_Apocalypse) - thanks to BigBadCon 2016 for inspiration

# To the Game Master

First of all, thanks for helping playtest this game! 

Your primary duty is that everyone playing treats each other with Kindness, Consideration and Respect.

Your first time running this game will be awkward. Embrace it! But don’t budge on the fundamental rules - treating each other with Kindness, Consideration, and Respect at all times.

# Game Requirements

Gather at least three players to make a mob, upper limit unknown... You facilitate. I (the designer) have played with up to 15 players in the mob.

    NOTE: No prior mobbing experience is necessary.
* Verify that at least one person in this mob must have some minimum fluency in Test Driven Development; i.e., ability to move fluently through the Red, Green, Refactor stages with minimal code necessary.
* Get a shared screen big enough for all players to see comfortably - you might consider using a projector. Large screen TVs work great.
* Get one shared keyboard - consider having some hand sanitizer available to avoid sharing cooties.
* Get one or two pairs of scissors and tape - scotch, masking, poster tape will all work.
* Print out all 3 Level 1 rolesheets for each player in your game, and at least one set of Level 2 rolesheets.

# Before players sit down to play

* Set up an IDE with a test file in a coding language that at least one person in your session will be fluent in. 
Create one test failing successfully in a test file in the coding language of choice.
Decide on some way to time rotations for three roles - Driver, Navigator and Mobber.  

* Plan to solve the FizzBuzz kata - creating a solution that generates output matching the pattern of “1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, FizzBuzz, 16....” up to a given number.

* If you complete that kata too quickly, here are some ideas for extending the exercise. 
    1. Pass divisor arguments: `FizzBuzzExtended(100, {fizz: 3, buzz: 4})` 
    2. Pass any number of divisor arguments: `FizzBuzzExtended(100, {fizz: 3, buzz: 4, foo: 8, bar: 9})`
    3. Create a FizzBuzz cuckoo clock that accepts a time in 24-hour format (`FizzBuzzCuckoo("16:15")`) and returns "Fizz," "Buzz," or "FizzBuzz" if the minute portion is evenly divisible, "Cuckoo" if the time is on a half hour, or as many "Cuckoos" as needed for the top of the hour (e.g. 6 if given `"06:00"` or `"18:00"`.

* You will lead the rotation of Driver/Navigator positions every 3 minutes. The Driver moves to the right and becomes the new Navigator, the Navigator becomes a generic Mobber. Rotate consistently in a fixed order. 

* Install and Use the Mob Timer to guide mob role rotations (optional).

* Create and label a Mob Squad zone, a mob badge parking lot, by setting aside a piece of blank wall or whiteboard that will be covered in mob badges that individuals players complete. This becomes the group’s achievement, the total number of rolesheets the members have completed.

# Starting the game

Read aloud: 

“Hello everyone. We are here to play Mob Programming: the Role-Playing Game. The first most important rule is this: that we treat each other with Kindness, Consideration, and Respect at all times. Can you help me with making sure we remember this when things get tough?... [wait for reply]... Mob Programming is a development practice used for raising code quality and removing obstacles. In practice it usually feels like a bulldozer rather than a racecar - unstoppable and thorough. That’s mobbing!

"A rolesheet is what we call the sheets with icons and descriptions of roles on them. Now, there are currently three levels of rolesheet and counting. We're only going to worry about level 1 right now. Depending on where you are in the rotation, you will be using the appropriate rolesheet. 

"If you are at the keyboard, you are a driver and will be filling out the Driver rolesheet. If you are sitting to the right of the driver, you are the navigator and will be filling out the Navigator rolesheet. Otherwise you will be working on the Mobber rolesheet.

“The goal of this game is twofold - the first is to become a great mob by ‘embodying” the role outlined in your rolesheet as accurately as possible. The second one is to ‘build your group mob’ by helping each other complete as many rolesheets you can in this session. If you do this with Kindness, Consideration, and Respect, congratulations! You may join the annals of the great mobs of history.”

# After each player has chosen a rolesheet: 

“Now look at your rolesheets. You’ll note that there are specific actions you take that give you ‘XP’s, also known as “experience points”. It’s up to you to decide when you have taken one of those actions and then check the box. Every time you decide you have exhibited a behavior that gets you XP, announce what it is out loud to the group and check a box.”

“When you check all the boxes you can switch rolesheets, but we’ll talk more about that once it happens.”

Decide the order of rotation, have the players get in their positions as decided by the rotation order, Driver/Navigator/Mob. 
# Before you start the timer tell the players:

“As you can tell by looking at your roles, the Driver’s job is to type what the Navigator instructs them to type. The Navigator’s job is to sift the ideas of the mob and instruct the Driver what to type.

"Now this game can get crazy and the coding challenge can make you forget that you have roles to complete. Therefore, the person directly to the right of the Navigator, your job is to help the Navigator remember to check boxes when they complete the XP behaviors. The person directly to the left of the Driver has the same job, to remind the Driver when they have completed a behavior and can check a box."

"Remember, our goal is to finish as many roles as possible in an hour and beat previous records (as of May 2018 the record is 39 badges in an hour). Any questions?”

Barring unanswerable questions, now start the 3 minute timer. Rotate positions when the timer goes off - Driver becomes Navigator, Navigator becomes mob member, and the next mob member becomes Driver.

Once play has begun, please monitor the presence of Kindness, Consideration and Respect. If at any time you notice one of these qualities not being present, simply speak up and say to the mob, “Kindness please!” or “Consideration please!” or “Respect please”, depending on which is missing.

Every rotation, stop the rotation and ask the players the following questions  (please take notes on their answers):

“What stands out for you? What did you notice about the coding challenge, or the overall gameplay? Is there anything you're struggling with?”

Don’t spend more than 5 minutes on this discussion. Make it brief and take notes, restart the timer and have another Q&A at the end of the next rotation. Rinse and repeat.

All roles except Driver and Navigator travel with the player. Driver and Navigator role sheets are pulled out and used, *and can score XP*, only when at those positions in rotation, not in the general mob. Keep any previous role sheet available to resume for when you are done with Driver/Navigator rotation (and therefore can no longer get XP for those roles until you rotate back into them).

# When a player finishes a rolesheet

Ask them to cut out the icon badge on the dotted line, put tape on the back and stick it up in the mob badge parking lot. This zone is the group Mob Squad and will fill up with the various badges as they finish rolesheets.

They can keep the rolesheet they have cut up - the moves can still net them XP, per the instructions on the rolesheet.

# After 1 hour of rotations (or less depending on time available)

Stop the game. Count badges and total. This is the mob’s score for the game.

Have a more expansive discussion, 10-15 minutes. What was a high point for you? What was a low point you experienced? For any rolesheets you completed, what did you like? How would you play it differently next time? 

# FIN

That’s it! That’s the game. Hope you had fun, get your notes to me, and try running it as often as you like.

Thanks for playing - Sincerely, Willem Larsen



 





