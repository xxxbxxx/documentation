---
layout: default
title: Modes settings list
description: List of all the settings available in the Nadeo modes
tags:
- dedicated
- server
---

# TrackMania

## All (ModeBase)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_ChatTime**|15|Chat time at the end of the map|
|**S_AllowRespawn**|True|Allow the players to respawn or not|
|**S_WarmUpDuration**|-1|Duration of the warm up phase (<= 0 to disable)|
|**S_UseScriptCallbacks**|False|Turn on/off the script callbacks, useful for server manager|
|**S_UseLegacyCallbacks**|True|Turn on/off the legacy callbacks
|**S_ScoresTableStylePath**|""|Try to load a scores table style from an XML file|

## Cup (+RoundsBase)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_RoundsPerMap**|5|Rounds per map|
|**S_NbOfWinners**|3|Number of winners|
|**S_WarmUpDuration**|2|Duration of the warm up phase (<= 0 to disable)|

## Laps

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TimeLimit**|0|Time limit (0 to disable, < 0 automatic based on author time)|
|**S_ForceLapsNb**|5|Number of Laps (<= 0 to disable)|
|**S_FinishTimeout**|-1|Finish timeout (< 0 automatic based on author time)|

## Rounds (+RoundsBase)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_PointsLimit**|50|Points limit|
|**S_UseTieBreak**|True|Continue to play the map until the tie is broken|

## RoundsBase

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_PointsLimit**|100|Points limit|
|**S_FinishTimeout**|-1|Finish timeout (< 0 automatic based on author time)|
|**S_UseAlternateRules**|False|Use alternate rules|
|**S_ForceLapsNb**|-1|Force number of laps (<= 0 to disable)|
|**S_DisplayTimeDiff**|False|Display time difference at checkpoint|

## Team (+RoundsBase)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_PointsLimit**|5|Points limit|
|**S_MaxPointsPerRound**|6|The maxium number of points attributed to the first player to cross the finish line|
|**S_PointsGap**|1|The number of points lead a team must have to win the map|
|**S_UsePlayerClublinks**|False|Use the players clublinks, or otherwise use the default teams|

## TeamAttack

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TimeLimit**|300|Time limit|
|**S_MinPlayerPerClan**|3|Minimum number of players per clan|
|**S_MaxPlayerPerClan**|3|Maximum number of players per clan|
|**S_MaxClanNb**|-1|Maximum number of clans (<= 0 to disable)|

## TimeAttack

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TimeLimit**|300|Time limit|

# ShootMania

## All (ModeBase)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_AutoManageAFK**|False|Switch inactive players to spectators|
|**S_AFKIdleTimeLimit**|90000|AFK default idle time limit|
|**S_UseScriptCallbacks**|False|Turn on/off the script callbacks, useful for server manager|
|**S_NeutralEmblemUrl**|""|Replace the default neutral emblem by another one|
|**S_ScoresTableStylePath**|""|Try to load a scores table style from an XML file|

## ModeMatchmaking

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_MatchmakingAPIUrl**|https://matchmaking.maniaplanet.com/v5|URL of the matchmaking API. If you don't plan to use a custom matchmaking function leave this setting at its default value.|
|**S_MatchmakingMode**|0|This is the most important setting. It can take one of these five values : 0 -> matchmaking turned off, standard server; 1 -> matchmaking turned on, use this server as a lobby server; 2 -> matchmaking turned on, use this server as a match server; 3 -> matchmaking turned off, use this server as a universal lobby server; 4 -> matchmaking turned off, use this server as a universal match server.|
|**S_LobbyTimePerRound**|30|Duration (in seconds) of a round between the activations of the matchmaking function. It can't be smaller than 15 seconds.|
|**S_LobbyRoundPerMap**|60|Number of rounds played before going to the next map.|
|**S_LobbyMatchmakerTime**|10|Duration (in seconds) of the matchmaking function. It allows the players to see with who they will play their match or cancel it if necessary.|
|**S_LobbyInstagib**|0|Use the Laser instead of the Rocket in the lobby.|
|**S_LobbyDisplayMasters**|1|Display a list of Masters players in the lobby.|
|**S_LobbyAllowMatchCancel**|1|Allows or not the players in the lobby to cancel a match.|
|**S_LobbyLimitMatchCancel**|0|If the players are allowed to cancel, how many matches can they cancel before being penalized.|
|**S_MatchmakingErrorMessage**|An error occured in the matchmaking API. If the problem persist please try to contact this server administrator.|This message is displayed in the chat to inform the players that an error occured in the matchmaking system.|
|**S_MatchmakingLogAPIError**|0|Log the API errors. You can activate it if something doesn't work and you have to investigate. Otherwise it's better to let it turned off because this can quickly write huge log files.|
|**S_MatchmakingLogAPIDebug**|0|Same as above, turn it on only if necessary.|
|**S_MatchmakingLogMiscDebug**|0|Same as above, turn it on only if necessary.|

