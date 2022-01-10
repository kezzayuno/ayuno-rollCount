# Specifications 

## Home Menu
- Center-Top of the screen is the app title: RollCount!
- Bottom of the screen: leftmost corner is a + button to add a new game session, rightmost is Total: # where this is the total amount of game sessions saved (max amount of game session they can make is 10)
- List of game sessions (each game session block is clickable for more detailed viewing presenting the name of the game, the NdM, and date with an editable (...) option (choices: edit or delete (deletes game session))
- Up and down scroll feature

## Add New Game Menu
- Input game name (up to 40 characters long)
- Input # rolls 
- Input # dice sides
- Start date is automatically generated (when the player presses the "Begin" button)
  - Begin button leads to the Game Screen

## Edit Menu
- Date [yyyy] [mm] [dd]
- Rolls [#]
- Dice Sides [#]
- Name [...] (up to only 40 characters long) 
- "clear" button (clears the data in that game session) 
[#] -- slide down button where Rolls (1-3) and Dice Sides (4,6,8,10,12,20)
Date is restricted -- no future dates and past restricted to edit no further than current year 
- Upperleft corner is <- button (go back to home screen) -- WARNING pop-up if they do not save ("Save?" Yes No)
- "save" button topright corner 

## Game Screen
- Top-centered on header is the game name
- <- button to go back to home screen 
- Left corner under <- is date 
- Right corner (not on header) "NdM" where N would be an integer indicating the roll number and M would be an integer indicating the sides of the dice
- Middle of screen is a graphical histogram (histogram graph with the labels under each bar: # of rolls chosen, under this specific dice side) -- updates;
- Corner of histogram is "more" button which shows a pop-up of the current max, min, average (that have been rolled) 
- Below the histogram to the right is "<" and ">" which are buttons that undo or redo)
  - In the beginning, these are grey but as choices are made the "<" will be highlighted (indicating the player can undo), if they do undo, the ">" will be highlighted meaning they could redo their choice 
- Under the histogram and the < and > buttons are the buttons each indicating the possibilities (e.g., 1d6 is 1 roll and 6 sides: therefore, 1,2,3,4,5,6 are the buttons to be shown) 
Up and down scrolling feature is only added if necessary (for example, the player's NdM imply a really large amount of buttons) 

## Save + Persistence 
- Data is stored even when the app is closed 
- Save all game sessions created 
