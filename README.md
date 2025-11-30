===============================================================
                    
                    MINI 2D SHOOTER PROTOTYPE
                     C++  /  SFML FRAMEWORK
                     
===============================================================

Project Summary:
    A small 2D shooter prototype built with C++ and SFML.
    Features a player character, weapons system, bullets,
    tile-based map, and a simple game architecture.

---------------------------------------------------------------
 HERO SYSTEM
---------------------------------------------------------------
    Class: Hero (inherits from Entity)

    • Movement, jumping, gravity simulation
    • Frame-based sprite animation
    • Direction handling (left / right)
    • Visible hitbox for collision debugging
    • On-screen health rendering

---------------------------------------------------------------
 WEAPONS & BULLETS
---------------------------------------------------------------
    Weapons:
        • Abstract class "Weapons"
        • Virtual method: shoot(...)
        • Implementation: WeaponsKalashnikov

    Bullets:
        Class: Bullet
        • High-speed movement using deltaTime
        • On-screen boundary checking
        • Accurate FloatRect collision area
        • Direction-based velocity vector

---------------------------------------------------------------
 MAP SYSTEM
---------------------------------------------------------------
    • ASCII level stored in arr[]
    • Tiles converted into sprite objects
    • Collision tiles stored in collisionTiles
    • Simple and readable map structure

===============================================================
