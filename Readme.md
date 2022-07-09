# Rock Paper Scissor
In this project, I will learn how to create a Rock Paper Scissor game using Computer Vision. I will use hand tracking to find the move of the player and generate a random move for the AI.

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/rock_paper_scissor.git`
2. Install all the requirements
`run libraries.bat` or
`pip install -r requirements.txt`
3. Run the program
`python main.py`

## Help
You might face issue with webcam not showing and you get errors.
To solve it just change the value in this line (for example to `1`).
`cap = cv2.VideoCapture(0)`
Increment this number until you see your webcam.

## How to play
Press `s` to start the game

## Result
![Alt Text](https://github.com/paveldat/rock_paper_scissor/blob/main/result/result.gif)