Description

A chess game written, using SFML. Has four board types and two pieces types - set random by default, but user can set them manually via Game::Game() method.
Screenshots are in files/Screenshots folder.

Planned Features

-AI Integration: Add Stockfish engine support for playing against a strong AI opponent. 
-Timer: Implement a chess clock with configurable time controls (e.g., blitz, rapid, classical). 
-Side Selection: Allow players to choose to play as White or Black before the game starts. 
-Player Modes: Support player vs. player and player vs. AI game modes.

Known Limitations / Incompatible Features 
(these features are currently not compatible with the existing game logic and may require significant refactoring)

-Enemy Move Highlighting: Display all legal moves of player's king depending on enemy pieces positions. 
-Draw Detection: Implement full draw condition handling (e.g., stalemate, threefold repetition, 50-move rule).