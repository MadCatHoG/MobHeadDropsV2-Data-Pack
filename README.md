# MobHeadDropsV2 Data Pack for Minecraft 1.13
Mob Head Drops V2 Data Pack allows mobs to drop their heads on player kill. This project is a combination of my old Command Block contraption MobHeadDrops and Carl Poole's version of Xisuma's More Mob Heads.

To enable the datapack, copy the zip file under the releases directory into your map's "datapacks" folder. If your server is running, make sure to run /reload.

# Normal Rates

##Rare chance 0.8% L3
rare_chance={"chance"=>0.005, "multiplier"=>0.001}
rares=["enderman","zombie_pigman","blaze" ]

##Low chance 2.9% L3
low_chance={"chance"=>0.005, "multiplier"=>0.008}
lows=["cow","chicken","sheep","slime","cave_spider","drowned",
	"jebsheep","pig","mushroom_cow","cod","tropical_fish","salmon",
	"guardian","iron_golem","spider","squid","witch"]

##Mid chance 4% L3
mid_chance={"chance"=>0.010, "multiplier"=>0.013}
mids=["silverfish","magma_cube","skeleton_horse","ghast","husk","stray",
	"villager","pufferfish","vex","bat","phantom"]

##Mid-High chance 12.5% L3
midhigh_chance={"chance"=>0.05, "multiplier"=>0.025}
midhighs=["turtle","snow_golem","wolf","dolphin","mule","chargedcreeper",
	"endermite","ender_dragon"]

##High chance 36% L3
high_chance={"chance"=>0.09, "multiplier"=>0.09}
highs=["vindicator","evoker","shulker","wither", 
	"donkey"]

##Super high chance 69% L3
superhigh_chance={"chance"=>0.09, "multiplier"=>0.2}
superhighs=["polar_bear","zombie_horse", "elder_guardian"]

##More Mobs (Variations)
colored sheep = low_chance
zombie_villager = mid_chance
cats,horse,llama,parrot,rabit = midhigh_chance

##Shulker
Drops a minimum of 2 shells, 3 max


#Credits

From Carl Poole's Project credits to:
- minecraft-heads.com for the mob head resources
- xNitrate for the original 1.13 migration attempt
- carlpoole for refinements along the snapshot releases
- Veritas83 for the example of making a looping Minecraft function: https://github.com/Veritas83/minecraft-1.13-function-loop
- MadCat for help! Check out his data packs and youtube channel https://github.com/MadCatHoG & https://www.youtube.com/channel/UChjM6LjFpONx0xgefpmLK4A

MadCat's credits to:
- Carl Poole for putting together the pack, new heads and command updates from Minecraft 1.12 to 1.13.
- MadCat for a function overhaul to avoid using scoreboards and avoid running functions all the time.
