# BASIC_CARD

This module is for anyone who is interested in creating  their own card game.  The functions included are self explanatory and allow to perform basic fucntions on an indidual card, deck of cards or individual hands. It uses the external pygame module to display the cards visually hence this can be used along with pygame module.  It also uses the python in-built random module.


## Methods included

- compare_cards(c1, c2) : Takes two arguments of which both are instances of the Card object. Returns the highest value of the card.  'A', 'K', 'Q' and so on are deemed highest in that order. Feel free to modify according to your needs.

- match_card(surface, i, x, y): Takes four arguments. 'surface' refers to the surface obejct in pygame where the card should be blitted. i' refers to the instance of the Card object. 'x' refers to the x coordinate and 'y' refers to the y coordinate the card should be blitted on the screen.  x and y starts from the top left corner of the screen.

- have_suits(hand, s): Takes two arguments where 'hand' refers to a hand which is a list object with instances of the Card object. 's' refers to the suit which is a string ('hearts', 'clubs', 'spades', 'diamonds'). Returns a boolean of either True if have and False if not.

- least_high_card(c, hand): Takes two argumensts where 'c' refers to an instance of Card object. 'hand' refers to a list object containing instances of the Card object.  Returns the highest card in the hand but lower than 'c'

- lowest_valuCard_of_suit(hand, s): Takes two arguements where 'hand' refers to a list object containing instances of the Card object.  's' refers to the suit which is a string ('hearts', 'clubs', 'spades', 'diamonds').  Returns the lowest value of the card from the suit 's'.

- lowest_valueCard(hand): Takes one argument where 'hand' refers to a list object with instances of the Card object.  Returns the lowest value of a card in the 'hand'.

- highest_valueCard_of_suit(hand, s): Takes two arguements where 'hand' refers to a list object containing instances of the Card object.  's' refers to the suit which is a string ('hearts', 'clubs', 'spades', 'diamonds').  Returns the highest value of the card from the suit 's'.

- highest_valueCard(hand): Takes one argument where 'hand' refers to a list object with instances of the Card object.  Returns the highest value of a card in the 'hand'.


* Credit for the png images of the card pack goes to: Andrew Tidey http://creativecommons.org/publicdomain/zero/1.0/

Licensed under [MIT License](LICENSE)
Thanks
