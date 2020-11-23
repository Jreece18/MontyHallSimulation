# MontyHallSimulation

The Monty Hall Problem is a probability puzzle based on the gameshow Let's Make A Deal.

1. There are three doors, 1 with a car (the prize), 2 with goats (the consolation).
2. You are told to pick a door.
3. Monty, the host, reveals a goat behind one of the other doors. Leaving only your door and one other left.
4. He offers you the chance to stick or twist, either keeping your original door, or swapping to the other that has not yet been revealed.
5. You win the prize behind the door you have selected.
6. What do you do? Stick or switch?

It's a problem loaded with both emotional and mathematical obstacles, often leading the player to make the wrong decision, whether they use logical reasoning or go with their gut instinct. The correct decision would be to switch to the other door that has yet to be revealed. While this is not particularly intuitive, the decision is not 50/50. 

The host has to reveal a door containing a goat, otherwise the game is ruined. You correctly pick the car only 1/3 of the time, therefore 2/3s of the time, Monty reveals, by omission, the door belonging to the car. If you choose to switch to the unrevealed door, you will win 2/3s of the time. This does not work for more modern gameshows such as Deal Or No Deal, as the improved probability is based on the information gain explained above. If the host did not know where the car was, or he could open the door belonging to the car, the odds would not be improved.

### Situation 2/3s of the time:

1. You pick a goat.
2. One of the other doors has the car, the other has another goat.
3. The host cannot pick the car, as the gameshow will be over.
4. Therefore, 2/3s of the time, the car is revealed to you as the door the host did not pick.

### Analysis

Most people's instinct is to keep their original choice, from a combination of thinking the probabilities are equally distributed across all three doors and a preference for their chosen door (through loss or 'switch' aversion). While this incorrect decision can be the cause of cognitive biases, it is also susceptible to incorrect reasoning through a misunderstanding of the probability distribution (Tabau, Aguilar-Lleyda, and Johnson, 2015).

As can be seen from the graph in the notebook, even arbitrarily choosing whether you keep or switch provides a better outcome to just keeping your original door. Regardless of this, many people will still choose to keep their door even if they are told they have better odds if they switch. This can be explained by psychology, with research suggesting that the pain of losing a possession is twice as powerful as the pleasure of acquiring it (Tversky and Kahneman, 2000). Whether the correct decision is known or not, there remains a temptaton to base decisions off emotions. 

Simulating each decision 10,000 times may prove to be more persuading than simply explaining the probability, as most people tend to be more susceptible to practical experience over theory. 

### References

Tabau, E., Aguilar-Lleyda, D., Johnson, E. D. (2015). Reasoning and choice in the Monty Hall Dilemma (MHD): implications for improving Bayesian reasoning. Front Psychol 6:353. doi:10.3389/fpsyg.2015.00353

Tversky, A., & Kahneman, D. (2000). Loss Aversion in Riskless Choice: A Reference-Dependent Model. In D. Kahneman & A. Tversky (Eds.), Choices, Values, and Frames (pp. 143-158). Cambridge: Cambridge University Press. doi:10.1017/CBO9780511803475.008
