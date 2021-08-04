README.md
GA logo

Homework: Unix CLI Practice

Class: SEI
Creator: Thom Page 
Modified by: Kristyn Bryan and Reuben Ayres 
Topics: Terminal, boolean expressions, reading code, while loops, for loops 

Section 1: Terminal Practice

Episode X: A New Terminal

A long time ago in a Unix environment far, far away, young Jedi padawans who knew only of desktop software were seduced by the dark side of the Force to enter… The Terminal.

Follow the instructions below using all the console commands introduced in Fundamentals, class, or that you find on your own.

Setup

Open the Terminal app

Create a new directory in your sei/fundamentals directory called star_wars.

Create a file called commands.txt.

Paste the answer to each numbered question (i.e. the command(s) that accomplished the task) in commands.txt once you get it to work.

Remember, you can learn about any Unix command by typing man and then the command name. E.g., man ls. Type Q to get out of the Manual page ("man page") viewer.

Part I: Set the Scene

Complete all work inside the star_wars folder.

Create a directory called death_star, and make the following files inside of it: darth_vader.txt, princess_leia.txt, storm_trooper.txt

In a directory galaxy_far_far_away, make a directory named tatooine and create the following files in it: luke.txt, ben_kenobi.txt.

Inside of tatooine make a directory called millenium_falcon, and in it create: han_solo.txt, chewbaca.txt


Part II: mv - rename

You can rename a file using the mv command.
Rename ben_kenobi.txt to obi_wan.txt.

Part II: cp - copy

You can copy a file from one location to another using the cp command. (man cp for more info)
Directories can be sibling (parrell to each other) or can be parents (the folder that contains the folder you are in)
Copy storm_trooper.txt from death_star to tatooine.

Part IV: mv - move

You can use the mv command to move files from one location to another. mv can be used for renaming, moving, or both. Run man mv to see the options—remember hit the Q key to get out of the manual page viewer.
Move luke.txt and obi_wan.txt to the millenium_falcon.

Move millenium_falcon out of tatooine and into galaxy_far_far_away.

Move millenium_falcon into death_star.

Move princess_leia.txt into the millenium_falcon.


Part V: rm - remove

BE CAREFUL WITH rm!!! THERE IS NO "TRASH" IN THE UNIX CLI. WHEN YOU DELETE SOMETHING IT IS GONE FOREVER!!!

You can use rm to delete a file.

Delete obi_wan.txt.

Part VI: all together

In galaxy_far_far_away, make a directory called yavin_4.

Move the millenium_falcon out of the death_star and into yavin_4.

Make a directory in yavin_4 called x_wing.

Move princess_leia.txt to yavin_4 and luke.txt to x_wing.

Move the millenium_falcon and x_wing out of yavin_4 and into galaxy_far_far_away.

In death_star, create directories for tie_fighter_1, tie_fighter_2 and tie_fighter_3.

Move darth_vader.txt into tie_fighter_1.

Make a copy of storm_trooper.txt in both tie_fighter_2 and tie_fighter_3.

Move all of the tie_fighters out of the death_star and into galaxy_far_far_away.


Part VII: rm -r: remove directories and everything they contain

BE CAREFUL WITH rm!!! THERE IS NO TRASH CAN IN THE UNIX CLI. WHEN YOU DELETE SOMETHING IT IS GONE FOREVER

Before you hit enter, make sure are deleting the right thing, or you could accidentally delete the contents of your computer (it has happened).

This command will not typically ask you if you "really want to delete." It will just delete.

Remove tie_fighter_2 and tie_fighter_3.
Part VIII:

Touch a file in x_wing called the_force.txt.

Destroy the death_star and anyone inside of it.

Return x_wing and the millenium_falcon to yavin_4.

Celebrate. You've reached the end of section 1 :)