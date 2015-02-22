#  Dishonored Cuhrayzee mod
The goal of this mod is to motivate and inspire players to experiment with the game's already excellent mechanics and accomodate the damage output that this comes with. It uses the excellent Dishonored Ultimate Difficulty Mod by JDV as a base since most of the changes it makes are also applicable to what i want to achieve with this mod. This mod will be focusing on the raw action-game aspect of dishonored. 

*update* 
Unsatisfied with the main game's hitstun combo potential I went apeshit on every value I could find that changed things to my liking. The result is that i learned a lot and blink in particular is now a lot more snappy. You can do 2 in the air, with a slight falling damage as a consequence. Also it's possible to blink strike bounce off an enemy and hit him while bouncing, the first combo I consider a real combo. 

- updated to-do list




*update* 23-09-2014
 When testing the previous version i noticed that even though i lowered mana cost to 0, the mana recovery you get from using   
 powers is still intact. It is my plan to disable this mana recovery and add some cost for the overpowered powers like Blink 
 and Time Bend, and leave it intact for others that are less often used such as rat summon, and possess. This way i hope to 
 motivate players to use a variety of powers. 
 The problem is i do not know what file to edit to find these settings.



*update* 21-09-2014
- 5] made mana cost 0 across the board. 
- 6] lowered rune cost to 2 and 4 for all powers.
- 7] increased ammo capacity to 5000

*update* 16-09-2014
-  6] Lowered Rune cost for enhancements
- 11] Restored pistol spread, but it doesn't hit grenades




--------------------------------

top priority to-do:
-  1] Increase Enemy hp by a very large amount.
-  2] disable assassination attacks. 
- 14] figure out if a certain stun animation does not allow ass.attacks
- 15] stunned enemies that are hit need to be stunned again (how? probably hex)
- 16] Make wind blast throw enemies upward and not forward as a juggle starter

Medium Priority to-do:
-  8] Increase gadget # added upon pickup and buying.
- 13] Disable mana recovery on blink and Time Bend, increase their mana cost to 20 and 30 respectively.
- 17] polish blink more by lowering range and tinkering with close collision distance, speed, step distance, etc values
- 18] enable instant power switching without gfx glitches

lower priority to-do:
-  9] add more enemies.
- 10] add 1 invincible enemy at the hound pits pub to practice on.
- 12] find other .ini options that could enhance this gameplay style.
-  4] grant all weapon blueprints at the start of the game.
-  3] disable instant kill areas like the garbage bin and some roof areas.

undecided ideas list:
- change the use of sleep darts. maybe a stun effect
- change both blink levels to be more combat emphasized. far lower range.
- Change wind blast 2 to do less damage
- remove adrenaline piss filter
- change strafe movement speed to allow sideways dodging
- remove turning speed changes when running
- increase player hp
- tweak sliding damage to be more useful as an attack
- lower falling damage with agility levels 0
- Look into effects of stun length. 




# Installation

Please backup these folders before you make any changes!!!


Extract the contents of ini edits into: (After copying the .ini files, set them to read-only!)

    %userdirectory%/My Documents/My Games/Dishonored/DishonoredGame/Config

Extract the contents of upk edits into:

    \dishonored\dishonoredgame\CookedPCConsole\









# Changes from the original mod by JDV: (ignore this)

