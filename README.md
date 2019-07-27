# Project Apogee

## Description

Project Apogee is a multiplayer procedural space sandbox game with a focus on
complex interconnected simulation systems. At the core of the experience are
simulated, player programmable, computer systems based on real historical
architectures. These computers drive the majority of the in-game systems and
award a huge amount of creative freedom to players by letting them program how
various aspects of their ships and other in-game equipment work. Ships are both
customizable and upgradeable and will operate under newtonian physics models.
Players can engage in mining, scavenging, trading, crafting, combat, and many
other dedicated roles.

## Computers

Project Apogee features the following three historic computer architectures,
each with its own specific use case. The advantage of using existing
architectures is that players can compile and use existing real world software
on these in-game machines, as opposed to having to write everything from
scratch.

* [PDP-11](https://en.wikipedia.org/wiki/PDP-11)
* [Data General Nova 1200](https://en.wikipedia.org/wiki/Data_General_Nova)
* [RCA CDP1802](https://en.wikipedia.org/wiki/RCA_1802)

The PDP-11 is the most powerful of the three systems. It has incredible
scalability and can control an huge quantity of I/O devices. This computer
system can occupy an entire room and requires an enormous amount of power to
run. It is most commonly found on the largest ships in the game as a result.

The Data General Nova 1200, while not as scalable as the PDP-11, is still very
powerful in its own right. Still requiring a considerable amount of power to
run, yet far more compact than the PDP-11, this computer is the perfect middle
ground of size to computing power. This system can be found in small, one or two
person, ships such as planetary landers, mining ships, and fighter ships.

The RCA CDP1802 is a comparatively tiny system, requiring only a small amount
of power to operate. Unfortunately, this relegates the system to
non-computationally-intensive tasks such as controlling the player's spacesuit.
As such, it can most commonly be found in small, man-portable, pieces of
equipment.

## Ships

There are two main types of ships in Project Apogee: large and small. All ships
obey a realistic newtonian physics model and are entirely controlled by their
respective onboard computer systems. Each ship features external components such
as engines, weapons, sensors, radio, radar, and reaction control systems. These
can be swapped out and upgraded by the player to improve that ship's
capabilities. Components are what the computer interfaces with to control the
ship. Both types of ships use their computer systems to facilitate [fly by wire](https://en.wikipedia.org/wiki/Fly-by-wire) 
capabilities. Pilot's control instruments such as the throttle, and flightsick
have their statuses periodically read by the computer. These statuses are then
translated into the correct thruster movements needed to maneuver the ship.
Due to the highly programmable nature of these computer systems, it is entirely
possible for players to create fully autonomous ships.

Large ships offer a high degree of customization to the player. The entire
interior of the ship can be reconfigured to suit the player's needs. Players
can optimize the internal layout of their ship to increase the performance of
certain tasks and external components. These components are controlled by the
ship's on-board PDP-11 computer system. Large ships are intended to act as bases
of operation for players and are not capable of landing on planets. Only large
ships are equipped with faster than faster than light capabilities.

Small ships are geared towards specific tasks such as mining, fighting, or
landing on planets. These ships do not have a walkable interior. Instead they
have small cockpits that can fit one or two players. The ship's components are
similarly controlled by the small ship's onboard Data General Nova 1200
computer system.