## Battle

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_RespawnTime**|6001|Time before respawn|
|**S_AutoBalance**|True|Use auto balance at the start of the map|
|**S_RoundsToWin**|2|Points to win a map|
|**S_RoundGapToWin**|1|Minimum gap between the two teams to win a map|
|**S_RoundsLimit**|3|Point limit on map|
|**S_TimeLimit**|300|Round time limit (seconds)|
|**S_CaptureMaxValue**|30000|Pole capture time (milliseconds)|
|**S_AlternativePoints**|False|Use atk and def points as score|
|**S_AllowBeginners**|False|Is a Beginners Welcome server|
|**S_AutoManageAFK**|True|Switch inactive players to spectators|
|**S_ArmorPoints**|2|Starting armor points for the players|
|**S_NbPlayersPerTeam**|5|Numpber of players per team in matchmaking|
|**S_UsePlayerClublinks**|False|Use the players clublinks, or otherwise use the default teams|

## Combo (+ModeMatchmaking)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_NbPlayersPerTeam**|2|Number of players per team (Max. 5)|
|**S_PointsLimit**|3|Points limit (0: No points limit)|
|**S_RoundTimeLimit**|300|Round time limit (0: No time limit)|
|**S_WarmUpDuration**|90|Warmup duration (0: disabled)|
|**S_AllowUnbalancedTeams**|False|Allow a game to begin without the same number of players in each team|
|**S_UseArmorReduction**|False|Reduce the armor of players above two armor points|
|**S_UsePlayerClublinks**|False|Use the players clublinks, or otherwise use the default teams|

## Elite (+ModeSport, +ModeMatchmaking)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TurnWin**|9|Number of points to win a map|
|**S_UseDraft**|False|Use draft mode at match beginning|
|**S_DraftBanNb**|4|Number of map to ban during draft|
|**S_DraftPickNb**|3|Number of map to pick during draft|
|**S_RequiredPlayersNb**|3|Number of players per team|
|**S_DisplayRulesReminder**|True|Display a window with the rules when the match begins

## Heroes (+ModeSport)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TurnWin**|10|Number of points to win a map|
|**S_TimePoleElimination**|10.|Capture time limit after defense elimination|

## Joust

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_RoundPointsToWin**|7|Round points to win|
|**S_RoundPointsGap**|2|Round points gap|
|**S_RoundPointsLimit**|11|Round points limit|
|**S_RoundTimeLimit**|0|Round time limit (<= 0 to disable)|
|**S_PoleTimeLimit**|45|Pole capture time limit|
|**S_MatchPointsToWin**|3|Match points to win|
|**S_MatchPointsGap**|0|Match points gap|
|**S_MatchPointsLimit**|3|Match points limit|
|**S_Matchmaking**|3|Use Joust with matchmaking|
|**S_MatchmakingSleep**|0|Matchmaking match end duration (-1: infinite)|
|**S_UsePlayerClublinks**|False|Use the players clublinks, or otherwise use the default teams|
|**S_UseLobby**|False|Launch server in lobby mode|
|**S_LobbyTimePerMap**|86400|Time limit in lobby mode (sec., 0: no limit)|
|**S_UseWarmup**|False|Start with a warmup|

## ModeSport

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_Mode**|0|Mode 0: classic, 1: free|
|**S_TimeLimit**|60|Time for an attack on a map|
|**S_TimePole**|15|Time allowed to reach the pole by the end of the attack|
|**S_TimeCapture**|1.5|Time to capture a pole for the attack clan (* NbPoles)|
|**S_WarmUpDuration**|90|Duration of the warmup (<= 0 to disabled)|
|**S_MapWin**|2|How many maps a clan has to win to win the match|
|**S_TurnGap**|2|Points lead necessary to win a map|
|**S_TurnLimit**|15|Maximum number of points before next map|
|**S_DeciderTurnLimit**|20|Points limit on decider map|
|**S_QuickMode**|False|Mutliplier for the sleep times between rounds|
|**S_UseLegacyCallback**|True|Send the old JSON callbacks|
|**S_Matchmaking**|False|Use Elite with matchmaking|
|**S_MatchmakingSleep**|0|Matchmaking match end duration (<= 0 infinite)|
|**S_UseLegacyCallback**|True|Send the old JSON callbacks|
|**S_UsePlayerClublinks**|False|Use the players clublinks, or otherwise use the default teams|
|**S_DisplaySponsors**|True|Display the sponsors of the attacker when spectating him|
|**S_RestartMatchOnTeamChange**|False|Restart the match after the warm up if the teams have changed|
|**S_Practice**|False|Play in practice mode|
|**S_PracticeRoundLimit**|3|Number of attack turns by player in practice mode|

## Melee

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TimeLimit**|6001|Time limit on a map. Setting a negative value disable the limit|
|**S_PointLimit**|25|Points limit on a map. Setting a negative value disable the limit|

