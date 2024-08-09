module Game::TicTacToe {
    struct Game {
        board: vector<vector<u8>>,
        current_player: address,
    }

    public fun new_game(player1: address, player2: address): Game {
        let board = vector::empty();
        vector::push_back(&mut board, vector::empty());
        vector::push_back(&mut board, vector::empty());
        vector::push_back(&mut board, vector::empty());
        Game { board, current_player: player1 }
    }

    public fun make_move(game: &mut Game, row: u8, col: u8, player: address) {
        // Logic for making a move
        // Ensure it's the player's turn, update board, etc.
    }
}