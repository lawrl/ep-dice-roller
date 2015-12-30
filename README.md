# Eclipse Phase Dice Roller

## Purpose

The EP dice roller is a simple web app to help players and game masters of the a roleplaying game [*Eclipse Phase*](http://eclipsephase.com) with common math and random number generation tasks, replacing a calculator and dice in most if not all cases. 

## (Planned) Features
 - Uses the random.org API to generate random numbers ni lieu of ten sided dice (d10's)
   - Uses only one, separate function to actually call the API and return results in batches
 - The user will see all raw dice rolls alongside the calculated results
 - Intuitive UI
 - A nice looking, responsive widget grid layout of individual roller tools, for all devices
 - Buttons that are satifying to click
 - Specific rollers: 
   - An **Xd10+Y roller**
   - A **Success Test roller** showing 
     - Either success, failure, excellent success, severe failure, critical success, or critical failure, 
     - The roll, 
     - The target number, and 
     - The Margin of Success or Margin of Failure
   - A **(Variable) Opposed Test roller** showing 
     - A summary of the result (eg. "action fails: initiator succeeded, but resistor succeeded and rolled higher")
     - The information for both rolls (result, rolls, target numbers, MoS/MoF)
   - An **Initiative roller** which can roll multiple player's initiatives at the same time.
