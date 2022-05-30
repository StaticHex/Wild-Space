# Tech Demo

## High Level Goals

* Create player tutorial
* Implement basic mechanics for:
    * Hunting and capturing monsters
    * Using items
    * HUD and Main Menu
    * Player and player controls
    * Camera controls

## TODO List

☐ 3 Monsters (Iggy, Eyegore, and Anglurk) modeled, rigged, animated, and AI behavior programmed
☐ Environment for S. S. Humdinger (ship) modeled
☐ Tablet, CAPSULE, Crowbar, Power Bar (food), Psychosis Meds, and Bandages Modeled
☐ Player Modeled, rigged, and animated + player controls
☐ Camera controls
☐ Menu and HUD designed

## Basic Story / Flow

* Game starts with player on the ground (zoom in of player's face)
* Camera begins zooming out as player slowly gets up
* Player puts hand over side and pulls hand away to reveal blood
* *ding noise (email)*
    * No HUD at this point
    * Game will not progress until player checks computer
* Player checks computer, email pops up. *Hey Gary you there?, I tried messaging you but got no response. When you get a chance can you check the stasis tanks? I'm getting some really weird readings and just want to make sure everything's OK. We don't want any of the acquired test subjects to escape or anything. Anyway I'm sure it's nothing; but check if you get the chance. Oh, also, mot sure if you noticed yet but I fixed that tablet like you asked, I put it on one of the tables in the lab. - J. T.*
* Game waits for player to find and pick up tablet
    * Game will not progress until player picks up tablet
    * Once tablet is picked up; HUD shows. Stress will be mid level, food meter is low and HP is low
* Tablet displays a message *WARN: Minor injury detected, scanning room ...*
    * Progress bar (fx only, not actually doing anything lol)
    * After a second *Medical box found, recommend applying first aid immediately*
    * Medical box targeted here, game doesn't progress until medical box is picked up
        * Once picked up, player's health rises
* Tablet makes a ding and opens menu. The section labeled "Taxonomy" opens. 
    * 3 records exist with blacked out silhouettes
    * The first one (Iggy) opens along with a radar screen showing some light blips. Message explains *By pressing the "track" button, you can hunt down monsters using various clues left by that creature in the environment*
        * Game does not progress until player chooses "track"
* Radar appears in upper right corner of screen, as player moves around the lab, the blips get brighter and darker. When a player gets close enough they get the option to "scan". There are 3 clues for Iggy in the lab
    * Spines scattered near where the player started
    * Claw marks on one of the walls
    * A dent in the lab doors
* Once all clues are found a cutscene triggers, Iggy jumps out from behind the tanks. 
* Tablet informs player how to cycle through items and to use capsules to capture monsters
    * Also explains CAPSULES are a special type that can be used as many times as needed and that real CAPSULES can only be used once
* Once Iggy is captured it drops a power bar
* Player walks up to door and swipes ID card, door tries to open and then smokes
* Tablet *WARN: Door malfunction detected, recommend manual override*
* Crowbar targeted
* If player tries to pry open door without eating first, they will fail. If this happens 3x tablet will warn player
* *WARN: Low blood sugar detected, recommend eating something to reduce fatigue* (inventory cycles to power bar)
* After eating, stamina goes up, and door can be opened, but doing so reduces stamina again slightly
* Player enters reactor room. 
* Tablet *WARN: Bio-signature detected, be advised stun baton will not work on larger adversaries*
    * Stress rises triggering psychosis.
* Tablet *WARN: High level of mental stress detected, use provided pharmaceuticals to help manage stress levels* 
    * Scrolls to psychosis meds.
    * Game will not progress until meds are taken, stress continues to rise slowly at this point. If player waits too long (like really long 5 - 10 min) they will pass out from stress which resets to half (does not kill).
* Cutscene of Eyegore bashing through left hallway leading to cafeteria
    * Game will not progress until player follows Eyegore
* Upon entering the cafeteria, a table flies at the player and they dodge out of the way. Tables are thrown against wall leaving a large open area.
* Tablet *INFO: Some monsters will require clever use of the environment in addition to tools.*
    * Can use the tranquilizer gun on the wall
    * Can hit one of the pipes to release steam
        * NOTE: Upon hitting Eyegore with steam it will take damage, however at this point it will also be stunned momentarily allowing the player to hit it with the stun baton (give a warning about this or let the player discover it?)
* Once Eyegore is sufficiently weakened it flies back into the reactor room. Following it reveals it sleeping. Can throw a capsule and capture it now.
* Once Eyegore is captured a loud "clang" sound is heard, player looks backwards towards lab.
* Going back into the lab reveals the grate to the air conditioner is off and there are now scratches on the walls. 
* Moving close to the crates will bring up a "scan" option. Scanning will activate a cutscene where the player climbs on top of some crates in the corner of the room and scans the claw marks. The player will then look into the vent and climb inside. The player drops down into the other hallway which the player does not have access to. 
* Cutscene triggers, lights change to emergency lights and siren begins to blair. Lights appear moving along the wall behind player. Anglurk jumps on top of player attempting to bite throat, but player holds mouth open with crowbar. Stressful music here ramping up, screen freezes and fades.
* End of demo
    * Thank player for playing
    * Mention some of the features we plan on adding
    * Links to twitter and website
    