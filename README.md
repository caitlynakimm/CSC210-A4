# A7 Linked Lists

Your readme should include the following information. **Each student** needs to submit all of this information, even when pair programming. 

## Submission Details

Your Name: Caitlyn Kim


Programming Partner Name (if you are submitting identical code):


Other Collaborators (submitting related but non-identical code):


Kudos/shout-out to particularly helpful members of the class or teaching staff:
- Shout out to Tabitha from class who helped me think about how to start the mouseClicked() method from Stage 2. Also, shout out to Tania (TA) who helped me check the logic of some of my Stage 2 methods.

Any references used besides JavaDoc and course materials:


If you used AI, please describe how and the interaction between AI and your understanding of this assignment and specifically the related data structures and algorithms:
- mouseReleased() was confusing for me to implement. I asked for hints/suggestions about how to think about certain edge cases such as if the location of the mouse release was not on a card but near a pile of cards or if the location of the mouse release was not on a card but near an empty pile. Doing this also helped me solve my NoSuchElementException because my method was originally causing whatever card(s) I released away from a pile to return to my cursor whenever I tried dragging any other card or on the screen. This helped me better understand how linked lists work, I obviously can't take any node out if there are no nodes in the first place.

## Reflection

In what ways were the use of linked lists particularly appropriate for this assignment?
- The linked lists and the use of iterators allowed me to insert specific cards and entire piles into empty piles or piles that already had cards in it easily without having to reindex every card (just need to update pointers). I was also able to remove cards and entire piles easily using loops and linked list iterators.

What was the major challenge you faced in completing this assignment?
- I think the major challenges for me were trying to understand which methods would be the most efficient to use within other methods and thinking of all the edge cases for the stage 2 methods (ex. if user is starting or already dragging cards, if where mouse released is on an empty/existing pile or on a card/no card). 

What do you feel you learned from this assignment?
- I think I got a better understanding of how iterators work to shrink and grow linked lists. I also learned that I can insert entire piles just from accessing the head or tail node.

