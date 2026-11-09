# MG5
## Devlog
Put your Devlog here.


1. NevMesh fit the game that need automatically route, which by giving destination and player automatically walk to the place. However, the script or rigidbody need a tactile movement which player need refine every single movement to complete the game. Thus, the game most suitable for NavMesh is Stardew Valley which need NPC to automatically found their way. However, the game 3D platform jumping game like Mario is more suitable for scripting a character’s movement.

2. Vector3.Distance() is used to count the distant between player and birds. When the "if" conditions is true, the RunAway will be called. In this case, the birds have a distance less than _interactDistance will automatically run away from player. This is same as drawing a circle which have a radius that is _interactDistance to judge whether the bird is scared or not.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
