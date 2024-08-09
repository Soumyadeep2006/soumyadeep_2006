<h3>Tic Tac Toe on Aptos</h4>
A simple implementation of the Tic Tac Toe game using the Move language on the Aptos blockchain.
<br>
Overview
<br>
This project uses a smart contract to manage the Tic Tac Toe game state, allowing two players to play securely on a decentralized platform.
<br>
Features
<br>
Decentralized Gameplay
<br>
Two-Player Support
<br>
Basic Game Logic
<br>
Getting Started
<br>
Prerequisites
<br>
Rust: Install
<br>
Aptos CLI: Install via:
<br>
bash
<br>
Copy code
<br>
cargo install --git https://github.com/aptos-labs/aptos-core.git aptos
<br>
Installation
<br>
Clone the repository:
<br>
bash
<br>
Copy code
<br>
git clone https://github.com/yourusername/aptos-tic-tac-toe.git
<br>
cd aptos-tic-tac-toe
<br>
Compile the contract:
<br>
bash
<br>
Copy code
<br>
aptos move compile --named-addresses default=<your_address>
  <br>
Deploy to testnet:
<br>
bash
  <br>
Copy code
  <br>
aptos move publish --profile testnet
  <br>
Usage
  <br>
Create a Game:
<br>
move
  <br>
Copy code
  <br>
Game::new_game(<player1_address>, <player2_address>)
  <br>
Make a Move:
<br>
move
  <br>
Copy code
  <br>
Game::make_move(&mut <game_instance>, <row>, <col>, <player_address>)
  <br>
License
  <br>
This project is licensed under the MIT License.
<br>

