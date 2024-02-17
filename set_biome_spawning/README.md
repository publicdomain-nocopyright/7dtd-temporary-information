> Early open source of spawning modlet by request of sinkingsun690.

These ways are used to achieve more zombies in the overall world on 7DTD Vanilla Public Server

Instructions:
1. Paste the mod from the `mods` folder into your own **dedicated server** or even your **7DTD Client**..  
2. Restart the dedicated server (or your 7DTD Client if you applied this mod to your client only).  
3. Connect to your dedicated server as a player; or play/continue existing single player world.
4. You should immediately see changes of zombies spawning in the whole biome.  
5. If zombies were killed around you before joining, it might takes up to ~4 in-game hours for new zombies to appear in the kill zone.  
   1. Walk around to some way further places to see zombies spawning. Sometimes you have to stop for 4-10 seconds and wait for zombies to appear while walking on a dedicated server if the ping is higher than 4ms. The usual player ping is around 24ms.  

### Advanced

`serverconfig.xml` changes are not needed for improvements to be visible,  
but it's recommended for Dedicated Servers that have more players than 2-3 online.  

![image](https://github.com/publicdomain-nocopyright/7dtd-temporary-information/assets/21064622/9cee9bc3-8ea2-42e9-b516-0d3cf1e8d45d)
> As can be seen on this live Dedicated Server 6 players were able to spawn active 60 zombies at the moment of taking picture.  
> This seems to be the moment where the further changes might be required to make sure the spawning is smooth and not limited.  

Find these lines:
```
<property name="MaxSpawnedZombies"				value="64" />	
<property name="MaxSpawnedAnimals"				value="50" />
```

Change to:
```
<property name="MaxSpawnedZombies"				value="164" />	
<property name="MaxSpawnedAnimals"				value="150" />
```

And it should be fine for at least 5-10 active players.
