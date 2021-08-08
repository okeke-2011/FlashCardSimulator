# FlashCardSimulator
This package simulates real world flashcard as a study tool for student. Users are able to create flashcards and test themselves using the flashcards at a later time.
The package I made consists of 3 classes - FlashCard, Deck and DeckHolder. 

A FlashCard object has a front, back (both text for now) and wait time which can all be edited. 

A Deck object is just a collection of FlashCard objects. With a Deck object you can add, remove, showcase and edit flash cards. The Deck object also has the ability to select a random card, show the front of the card, and reveal the back (after the specified wait time on the card). There is a variation of this random selector method that selects a specified number of cards (not just one) and one that selects all cards. 

A DeckHolder object holds a collection of flashcards using a HashMap. The keys are the deck names and the values are the Deck objects. Within a DeckHolder, you can add, delete or access a deck.
