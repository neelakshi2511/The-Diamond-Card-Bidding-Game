# The-Diamond-Card--Bidding-Game-

The Diamond Card bidding is a game where you'll put your strategic skills to the test against the computer! In this game, you'll be competing with the computer to bid for valuable cards provided by the banker. Your goal is to outsmart the computer and accumulate more points to emerge as the ultimate winner.

**How to Play:**

1. At the start of each round, the banker will present a deck of cards ranging from 2 to 14, excluding Ace, for bidding purposes.
2. You will be prompted to enter your bid for the banker's card. Make sure your bid is between 2 and 15 and hasn't been used in previous rounds. 
3. The computer will also place its bid for the banker's card.
4. Once both bids are placed, the highest bidder wins the round and acquires the banker's card, while the other bidder receives nothing.
5. The value of the banker's card is added to the winner's points tally. In case of a tie, both players receive half the value of the banker's card.
6. The game continues for a total of 13 rounds, with each player trying to maximize their points.

**Card Strategies:**

- Super High Cards (13,14) : Bid wisely, as these cards are valuable and can significantly boost your points.
- High Cards (10-12): Use them strategically as they can provide a good advantage in winning rounds.
- Mid Cards (5 to 9): Consider using these cards for tactical purposes during the game.
- Low Cards (2 to 4): Use these cards cautiously, as they have lower value but can still be useful in specific situations.

**Winning the Game:**

At the end of the 13 rounds, the player with the highest total points will be declared the winner. If you manage to outwit the computer and accumulate more points, you'll achieve victory .


**Funtions Used :**

1. **`banker_response'** : This function takes a list of banker cards as input, randomly chooses one card from the list, removes it from the list, and returns the chosen card.
2. **`user_bid`** : This function takes the banker's card and a list of user cards as input. It asks the user to input their bid, checks if the bid is valid (between 2 and 15 and not already used), removes the bid card from the user cards if valid, and returns the bid value.
3. **`bid_choice2`** : This function takes the banker's card and a list of cards as input. It removes the banker's card from the list and returns the removed card. 
4.**`determine_winner`** : This function takes the user card, computer card, banker card, user points, and computer points as input. It compares the user's card with the computer's card, updates the points accordingly based on the winner (user, computer, or tie), and returns a string indicating the result of the round.
5. **`final_result`**: This function takes the user points and computer points as input and determines the final result of the game based on the points. It returns a string indicating whether the user won, lost, or tied the game.
6. **`CARDS`**: This function runs a loop to simulate a game of bidding. It initializes the banker, user, and computer cards along with the points for user and computer. It also defines different card sets based on their values (Super High Cards, High Cards, Mid Cards, and Low Cards). Then, for each round (13 rounds in total), it calls the above functions to simulate the game, printing the computer's bid and the result of each round. After all rounds are played, it prints the final result of the game (who won or if it's a tie). It then asks the user if they want to play again and continues playing if the user inputs "YES" and stops otherwise.

