# [Foreword to Same Game at Cprogramming.com](https://www.cprogramming.com/tutorial/game_programming/same_game_part1.html?inl=pf)
In this five part series, we'll be creating a version of a game called SameGame using the Microsoft Foundation Class library from start to finish. We'll include features beyond the simple removing of blocks in the game. We'll implement an undo/redo subsystem and some user configuration dialogs. We'll show you step by step with not only source code but screenshots how to build a fun game from start to finish and how to use Microsoft's MFC classes. Every article comes with complete source code, so you can build and run the game yourself.

The rules to the SameGame are quite simple, you try to remove all of the colored blocks from the playing field. In order to remove a block the player must click on any block that is next to, vertically or horizontally, another with the same color. When this happens all of the blocks of that color that are adjacent to the clicked block are removed. All of the blocks above the ones removed then fall down to take their place. When an entire column is removed, all columns to the right are shifted to the left to fill that space. The blocks aren't shifted individually but as a column. The game is over when there are no more valid moves remaining. The goal is to end with an empty board in as little time as possible. Some versions of the SameGame use a scoring algorithm that can be implemented as an additional exercise for the user.

## Prerequisites
You'll need to have a basic C++ knowledge of functions, recursion, classes, and inheritance. The code was written using Visual Studio 2005 on Windows XP although later versions of Visual Studio should be fine although the screenshots will look slightly different from what you will see. You must use the Standard or Professional edition of Visual Studio; Visual Studio Express cannot be used, because it does not come with MFC.
Note: This was converted using Visual Studio 2019 Community Edition (16.10.3) and Windows SDK 19041 to an x64 project/solution on Windows 10 21H1.

## What You'll Learn
First and foremost, you'll learn some basics of how to create your own game. You'll learn about the Microsoft Foundation Class library and some basic usage and the Document/View architecture paradigm.

Here's an outline of the series, with links to each article:

[Same Game - Part 1](https://www.cprogramming.com/tutorial/game_programming/same_game_part1.html?inl=pf) Introduction to technologies and drawing the game board

[Same Game - Part 2](https://www.cprogramming.com/tutorial/game_programming/same_game_part2.html) Creating a real, playable game

[Same Game - Part 3](https://www.cprogramming.com/tutorial/game_programming/same_game_part3.html) Adding difficulty levels and other menu options

[Same Game - Part 4](https://www.cprogramming.com/tutorial/game_programming/same_game_part4.html) Changing the game board size and the block count

[Same Game - Part 5](https://www.cprogramming.com/tutorial/game_programming/same_game_part5.html) Adding undo/redo functionality and keyboard accelerators


## Why MFC?
MFC is an easy-to-use library, especially for a simple game like the one we want to make. It will make it easy to create an application with a true Windows look-and-feel.

## [License](LICENSE.md)

### [My Changes to the Game](CHANGES.md)
