Project: automaton
Aothors: David J. Barnes and Michael Kölling

This project is part of the material of the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 7.

Answers 

27- Yes, the exact same patterns emerge.

28- It clears the automaton by making all cells blank before restarting.

29- Yes, different patterns emerge this time.
    Yes, those patterns deterministic.
    
31- So that we can calculate the next generation of the automaton without changing the current one while we're still using.
    It does make a difference because updating state directly mixes the old and new generations.

32- Yes, we can by keeping just the previous cell's old value in a temporary variable while updating the array.
    Only one old cell 
    Using a full new array is better because it's safer, simpler and easier to understand.
    
 