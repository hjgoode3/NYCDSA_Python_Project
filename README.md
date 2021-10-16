Data Set Information

Data was web scraped using Python's Beautiful Soup package from:
http://rotoguru1.com/cgi-bin/fyday.pl?game=fd

This project analyzes weekly fantasy football data across the platforms FanDuel, DraftKings, and Yahoo Sports.Weekly fantasy football consists of online contests in which you play against friends or get paired with random other competitors on the host website. The goal of the contest is to score the most points among your competitors.Points are scored based on a points system corresponding to the accrual of stats by individual players during NFL games. For each contest, competitors draft a team of players filling specific position types. For examples each team could be required to have 1 Quarterback, 2 Running Backs, 2 Wide Receivers, 1 Tight End, and 1 Defense. Each player has a salary in virtual dollars required to be paid to draft the player for the week. Each competitor has a budget of virtual dollars used to fill his team for the contest. Better players (who are anticipated to score a large number of points) have a higher salary cost associated with them. Contests are played on a weekly basis corresponding to a week of the NFL season. Once all NFL games for the week are played, the player who's team scored the most points is named the winner.

Columns

  Week:  Number 1 - 17 corresponding to the week of the NFL season a game took place

  Year: Number 2017 - 2021 corresponding to the year an NFL season took place

  GID: Generic ID used by the website as an index for the data.

  Name: Name of NFL player recording points in the contest

  Pos: Position of the NFL player recording points in the contest

  Team: NFL team the player recording points belongs to

  h/a: 'h' or 'a' designation for whether the game was played at home or away

  Oppt: 'Opponent' The opposing NFL team the player recording points was competing against

  FD points: Fantasy points the player recorded on the FanDuel platform

  FD salary: Virtual dollars required to draft a player for a contest on the FanDuel platform

  DK points: Fantasy points the player recorded on the DraftKings platform

  DK salary: Virtual dollars required to draft a player for a contest on the DraftKings platform

  YH points: Fantasy points the player recorded on the Yahoo Sports platform

  YH salary: Virtual dollars required to draft a player for a contest on the Yahoo Sports platform
