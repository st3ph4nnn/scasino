# scasino

scasino (schizo-casino) is a fully fledged casino-like game to play.

the game features:

- casino-like currency (money and credits, 1$ = 3KR);  
- real casino-like games to play;  
- few minigames (named originally jobs, for in order to get money, there is no other way);  
- cloud config saving based on hardware id;  
- leaderboard feature (based on balance and stats) to compete with other people;  
- neat graphics (minimalistic, but they look cool);  
- anti-cheating system so everyone plays fair (not perfect, but it will stop memory value editors 90% of the time)  
- lightweight usage on resources (tested on windows 10 with I3-4030U 1.8 GHZ and 8GB DDR3 RAM; about 3% cpu usage and 50MB ram)  
- relatively old hardware support (though has to be 64-bit; minimum INTEL HD 2000 iGPU and a fairly bad-decent CPU);
- cross play ability (currently only supports linux and windows)
- ... more to come

# quick start

### linux (any kind)
just download the latest linux release, open a terminal and use ./scasino to play.

### windows
download the latest windows release (in form of a zip file) and extract it somewhere.  
WARNING! both of the dll files MUST be in the same directory as the executable  
double click the executable.

# FAQ

1. how do i open it?
- see quick start

2. if i upgrade my PC, will i be able to still have my config file?
- yes, you can upgrade some parts, including ram, storage drive, gpu, but not the cpu.

3. will there be a mobile version?
- no. not in the near future.

4. why the game does not open?
- restart your PC. there is a very rare flaw i cannot fix unfortunately.

5. can i play offline?
- no. maybe i will make a mode in the future.

6. will this game ever be open source?
- currently no. it features an anti cheat system, and it is played online. releasing an open source release will be help hackers to reverse engineer the game. Maybe in the future i will make a open source release, where you can only play by yourself.

# backstory

scasino became as an idea back in 2021, and firstly the development had begun by using a terminal.    
Yes, there were no graphics or such. We have built everything from scratch (including a UI) back then. We managed to make  
a game that was playable, but never released. After some time we scrapped the idea, until i found raylib.  
That got me into graphics and such stuff, and more into game developing. For about 2 months on working off and on    
we got to a stable release using raylib. If you want to check more of my raylib games, check my other repos

