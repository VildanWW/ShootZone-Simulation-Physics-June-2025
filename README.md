🎮 Mini 2D Shooter Prototype (C++ / SFML)

This project is a small 2D shooter prototype built with C++ and SFML. It includes a basic game architecture with a player character, map collisions, weapons, and bullet systems.

🔧 Project Structure
Hero

Implemented in the Hero class (inherits from Entity)

Movement, jumping, gravity simulation

Sprite animation using frame-based updates

Direction handling (facing left/right)

Hitbox for simple collision checks

Health rendering on the screen

Weapons & Bullets

Abstract base class Weapons with a virtual shoot() method

Concrete weapon: WeaponsKalashnikov

Bullet class provides:

High-speed movement with deltaTime

Visible area check (isOffScreen)

Accurate collision bounds (FloatRect)

Map System

ASCII map layout stored in arr[]

Tile generation using shared sprites

Collision tiles stored in collisionTiles

Simple and readable level structure
