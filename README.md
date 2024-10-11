# bzbianca.github.io

# *About Me*

## My Interests

I like to play a variety of **video games** like *Valorant* while balancing school like learning how to ***program*** and **general academics**

### Setup List

* Monitor
* ~~PC~~
* Mouse
* Mousepad
* Keyboard

### Top 10 Letters
1. Z
2. V
3. B
4. R
5. O
6. L
7. W
8. T
9. Y
10. U

### To-Do List

* [] Homework
* [] More homework
* [x] Take a break
* [x] Eat food
* [x] Gaming
* [] Go outside
* [] Study
* [x] Procrastinate
* [] Figure out schedule
* [x] Make food

### GO-TO Websites
1. [Youtube](www.youtube.com) - Watch any video that interests me. Or use it for school or to learn something new.
2. [Roblox](www.roblox.com) - Go to website when I am bored. Or when a friend asks for me to join.
3. [Google](www.google.com) - When I need to search something up. Googling is probably the most useful site in this list.

## My Mermaid Charts

### How to Valorant
 
 ```mermaid
stateDiagram-v2
 HowtoManageRounds --> BuyPhase
 BuyPhase --> RoundStart
 RoundStart --> Won
 Won --> FullBuy
 RoundStart --> Lost
 Lost --> FullSave
 FullBuy --> BuyPhase
 FullSave --> BuyPhase

 HowToAim --> CrosshairPlacement
 CrosshairPlacement --> SeeEnemy
 SeeEnemy --> Microadjust
 Microadjust --> Shoot
 Shoot --> Strafe
 Strafe --> Microadjust
 ```

### How to Composition in Valorant

```mermaid
classDiagram
 note "Depends on map"
 Compositions <|-- Duelist
 Compositions <|-- Initiator
 Compositions <|-- Sentinel
 Compositions <|-- Controller
 Compositions: 1 Duelist, 2 Initiator, 1 Sentinel, 1 Controller
 Compositions: 1 Duelist, 1 Initiator, 1 Sentinel, 2 Controller(2nd)
 class Duelist{
        Jett
        Raze
        Neon
        Iso
        Phoenix(Flash)
        Reyna(Flash)
        Yoru(Flash)
 }
 class Initiator{
        Sova
        Skye
        KAY-O
        Fade
        Gekko
        Breach(No info gathering)
 }
 class Sentinel{
        Cypher
        Killjoy
        Chamber
        Sage(Can't flank watch)
        Deadlock(Can't flank watch)
        Vyse(Can't flank watch)

 }
 class Controller{
        Brimstone
        Omen
        Astra
        Clove
        Viper(Wall-Type)
        Harbor(WallType)
 }