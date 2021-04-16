# InsSandstormMOTD
full project of a MOTD mod.

----------------------------------------
Files with "_T"_ after were for test version of MOTD and have some new features and debug options, one of testing features that never made it in is translation.
Main files inside (so req 100% and others can be deleted if you want) are:
MOTD_REEWORKED\Content\Other_Stuff --> MOTD_Info <-- actor that stores information from server, so it could be passed to the client and client could show it.
MOTD_REEWORKED\Content\Mutators --> Motd_N  <-- this mutator holds inside code for: allowing to be used in massacre gamemode and several other mods + it has detection for: if hardcore scenario, hardcore hud. Also, used to get information from your INI file to MOTD_Info actor.
MOTD_REEWORKED\Content\Huds --> BP_HUD_MOTD_N <-- hud that stores classic insurgency hud + motd hud
                            --> BP_Widget_Serverinfo_FInal_Aly <-- Main MOTD hud, this hud takes information from MOTD_Info actor and shows it to the user + handles on click events and other cool stuff. this hud is used everywhere, other stuff can be easily deleted or switched out how you want.
