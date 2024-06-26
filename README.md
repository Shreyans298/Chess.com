# Chess.com Project


**Overview:**

**1. Initialization:** Chess objects are initialized. Initial values of dragged piece, source square, and playerRole (White or Black) are set to NULL.

**2. Initial Board Rendering of both the users:** Display initial setup of the chessboard, ie. all the chess peices to their respective home sqaures.

**3. Addition of drag and drop functionality of chess pieces:** using Socket Event Handling (showing the pther user the move played by the 1st user in real-time). Drag feature is available only for it's colour pieces. When a piece is dragged, sourceSquare and draggedPiece are updated. Similarly, when a piece is dropped, we handle its move according to the power of the draggedPeice, and emit it to the server.


**Variables used:**

**1. Socket:** Connect to the server using Socket.io
**2. Chess:** An instance of the Chess class.
**3. Board Element:** DOM Element with the ID "ChessBoard".
**4. DraggedPiece:** The piece being dragged during drag_and_drop action.
**5. Source Square:** Stores the starting square of the dragged piece.
**6. PlayerRole:** Holds "W", if its colour is White, "B" corresponding to Black colour, or NULL, if one is a spectator.
  
