# IMP Functions

1. Self
```self.search_depth = search_depth 
self.score = score_fn
self.time_left = None
self.TIMER_THRESHOLD = timeout
```
1. game
```apply_move(move)
copy()
forecast_move(move)
get_blank_spaces()
get_legal_moves(player)
get_opponent(player)
get_player_location(player)   
is_loser(player)

is_winner(player)
move_is_legal(move)
utility(player)
        Returns a floating point value: +inf if the specified player has won the game, -inf if the specified player has lost the game, and 0 otherwise.
```
        
