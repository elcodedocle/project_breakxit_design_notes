# project_breakxit_design_notes

0.0.1RC1 GOALS

backend
json receives move, returns random RPS
frontend
form can send move, print player move, computer move, winner
player_bot -> autoplay button on frontend sends random move

X.X.XRC1 GOALS

Interfaces:
Strategy - get_next_move
Rules(matrix move_id x move_id)
Game(datetime, me, him)
Opponent - Game[] get_games(), get_game(gameid), push_game(Game), get_strategy
Player - set_opponent
WebRPS - game_id(/RPS/, /RPSLS/), player_id(optional), move(required)
validate move
validate player id

first strategy: random
second strategy: neural_network
