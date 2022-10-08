# OrburierProject
Orburier is an UE5 network predicted gameplay framework. This is the main project.

The goal here is to create a generic framework base on which other systems can build on and interact over. This way Movement-/Abilitiy-/Combat-/Interaction-System could predictively interact with each other similar to abilities in the GamepalyAbilitySystem.

## WHY?
The GamepalyAbilitySystem is a great system for most cases, BUT it sometimes has problems when trying to combine abilities and movement in predicted environments.

## btw
I don't expect this to be finished... ever... not gonna lie...

# Structure
The systems are organised as plugins in their own git repository and will be included here as submodules. Every system gets its own test plugin (which again is organised as a standalone git repository) for automated tests under the "Tests"-subfolder.
This project will be used to develop all the Orburier-systems.
