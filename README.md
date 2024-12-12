# IPL Auction Game

This project is an interactive **IPL Auction Game** where users can participate in a virtual IPL auction and bid for players. It simulates the real-world auction process where each team has a limited budget to purchase players, and players are selected based on their roles and team requirements. The game is built using **HTML**, **CSS**, and **JavaScript**.

### Live Demo
You can try the game online by visiting the following link:

[IPL Auction Game Live Demo](https://sherjinag.github.io/ipl_auction_game/auction.html)

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Play](#how-to-play)
- [How to Run Locally](#how-to-run-locally)
- [File Structure](#file-structure)
- [Project Setup](#project-setup)
- [Challenges Faced](#challenges-faced)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
The **IPL Auction Game** allows users to bid for their favorite cricket players in a virtual auction environment, mimicking the actual IPL (Indian Premier League) auction process. Players are categorized into batsmen, bowlers, all-rounders, and wicketkeepers, and the user is required to manage their team within a fixed budget.

This game was designed for entertainment purposes, as well as a demonstration of JavaScript, CSS, and HTML for interactive web applications.

---

## Features
- **Team Management**: Users can manage their IPL team by bidding on players within their available budget.
- **Real-time Auction**: AI-controlled teams will also participate in the auction, bidding on players.
- **Player Stats**: Each player has specific attributes, such as skill level, position, and price.
- **Budget System**: Each team has a total budget to spend on players, ensuring strategic decision-making.
- **Dynamic Gameplay**: The game updates the current state as the auction progresses.
- **Realistic Player Choices**: AI selects players according to their team composition and needs (e.g., number of batsmen, bowlers).
  
---

## Technologies Used
- **HTML**: For structuring the pages.
- **CSS**: For styling and layout.
- **JavaScript**: For interactive features like the auction logic, AI bidding, and player management.
- **Local Storage**: To save the user's team progress and budget.
  
---

## How to Play
1. **Start the Game**: Open the live demo or the locally hosted game in your browser.
2. **Choose a Team**: You will be prompted to choose your team and budget.
3. **Bidding**: Players are auctioned one at a time. You can place bids on players by clicking the “Bid” button.
4. **Team Building**: Manage your budget carefully to complete your team within the set requirements (e.g., number of batsmen, all-rounders, etc.).
5. **AI Teams**: Other teams will bid automatically based on their requirements, adding an extra layer of complexity to the game.
6. **Game Over**: The auction concludes when all teams have completed their roster. The player with the most valuable team, within the budget constraints, wins the game.

---

## How to Run Locally
To run this game locally on your computer, follow the steps below:



### 1. Clone the Repository
```bash
git clone https://github.com/SHERJINAG/ipl_auction_game.git
---
## File Structure
ipl_auction_game/
├── auction.html         # Auction game page
├── images/              # Folder containing images and icons
│   ├── player_images/   # Player images for auction
│   ├── team_logos/      # Logos of IPL teams
├── script.js                 # JavaScript files

├── st.css
└── README.md            # Project documentation
---
## Project Setup
To set up and start working on this project locally:

Ensure that you have a web browser installed (e.g., Chrome, Firefox).
Clone the repository and open the auction.html file directly in your browser.
---

## Challenges Faced
During the development of this game, several challenges were encountered:

AI Bidding Logic: Developing an intelligent AI system that mimics the real IPL auction process was complex. It had to consider player stats, budget management, and team requirements.
Responsive Design: Ensuring that the game works seamlessly across different devices, especially mobile phones, required careful consideration of CSS media queries.
Real-time Updates: Managing real-time updates of the auction and handling bids simultaneously from multiple teams (human and AI) was a key challenge.
---
## Contributing
If you would like to contribute to this project, feel free to fork the repository and make a pull request with your changes. Please ensure that you follow the existing code style and provide a detailed description of your changes.

To contribute:

Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes with a descriptive message.
Push your changes and create a pull request.
---
## License
This project is licensed under the MIT License - see the LICENSE file for details.
---

## Acknowledgments
IPL: The game is inspired by the real IPL Auction process.
GitHub: For hosting and providing a platform for collaboration.
Stack Overflow: For solving development-related queries.
---
