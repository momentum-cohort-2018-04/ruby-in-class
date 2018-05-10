# Blackjack Planning

## Directions

This weekend's homework is to build a Blackjack game in Ruby that runs on the command line.

Since we'll be doing this OO style, we'll begin with designing our classes and their architecture.

### Step One

Design a Card class and a Deck class. Write down what properties you think they should have, what behaviors they might have, and what other classes they will interrelate with or collaborate with in the course of a game. For example, for a card, you might write down:

```text
Card
    - has a rank and suit
    - has a point value
  Collaborators:
    - collected into a Deck
    - collected into a Hand for each Player and a Hand for the Dealer
```

### Step Two

Read through [the rules of blackjack](https://en.wikipedia.org/wiki/Blackjack) carefully. After reading through them, write out the steps to run the game in outline format. (See the additional resources for more on the rules of blackjack.)

Talk about how you might translate these into classes. You don't have to write the code for each method yet, but do sketch out the classes and methods.

## Additional Resources

- Other Blackjack rule summaries:

  - <http://www.pagat.com/banking/blackjack.html>
  - <http://wizardofodds.com/games/blackjack/basics/#toc-Rules>