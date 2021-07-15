## Software Modelling and Design Project 2 - Whist Card Game

*Developed in collaboration with Andrew Lee*

This program is an implementation of the card game 'Whist', complete with a GUI utilising the library JGameGrid. The program allows for 4 players, 
whether human or the provided AI types, to play the game.

The main purpose of this project was to test our software design and modelling skills. We were given a (somehow) working skeleton with some very 
stinky code that implemented the basics of the game, with our job being to refactor the existing code into an extensible and cohesive design.
From our new design, we were to implement the required features given in the spec (`docs/project-spec.pdf`) using best-practice object oriented design
patterns. Throughout the project we use design patterns outlined by the 'Gang of Four', explaining the rationale for our design decisions in our report
(`docs/Report.pdf`).

The final codebase has been extensively modelled, including:
* A complete UML Class Diagram (`docs/uml-class-diagram.pdf`)
* A state machine of the Game class (`docs/game-state-machine.pdf`)
* A UML sequence diagram of the smart player strategy (`docs/sequence-smart-player.pdf`)
* And a UML domain diagram (`docs/domain-diagram.pdf`)

#### Project Structure
* `docs/` contains all documentation relevant to the project
* `lib/` contains the JGameGrid framework essential for the GUI
* `swen30006/` contains all project source files, with `swen30006/sprites/` containing media files
* `*.properties` contain various config options for the project

