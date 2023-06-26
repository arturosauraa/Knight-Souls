# Knight Souls
 This is a prototype game made in Unreal Engine 5.1.1.
 It is a game in which the character has a sword and a shield and fights against an AI which combats with a sword.

 PLAYER
 The player has an Animation Blueprint with a locomotion system and a targetlocked enemy system. This allows the player to move freely around the map and also engage with the enemy with a specific locomotion. It also has to BPC which are the attack system and player statistics. The first one is for the player to attack with the sword and the second one is the system that is in charge of the statistics of the player, such as health, stamina and leveling up.
 AI ENEMY
 This AI has a behaviour tree with multiple tasks and a service to patrol around the map, follow the player, have a attack range and attack against the enemy. The AI also contains the two BPC of the player to have a health system and attack system.
 
