# CV_Final_Project

#### Objective
The objective of this project is to build a machine learning model that can detect the positions of chess pieces on a board from images. This involves training a Convolutional Neural Network (CNN) to classify the chess pieces based on their positions in the given images.

### About Dataset
Dataset link: https://www.kaggle.com/datasets/koryakinp/chess-positions
### Context
The goal of the project is to build a model able to generate FEN description based on a schematic image of a chess board.

### Content
100000 images of a randomly generated chess positions of 5-15 pieces (2 kings and 3-13 pawns/pieces)
Images were generated using 28 styles of chess boards and 32 styles of chess pieces totaling 896 board/piece style combinations.

Images were generated using this custom-build tool

All images are 400 by 400 pixels.

Training set: 80000 images
Test set: 20000 images
Pieces were generated with the following probability distribution:

30% for Pawn
20% for Bishop
20% for Knight
20% for Rook
10% for Queen
2 Kings are guaranteed to be on the board.

Labels are in a filename in Forsyth–Edwards Notation format, but with dashes instead of slashes.