## AI.ini

	[DishonoredGame.DishonoredGlobalAIManager]
	m_bCorpseCleanupInView=True --> False
	m_BullyCooldownPeriod=(m_fMinValue=3 --> 6, m_fMaxValue=8 --> 12)
	m_CorpseAbsoluteMaximumCount=10 --> 50
	m_CorpseIdealMaximumCount=5 --> 45
	m_fGroupDistance=1000 --> 2000
	m_fUpdateTime=1 --> 100
	m_ReactionDelay=(m_fMinValue=0.18 --> 0.12,m_fMaxValue=0.30 --> 0.20)
	m_TetherDelay=(m_fMinValue=6 --> 3, m_fMaxValue=8 --> 6)
	
	[DishonoredGame.DishonoredSearchCrumbsComponent] 
	m_fChanceOfPsychicSearch=0.25 --> 0.75
	m_fCrumbLifetime=150 --> 150
	m_fDistanceBetweenCrumbs=800 --> 1200
	m_fMaxWanderStep=1000 --> 1500
	m_fMinWanderStep=500 --> 750
	m_fStickyProxyDuration=1 --> 2
	m_fWanderAngularRange=60 --> 75
	m_iNumSearchCrumbs=25 --> 50
	
	[DishonoredGame.DisAINoiseManager]
	m_LoudnessDistanceArray=0.000000
	m_LoudnessDistanceArray=200 --> 400
	m_LoudnessDistanceArray=300 --> 600
	m_LoudnessDistanceArray=400 --> 800
	m_LoudnessDistanceArray=500 --> 1000
	m_LoudnessDistanceArray=600 --> 1200
	m_LoudnessDistanceArray=800 --> 1600
	m_LoudnessDistanceArray=1000 --> 2000
	m_LoudnessDistanceArray=1200 --> 2400
	m_LoudnessDistanceArray=1500 --> 3000
	m_LoudnessDistanceArray=2000 --> 4000
	m_LoudnessDistanceArray=2500 --> 5000
	m_LoudnessDistanceArray=3000 --> 6000
	m_LoudnessDistanceArray=4000 --> 8000
	m_LoudnessDistanceArray=5000 --> 10000
	m_LoudnessDistanceArray=6000 --> 12000
	m_LoudnessDistanceArray=0.000000
	
	[DishonoredGame.DisGlobalCombatManager]
	m_fInhibitionTimeAttractSpell=15 --> 7.5
	m_fInhibitionTimeBackStep=8 --> 4
	m_fInhibitionTimeGrenades=10 --> 5
	m_fInhibitionTimeGrenadesWhenUnreachable=5 --> 2.5
	m_fInhibitionTimeJumpAttack=3.0 --> 1.5
	m_fInhibitionTimeLongAttack=0.8 --> 0.4
	m_fInhibitionTimeMediumAttack=1 --> 0.5
	m_fInhibitionTimeShortAttack=2 --> 1
	m_fInhibitionTimeSideStep=6 --> 3
	m_fInhibitionTimeStepBackAttack=1 --> 0.5
	m_fInhibitionTimeTeleportSpell=10 --> 5
	m_fInhibitionTimeThrowRocks=5 --> 2.5
	m_fInhibitionTimeWeeperArmGrab=20 --> 10
	m_fInhibitionTimeWHArmAttack=8 --> 4
	m_fInhibitionTimeWHJumpAttack=30 --> 15
	
	m_InnerSkirmishCaps[0]=1 --> 2
	m_InnerSkirmishCaps[1]=2 --> 3
	m_InnerSkirmishCaps[2]=3 --> 5
	m_InnerSkirmishCaps[3]=3 --> 6
	m_TotalSkirmishCaps[0]=2 --> 4
	m_TotalSkirmishCaps[1]=3 --> 6
	m_TotalSkirmishCaps[2]=4 --> 7
	m_TotalSkirmishCaps[3]=4 --> 8

## Camera.ini

	[DishonoredGame.DishonoredCamera_Lean]
	m_fMaxLeanAngle=15 --> 4
	m_fMaxLeanAngle_Crouched=15 --> 4
	m_fMaxLeanSoftenAngle= 4 --> 2
	m_fMaxLeanSoftenSpeed= 4 --> 2
	
## Engine.ini

	[FullScreenMovie]
	bForceNoStartupMovies=false --> true

## Player.ini

	[DishonoredGame.DishonoredPlayerPawn]
	m_fVisRegionTopHeight_Crouched=40.000000 --> 100
	m_fOffscreenMeleeDamageReduction[0]=0.5 --> 0
	m_fOffscreenMeleeDamageReduction[1]=0.5 --> 0
	m_fOffscreenMeleeDamageReduction[2]=0.5 --> 0
	m_fOffscreenMeleeDamageReduction[3]=0.5 --> 0

	[DishonoredGame.DisThreatPerceptionComponent]
	m_fEngagedThreatRadius=700 --> 3000
	m_fThreatPredictionTime=1 --> 0.25
	m_fUnawareThreatRadius=400 --> 2000

	[DishonoredGame.DishonoredPowersComponent]
	m_Powers=(m_Name="Vitality",m_eUISelection=eDisUISelectionType_Vitality,        m_Levels=((m_RuneCost=0,m_Modifiers=), (m_RuneCost=1 --> 6,m_Modifiers=((m_AttributeName="Attribute_HealthMax",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=20))),(m_RuneCost=3-->4,m_Modifiers=((m_AttributeName="Attribute_HealthMax",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=20.000000),(m_AttributeName="Attribute_HealthRegenLimit",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=20.000000),(m_AttributeName="Attribute_HealthRegenInitialDelay",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=5.000000)))),m_CurrentLevel=-1)
	m_Powers=(m_Name="BloodThirsty",m_eUISelection=eDisUISelectionType_BloodThirsty,m_Levels=((m_RuneCost=0,m_Modifiers=), (m_RuneCost=2 --> 6,m_Modifiers=),(m_RuneCost=3 --> 4,m_Modifiers=((m_AttributeName="Attribute_AdrenalineMax",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=-20.000000)))),m_CurrentLevel=-1)
	m_Powers=(m_Name="ShadowKill",m_eUISelection=eDisUISelectionType_ShadowKill,    m_Levels=((m_RuneCost=0,m_Modifiers=), (m_RuneCost=2 --> 6,m_Modifiers=),(m_RuneCost=3 --> 4,m_Modifiers=)),m_CurrentLevel=-1)
	m_Powers=(m_Name="Celerity",m_eUISelection=eDisUISelectionType_Celerity,        m_Levels=((m_RuneCost=0,m_Modifiers=), (m_RuneCost=2 --> 6,m_Modifiers=((m_AttributeName="Attribute_JumpZ_PowerJump",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=1300),(m_AttributeName="Attribute_PowerJumpFullStop_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=1000),(m_AttributeName="Attribute_FullStop_ExtraStopVel_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=500.000000),(m_AttributeName="Attribute_HeldPowerJumpButtonTime_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=0.400000),(m_AttributeName="Attribute_HeldPowerJumpAccel_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=1800),(m_AttributeName="Attribute_MaxSpeedBeforeFallingDamage",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=2550.000000),(m_AttributeName="Attribute_MaxSpeedBeforeFallingDeath",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=3500.000000))),(m_RuneCost=3 --> 4,m_Modifiers=((m_AttributeName="Attribute_JumpZ_PowerJump",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=1300.000000),(m_AttributeName="Attribute_PowerJumpFullStop_PROTOTYPE",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=1500.000000),(m_AttributeName="Attribute_FullStop_ExtraStopVel_PROTOTYPE",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=500.000000),(m_AttributeName="Attribute_HeldPowerJumpButtonTime_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=0.400000),(m_AttributeName="Attribute_HeldPowerJumpAccel_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=3000.000000),(m_AttributeName="Attribute_WaterSpeed",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=10.000000),(m_AttributeName="Attribute_GroundSpeedSprint",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=30.000000),(m_AttributeName="Attribute_LandAnimRate",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=50.000000),(m_AttributeName="Attribute_MantleAnimRate",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=50.000000),(m_AttributeName="Attribute_GroundStrafeMultiplierSprint",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=0.500000),(m_AttributeName="Attribute_GroundBackwardMultiplierSprint",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=0.400000),(m_AttributeName="Attribute_MaxSpeedBeforeFallingDamage",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=2550.000000),(m_AttributeName="Attribute_MaxSpeedBeforeFallingDeath",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=3500.000000)))),m_CurrentLevel=-1)

