# Project Description

### Project Description:

Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three" style puzzle game where the player must connect tiles of the same color in order to clear the board and win the level. It also features singing cats. We're not kidding!

As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention and game rounds.

To complete this project, you should be comfortable working with pandas DataFrames and with using the pandas plot method. You should also have some understanding of hypothesis testing and bootstrap analysis.

### Data Description:
**Source:** [Kaggle](https://www.kaggle.com/datasets/yufengsui/mobile-games-ab-testing/data)

The data is from 90,189 players that installed the game while the AB-test was running. The variables are:
- `userid` - a unique number that identifies each player.
- `version` - whether the player was put in the control group (gate_30 - a gate at level 30) or the test group (gate_40 - a gate at level 40).
- `sum_gamerounds` - the number of game rounds played by the player during the first week after installation
- `retention_1` - did the player come back and play 1 day after installing?
- `retention_7` - did the player come back and play 7 days after installing?

When a player installed the game, he or she was randomly assigned to either gate_30 or gate_40.

### A/B Testing Process:

1. Understanding Business Problem
2. Scrubbing
    - Missing values
    - Duplicates
    - Outliers 
3. A/B Testing
    - A/B Testing on continuous variables
    - A/B Testing on discrete variables
4. Interpreting
    - Evaluating the results
    - Making inferences
    - Recommendation for customer/director/ceo etc.