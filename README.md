# GameOfLife
Game of life with Python and OpenCV

This is my take on Game of High Life using Python and OpenCV.
Rules are as follows:
  - Any cell "sees" 8 neighbours (N, S, W, E, NW, NE, SW, SE)
  - Any living cell dies if it has less than 2 or more than 3 alive neighbours.
  - Any living cell with 2 or 3 alive neighbours remains alive.
  - Any dead cell with 3 or 6 alive neighbours becomes a live cell.
  - Rules are applied on each cell simultaneously per iteration.
  
My implementation requires the following packages:
  - Numpy (pip install numpy)
  - OpenCV (cv2) (pip install opencv-python)
  - 
