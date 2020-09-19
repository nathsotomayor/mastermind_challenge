---
title: "How to build a Mastermind Game in Python"
date: 2020-09-18
---

![mastermind-small](https://user-images.githubusercontent.com/28455356/93660506-452c2680-fa15-11ea-9741-be1cc0f987d3.jpg)

This is our Mastermind Game challenge implementation and our explanation to how build it.

Our team group is:

  * David Orejuela
  * Emma Navarro
  * Santiago Peña
  * Nathaly Sotomayor Ampudia
  
### Initial requirements

  * Python 2.7 or greater
  * Tkinter GUI library
  * Xming Server (Windows OS) or another graphic interface handler according to your OS
  * Configure your system to handle graphic interface applications  
 
### Download and Installation

You must have `git` installed

Open the command line interface and clone the repository:

  `git clone` [https://github.com/daorejuela1/mastermind.git](https://github.com/daorejuela1/mastermind.git)
  
### Usage

Go to the repository folder and execute `main.py`

  ```bash
  cmd/mastermind~$ ./main.py
  ```
  
## :video_game: The Game

![set_size_game](https://user-images.githubusercontent.com/28455356/93660394-00ec5680-fa14-11ea-86d4-22af77145691.gif)

### :scroll: Rules

Your aim is to crack the code fast enough to get a high score and make it onto our Master Code Breakers list.

You get 8 attempts at breaking the code. If you can't discover it by then then you lose that game. But that's ok. You can get a new code and try again.

The Code Breaker code is made up of 4 to 6 colours from the 8 available colours. To win you must place the right marbles in the right order. After each attempt you will be told how you went.

:white_circle: **White marble** - Means that there is one of your marbles in the code but not in the right place.

:black_circle: **Black marble** - Means that there is one of your marbles in the code and in the right place.

![PlaywithFriends](https://user-images.githubusercontent.com/28455356/93660450-ac95a680-fa14-11ea-917d-006ccfb9440f.gif)

#### Play and Have Fun! :space_invader:
