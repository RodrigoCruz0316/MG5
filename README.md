# MG5
## Devlog
1.I think its advantageuos to use a Navmesh compared to scripting a characters movement depending on how the game setup is. If we look at Navmesh, its better to use it when you need your character to move around places based on how the level is set. It works best by telling your character where to go such as if they need to go through something. One game I can think of can be Resident Evil 4 where the infected can go through buildings and tells them where to go and what to avoid. It would not make sense to use Navmesh when making something that is fast paced requiring different animations and physics. One game I can think of where Navmesh doesn't make sense can be Fifa. In the game the characters movements rely on various physics such as how the player interacts with the ball or other players. In this case you're not telling the players to move to this spot, you are requiring your players to move constantly meaning navmesh wouldn't make sense for this. Overall it's better to use Navmesh when asking character's in a game to go from one point to another while it would not make sense to use it when you're asking for different physics of your characters where everything moves quickly. 

2.After fixing the loop, when looking at Vector3.Distance it is figuring out the distance between the birds and player. In the if statement, the birds in _birds if they are close to the player will move away. It uses _interactDistance to decide when the birds will run away from the player. If it notices that the player is away from the birds, they won't move. The statement works by checking the players distance from the bird and as the player nears them, they run away. 

https://pearl-carp.itch.io/mg5

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)