# Memorize

Assignment that is part of Stanford's CS193p course.

## Description
Memorize is a simple card game in which all of the cards are laid face down on a surface and two cards are flipped face up over each turn. 
The object of the game is to turn over pairs of matching cards.

## How did I extend the assignment?
- Added formal concepts of "Themes" for the cards with 6 different themes with varying # of cards each new game
- Added business logic for scoring correct matches and incorrect matches based on whether user has already seen a card
- Implemented shuffling button during game with SF Symbols
- Added colorful gradients to themes along with animations for new games and shuffling

## Technologies Used
- SwiftUI
- Xcode
- MVVM Architecture

## Technologies Used
- SwiftUI
- Core Data
- Haptics 
- Core Animation
- Putting Views together using VStack, HStack, etc.
- Modifying Views (using .font(), etc.)
- Using @State
- Using a Range (e.g. 0..<emojiCount) as a subscript to an Array
- The SF Symbols application
- Putting system images into your UI using Image(systemName:)
- Looking things up in the documentation (Array and possibly Font)
- Int.random(in:) 

## Demo
![Dice Roll Demo](Demo/demo.gif)
