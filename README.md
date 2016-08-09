# bgBuilder
Board Game Builder

## Getting Started
Note that you may need administrative privileges to perform some of the following commands.

- [Python](https://www.python.org/downloads/)
  - Verify with `python --version`
- [Upgrade `pip`](https://pip.pypa.io/en/stable/installing/#upgrading-pip)
  - `python -m pip install -U pip`
  - Verify with `pip --version`
- [pytest](http://docs.pytest.org/en/latest/getting-started.html)
  - `pip install -U pytest`
  - Verify with `py.test --version`
- [Sphinx](http://www.sphinx-doc.org/en/stable/install.html)
  - `pip install -U sphinx`
  - Verify with `sphinx-build --version`

## Carcassonne
Game concepts, entities, rules, actions, etc.

- Game
  - Turn Order
  - End Condition
  - Win Condition
- Turn
  - Actions
    - Required
      - Draw Tile
      - Place Tile
      - Score Completed Features
    - Optional
      - Place Follower
- Player
  - Starting Player
  - Score
  - Color
  - Supply
  - Place Tile
- Board
  - Placed Tiles
  - Coordinate System
- Deck
  - Shuffle
  - Draw Tile
- Tile
  - Start Tile
  - Sides
  - Type
  - Location
    - Deck
    - Board
      - Coordinates
  - Features
    - Road Sections
    - Crossroads
    - City Sections
      - Banner
    - Field Sections
    - Monasteries
    - River Sections
    - River Source
    - Lake
- Follower
  - Color
  - Type
    - Thief
    - Knight
    - Monk
    - Farmer
- Rules
  - Tile Placement
  - Feature Completion
  - Feature Scoring
  - Starting Player