## PlayerState.ini

	[DishonoredGame.StatePlayerMasterLeaning]
	m_fLeanReleaseTime=0.2 --> 0.4
	m_fLeanSpeed=1000 --> 750
	m_fMaxAllowedPitchDegrees=35 --> 45
	m_fMaxAllowedYawDegrees=60
	m_fMinAllowedPitchDegrees=-35 --> -45
	m_fMinAllowedYawDegrees=-60

	[DishonoredGame.StatePlayerMasterStunned]
	m_fStunDuration=0.1 --> 0.4
	m_bAllowIncomingAttacks=False --> True
	
	[DishonoredGame.StatePlayerMasterChoice_Base]
	m_bAllowIncomingAttacks=False --> True
	m_bAllowExplosionsFromPlayer=False --> True
	
	[DishonoredGame.StatePlayerMasterVersus]
	m_bAllowIncomingAttacks=False --> True
	
	[DishonoredGame.StatePlayerMasterMinigame]
	m_bAllowIncomingAttacks=False --> True

## Weapon.ini

	[DishonoredGame.DishonoredDamageType_BulletBlast]
	m_bDisableHitReaction=True \\ added
	m_bCannotKillNPC=True \\ added
	m_bInstaDeath_NonPlayerToNPC=True --> False
	m_ExpectedHitReaction=eDisPawnHitReactionType_Strong --> None 

	[DishonoredGame.DishonoredDamageType_Bullet]
	m_ExpectedHitReaction=eDisPawnHitReactionType_Knockdown --> None
	m_bInstaDeath_NonPlayerToNPC=True --> False

	[DishonoredGame.DishonoredDamageType_BulletMedium]
	m_bInstaDeath_NonPlayerToNPC=True --> False

	[DishonoredGame.DisDamageType_PostPossessSleep]
	m_fTimeBeforeSleep=0 --> 7.5

	[DishonoredGameContent.DisDamageType_Arrow_Sleep]
	m_bInstantSleepForUnawareNPCs=True --> False
	m_fTimeBeforeSleep=1.500000 --> 7.5

	[DishonoredGame.DisDamageType_SpringRazor]
	m_bApplyDamageReduction=False \\ added

	[DishonoredGame.DisDamageType_SpringRazorPlaced]
	m_bApplyDamageReduction=False \\ added	

	[DishonoredGame.DisDamageType_WindBlast]
	m_bCannotKillNPC=True \\ added

// spell price overview: (total runes = 39, total cost = 58 --> 78 --> 54):

blink1          = 2
blink2          = 4
posession1      = 2
posession2      = 4
bendTime1       = 2
bendTime2       = 4
devouringSwarm1 = 2
devouringSwarm2 = 4
windBlast1      = 2
windBlast2      = 4
darkVision1     = 2
darkVision2     = 4
 -- total       = 36

vitality1       = 2
vitality2       = 1
bloodThirsty1   = 2
bloodThirsty2   = 1
agility1        = 2
agility2        = 1
shadowKill1     = 2
shadowKill2     = 1
-- total        = 12
