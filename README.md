# Preproposal

## What idea(s) do you have for your final project?

I want to do a game, maybe a dice game or a card game.

## If you plan to collaborate with one or two classmates, what are their names?

TODO

## Do you have any questions of your own?

TODO
# Proposal

## What will (likely) be the title of your project?

Blackjack Strategy Simulator

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A Python-based Blackjack game that lets you play interactively and simulate thousands of hands to compare how different strategies perform statistically.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The software will have two modes: a playable Blackjack game where the user makes decisions (hit, stand, double down) against a dealer, and a simulation mode that runs thousands of automated hands to analyze win rates across different strategies (e.g., always hit under 17, use basic strategy, always stand). Results will be displayed as printed statistics and a matplotlib bar or line chart showing win percentages per strategy. The project will be built using only Python standard libraries plus matplotlib for visualization, and run entirely from the terminal.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

TODO, if applicable

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

TODO, if applicable

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?
A fully playable Blackjack game with correct game logic: dealing, hitting, standing, bust detection, and dealer rules.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

A working simulation mode that runs automated hands and prints win/loss statistics comparing at least two different playing strategies.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

Matplotlib charts visualizing strategy performance across 1,000+ simulated hands, plus a clean and polished terminal interface for the interactive game mode.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

The first step is building the card and deck logic: representing a deck as a list of dictionaries, shuffling with random.shuffle(), and handling Ace values that can be 1 or 11. From there, the game loop follows naturally using loops and conditionals already covered in class. The main new skill to acquire is matplotlib, specifically how to create a simple bar chart from a dictionary of results. I will also research basic Blackjack strategy online to make the simulation strategies accurate. Since this is a solo project, all parts will be completed individually