## Realm

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_PoleCaptureDuration**|15|Duration of the pole capture|
|**S_PoleUncaptureSpeed**|3.|Speed multiplier for the uncapture|
|**S_UsePoleRegeneration**|False|Use pole regeneration|
|**S_SpawnTimeBase**|10|Time before respawn|
|**S_SpawnTimeIncrease**|5|Respawn time increment per minute|
|**S_SpawnTimeMax**|60|Maximum time before respawn|
|**S_MapPointsLimit**|2|Number of rounds to win a map|
|**S_MapPointsGap**|2|Minimum round gap between the two teams to win|
|**S_MapRoundsLimit**|3|Maximum number of rounds on a map|
|**S_UsePlayerClublinks**|False|Use the players clublinks, or otherwise use the default teams|

## Royal

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_MapPointsLimit**|200|Points to win a map|
|**S_OffZoneActivationTime**|4|Tornado activation duration|
|**S_OffZoneAutoStartTime**|90|Time before auto activation of the tornado|
|**S_OffZoneTimeLimit**|50|Tornado shrink duration|
|**S_OffZoneMaxSpeed**|1.25|Maximum speed multiplier for the tornado|
|**S_EndRoundTimeLimit**|60|Time limit after the tornado is completly shrunk|
|**S_SpawnInterval**|5|Time between each wave of spawns|
|**S_UseEarlyRespawn**|True|Allow early respawn|
|**S_EndMapChatTime**|20|End map chat time|
|**S_MultiClans**|True|Allow multi clans mode|
|**S_MinPlayersNbPerClan**|3|Minimum number of players per clan|
|**S_AllowBeginners**|False|Is a Beginners Welcome server|
|**S_AutoManageAFK**|True|Switch inactive players to spectators|

## Royal Exp (+Royal)

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_AllowDoubleCapture**|True|Allow a second pole capture after the first activation|
|**S_OffZoneMaxSpeedTime**|8|Duration of capture to reach maximum speed|

## Siege

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TimeBetweenCapture**|0|Minimum time between two captures (0 = unlimited)|
|**S_CaptureTimeLimit**|45|Time limit to capture one goal (0 = unlimited)|
|**S_CaptureTimeBonus**|10|Bonus time for capturing|
|**S_GoalCaptureTime**|1.|Time to capture a gate in seconds|
|**S_NbRoundMax**|5|Set a winner after xx rounds (0 = unlimited)|
|**S_MapsToWin**|1|Number of maps to win the match (0 = don't do match)|
|**S_WarmUpDuration**|0|Duration of the warm up round (0 = no warmup)|
|**S_ClanNbMinPlayers**|1|Wait until this minimum is reach before starting the map|
|**S_ClanNbMaxPlayers**|0|Do not spawn players beyond this limit, 0=no limit|
|**S_UseSuddenDeathMode**|True|Do not allow a team to win on first turn|
|**S_AutoBalance**|True|Use auto balance at the start of the map|
|**S_WeaponMode**|2|0: Rocket vs Laser, 1: WeaponSelection, 2: WeaponSwitch, 3: Store|
|**S_UseOldCaptureMode**|False|Capture only one gate per checkpoint instead of all the gates|
|**S_DefCanRevertCapture**|False|If true the defender can revert the capture by stepping on the gate|
|**S_CaptureThreshold**|300|Time (in ms) before the activation/annulation of the capture|
|**S_GatesStopDefenders**|True|Don't let defenders go through closed the gates|
|**S_AutoManageAFK**|True|Switch inactive players to spectators|
|**S_DisplayRulesReminder**|True|Display a window with the rules when the match begins|
|**S_UsePlayerClublinks**|False|Use the players clublinks, or otherwise use the default teams|

## SiegeV1

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TimeBetweenCapture**|45|Minimum time between two captures (0 = unlimited)|
|**S_CaptureTimeLimit**|15|Time limit to capture one goal (0 = unlimited)|
|**S_GoalCaptureTime**|5.|Time to capture a goal in seconds|
|**S_NbRoundMax**|5|Set a winner after xx rounds (0 = unlimited)|
|**S_MapsToWin**|0|Number of maps to win the match (0 = don't do match)|
|**S_WarmUpDuration**|0|Duration of the warm up round (0 = no warmup)|
|**S_ClanNbMinPlayers**|1|Wait until this minimum is reach before starting the map|
|**S_ClanNbMaxPlayers**|0|Do not spawn players beyond this limit, 0=no limit|
|**S_AutoBalance**|True|Use auto balance at the start of the map|
|**S_AutoManageAFK**|True|Switch inactive players to spectators|
|**S_DisplayRulesReminder**|True|Display a window with the rules when the match begins|
|**S_Matchmaking**|False|Use Elite with matchmaking|
|**S_MatchmakingSleep**|0|Matchmaking match end duration (-1: infinite)|
|**S_UsePlayerClublinks**|False|Use the players clublinks, or otherwise use the default teams|

## TimeAttack

|Setting|Default value|Description|
|:-:|:-:|:-:|
|**S_TimeLimit**|360|Time limit (in seconds)|
