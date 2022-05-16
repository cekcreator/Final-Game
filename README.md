Compile runs: 
	g++ game.cpp Attack.cpp Enemy.cpp Character.cpp Bag.cpp Map.cpp Stats.cpp Stat.cpp -o main

Dependencies: 
	Need all the cpp files for the game to work and the txt file 
  
Project details: 
	This project is based of the game Elden ring, obviously not as in depth as the real game. 
    The game allows players to choose between the a knight and a mage, allows them to set the name of their player as well. 
    The game takes you through different parts like the dark cave and the castle. 
    The dark cave you have to make through and you find runes. Going to the castle, you encounter your first battle. 
    Every battle has a health bar and an option to attack or heal. Attacking has a 30% of doing a critical hit of 45 damage. 
    Every enemy does the 5 more damage to you for the reason of healing or hoping for a critical hit. 
    After killing the first knight you can go through the castle. 
    There are two maps here, the first map is simply navigating the castle, the second map has you sneak around
     a disgruntled knight, if you hit the misfortune locations you will be forced the knight.
    After this fight you then fight the final boss. 
    After every fight if you die your stats are always added to the file “stats.txt. 
    After every fight you have the option to heal for the next fight. 
    Other menu options allow you read the last players stats, enter a name and read their stats, and the best stats overall for each category. 
