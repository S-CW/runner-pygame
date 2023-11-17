# Runner Game
## Overview
Runner Game is a Python-based game that utilizes the pygame package to create an entertaining gaming experience.

## How to use
1. **Clone the Repository**
```bash
   git clone git@github.com:S-CW/Runner-game.git
```

2. **Install Dependencies**
    Install the required dependencies from the **requirements.txt** file using pip.
    `
    pip install -r requirements.txt
    `

3. **Run the Game**
    To start the game, open a terminal and run the following command:
    `
        python runner.py 
    `

## Control
1. Press **P** to open setting menu

2. Press **M** ingame to mute/unmute

## Variable
1. **spawn_rate_type**, a list of monster type that control the spawn rate of monster type. As of now only two monster type is available: bird, snail
**Usage**
`
    ['fly', 'snail', 'snail', 'snail']
`


## Future development
Here are some planned enhancements for future development:

- [x] **Adjustable Background Music Volume**
    Allow users to adjust the volume of the game to their preference.
- [x] **Progressive Difficulty**
    Implement a feature where the game's speed gradually increases as the player's score goes up, making the game more challenging over time.
- [ ] **Additional Scoring Opportunities**