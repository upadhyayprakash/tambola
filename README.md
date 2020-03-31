# Tambola - A Group Entertainment
### A network based multi-player Indian game a.k.a. Housey or Housie.

## Tickets: Tambola Sample Ticket
![Alt Text](https://i.pinimg.com/originals/8f/db/ee/8fdbeef61d74f5ed7cb2f4fed6ee5986.jpg "Tambola Sample Ticket")

## Game Play:
- Each participant is alloted a Random Ticket
- Each Ticket as 3 Rows and 9 Column. Totaling 27 Cells.
- Random Numbers between 1 and 90 are filled in 15 of those cells. Other cells are disabled/blocked.
- The announcer starts calling the number one at a time, by picking coins from the shuffled coin bowl.

![Alt Text](https://i.pinimg.com/600x315/02/9d/e7/029de77a5ab9ec2e3da5a305db894029.jpg "Shuffled Coins")

- Participants with Housie Ticket, match the announced number in their Ticket and Check/Cross that cell.
- Then, there're Winning Criteria as follows:(may change per game)
	1. Top Row All checked
	2. Middle Row All checked
	3. Bottom Row All checked
	4. Full Housie(All cells Checked)
- Participants full-filling any of the Winning criteria should click on the 'DAB' button or call-out their game fastest. It's possible for two players to win the Row at one time, so the fastest to DAB wins it.
- Once the participant clicks on the DAB button, their Ticket is verified with the Drawn coins. There're two scenarios:
	1. All his checked cells match with drawn conis, so his claim is correct, and he wins that row. That winning criteria is removed as already CLAIMED.
	2. Some of his checked cells are not yet announced, his claim is incorrect, so he's disqualified for further draw of that game. The game continues with further draws.

- The leaderboard can be listed after all the numbers are drawn(1 to 90)

## User Flow:
- Log-in to the Tambola Website
- On the HOME page, user can see the game slots by hour of the Day.
- User can select any future HOUR to enter into the game.
- Game starts on time.
- Participants are given 10 mins to ENTER into the game.
- Once the Game starts, the participants List is frozen.
- All the Valid Participants are alloted a random Ticket, unique for every user.
- Game is then controlled by the Backend Server, allowing every user to make changes in their Ticket based on the Announced Random number by the UI.
- The first user to satisfy the criterion of every "Valid Winning Criteria" should "DAB" in order to claim their Win.
- Likewise, all the 90 random numbers are drawn and Winners of each criteria are declared by end of the Draw.

### This game has been played since decades and quite a popular across Indian kids of 80s/90s. Since this Lockdown has affected many of them and isolated them from Social interaction, this game binds the people's Emotion and has also been used as a Gambling medium(Optional)
