# SCP - Containment Breach: No Drop Challenge - Scoring System
### Scores for this challenge are calculated with a formula holding to several factors.
In order to calculate your score, you’ll need to understand the following made up abbreviations:
* (CTR): Points awarded for finishing the Regular challenge.
* (CTH): Points awarded for finishing the Hard challenge.
* (POF): Points awarded for finishing the game.
* (PPA): Points awarded per unlocked achievement.
* (PPM): Penalty points given for each minute the game is played. (See “Playtime Setup” for more info)
* (INV): Indicates an invalid setup for this challenge, points will not be awarded in this case.

*An example of an invalid setup is: Playing on Keter difficulty while doing the Regular challenge type.


### Playtime Setup:
Playtime is calculated in the following matter

Every minute played will count towards your penalty points, minutes are rounded upwards at the 30 second mark.

This means that:

* 1 minute and 29 seconds will count as 1 minute.
* 1 minutes and 30 seconds will count as 2 minutes.

To ease timing, I recommend you to use **forxandknives’s** 1.3.11NEW.ASL auto splitter together with my layout and splits for the application LiveSplit.

These will do all the timing work for you allowing you to focus on the game.


A guide on how to do this can be found at:

https://github.com/forxandknives/Containment-Breach-Autosplitters/blob/master/README.md

https://livesplit.org/

*I am not the author/ creator of this script, all credits for the script go towards **forxandknives**.


### Base score
Each “setup” has its own base score and additional points that can be awarded.

The following table shows this in detail:

Playthrough Difficulty: | Safe | Euclid | Keter
------------------------|------|--------|------
CTR: | 100.00 | 150.00 | INV
CTH: | INV | 200.00 | 300.00
POF: | 50.00 | 100.00 | 150.00
PPA: | 1.00 | 1.50 | 2.25
PPM: | 1.00 | 0.50 | 0.25
			
Your score can be calculated with the following formula:			

(CTR or CTH) + POF + PPA - PPM			

Example of a score calculation:			
			
Challenge Type: | Regular
----------------|--------
Playthrough Difficulty: | Safe		
Total achievements: | 11.00		
Total minutes played: | 81.00		
			
Formula: CTR(100.00) + POF(50.00) + PPA(11.00) - PPM(81.00)			

Result: 80.00 points.
