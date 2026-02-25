WOOD
Working title: We Observe Odd Disturbances
________________________________________
1. Overview
WOOD is a cooperative psychological horror game about working the night shift in a facility that slowly starts to fall apart.
One player watches the facility through CCTV cameras.
Other players work inside the building, fixing real physical problems.
The core twist is that the person watching the cameras cannot always trust what they see.
Some things on the cameras are real. Others are hallucinations.
Mistakes cost money.
Ignoring problems costs even more.
There is no PvP.
The tension comes from bad information, pressure, and limited time.
________________________________________
2. Platform & Technology
Engine: Unity
Platform: PC
Operating System: Windows
Controls: Mouse and Keyboard
Singleplayer and co-op
________________________________________
3. Project Goals (Near Term)
●	Release a singleplayer demo on itch.io

●	Create a Steam page with screenshots and a trailer

●	Produce short-form videos for TikTok, Instagram, and YouTube Shorts

●	Reach 10,000 Steam wishlists

●	Secure publisher funding for the next development stage (approximately six months of paid work)

________________________________________
4. Core Design Pillars
●	Asymmetrical roles with different information

●	Psychological horror driven by uncertainty

●	Constant time and money pressure

●	Communication as a core mechanic

●	No player-versus-player conflict

________________________________________
5. Player Roles
5.1 Manager (Observer)
●	Works from a separate control room

●	Spends the shift watching CCTV feeds

●	Spots and reports anomalies

●	Coordinates the team

●	Is the only player who experiences hallucinations

●	Can unintentionally harm the team by making wrong decisions

5.2 Handymen (Field Operators)
●	Move inside the facility

●	Repair real breakdowns

●	Deal with intruders

●	Confirm or deny what exists in physical space

●	Never see hallucinations

________________________________________
6. Singleplayer Experience
Singleplayer is the baseline version of the game.
The player controls one character and can switch freely between two modes.
6.1 Field Mode
●	The player is inside the facility

●	Breakdown repairs are done physically
6.2 Camera Mode
●	The player observes the facility through CCTV

●	Anomalies can be reported from this mode
To keep solo play manageable:
●	fewer breakdowns spawn

●	fewer anomalies appear
The main challenge is attention management.
Time spent watching cameras means other problems continue to get worse.
________________________________________
7. Core Gameplay Loop
1.	Observe CCTV feeds

2.	Notice something suspicious

3.	Decide whether it is real

4.	Report it or verify it
5.	Repair breakdowns

6.	Lose or earn money

7.	Repeat until the shift ends

________________________________________
8. Shifts and Win Conditions
One shift equals one round.
Each round lasts between 10 and 20 minutes.
Final duration is determined through playtesting.
The main performance metric is Pay.
8.1 Win Condition
The team wins if the final Pay is equal to or higher than the baseline payout.
8.2 Lose Conditions
●	Pay drops below the allowed threshold

●	(Future) the team is eliminated by threats
________________________________________
9. Pay System
●	Every breakdown causes an immediate loss of Pay when it appears

●	As long as a breakdown remains unfixed, it continues to drain Pay at regular intervals

●	Repairing a breakdown stops the damage and grants a cash reward

All balance values are adjusted through playtesting.
________________________________________
10. Game Systems Overview
Each system is described by:
what it is, why it exists, how it works, and how it appears in the game.
________________________________________
11. CCTV Camera Mode
CCTV Camera Mode is the main observation interface.
●	Displays multiple camera feeds

●	Uses a visible mouse cursor

●	Allows interaction with any point in the image

Cameras are the only reliable way to detect anomalies.
________________________________________
12. Reporting Anomalies
Reporting is the primary method of resolving anomalies.
●	The player clicks a suspicious location in a camera feed

●	A context menu opens with anomaly types

●	If the correct type is selected:

○	a short progress indicator appears

○	the anomaly is resolved

○	a brief visual glitch confirms success

●	If the report is incorrect:

○	a message indicates nothing was found

○	the player receives a penalty or cooldown

________________________________________
13. Anomalies
Anomalies are real, abnormal changes in the environment.
●	Each anomaly appears only once per shift

●	Most anomalies are resolved through reporting

Current anomaly types include:
●	Extra objects appearing

●	Objects disappearing

●	Objects changing

●	Objects moving

●	Intruders

●	Camera malfunctions

●	Unexpected text or labels

Players must decide whether to report immediately or verify first.
________________________________________
14. Hallucinations
Hallucinations are fake anomalies that exist only in the camera view.
●	Visible only to the Manager

●	Designed to look like real anomalies

●	Reporting them causes a Pay penalty

●	They disappear on their own after a short time

●	Optionally, pills can remove hallucinations instantly

Hallucinations exist to prevent report spamming and to force communication.
________________________________________
15. Breakdowns
Breakdowns are real physical problems inside the facility.
●	They appear over time

●	They immediately reduce Pay

●	They continue to drain Pay until repaired

Examples of breakdowns:
●	Loose bolts and mechanical issues

●	Floor stains and spills

●	Garbage that must be disposed of

●	Pipe clogs

●	Electrical and fuse failures

________________________________________
16. Tools (MVP)
●	Bolt driver - tighten bolts

●	Mop - clean stains

●	Furnace - dispose of garbage

●	Plunger - remove clogs

●	Fuse panel - restore power

●	Shotgun - deal with intruders

________________________________________
17. Intruders
●	Intruders can appear anywhere in the facility

●	They can be spotted on CCTV

●	Reporting an intruder does not remove it

●	Intruders must be dealt with physically using the shotgun

●	Reporting intruders is never treated as a false report

________________________________________
18. Communication
Communication is the main strategic layer of the game.
●	The Manager asks for confirmation

●	Handymen confirm or deny what exists in physical space

●	This is how the team distinguishes between real anomalies and hallucinations

________________________________________
19. Facility (MVP)
The MVP facility includes five monitored rooms:
●	Bathrooms

●	Basement

●	VIP Office

●	Gallery

●	Foyer / Lobby

All rooms are connected by corridors.
Additional areas:
●	One shared tool room

●	In co-op mode, a separate locked room for the Manager


