0.1.21 (DAY 199)
- fixed the 'new!' notification reappearing on every join 
- fixed the raycast not lining up with the ui panels in the lobby
- minor lighting fixes

0.1.20 (DAY 197)
- there are 3 people who may already know where the thing i added is, and if any of them get it first it is rigged to self destruct and never come back via persistence you have been warned
- this changelog is now loaded from github
	- updates now come with an in-world notification
- fixed elevator lighting
- i might be maintaining this world instead of cleaning my room

0.1.19 (DAY 194)
- snowballs picked up from snow poffs now scale appropriately to the player
- started adding functionality to doors
- fixed an issue where if your avatar height was too small, you could't hold a snowball without eating it
- improved the development pipeline and probably broke some things but this means new changes will be easier yay!

0.1.17 (DAY 86 - 190)
- rebaked lights since glim has ao now
- updated post-processing (custom tonemapping) 
- fixed mysterious lantern emerging from the ground at the start of daily
- hopefully fixed broken mirror on quest

0.1.16 (DAY 73-85)
- added synced music with random order based on the day
- started construction on train
- added a picnic blanket and a lantern... somewhere
- fixed extra settings panel under lobby??
- fixed changelog scrollable area being wrong, it adapts now yayy

0.1.15 (DAY 72)
- added graphics settings!
- upgraded light volumes
- several optimizations
	- improved effectiveness of static batching
- in certain conditions, frames may improve by up to 200% avg :)

0.1.14 (DAY 25 - 71)
- forgot we had a changelog oops
	- this is like several months range and a bunch of stuff is left out probably
- added twinkle in the sky when you throw someone out of bounds
- added fork and spoon
- added mini snowball

0.1.13 (DAY 24)
- fixed music system
- fixed some lighting / sound issues that arose on return from [REDACTED]
- added an elevator call button

0.1.12 (DAY 22)
- added daily message submit guide
- i forgot

0.1.11 (DAY 18) 
- better performance on quest!
	- disabled light volumes for now, made it like 10x better (at least on quest pro)
	- some material optimizations

0.1.10 (DAY 17)
- fixed big snowball not exploding properly
- fixed missing snow crate mesh
- snowball (cat) is now aware of gravity direction
	- this is important and productive i swear
- optimized day counter and timer
	- no longer runs in update, yay

0.1.9 (DAY 16)
- re-enabled changelog!
- added flickering to daily message sign
- made snowyinator despawnable so it doesn't get lost
- reworked elevator animator so sound effects can be added (small issues likely)
	- also added hum sound while its moving but this is temporary
- elevator now automatically takes you to lobby
- fixed fog not changing in other levels

0.1.8 (DAY 11)
- added daily messages in lobby
	- happy birthday ashley!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
- half-fixed snowballs not showing up for remote players when grabbed
	- they're just a little out of sync now (until dropped & again)

0.1.7 (DAY 9)
- snowballs now properly collide with players
- switched to SmartObjectSync
	- this seems to have fixed the issue where snowball grabbing doesn't work at first!
- fixed handheld snowyinator not being very effective over network
- fixed the daily counter updating after <>< daily instead of ❄️ daily 
- probably broke the big snowball

0.1.6
- fixed snowballs exploding early over network 
- other stuff (i had exams this week and stopped updating the changelog)

0.1.5 (DAY 7)
- snowball (cat) and mute cube will now get lost less often
- other stuff (i had exams this week and stopped updating the changelog)

0.1.4 (DAY 6)
- quest compatibility!
- revamped timer with LED screen & glitch effect
- other stuff (i had exams this week and stopped updating the changelog)

0.1.3 (DAY 4)
- added more signatures
- fixed despawnable causing constant network clogging 
- other stuff (i had exams this week and stopped updating the changelog)

0.1.2 (DAY 3)
- Fixed text alignment in daily vrchat counter being like 2 degrees off
- Fixed some missing colliders

0.1.1 (DAY 2)
- Fixed daily VRChat counter **ERR**O**R**
- Fixed missing ice collider
- Restored elevator autonomy
- Added more gaps

0.1.0 (DAY 1)
- Daily VRC counter
- Chimney warping
- Handheld Snowyinator
- Added the sun
- Added snow piles to grab snowballs from
- Added snowball (cat)
- Added find your friends player teleport
- Re-added clouds
- Music zone priority implemented
- Removed general process autonomy
- Temporarily relocated Paul 
- a bunch of stuff i forgot probably

0.0.2  (DAY -34)
- Added dialogue system prototype
- Added wavering effect to fire point light volumes
	- this is optimized so that it only runs when you can see the light
- Added changelog ui to world
- Removed font tag from dialogue for the time being since idk how to get vrc to know where the font assets are
- Made ObjectManager work better again maybe hopefully

0.0.1  (DAY -36)
- Started changelog
- Allowed the snow factory to fire at specific players
- Snowballs can now hit players (maybe, untested lol)
- Added a trail to snowballs
- Added solidified silence
- Made it harder to get stuck on the walls while falling through a certain location
- Optimized particle star shader 
	- reads star positions from a pre-computed texture 
	- renders on background only
- fixed big snowball lag spike
- fixed imposter snowballs exploding instantly on drop
- custom json playerdata management
- ObjectManager is easier to use and more optimized
	- builds object pools from prefabs on build, so they don't have to be made manually
	- identifies objects by source instance id rather than by name

0.0.01 (DAY -92)
- closed beta uploaded






















 (  •   • )
