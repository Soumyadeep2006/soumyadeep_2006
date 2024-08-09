Tic Tac Toe on Aptos
A simple implementation of the Tic Tac Toe game using the Move language on the Aptos blockchain.

Overview
This project uses a smart contract to manage the Tic Tac Toe game state, allowing two players to play securely on a decentralized platform.

Features
Decentralized Gameplay
Two-Player Support
Basic Game Logic
Getting Started
Prerequisites
Rust: Install

Aptos CLI: Install via:

bash
Copy code
cargo install --git https://github.com/aptos-labs/aptos-core.git aptos
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/aptos-tic-tac-toe.git
cd aptos-tic-tac-toe
Compile the contract:

bash
Copy code
aptos move compile --named-addresses default=<your_address>
Deploy to testnet:

bash
Copy code
aptos move publish --profile testnet
Usage
Create a Game:

move
Copy code
Game::new_game(<player1_address>, <player2_address>)
Make a Move:

move
Copy code
Game::make_move(&mut <game_instance>, <row>, <col>, <player_address>)
License
This project is licensed under the MIT License.

