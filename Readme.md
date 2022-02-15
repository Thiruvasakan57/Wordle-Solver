Repository logs evolution of solver. 
MARK-1: 
  Elimination based only on the presence or the absence of a letter in the secret word. 
  User has to input in lower cases, the letters present and the letters absent after each guess. 
  Baby steps :)
  
 MARK-2: 
  Elimination based on both presence, absence and positional info of a letter in the secret word. 
  User has to input the 'guess' and 'clue' after each guess in the wordle game. 
  Known issue: Program returns empty list when guess has a repeating letter. 
  
  Areas to improve: 
    Write functions and make it modular in the try to solve known issue of guess having a repeating letter.
  
MARK-3: 
  Vision: 
  Elimination based on both presence, absence and positional info of a letter. 
  Program also suggests words to guess based on frequency analysis of letters in the updated database of possible words after each trial.
