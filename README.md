Top-Down Adventure Game
Overview
A top-down perspective game inspired by The Legend of Zelda series. Developed in Unity, it features procedural dungeon generation, interactive objects, combat mechanics, and a health system.

Core Scripts
DungeonGenerator.cs
Purpose: Procedurally generates connected rooms and corridors.
Details: Uses a random walk algorithm to place rooms in different directions, ensuring they are connected.
InteractiveObject.cs
Purpose: Manages interactions with objects like doors, levers, and treasure chests.
Details: Provides player feedback (e.g., sounds or animations) for each interaction type.
PlayerCombat.cs
Purpose: Handles player attacks and health.
Details: Allows melee and ranged attacks, checks for enemy collisions, and calculates damage.
Enemy.cs
Purpose: Controls enemy behavior and health.
Details: Manages enemy health and triggers their destruction when HP reaches zero.
Key Mechanics
Dungeon Generation
Method: A random walk algorithm places rooms in a grid, with varied room types (e.g., standard, treasure).
Tilemap: Visualizes rooms using Unity’s Tilemap, creating a classic dungeon feel.
Combat
Attack Types: Melee (with range checks) and ranged attacks.
Health System: Both player and enemies have health points, with a game-over trigger for the player when health reaches zero.
Event Handling
Interactive Objects: Objects like doors and chests respond to player interactions.
Feedback: Sound and animation provide player feedback upon interaction.
