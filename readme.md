## NoFertilityParticles

Reliquary "Lilypad of Fertility" sends certain particles (villager happy, event 2005) to the client every time any plant is affected by any pad. In large farms this causes tens of thousands of packets to be sent every second effectively ddosing the players and even causing FPS drops with particles turned off. Players with a slow connection will not be able to log in or keep getting timed out. We prevent this event from firing entirely to put an end to this madness.