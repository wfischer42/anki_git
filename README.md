# A Collaborative Anki Workflow for Coding

For the code-formatting Anki add-on, use the code `463041493`

Let's start by seeing how it responds to a shared "Test Deck."

## Workflow
* Pull from master, then import the latest `test_deck.apkg`
* create a new git branch
* Add a new card. Study existing cards.
* Export deck to test_deck.apkg
  * DON'T `include scheduling information`
* Add and commit changes to branch
* Create pull-request & merge
* Other collaborators repeat!

## Objectives
* Test that Anki maintains spaced repetition info
* Test that un-edited cards are not replaced or duplicated
* Test that divergent branches can be merged without conflict
