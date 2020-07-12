// this script was compiled with wurst 1.8.1.0-jenkins-Wurst-1248
globals
// integer PLAYER_NEUTRAL_PASSIVE=0
// integer PLAYER_NEUTRAL_AGGRESSIVE=0
// alliancetype ALLIANCE_PASSIVE=null
// alliancetype ALLIANCE_HELP_REQUEST=null
// alliancetype ALLIANCE_HELP_RESPONSE=null
// alliancetype ALLIANCE_SHARED_XP=null
// alliancetype ALLIANCE_SHARED_SPELLS=null
// alliancetype ALLIANCE_SHARED_VISION=null
// version VERSION_REIGN_OF_CHAOS=null
// racepreference RACE_PREF_HUMAN=null
// racepreference RACE_PREF_ORC=null
// racepreference RACE_PREF_UNDEAD=null
// mapcontrol MAP_CONTROL_USER=null
// mapcontrol MAP_CONTROL_COMPUTER=null
// mapcontrol MAP_CONTROL_RESCUABLE=null
// placement MAP_PLACEMENT_TEAMS_TOGETHER=null
// startlocprio MAP_LOC_PRIO_LOW=null
// startlocprio MAP_LOC_PRIO_HIGH=null
// playerslotstate PLAYER_SLOT_STATE_PLAYING=null
// fgamestate GAME_STATE_TIME_OF_DAY=null
// playerstate PLAYER_STATE_GIVES_BOUNTY=null
// playerstate PLAYER_STATE_ALLIED_VICTORY=null
// unitstate UNIT_STATE_LIFE=null
// unitstate UNIT_STATE_MAX_LIFE=null
// unitstate UNIT_STATE_MANA=null
// playerunitevent EVENT_PLAYER_UNIT_RESCUED=null
// playerunitevent EVENT_PLAYER_UNIT_DEATH=null
// playerunitevent EVENT_PLAYER_UNIT_SELECTED=null
// playerunitevent EVENT_PLAYER_UNIT_CONSTRUCT_START=null
// playerunitevent EVENT_PLAYER_UNIT_UPGRADE_CANCEL=null
// playerunitevent EVENT_PLAYER_UNIT_UPGRADE_FINISH=null
// playerunitevent EVENT_PLAYER_UNIT_ISSUED_ORDER=null
// playerunitevent EVENT_PLAYER_UNIT_ISSUED_POINT_ORDER=null
// playerunitevent EVENT_PLAYER_UNIT_ISSUED_TARGET_ORDER=null
// playerunitevent EVENT_PLAYER_UNIT_SELL_ITEM=null
// playerunitevent EVENT_PLAYER_UNIT_SPELL_CAST=null
// playerunitevent EVENT_PLAYER_UNIT_SPELL_EFFECT=null
// limitop LESS_THAN=null
// limitop EQUAL=null
// limitop GREATER_THAN_OR_EQUAL=null
// unittype UNIT_TYPE_HERO=null
// unittype UNIT_TYPE_STRUCTURE=null
// itemtype ITEM_TYPE_PERMANENT=null
// itemtype ITEM_TYPE_CHARGED=null
// itemtype ITEM_TYPE_ARTIFACT=null
// fogstate FOG_OF_WAR_VISIBLE=null
// integer CAMERA_MARGIN_LEFT=0
// integer CAMERA_MARGIN_RIGHT=0
// integer CAMERA_MARGIN_TOP=0
// integer CAMERA_MARGIN_BOTTOM=0
// originframetype ORIGIN_FRAME_GAME_UI=null
// real bj_GAME_STARTED_THRESHOLD=0.
// integer bj_MAX_PLAYERS=0
// integer bj_PLAYER_NEUTRAL_VICTIM=0
// integer bj_MAX_PLAYER_SLOTS=0
// integer bj_MAX_SKELETONS=0
// integer bj_MAX_STOCK_ITEM_SLOTS=0
// integer bj_MAX_STOCK_UNIT_SLOTS=0
// integer bj_MAX_ITEM_LEVEL=0
// real bj_TOD_DAWN=0.
// real bj_TOD_DUSK=0.
// real bj_STOCK_RESTOCK_INITIAL_DELAY=0.
// real bj_STOCK_RESTOCK_INTERVAL=0.
// integer bj_STOCK_MAX_ITERATIONS=0
// real bj_RESCUE_PING_TIME=0.
// integer bj_MAX_QUEUED_TRIGGERS=0
// real bj_QUEUED_TRIGGER_TIMEOUT=0.
// real bj_CORPSE_MAX_DEATH_TIME=0.
// force bj_FORCE_ALL_PLAYERS=null
// rect bj_mapInitialPlayableArea=null
// timer bj_gameStartedTimer=null
// trigger bj_dncSoundsDay=null
// trigger bj_dncSoundsNight=null
// sound bj_dayAmbientSound=null
// sound bj_nightAmbientSound=null
// trigger bj_dncSoundsDawn=null
// trigger bj_dncSoundsDusk=null
// sound bj_dawnSound=null
// sound bj_duskSound=null
// boolean bj_useDawnDuskSounds=false
// boolean bj_dncIsDaytime=false
// sound bj_rescueSound=null
// trigger bj_stockItemPurchased=null
// timer bj_stockUpdateTimer=null
// integer bj_stockPickedItemLevel=0
// itemtype bj_stockPickedItemType=null
// trigger bj_rescueUnitBehavior=null
// boolean bj_rescueChangeColorUnit=false
// boolean bj_rescueChangeColorBldg=false
// integer bj_queuedExecTotal=0
// timer bj_queuedExecTimeoutTimer=null
// trigger bj_queuedExecTimeout=null
// integer bj_groupEnumTypeId=0
// player bj_groupEnumOwningPlayer=null
// location bj_enumDestructableCenter=null
// real bj_enumDestructableRadius=0.
// group bj_suspendDecayFleshGroup=null
// group bj_suspendDecayBoneGroup=null
// timer bj_delayedSuspendDecayTimer=null
// trigger bj_delayedSuspendDecayTrig=null
// integer bj_livingPlayerUnitsTypeId=0
// fogmodifier bj_lastCreatedFogModifier=null
real AbilitySystem_INFO_MSG_TIME=0.
real AbilityData_Harvest_cooldown=0.
real Angle_DEGTORAD=0.
real Angle_RADTODEG=0.
real Basics_ANIMATION_PERIOD=0.
integer Basics_HEIGHT_ENABLER=0
player Basics_DUMMY_PLAYER=null
integer BitSet_BITSET_SIZE=0
integer array BitSet_pows
real BuildingSystem_BUILDING_ADJUSTMENT_RATE=0.
real BuildingSystem_BUILDING_START_HP_PERCENTAGE=0.
real BuildingSystem_MAX_AUTO_ORDER_RANGE=0.
real BuildingSystem_MAX_NEAR_BY_RANGE=0.
integer BuildingSystem_BUILDING_GROUND_UNIT_ID=0
string BuildingSystem_BUILD_PROGRESS_ICON_PATH=null
string BuildingSystem_BUILD_TIME_LEFT_ICON_PATH=null
string BuildingSystem_WORKERS_ICON_PATH=null
integer BuildingSystem_BUILDING_SITE_MAP=0
integer BuildingSystem_WORKER_MAP=0
unit BuildingSystem_testBuildingSystem_Build_building=null
integer array ClosureForGroups_tempCallbacks
integer ClosureForGroups_tempCallbacksCount=0
integer ClosureForGroups_maxCount=0
integer ClosureForGroups_iterCount=0
integer ClosureTimers_x=0
integer Colors_COLOR_WHITE_red=0
integer Colors_COLOR_WHITE_green=0
integer Colors_COLOR_WHITE_blue=0
integer Colors_COLOR_WHITE_alpha=0
integer array Colors_PLAYER_COLORS_red
integer array Colors_PLAYER_COLORS_green
integer array Colors_PLAYER_COLORS_blue
string array Colors_hexs
integer Colors_decs=0
player Command_GiveWares_USER_PLAYER=null
string Command_GiveWares_COMMAND=null
string Command_GiveWares_COMMAND_SHORT=null
player Command_ShowAll_USER_PLAYER=null
string Command_ShowAll_COMMAND=null
string Command_ShowAll_COMMAND_SHORT=null
player Command_Test_USER_PLAYER=null
string Command_Test_COMMAND=null
string Command_Test_COMMAND_SHORT=null
player Command_UnitTests_USER_PLAYER=null
string Command_UnitTests_COMMAND=null
string Command_UnitTests_COMMAND_SHORT=null
integer AbilityIdsCustom_showTargetInfo=0
integer AbilityIdsCustom_harvest=0
integer AbilityIdsCustom_build=0
integer AbilityIdsCustom_transferWares=0
integer AbilityIdsCustom_addBuildingBuff=0
integer AbilityIdsCustom_enterBuilding=0
integer AbilityIdsCustom_changeProduct=0
integer AbilityIdsCustom_removeWorker=0
integer BuffIdsCustom_building=0
integer Custom_buildingGround=0
integer Melee_townHall=0
integer Melee_keep=0
integer Melee_castle=0
integer Melee_farm=0
integer Melee_altarOfKings=0
integer Melee_barracks=0
integer Melee_lumberMill=0
integer Melee_blacksmith=0
integer Melee_workshop=0
integer Melee_arcaneSanctum=0
integer Melee_gryphonAviary=0
integer Melee_scoutTower=0
integer Melee_guardTower=0
integer Melee_cannonTower=0
integer Melee_arcaneTower=0
integer Melee_arcaneVault=0
integer Melee_peasant=0
integer Melee_footman=0
integer Trees_beech=0
integer Trees_beech_Var1=0
integer Trees_beech_Var2=0
integer Trees_beech_Var3=0
integer Trees_beech_Var4=0
integer Trees_birch=0
integer Trees_birch_Var1=0
integer Trees_birch_Var2=0
integer Trees_birch_Var3=0
integer Trees_greyOak=0
integer Trees_greyOak_Var1=0
integer Trees_greyOak_Var2=0
integer Trees_greyOak_Var3=0
integer Trees_greyOak_Var4=0
integer Trees_chestnut=0
integer Trees_chestnut_Var1=0
integer Trees_chestnut_Var2=0
integer DummyRecycler_DUMMY_UNIT_ID=0
integer DummyRecycler_ROOT_ENABLER=0
integer DummyRecycler_DIFFERENT_ANGLES=0
real DummyRecycler_ANGLE_DEGREE=0.
integer DummyRecycler_SAVED_UNITS_PER_ANGLE=0
timer DelayNode_t=null
integer DelayNode_first=0
integer array DummyRecycler_angleQueues
integer ErrorHandling_MUTE_ERROR_DURATION=0
integer ErrorHandling_PRIMARY_ERROR_KEY=0
hashtable ErrorHandling_HT=null
boolean ErrorHandling_suppressErrorMessages=false
framehandle Framehandle_GAME_UI=null
integer Framehandle_BLZ_FRAMENAME_MAXLENGTH=0
timer GameTimer_gameTimer=null
real GameTimer_currentTime=0.
group Group_ENUM_GROUP=null
group Group_iterGroup=null
hashtable HashList_ht=null
hashtable HashList_occurences=null
string Icons_bTNBash=null
string Icons_bTNBundleOfLumber=null
string Icons_bTNEngineeringUpgrade=null
string Icons_bTNFarm=null
string Icons_bTNHumanArmorUpOne=null
string Icons_bTNHumanLumberUpgrade1=null
string Icons_bTNHumanLumberUpgrade2=null
string Icons_bTNMonsterLure=null
string Icons_bTNSleep=null
string Icons_bTNSnazzyScroll=null
string Icons_bTNStatUp=null
string Icons_bTNWorkshop=null
integer InstantDummyCaster_DUMMY_CASTER_UNIT_ID=0
integer InstantDummyCaster_DUMMY_ROOT_ABIL_ID=0
unit InstantDummyCaster_caster=null
integer Integer_INT_MAX=0
integer Integer_INT_MIN=0
boolean MagicFunctions_compiletime=false
rect MapBounds_playableMapRect=null
rect MapBounds_boundRect=null
region MapBounds_boundRegion=null
real MapBounds_playableMin_x=0.
real MapBounds_playableMin_y=0.
real MapBounds_playableMax_x=0.
real MapBounds_playableMax_y=0.
real MapBounds_boundMin_x=0.
real MapBounds_boundMin_y=0.
real MapBounds_boundMax_x=0.
real MapBounds_boundMax_y=0.
real Matrices_ZERO44_m00=0.
real Matrices_ZERO44_m01=0.
real Matrices_ZERO44_m02=0.
real Matrices_ZERO44_m03=0.
real Matrices_ZERO44_m10=0.
real Matrices_ZERO44_m11=0.
real Matrices_ZERO44_m12=0.
real Matrices_ZERO44_m13=0.
real Matrices_ZERO44_m20=0.
real Matrices_ZERO44_m21=0.
real Matrices_ZERO44_m22=0.
real Matrices_ZERO44_m23=0.
real Matrices_ZERO44_m30=0.
real Matrices_ZERO44_m31=0.
real Matrices_ZERO44_m32=0.
real Matrices_ZERO44_m33=0.
integer MultiboardPrioritySystem_COUNT_PLAYERS=0
string MultiboardPrioritySystem_HEADLINE_ICON_PATH=null
string MultiboardPrioritySystem_SUB_HEADLINE_ICON_PATH=null
integer array MultiboardPrioritySystem_currentBoards
string ObjectIds_CHARMAP=null
integer ObjectInfoSystem_COUNT_PLAYERS=0
integer ObjectInfoSystem_MULTIBOARD_PRIORITY=0
real ObjectInfoSystem_ADJUSTING_TIME=0.
string ObjectInfoSystem_MULTIBOARD_NAME=null
integer array ObjectInfoSystem_datasets
trigger OnUnitEnterLeave_eventTrigger=null
group OnUnitEnterLeave_preplacedUnits=null
unit array OnUnitEnterLeave_tempUnits
integer OnUnitEnterLeave_tempUnitsCount=0
integer OnUnitEnterLeave_ABILITY_ID=0
string OrderSystem_ORDER_ICON_PATH=null
real OrderSystem_POS_TOLERANCE_RANGE=0.
real OrderSystem_POS_CHECK_RATE=0.
integer OrderSystem_ORDER_SOURCE_MAP=0
integer OrderSystem_ORDER_TARGET_MAP=0
integer OrderIds_attack=0
integer OrderIds_attackground=0
integer OrderIds_frostnova=0
integer OrderIds_holdposition=0
integer OrderIds_innerfire=0
integer OrderIds_move=0
integer OrderIds_patrol=0
integer OrderIds_repair=0
integer OrderIds_repairoff=0
integer OrderIds_repairon=0
integer OrderIds_shadowstrike=0
integer OrderIds_stop=0
integer OrderIds_thunderbolt=0
integer OrderIds_undefend=0
integer SpecialOrders_cancel=0
integer SpecialOrders_smart=0
integer SpecialOrders_stunned=0
string PersonSystem_FOOD_ICON_PATH=null
string PersonSystem_SLEEP_ICON_PATH=null
string PersonSystem_HOUSE_ICON_PATH=null
string PersonSystem_WORKPLACE_ICON_PATH=null
real PersonSystem_MAX_FOOD=0.
real PersonSystem_MAX_SLEEP=0.
integer PersonSystem_MAX_DAYS_NO_FOOD=0
integer PersonSystem_MAX_DAYS_NO_SLEEP=0
real PersonSystem_STATS_ADJUSTMENT_RATE=0.
integer PersonSystem_surnameCounter=0
integer PersonSystem_PERSON_MAP=0
player array Player_players
player Player_localPlayer=null
boolean Preloader_autoFinish=false
group Preloader_dumg=null
unit Preloader_dum=null
integer Printing_DEBUG_LEVEL=0
real Printing_DEBUG_MSG_DURATION=0.
real Real_REAL_MAX=0.
trigger array RegisterEvents_t
integer RegisterEvents_onCastMap=0
real ResourceSystem_MAX_AUTO_ORDER_RANGE=0.
string ResourceSystem_WORKERS_ICON_PATH=null
integer ResourceSystem_RESOURCE_MAP=0
integer ResourceSystem_findNextResource_Priority=0
group ResourceSystem_findNextResource_ValidUnits=null
integer SmartOrderSystem_SMART_USED_ABILITY_IDS=0
player StartupSystem_USER_PLAYER=null
real StartupSystem_START_VEC_x=0.
real StartupSystem_START_VEC_y=0.
integer StartupSystem_START_PEASANT_COUNT=0
integer StartupSystem_START_WOOD_COUNT_PER_PEASANT=0
string StartupSystem_currentInitStatus=null
integer Stock_MAX_WARE_COUNT=0
integer Stock_MAX_WARE_TYPES=0
string StorageSystem_CAPACITY_ICON_PATH=null
integer StorageSystem_STORAGE_MAP=0
string String_charset=null
string String_numberset=null
hashtable Table_ht=null
integer TerrainUtils_DUMMY_ITEM_ID=0
timer array TimerUtils_freeTimers
integer TimerUtils_freeTimersCount=0
integer TimerUtils_timerData=0
integer TimerUtils_HELD=0
integer TypeCasting_typecastdata=0
real TypeCasting_R2I_PRECISION=0.
trigger UnitIndexer_onIndexTrigger=null
trigger UnitIndexer_onDeindexTrigger=null
unit array UnitIndexer_tempUnits
integer UnitIndexer_tempUnitsCount=0
boolean UnitTest_SHOW_START_TEST_MESSAGE=false
string UnitTest_TEST_NAME_WURSTUNIT=null
integer UnitTest_TEST_NAME_MAP=0
real UnitData_AltarOfKings_scalingValue=0.
real UnitData_ArcaneSanctum_scalingValue=0.
real UnitData_ArcaneTower_scalingValue=0.
real UnitData_ArcaneVault_scalingValue=0.
real UnitData_Barracks_scalingValue=0.
real UnitData_Blacksmith_scalingValue=0.
real UnitData_CannonTower_scalingValue=0.
real UnitData_Castle_scalingValue=0.
real UnitData_GuardTower_scalingValue=0.
real UnitData_Keep_scalingValue=0.
real UnitData_LumberMill_scalingValue=0.
real UnitData_ScoutTower_scalingValue=0.
real UnitData_Townhall_scalingValue=0.
real UtilityFunctions_MIN_TRIGGER_SLEEP_TIME=0.
real UtilityFunctions_MIN_ACTION_SLEEP_TIME=0.
real UtilityFunctions_INGAME_DAY_SECONDS=0.
integer UtilityFunctions_BASE_UNIT_TYPE_ID_MAP=0
real Vectors_ZERO2_x=0.
real Vectors_ZERO2_y=0.
integer WorkshopSystem_MAX_STORABLE_EDUCTS=0
integer WorkshopSystem_MAX_STORABLE_PRODUCTS=0
real WorkshopSystem_PRODUCTION_ADJUSTMENT_RATE=0.
string WorkshopSystem_PRODUCTION_PROGRESS_ICON_PATH=null
string WorkshopSystem_PRODUCTION_TIME_LEFT_ICON_PATH=null
string WorkshopSystem_WORKERS_ICON_PATH=null
integer WorkshopSystem_WORKSHOP_MAP=0
hashtable hashtable_compiletime=null
hashtable hashtable_compiletime_569=null
hashtable hashtable_compiletime_570=null
hashtable hashtable_compiletime_571=null
integer array CallbackSimple_nextFree
integer CallbackSimple_firstFree=0
integer CallbackSimple_maxIndex=0
integer array CallbackSimple_typeId
integer array CallbackSingle_nextFree
integer CallbackSingle_firstFree=0
integer CallbackSingle_maxIndex=0
integer array CallbackSingle_typeId
integer array CallbackPeriodic_nextFree
integer CallbackPeriodic_firstFree=0
integer CallbackPeriodic_maxIndex=0
integer array CallbackPeriodic_typeId
integer array Stock_nextFree
integer Stock_firstFree=0
integer Stock_maxIndex=0
integer array Stock_typeId
integer array ForGroupCallback_nextFree
integer ForGroupCallback_firstFree=0
integer ForGroupCallback_maxIndex=0
integer array ForGroupCallback_typeId
integer array OffsetIdGenerator_nextFree
integer OffsetIdGenerator_firstFree=0
integer OffsetIdGenerator_maxIndex=0
integer array ArrayQueue_nextFree
integer ArrayQueue_firstFree=0
integer ArrayQueue_maxIndex=0
integer array ArrayQueue_typeId
integer DelayNode_firstFree=0
integer array DelayNode_typeId
integer array HLIterator_nextFree
integer HLIterator_firstFree=0
integer HLIterator_maxIndex=0
integer array HLIterator_typeId
integer array HashList_nextFree
integer HashList_firstFree=0
integer HashList_maxIndex=0
integer array HashList_typeId
integer array Table_nextFree
integer Table_firstFree=0
integer Table_maxIndex=0
integer array Table_typeId
integer array Comparator_nextFree
integer Comparator_firstFree=0
integer Comparator_maxIndex=0
integer LLBackIterator_firstFree=0
integer array LLBackIterator_typeId
integer array LLEntry_nextFree
integer LLEntry_firstFree=0
integer LLEntry_maxIndex=0
integer array LLEntry_typeId
integer array LLIterator_nextFree
integer LLIterator_firstFree=0
integer LLIterator_maxIndex=0
integer array LLIterator_typeId
integer array LinkedList_nextFree
integer LinkedList_firstFree=0
integer LinkedList_maxIndex=0
integer array LinkedList_typeId
integer array Board_nextFree
integer Board_firstFree=0
integer Board_maxIndex=0
integer array PlayerIDClosure_nextFree
integer PlayerIDClosure_firstFree=0
integer PlayerIDClosure_maxIndex=0
integer array PlayerIDClosure_typeId
integer array IdGenerator_nextFree
integer IdGenerator_firstFree=0
integer IdGenerator_maxIndex=0
integer array Dataset_nextFree
integer Dataset_firstFree=0
integer Dataset_maxIndex=0
integer array Dataset_typeId
integer array CallbackCondition_nextFree
integer CallbackCondition_firstFree=0
integer CallbackCondition_maxIndex=0
integer array CallbackCondition_typeId
integer array OrderAction_nextFree
integer OrderAction_firstFree=0
integer OrderAction_maxIndex=0
integer array OrderAction_typeId
integer array OrderSource_nextFree
integer OrderSource_firstFree=0
integer OrderSource_maxIndex=0
integer array OrderSource_typeId
integer array OrderTarget_nextFree
integer OrderTarget_firstFree=0
integer OrderTarget_maxIndex=0
integer array OrderTarget_typeId
integer array Person_nextFree
integer Person_firstFree=0
integer Person_maxIndex=0
integer array Person_typeId
integer array UnitIndex_nextFree
integer UnitIndex_firstFree=0
integer UnitIndex_maxIndex=0
integer array UnitIndex_typeId
integer array UnitMap_nextFree
integer UnitMap_firstFree=0
integer UnitMap_maxIndex=0
integer array UnitMap_typeId
unit array source
unit array source_716
integer array targetBuildingSite
unit array source_717
unit array source_718
integer array targetResource
integer array targetResource_732
unit array source_719
unit array target
unit array source_720
integer array targetResource_733
unit array source_721
group array finishedBuildings
unit array building
integer array workerCount
string array testName
integer array buildingSiteCount
unit array unitA
unit array unitA_738
real array BuildingSite_fullHP
integer array BuildingSite_workerCount
real array BuildingSite_workProgressCurrent
real array BuildingSite_workProgressFinished
real array BuildingSite_workPower
integer array BuildingSite_upgradeProgress
unit array worker
timer array CallbackSingle_t
integer array ArrayQueue_rp
integer array ArrayQueue_size
unit array DelayNode_u
real array DelayNode_delayTime
integer array DelayNode_next
integer array HLIterator_i
integer array HLIterator_list
integer array HashList_size
integer array HashMap_size
integer array IterableMap_keys
boolean array IterableMap__destroyed
integer array result
integer array LLEntry_elem
integer array LLEntry_prev
integer array LLEntry_next
integer array LLIterator_dummy
integer array LLIterator_current
integer array LLIterator_parent
boolean array LLIterator_destroyOnClose
integer array LinkedList_dummy
integer array LinkedList_size
integer array LinkedList_staticItr
integer array LinkedList_staticBackItr
string array Board_name
integer array Board_priority
integer array Board_disableFunc
integer array Dataset_playerID
multiboard array Dataset_usedMultiboard
timer array Dataset_adjustingTimer
unit array Dataset_targetedUnit
destructable array Dataset_targetedDestructable
unit array this
real array w_lastPos_x
real array w_lastPos_y
unit array source_722
unit array source_723
unit array source_724
unit array source_725
item array targetI
unit array source_726
unit array source_727
timer array OrderAction_t
integer array OrderAction_invalidateCb
integer array OrderAction_cancelCb
integer array OrderAction_finishCb
integer array OrderAction_finishCondition
unit array OrderSource_source
integer array OrderSource_orderId
integer array OrderSource_orderAction
unit array OrderSourceU_target
integer array OrderTarget_sources
string array Person_name
real array Person_food
real array Person_sleep
unit array Person_house
unit array Person_workplace
boolean array Resource_isKilledWhenDepleted
real array Resource_workProgress
integer array Resource_workerCount
unit array u
integer array Stock_wares
unit array Stock_user
integer array Storage_maxCapacity
integer array Storage_usedCapacity
unit array UnitIndex__unit
integer array IterableUnitHashMap_keys
integer array UnitHashMap_map
integer array UnitHashMap_nullElem
integer array Workshop_productionVariant
real array Workshop_workProgressCurrent
real array Workshop_workProgressFinished
real array Workshop_workPower
group array Workshop_workers
integer wareFromIndex_return_wareType=0
integer wareFromIndex_return_count=0
real real_asAngleDegrees_return_radians=0.
real real_asAngleRadians_return_radians=0.
real unit_getPos_return_x=0.
real unit_getPos_return_y=0.
integer dispatch_Stock_Stock_Stock_getWare_return_wareType=0
integer dispatch_Stock_Stock_Stock_getWare_return_count=0
real vec2_op_minus_return_x=0.
real vec2_op_minus_return_y=0.
real widget_getPos_return_x=0.
real widget_getPos_return_y=0.
real vec2_angleTo_return_radians=0.
real vec2_toVec3_return_x=0.
real vec2_toVec3_return_y=0.
real vec2_toVec3_return_z=0.
real item_getPos_return_x=0.
real item_getPos_return_y=0.
real vec2_op_plus_return_x=0.
real vec2_op_plus_return_y=0.
real vec2_op_mult_return_x=0.
real vec2_op_mult_return_y=0.
integer ware_changedCopy_return_wareType=0
integer ware_changedCopy_return_count=0
integer dispatch_Stock_Stock_Stock_getLastWare_return_wareType=0
integer dispatch_Stock_Stock_Stock_getLastWare_return_count=0
real unit_getFacingAngle_return_radians=0.
integer Stock_getWare_return_wareType=0
integer Stock_getWare_return_count=0
integer Stock_getLastWare_return_wareType=0
integer Stock_getLastWare_return_count=0
code ref_function_init_Abilities=null
code ref_function_init_AbilityIds=null
code ref_function_init_Real=null
code ref_function_init_Integer=null
code ref_function_init_BitSet=null
code ref_function_init_String=null
code ref_function_init_TargetsAllowed=null
code ref_function_init_Angle=null
code ref_function_init_Vectors=null
code ref_function_init_Player=null
code ref_function_init_Destructable=null
code ref_function_init_Maths=null
code ref_function_init_Printing=null
code ref_function_init_MagicFunctions=null
code ref_function_init_Basics=null
code ref_function_init_GameTimer=null
code ref_function_init_ErrorHandling=null
code ref_function_init_Matrices=null
code ref_function_init_Quaternion=null
code ref_function_init_Table=null
code ref_function_init_Playercolor=null
code ref_function_init_Colors=null
code ref_function_init_Framehandle=null
code ref_function_init_Group=null
code ref_function_init_Lightning=null
code ref_function_init_WeatherEffects=null
code ref_function_init_TypeCasting=null
code ref_function_init_HashList=null
code ref_function_init_EventHelper=null
code ref_function_init_AbilityObjEditing=null
code ref_function_init_RegisterEvents=null
code ref_function_init_MapBounds=null
code ref_function_init_ClosureForGroups=null
code ref_function_init_LinkedList=null
code ref_function_init_ObjectIds=null
code ref_function_init_UnitIds=null
code ref_function_init_Icons=null
code ref_function_init_DummyRecycler=null
code ref_function_init_TimerUtils=null
code ref_function_init_ClosureTimers=null
code ref_function_init_Preloader=null
code ref_function_init_ConstantDataSystem=null
code ref_function_init_Orders=null
code ref_function_init_UtilityFunctions=null
code ref_function_init_UnitTest=null
code ref_function_init_Stock=null
code ref_function_init_ObjectIdGenerator=null
code ref_function_init_OnUnitEnterLeave=null
code ref_function_init_MultiboardPrioritySystem=null
code ref_function_init_UnitIndexer=null
code ref_function_init_StorageSystem=null
code ref_function_init_InstantDummyCaster=null
code ref_function_init_OrderSystem=null
code ref_function_init_Buildings=null
code ref_function_init_Doodads=null
code ref_function_init_Objects=null
code ref_function_init_Sounds=null
code ref_function_init_Soundsets=null
code ref_function_init_Textures=null
code ref_function_init_UI=null
code ref_function_init_Units=null
code ref_function_init_AttachmentPoints=null
code ref_function_init_UnitsPresetFunctions=null
code ref_function_init_Unit_TownHall=null
code ref_function_init_Unit_AltarOfKings=null
code ref_function_init_Unit_ArcaneSanctum=null
code ref_function_init_Unit_ArcaneTower=null
code ref_function_init_Unit_ArcaneVault=null
code ref_function_init_Unit_ScoutTower=null
code ref_function_init_Unit_LumberMill=null
code ref_function_init_Unit_Keep=null
code ref_function_init_Unit_Barracks=null
code ref_function_init_Unit_Blacksmith=null
code ref_function_init_Unit_CannonTower=null
code ref_function_init_Unit_Castle=null
code ref_function_init_Unit_GuardTower=null
code ref_function_init_BuildingSystem=null
code ref_function_init_ResourceSystem=null
code ref_function_init_Ability_Harvest=null
code ref_function_init_WorkshopSystem=null
code ref_function_init_PersonSystem=null
code ref_function_init_AbilitySystem=null
code ref_function_init_Command_GiveWares=null
code ref_function_init_Command_ShowAll=null
code ref_function_init_Command_Test=null
code ref_function_init_Command_UnitTests=null
code ref_function_init_ObjectInfoSystem=null
code ref_function_init_SmartOrderSystem=null
code ref_function_init_StartupSystem=null
code ref_function_init_TerrainUtils=null
code ref_function_init_WorldGenerationSystem=null
code ref_function_code__registerPlayerUnitEvent_AbilitySystem=null
code ref_function_code__registerPlayerUnitEvent_AbilitySystem_598=null
code ref_function_code__onUnitDeindex_BuildingSystem=null
code ref_function_code__registerPlayerUnitEvent_BuildingSystem=null
code ref_function_code__registerPlayerUnitEvent_BuildingSystem_600=null
code ref_function_code__Filter_BuildingSystem=null
code ref_function_code__ForGroup_BuildingSystem=null
code ref_function_code__Filter_ClosureForGroups=null
code ref_function_executeCommand=null
code ref_function_executeCommand_619=null
code ref_function_executeCommand_620=null
code ref_function_executeCommand_621=null
code ref_function_DelayNode_recycle=null
code ref_function_code__startPeriodic_GameTimer=null
code ref_function_code__ForGroup_Group=null
code ref_function_code__registerPlayerUnitEvent_ObjectInfoSystem=null
code ref_function_code__registerPlayerUnitEvent_ObjectInfoSystem_602=null
code ref_function_code__onLeave_OrderSystem=null
code ref_function_code__registerPlayerUnitEvent_OrderSystem=null
code ref_function_code__registerPlayerUnitEvent_OrderSystem_604=null
code ref_function_code__registerPlayerUnitEvent_OrderSystem_605=null
code ref_function_code__registerPlayerUnitEvent_OrderSystem_606=null
code ref_function_code__registerPlayerUnitEvent_OrderSystem_607=null
code ref_function_code__registerPlayerUnitEvent_OrderSystem_608=null
code ref_function_code__onEnter_PersonSystem=null
code ref_function_code__onLeave_PersonSystem=null
code ref_function_code__registerPlayerUnitEvent_RegisterEvents=null
code ref_function_code__onEnter_ResourceSystem=null
code ref_function_code__onUnitDeindex_ResourceSystem=null
code ref_function_code__Filter_ResourceSystem=null
code ref_function_code__registerPlayerUnitEvent_SmartOrderSystem=null
code ref_function_runStartup=null
code ref_function_code__onEnter_StorageSystem=null
code ref_function_code__onLeave_StorageSystem=null
code ref_function_code__onEnter_UnitIndexer=null
code ref_function_code__onLeave_UnitIndexer=null
code ref_function_code__onEnter_WorkshopSystem=null
code ref_function_code__onUnitDeindex_WorkshopSystem=null
code ref_function_code__registerPlayerUnitEvent_WorkshopSystem=null
code ref_function_CallbackPeriodic_staticCallback=null
code ref_function_code__start_CallbackSingle_ClosureTimers=null
code ref_function_code__startPeriodic_Dataset_ObjectInfoSystem=null
code ref_function_code__Filter_registerEnterRegion_nullTimer_OnUnitEnterLeave=null
code ref_function_code__registerPlayerUnitEvent_nullTimer_OnUnitEnterLeave=null
code ref_function_code__ForGroup_nullTimer_OnUnitEnterLeave=null
code ref_function_code__start_OrderAction_OrderSystem=null
code ref_function_code__startPeriodic_OrderAction_OrderSystem=null
unit unit_findNextBuildingSitetempReturn=null
unit createDummytempReturn=null
unit group_nexttempReturn=null
timer getTimertempReturn=null
unit vec2_getNearestUnittempReturn=null
unit unit_replacetempReturn=null
multiboard dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboardtempReturn=null
unit dispatch_Table_Table_Table_loadUnittempReturn=null
trigger dispatch_Table_Table_Table_loadTriggertempReturn=null
endglobals
function InitGlobals takes nothing returns nothing
endfunction

function Loglevel_getTag takes integer this_1 returns string
	local integer temp = this_1
	if temp == 0 then
		return "|cffADADADtrace|r"
	elseif temp == 1 then
		return "|cff2685DCdebug|r"
	elseif temp == 2 then
		return "|cffFFCC00info|r"
	elseif temp == 3 then
		return "|cffF47E3Ewarning|r"
	else
		return "|cffFB2700error|r"
	endif
endfunction

function printLog_1100 takes player showTo, integer loglvl, string msg returns nothing
	local string compositeMsg
	if Printing_DEBUG_LEVEL <= loglvl then
		set compositeMsg = Loglevel_getTag(loglvl) + " - " + msg
		call DisplayTimedTextToPlayer(showTo, 0., 0., Printing_DEBUG_MSG_DURATION, compositeMsg)
	endif
endfunction

function Log_error takes string msg returns nothing
	call printLog_1100(Player_localPlayer, 4, msg)
endfunction

function compileError takes string msg returns nothing
endfunction

function hashtable_hasBoolean takes hashtable this_1, integer parentKey, integer childKey returns boolean
	return HaveSavedBoolean(this_1, parentKey, childKey)
endfunction

function hashtable_hasInt takes hashtable this_1, integer parentKey, integer childKey returns boolean
	return HaveSavedInteger(this_1, parentKey, childKey)
endfunction

function hashtable_loadBoolean takes hashtable this_1, integer parentKey, integer childKey returns boolean
	return LoadBoolean(this_1, parentKey, childKey)
endfunction

function hashtable_loadInt takes hashtable this_1, integer parentKey, integer childKey returns integer
	return LoadInteger(this_1, parentKey, childKey)
endfunction

function hashtable_saveBoolean takes hashtable this_1, integer parentKey, integer childKey, boolean value returns nothing
	call SaveBoolean(this_1, parentKey, childKey, value)
endfunction

function hashtable_saveInt takes hashtable this_1, integer parentKey, integer childKey, integer value returns nothing
	call SaveInteger(this_1, parentKey, childKey, value)
endfunction

function real_toInt takes real this_1 returns integer
	return R2I(this_1)
endfunction

function string_getHash takes string this_1 returns integer
	return StringHash(this_1)
endfunction

function error takes string msg returns nothing
	local integer hash
	if MagicFunctions_compiletime then
		call compileError("ERROR: " + msg)
	else
		if  not ErrorHandling_suppressErrorMessages then
			set hash = string_getHash(msg)
			if hashtable_hasInt(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash) then
				if hashtable_loadInt(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash) + ErrorHandling_MUTE_ERROR_DURATION < GameTimer_currentTime then
					call Log_error(msg + "")
					call hashtable_saveInt(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash, real_toInt(GameTimer_currentTime))
					call hashtable_saveBoolean(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash, false)
				elseif hashtable_hasBoolean(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash) then
					if  not hashtable_loadBoolean(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash) then
						call Log_error("|cffFF3A29Excessive repeating errors are being omitted")
						call hashtable_saveBoolean(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash, true)
					endif
				else
					call Log_error("|cffFF3A29Excessive repeating errors are being omitted")
					call hashtable_saveBoolean(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash, true)
				endif
			else
				call hashtable_saveInt(ErrorHandling_HT, ErrorHandling_PRIMARY_ERROR_KEY, hash, real_toInt(GameTimer_currentTime))
				call Log_error("Message: " + msg + "")
			endif
		endif
		call I2S(1 / 0)
	endif
endfunction

function initCompiletimeState_0 takes nothing returns nothing
	set hashtable_compiletime_571 = InitHashtable()
	set hashtable_compiletime_570 = InitHashtable()
	set hashtable_compiletime_569 = InitHashtable()
	set hashtable_compiletime = InitHashtable()
	call SaveInteger(hashtable_compiletime_569, 37, 2021273654, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273910, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273655, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273911, 1)
	call SaveInteger(hashtable_compiletime_569, 1, 789744696, 15)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273652, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273908, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273653, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273909, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273656, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273912, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273657, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273913, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273650, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273906, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273651, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273907, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273648, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273904, 1)
	call SaveStr(hashtable_compiletime_569, 2, 1916262177, "xdaa")
	call SaveInteger(hashtable_compiletime_569, 37, 2021273649, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273905, 1)
	call SaveInteger(hashtable_compiletime_569, 1, -647782241, 2)
	call SaveStr(hashtable_compiletime_569, 2, -85648186, "ward")
	call SaveInteger(hashtable_compiletime_569, 37, 2021273889, 1)
	call SaveStr(hashtable_compiletime_569, 2, -1912775212, "invulnerable")
	call SaveInteger(hashtable_compiletime_569, 1, -1676716706, 11)
	call SaveStr(hashtable_compiletime_569, 2, -1543684401, "playerunits")
	call SaveStr(hashtable_compiletime_569, 2, 512215473, "Agho")
	call SaveInteger(hashtable_compiletime_569, 1, -1587459251, 10)
	call SaveStr(hashtable_compiletime_569, 2, 392811314, "item")
	call SaveInteger(hashtable_compiletime_569, 1, 1132341824, 1)
	call SaveStr(hashtable_compiletime_569, 2, -681966791, "ground")
	call SaveStr(hashtable_compiletime_569, 2, 1282521876, "Aloc")
	call SaveInteger(hashtable_compiletime_569, 1, -1474492777, 9)
	call SaveInteger(hashtable_compiletime_569, 1, -1663695754, 13)
	call SaveStr(hashtable_compiletime_569, 2, 1804483594, "air")
	call SaveStr(hashtable_compiletime_569, 2, -543400682, "vulnerable")
	call SaveStr(hashtable_compiletime_569, 2, 124309475, "structure")
	call SaveInteger(hashtable_compiletime_569, 1, -1894922563, 8)
	call SaveInteger(hashtable_compiletime_569, 1, -680649701, 4)
	call SaveStr(hashtable_compiletime_569, 2, -1221441622, "debris")
	call SaveInteger(hashtable_compiletime_569, 1, -242600650, 0)
	call SaveStr(hashtable_compiletime_569, 2, -1546575767, "none")
	call SaveInteger(hashtable_compiletime_569, 37, 2021273726, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273724, 1)
	call SaveInteger(hashtable_compiletime_569, 1, -854572045, 3)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273725, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273718, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526776, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273719, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526777, 1)
	call SaveInteger(hashtable_compiletime_569, 1, 349230650, 7)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273716, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526774, 1)
	call SaveInteger(hashtable_compiletime_569, 1, -1559655710, 12)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273717, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526775, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273722, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273723, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273720, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273721, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273710, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526768, 1)
	call SaveInteger(hashtable_compiletime_569, 1, 597637742, 14)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273711, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526769, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273708, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273964, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273709, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273714, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526772, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273715, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526773, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273712, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526770, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273713, 1)
	call SaveInteger(hashtable_compiletime_569, 39, 1098526771, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273702, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273958, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273703, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273959, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273700, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273956, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273701, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273957, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273706, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273962, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273707, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273963, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273704, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273960, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273705, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273961, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273698, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273954, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273699, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273955, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273697, 1)
	call SaveInteger(hashtable_compiletime_569, 37, 2021273953, 1)
	call SaveInteger(hashtable_compiletime_569, 1, -943650483, 5)
	call SaveStr(hashtable_compiletime_569, 2, -375264434, "tree")
	call SaveStr(hashtable_compiletime_569, 2, -612826229, "Avul")
	call SaveInteger(hashtable_compiletime_569, 1, -671760605, 6)
	call SaveStr(hashtable_compiletime_569, 2, 0, "")
endfunction

function initCompiletimeState takes nothing returns nothing
	call ExecuteFunc("initCompiletimeState_0")
endfunction

function HLIterator_onDestroy takes integer this_1 returns nothing
endfunction

function dealloc_HLIterator takes integer obj returns nothing
	if HLIterator_typeId[obj] == 0 then
		call error("Double free: object of type HLIterator")
	else
		set HLIterator_nextFree[HLIterator_firstFree] = obj
		set HLIterator_firstFree = HLIterator_firstFree + 1
		set HLIterator_typeId[obj] = 0
	endif
endfunction

function destroyHLIterator takes integer this_1 returns nothing
	call HLIterator_onDestroy(this_1)
	call dealloc_HLIterator(this_1)
endfunction

function dispatch_HLIterator_destroyHLIterator takes integer this_1 returns nothing
	if HLIterator_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HLIterator.HLIterator")
		else
			call error("Called HLIterator.HLIterator on invalid object.")
		endif
	endif
	call destroyHLIterator(this_1)
endfunction

function HLIterator_close takes integer this_1 returns nothing
	call dispatch_HLIterator_destroyHLIterator(this_1)
endfunction

function HashList_size_1 takes integer this_1 returns integer
	return HashList_size[this_1]
endfunction

function dispatch_HashList_HashList_HashList_size takes integer this_1 returns integer
	local integer HashList_HashList_size_result
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.size")
		else
			call error("Called HashList.size on invalid object.")
		endif
	endif
	set HashList_HashList_size_result = HashList_size_1(this_1)
	return HashList_HashList_size_result
endfunction

function HLIterator_hasNext takes integer this_1 returns boolean
	return HLIterator_i[this_1] < dispatch_HashList_HashList_HashList_size(HLIterator_list[this_1])
endfunction

function HashList_get takes integer this_1, integer index returns integer
	return hashtable_loadInt(HashList_ht, this_1, index)
endfunction

function dispatch_HashList_HashList_HashList_get takes integer this_1, integer index returns integer
	local integer HashList_HashList_get_result
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.get")
		else
			call error("Called HashList.get on invalid object.")
		endif
	endif
	set HashList_HashList_get_result = HashList_get(this_1, index)
	return HashList_HashList_get_result
endfunction

function HLIterator_next takes integer this_1 returns integer
	set HLIterator_i[this_1] = HLIterator_i[this_1] + 1
	return dispatch_HashList_HashList_HashList_get(HLIterator_list[this_1], HLIterator_i[this_1] - 1)
endfunction

function alloc_HLIterator takes nothing returns integer
	local integer this_1
	if HLIterator_firstFree == 0 then
		if HLIterator_maxIndex < 32768 then
			set HLIterator_maxIndex = HLIterator_maxIndex + 1
			set this_1 = HLIterator_maxIndex
			set HLIterator_typeId[this_1] = 692
		else
			call error("Out of memory: Could not create HLIterator.")
			set this_1 = 0
		endif
	else
		set HLIterator_firstFree = HLIterator_firstFree - 1
		set this_1 = HLIterator_nextFree[HLIterator_firstFree]
		set HLIterator_typeId[this_1] = 692
	endif
	return this_1
endfunction

function HLIterator_init takes integer this_1 returns nothing
	set HLIterator_i[this_1] = 0
endfunction

function construct_HLIterator takes integer this_1, integer list returns nothing
	call HLIterator_init(this_1)
	set HLIterator_list[this_1] = list
endfunction

function new_HLIterator takes integer list returns integer
	local integer this_1 = alloc_HLIterator()
	call construct_HLIterator(this_1, list)
	return this_1
endfunction

function HashList_iterator takes integer this_1 returns integer
	return new_HLIterator(this_1)
endfunction

function dispatch_HashList_HashList_HashList_iterator takes integer this_1 returns integer
	local integer HashList_HashList_iterator_result
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.iterator")
		else
			call error("Called HashList.iterator on invalid object.")
		endif
	endif
	set HashList_HashList_iterator_result = HashList_iterator(this_1)
	return HashList_HashList_iterator_result
endfunction

function IterableUnitHashMap_iterator takes integer this_1 returns integer
	return dispatch_HashList_HashList_HashList_iterator(IterableUnitHashMap_keys[this_1])
endfunction

function max_2 takes integer numbers_0, integer numbers_1 returns integer
	local integer maxNumber = Integer_INT_MIN
	local integer cond_result
	if numbers_0 > maxNumber then
		set cond_result = numbers_0
	else
		set cond_result = maxNumber
	endif
	set maxNumber = cond_result
	if numbers_1 > maxNumber then
		set cond_result = numbers_1
	else
		set cond_result = maxNumber
	endif
	set maxNumber = cond_result
	return maxNumber
endfunction

function min_2 takes integer numbers_0, integer numbers_1 returns integer
	local integer minNumber = Integer_INT_MAX
	local integer cond_result
	if numbers_0 < minNumber then
		set cond_result = numbers_0
	else
		set cond_result = minNumber
	endif
	set minNumber = cond_result
	if numbers_1 < minNumber then
		set cond_result = numbers_1
	else
		set cond_result = minNumber
	endif
	set minNumber = cond_result
	return minNumber
endfunction

function unit_getState takes unit this_1, unitstate state returns real
	return GetUnitState(this_1, state)
endfunction

function unit_addState takes unit this_1, unitstate state, real value returns nothing
	call SetUnitState(this_1, state, unit_getState(this_1, state) + value)
endfunction

function unit_addHP takes unit this_1, real wval returns nothing
	call unit_addState(this_1, UNIT_STATE_LIFE, wval)
endfunction

function unit_setMaxHP takes unit this_1, integer hp returns nothing
	call BlzSetUnitMaxHP(this_1, hp)
endfunction

function BuildingSite_adjustProgress takes integer this_1 returns boolean
	if BuildingSite_workPower[this_1] > 0. then
		set BuildingSite_workProgressCurrent[this_1] = BuildingSite_workProgressCurrent[this_1] + BuildingSite_workPower[this_1] * BuildingSystem_BUILDING_ADJUSTMENT_RATE
		if BuildingSite_workProgressCurrent[this_1] >= BuildingSite_workProgressFinished[this_1] then
			call UnitSetUpgradeProgress(Stock_user[this_1], 100)
			return true
		else
			call unit_setMaxHP(Stock_user[this_1], max_2(1, real_toInt(BuildingSite_fullHP[this_1] * (BuildingSite_workProgressCurrent[this_1] / BuildingSite_workProgressFinished[this_1] * (1. - BuildingSystem_BUILDING_START_HP_PERCENTAGE) + BuildingSystem_BUILDING_START_HP_PERCENTAGE))))
			call unit_addHP(Stock_user[this_1], BuildingSite_fullHP[this_1] * (1. - BuildingSystem_BUILDING_START_HP_PERCENTAGE) * BuildingSite_workPower[this_1] * BuildingSystem_BUILDING_ADJUSTMENT_RATE)
			set BuildingSite_upgradeProgress[this_1] = min_2(max_2(1, real_toInt(BuildingSite_workProgressCurrent[this_1] / BuildingSite_workProgressFinished[this_1] * 100.)), 99)
		endif
	endif
	call UnitSetUpgradeProgress(Stock_user[this_1], BuildingSite_upgradeProgress[this_1])
	return false
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_adjustProgress takes integer this_1 returns boolean
	local boolean BuildingSystem_BuildingSite_adjustProgress_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.adjustProgress")
		else
			call error("Called BuildingSite.adjustProgress on invalid object.")
		endif
	endif
	set BuildingSystem_BuildingSite_adjustProgress_result = BuildingSite_adjustProgress(this_1)
	return BuildingSystem_BuildingSite_adjustProgress_result
endfunction

function Table_loadInt takes integer this_1, integer parentKey returns integer
	return hashtable_loadInt(Table_ht, this_1, parentKey)
endfunction

function dispatch_Table_Table_Table_loadInt takes integer this_1, integer parentKey returns integer
	local integer Table_Table_loadInt_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.loadInt")
		else
			call error("Called Table.loadInt on invalid object.")
		endif
	endif
	set Table_Table_loadInt_result = Table_loadInt(this_1, parentKey)
	return Table_Table_loadInt_result
endfunction

function HashMap_get takes integer this_1, integer key returns integer
	return dispatch_Table_Table_Table_loadInt(this_1, key)
endfunction

function dispatch_HashMap_HashMap_HashMap_get takes integer this_1, integer key returns integer
	local integer HashMap_HashMap_get_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashMap.get")
		else
			call error("Called HashMap.get on invalid object.")
		endif
	endif
	set HashMap_HashMap_get_result = HashMap_get(this_1, key)
	return HashMap_HashMap_get_result
endfunction

function handle_getHandleId takes handle this_1 returns integer
	return GetHandleId(this_1)
endfunction

function unitToIndex takes unit object returns integer
	return handle_getHandleId(object)
endfunction

function UnitHashMap_get takes integer this_1, unit key returns integer
	return dispatch_HashMap_HashMap_HashMap_get(UnitHashMap_map[this_1], unitToIndex(key))
endfunction

function dispatch_UnitHashMap_UnitMap_UnitHashMap_get takes integer this_1, unit key returns integer
	local integer UnitMap_UnitHashMap_get_result
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitHashMap.get")
		else
			call error("Called UnitHashMap.get on invalid object.")
		endif
	endif
	set UnitMap_UnitHashMap_get_result = UnitHashMap_get(this_1, key)
	return UnitMap_UnitHashMap_get_result
endfunction

function group_addUnit_1 takes group this_1, unit units_0 returns nothing
	call GroupAddUnit(this_1, units_0)
endfunction

function group_hasNext takes group this_1 returns boolean
	return FirstOfGroup(this_1) != null
endfunction

function group_next takes group this_1 returns unit
	local unit iterUnit = FirstOfGroup(this_1)
	call GroupRemoveUnit(this_1, iterUnit)
	set group_nexttempReturn = iterUnit
	set iterUnit = null
	return group_nexttempReturn
endfunction

function hashtable_loadUnitHandle takes hashtable this_1, integer parentKey, integer childKey returns unit
	return LoadUnitHandle(this_1, parentKey, childKey)
endfunction

function Table_loadUnit takes integer this_1, integer parentKey returns unit
	return hashtable_loadUnitHandle(Table_ht, this_1, parentKey)
endfunction

function dispatch_Table_Table_Table_loadUnit takes integer this_1, integer parentKey returns unit
	local unit Table_Table_loadUnit_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.loadUnit")
		else
			call error("Called Table.loadUnit on invalid object.")
		endif
	endif
	set Table_Table_loadUnit_result = Table_loadUnit(this_1, parentKey)
	set dispatch_Table_Table_Table_loadUnittempReturn = Table_Table_loadUnit_result
	set Table_Table_loadUnit_result = null
	return dispatch_Table_Table_Table_loadUnittempReturn
endfunction

function hashtable_saveFogStateHandle takes hashtable this_1, integer parentKey, integer childKey, fogstate value returns nothing
	call SaveFogStateHandle(this_1, parentKey, childKey, value)
endfunction

function Table_saveFogState takes integer this_1, integer parentKey, fogstate value returns nothing
	call hashtable_saveFogStateHandle(Table_ht, this_1, parentKey, value)
endfunction

function dispatch_Table_Table_Table_saveFogState takes integer this_1, integer parentKey, fogstate value returns nothing
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.saveFogState")
		else
			call error("Called Table.saveFogState on invalid object.")
		endif
	endif
	call Table_saveFogState(this_1, parentKey, value)
endfunction

function unitFromIndex takes integer index returns unit
	call dispatch_Table_Table_Table_saveFogState(TypeCasting_typecastdata, 0, ConvertFogState(index))
	return dispatch_Table_Table_Table_loadUnit(TypeCasting_typecastdata, 0)
endfunction

function LLBackIterator_onDestroy takes integer this_1 returns nothing
endfunction

function dealloc_LLBackIterator takes integer obj returns nothing
	if LLBackIterator_typeId[obj] == 0 then
		call error("Double free: object of type LLBackIterator")
	else
		set LLBackIterator_firstFree = LLBackIterator_firstFree + 1
		set LLBackIterator_typeId[obj] = 0
	endif
endfunction

function destroyLLBackIterator takes integer this_1 returns nothing
	call LLBackIterator_onDestroy(this_1)
	call dealloc_LLBackIterator(this_1)
endfunction

function dispatch_LLBackIterator_destroyLLBackIterator takes integer this_1 returns nothing
	if LLBackIterator_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LLBackIterator.LLBackIterator")
		else
			call error("Called LLBackIterator.LLBackIterator on invalid object.")
		endif
	endif
	call destroyLLBackIterator(this_1)
endfunction

function LLEntry_onDestroy takes integer this_1 returns nothing
endfunction

function dealloc_LLEntry takes integer obj returns nothing
	if LLEntry_typeId[obj] == 0 then
		call error("Double free: object of type LLEntry")
	else
		set LLEntry_nextFree[LLEntry_firstFree] = obj
		set LLEntry_firstFree = LLEntry_firstFree + 1
		set LLEntry_typeId[obj] = 0
	endif
endfunction

function destroyLLEntry takes integer this_1 returns nothing
	call LLEntry_onDestroy(this_1)
	call dealloc_LLEntry(this_1)
endfunction

function dispatch_LLEntry_destroyLLEntry takes integer this_1 returns nothing
	if LLEntry_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LLEntry.LLEntry")
		else
			call error("Called LLEntry.LLEntry on invalid object.")
		endif
	endif
	call destroyLLEntry(this_1)
endfunction

function LLIterator_onDestroy takes integer this_1 returns nothing
endfunction

function dealloc_LLIterator takes integer obj returns nothing
	if LLIterator_typeId[obj] == 0 then
		call error("Double free: object of type LLIterator")
	else
		set LLIterator_nextFree[LLIterator_firstFree] = obj
		set LLIterator_firstFree = LLIterator_firstFree + 1
		set LLIterator_typeId[obj] = 0
	endif
endfunction

function destroyLLIterator takes integer this_1 returns nothing
	call LLIterator_onDestroy(this_1)
	call dealloc_LLIterator(this_1)
endfunction

function dispatch_LLIterator_destroyLLIterator takes integer this_1 returns nothing
	if LLIterator_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LLIterator.LLIterator")
		else
			call error("Called LLIterator.LLIterator on invalid object.")
		endif
	endif
	call destroyLLIterator(this_1)
endfunction

function LinkedList_onDestroy takes integer this_1 returns nothing
	local integer current
	if LinkedList_staticItr[this_1] != 0 then
		call dispatch_LLIterator_destroyLLIterator(LinkedList_staticItr[this_1])
	endif
	if LinkedList_staticBackItr[this_1] != 0 then
		call dispatch_LLBackIterator_destroyLLBackIterator(LinkedList_staticBackItr[this_1])
	endif
	set current = LLEntry_next[LinkedList_dummy[this_1]]
	loop
		exitwhen  not (current != LinkedList_dummy[this_1])
		set current = LLEntry_next[current]
		call dispatch_LLEntry_destroyLLEntry(LLEntry_prev[current])
	endloop
	call dispatch_LLEntry_destroyLLEntry(LinkedList_dummy[this_1])
endfunction

function dealloc_LinkedList takes integer obj returns nothing
	if LinkedList_typeId[obj] == 0 then
		call error("Double free: object of type LinkedList")
	else
		set LinkedList_nextFree[LinkedList_firstFree] = obj
		set LinkedList_firstFree = LinkedList_firstFree + 1
		set LinkedList_typeId[obj] = 0
	endif
endfunction

function destroyLinkedList takes integer this_1 returns nothing
	call LinkedList_onDestroy(this_1)
	call dealloc_LinkedList(this_1)
endfunction

function dispatch_LinkedList_destroyLinkedList takes integer this_1 returns nothing
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.LinkedList")
		else
			call error("Called LinkedList.LinkedList on invalid object.")
		endif
	endif
	call destroyLinkedList(this_1)
endfunction

function Stock_onDestroy takes integer this_1 returns nothing
	call dispatch_LinkedList_destroyLinkedList(Stock_wares[this_1])
endfunction

function BuildingSite_onDestroy takes integer this_1 returns nothing
	call Stock_onDestroy(this_1)
endfunction

function dealloc_BuildingSite takes integer obj returns nothing
	if Stock_typeId[obj] == 0 then
		call error("Double free: object of type BuildingSite")
	else
		set Stock_nextFree[Stock_firstFree] = obj
		set Stock_firstFree = Stock_firstFree + 1
		set Stock_typeId[obj] = 0
	endif
endfunction

function destroyBuildingSite takes integer this_1 returns nothing
	call BuildingSite_onDestroy(this_1)
	call dealloc_BuildingSite(this_1)
endfunction

function dispatch_BuildingSite_destroyBuildingSite takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.BuildingSite")
		else
			call error("Called BuildingSite.BuildingSite on invalid object.")
		endif
	endif
	call destroyBuildingSite(this_1)
endfunction

function Table_hasInt takes integer this_1, integer parentKey returns boolean
	return hashtable_hasInt(Table_ht, this_1, parentKey)
endfunction

function dispatch_Table_Table_Table_hasInt takes integer this_1, integer parentKey returns boolean
	local boolean Table_Table_hasInt_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.hasInt")
		else
			call error("Called Table.hasInt on invalid object.")
		endif
	endif
	set Table_Table_hasInt_result = Table_hasInt(this_1, parentKey)
	return Table_Table_hasInt_result
endfunction

function HashMap_has takes integer this_1, integer key returns boolean
	return dispatch_Table_Table_Table_hasInt(this_1, key)
endfunction

function dispatch_HashMap_HashMap_HashMap_has takes integer this_1, integer key returns boolean
	local boolean HashMap_HashMap_has_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashMap.has")
		else
			call error("Called HashMap.has on invalid object.")
		endif
	endif
	set HashMap_HashMap_has_result = HashMap_has(this_1, key)
	return HashMap_HashMap_has_result
endfunction

function Table_removeInt takes integer this_1, integer parentKey returns nothing
	call RemoveSavedInteger(Table_ht, this_1, parentKey)
endfunction

function dispatch_Table_Table_Table_removeInt takes integer this_1, integer parentKey returns nothing
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.removeInt")
		else
			call error("Called Table.removeInt on invalid object.")
		endif
	endif
	call Table_removeInt(this_1, parentKey)
endfunction

function HashMap_remove takes integer this_1, integer key returns nothing
	if dispatch_HashMap_HashMap_HashMap_has(this_1, key) then
		set HashMap_size[this_1] = HashMap_size[this_1] - 1
	endif
	call dispatch_Table_Table_Table_removeInt(this_1, key)
endfunction

function HashList_count takes integer this_1, integer elem returns integer
	return hashtable_loadInt(HashList_occurences, this_1, elem)
endfunction

function dispatch_HashList_HashList_HashList_count takes integer this_1, integer elem returns integer
	local integer HashList_HashList_count_result
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.count")
		else
			call error("Called HashList.count on invalid object.")
		endif
	endif
	set HashList_HashList_count_result = HashList_count(this_1, elem)
	return HashList_HashList_count_result
endfunction

function HashList_decrOccurences takes integer this_1, integer elem returns nothing
	call hashtable_saveInt(HashList_occurences, this_1, elem, dispatch_HashList_HashList_HashList_count(this_1, elem) - 1)
endfunction

function dispatch_HashList_HashList_HashList_decrOccurences takes integer this_1, integer elem returns nothing
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.decrOccurences")
		else
			call error("Called HashList.decrOccurences on invalid object.")
		endif
	endif
	call HashList_decrOccurences(this_1, elem)
endfunction

function HashList_removeAt takes integer this_1, integer index returns integer
	local integer tmp
	local integer i
	local integer temp
	call dispatch_HashList_HashList_HashList_decrOccurences(this_1, hashtable_loadInt(HashList_ht, this_1, index))
	set tmp = hashtable_loadInt(HashList_ht, this_1, index)
	set i = index
	set temp = HashList_size[this_1]
	loop
		exitwhen i > temp
		call hashtable_saveInt(HashList_ht, this_1, i, hashtable_loadInt(HashList_ht, this_1, i + 1))
		set i = i + 1
	endloop
	set HashList_size[this_1] = HashList_size[this_1] - 1
	return tmp
endfunction

function dispatch_HashList_HashList_HashList_removeAt takes integer this_1, integer index returns integer
	local integer HashList_HashList_removeAt_result
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.removeAt")
		else
			call error("Called HashList.removeAt on invalid object.")
		endif
	endif
	set HashList_HashList_removeAt_result = HashList_removeAt(this_1, index)
	return HashList_HashList_removeAt_result
endfunction

function HashList_remove takes integer this_1, integer t returns boolean
	local boolean result_1 = false
	local integer i = 0
	local integer temp = HashList_size[this_1] - 1
	loop
		exitwhen i > temp
		if t == hashtable_loadInt(HashList_ht, this_1, i) then
			set result_1 = true
			call dispatch_HashList_HashList_HashList_removeAt(this_1, i)
			exitwhen true
		endif
		set i = i + 1
	endloop
	return result_1
endfunction

function dispatch_HashList_HashList_HashList_remove takes integer this_1, integer t returns boolean
	local boolean HashList_HashList_remove_result
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.remove")
		else
			call error("Called HashList.remove on invalid object.")
		endif
	endif
	set HashList_HashList_remove_result = HashList_remove(this_1, t)
	return HashList_HashList_remove_result
endfunction

function HashList_has takes integer this_1, integer elem returns boolean
	return dispatch_HashList_HashList_HashList_count(this_1, elem) > 0
endfunction

function dispatch_HashList_HashList_HashList_has takes integer this_1, integer elem returns boolean
	local boolean HashList_HashList_has_result
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.has")
		else
			call error("Called HashList.has on invalid object.")
		endif
	endif
	set HashList_HashList_has_result = HashList_has(this_1, elem)
	return HashList_HashList_has_result
endfunction

function IterableMap_hasKey takes integer this_1, integer key returns boolean
	return dispatch_HashList_HashList_HashList_has(IterableMap_keys[this_1], key)
endfunction

function dispatch_IterableMap_HashMap_IterableMap_hasKey takes integer this_1, integer key returns boolean
	local boolean HashMap_IterableMap_hasKey_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling IterableMap.hasKey")
		else
			call error("Called IterableMap.hasKey on invalid object.")
		endif
	endif
	set HashMap_IterableMap_hasKey_result = IterableMap_hasKey(this_1, key)
	return HashMap_IterableMap_hasKey_result
endfunction

function IterableMap_remove takes integer this_1, integer key returns nothing
	call HashMap_remove(this_1, key)
	if dispatch_IterableMap_HashMap_IterableMap_hasKey(this_1, key) then
		call dispatch_HashList_HashList_HashList_remove(IterableMap_keys[this_1], key)
	endif
endfunction

function dispatch_HashMap_HashMap_HashMap_remove takes integer this_1, integer key returns nothing
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashMap.remove")
		else
			call error("Called HashMap.remove on invalid object.")
		endif
	endif
	if Table_typeId[this_1] <= 821 then
		call HashMap_remove(this_1, key)
	else
		call IterableMap_remove(this_1, key)
	endif
endfunction

function UnitHashMap_remove takes integer this_1, unit key returns nothing
	call dispatch_HashMap_HashMap_HashMap_remove(UnitHashMap_map[this_1], unitToIndex(key))
endfunction

function IterableUnitHashMap_tryRemove takes integer this_1, unit key returns integer
	local integer value
	if dispatch_HashList_HashList_HashList_has(IterableUnitHashMap_keys[this_1], unitToIndex(key)) then
		set value = UnitHashMap_get(this_1, key)
		call UnitHashMap_remove(this_1, key)
		call dispatch_HashList_HashList_HashList_remove(IterableUnitHashMap_keys[this_1], unitToIndex(key))
		return value
	else
		return UnitHashMap_nullElem[this_1]
	endif
endfunction

function dispatch_IterableUnitHashMap_UnitMap_IterableUnitHashMap_tryRemove takes integer this_1, unit key returns integer
	local integer UnitMap_IterableUnitHashMap_tryRemove_result
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling IterableUnitHashMap.tryRemove")
		else
			call error("Called IterableUnitHashMap.tryRemove on invalid object.")
		endif
	endif
	set UnitMap_IterableUnitHashMap_tryRemove_result = IterableUnitHashMap_tryRemove(this_1, key)
	return UnitMap_IterableUnitHashMap_tryRemove_result
endfunction

function unit_removeBuildingSite takes unit this_1 returns nothing
	local integer buildingSite = dispatch_IterableUnitHashMap_UnitMap_IterableUnitHashMap_tryRemove(BuildingSystem_BUILDING_SITE_MAP, this_1)
	if buildingSite != 0 then
		call dispatch_BuildingSite_destroyBuildingSite(buildingSite)
	endif
endfunction

function call_doPeriodically_BuildingSystem takes integer this_1, integer cb returns nothing
	local integer iterator = IterableUnitHashMap_iterator(BuildingSystem_BUILDING_SITE_MAP)
	local unit building_1
	local unit building_2
	local group from
	loop
		exitwhen  not HLIterator_hasNext(iterator)
		set building_1 = unitFromIndex(HLIterator_next(iterator))
		if building_1 != null and dispatch_BuildingSite_BuildingSystem_BuildingSite_adjustProgress(dispatch_UnitHashMap_UnitMap_UnitHashMap_get(BuildingSystem_BUILDING_SITE_MAP, building_1)) then
			call group_addUnit_1(finishedBuildings[this_1], building_1)
		endif
	endloop
	call HLIterator_close(iterator)
	set from = finishedBuildings[this_1]
	loop
		exitwhen  not group_hasNext(from)
		set building_2 = group_next(from)
		call unit_removeBuildingSite(building_2)
	endloop
	set building_1 = null
	set building_2 = null
	set from = null
endfunction

function Person_reduceStats takes integer this_1 returns boolean
	set Person_food[this_1] = Person_food[this_1] - PersonSystem_MAX_FOOD / PersonSystem_MAX_DAYS_NO_FOOD * (PersonSystem_STATS_ADJUSTMENT_RATE / UtilityFunctions_INGAME_DAY_SECONDS)
	set Person_sleep[this_1] = Person_sleep[this_1] - PersonSystem_MAX_SLEEP / PersonSystem_MAX_DAYS_NO_SLEEP * (PersonSystem_STATS_ADJUSTMENT_RATE / UtilityFunctions_INGAME_DAY_SECONDS)
	return Person_food[this_1] <= 0. or Person_sleep[this_1] <= 0.
endfunction

function dispatch_Person_PersonSystem_Person_reduceStats takes integer this_1 returns boolean
	local boolean PersonSystem_Person_reduceStats_result
	if Person_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Person.reduceStats")
		else
			call error("Called Person.reduceStats on invalid object.")
		endif
	endif
	set PersonSystem_Person_reduceStats_result = Person_reduceStats(this_1)
	return PersonSystem_Person_reduceStats_result
endfunction

function call_doPeriodically_PersonSystem takes integer this_1, integer cb returns nothing
	local integer iterator = IterableUnitHashMap_iterator(PersonSystem_PERSON_MAP)
	local unit person
	loop
		exitwhen  not HLIterator_hasNext(iterator)
		set person = unitFromIndex(HLIterator_next(iterator))
		if person != null and dispatch_Person_PersonSystem_Person_reduceStats(dispatch_UnitHashMap_UnitMap_UnitHashMap_get(PersonSystem_PERSON_MAP, person)) then
		endif
	endloop
	call HLIterator_close(iterator)
	set person = null
endfunction

function LLIterator_close takes integer this_1 returns nothing
	if LLIterator_destroyOnClose[this_1] then
		call dispatch_LLIterator_destroyLLIterator(this_1)
	endif
endfunction

function LLIterator_hasNext takes integer this_1 returns boolean
	return LLEntry_next[LLIterator_current[this_1]] != LLIterator_dummy[this_1]
endfunction

function LLIterator_next takes integer this_1 returns integer
	set LLIterator_current[this_1] = LLEntry_next[LLIterator_current[this_1]]
	return LLEntry_elem[LLIterator_current[this_1]]
endfunction

function alloc_LLIterator takes nothing returns integer
	local integer this_1
	if LLIterator_firstFree == 0 then
		if LLIterator_maxIndex < 32768 then
			set LLIterator_maxIndex = LLIterator_maxIndex + 1
			set this_1 = LLIterator_maxIndex
			set LLIterator_typeId[this_1] = 743
		else
			call error("Out of memory: Could not create LLIterator.")
			set this_1 = 0
		endif
	else
		set LLIterator_firstFree = LLIterator_firstFree - 1
		set this_1 = LLIterator_nextFree[LLIterator_firstFree]
		set LLIterator_typeId[this_1] = 743
	endif
	return this_1
endfunction

function LLIterator_init takes integer this_1 returns nothing
	set LLIterator_destroyOnClose[this_1] = true
endfunction

function LinkedList_getDummy takes integer this_1 returns integer
	return LinkedList_dummy[this_1]
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_getDummy takes integer this_1 returns integer
	local integer LinkedList_LinkedList_getDummy_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.getDummy")
		else
			call error("Called LinkedList.getDummy on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_getDummy_result = LinkedList_getDummy(this_1)
	return LinkedList_LinkedList_getDummy_result
endfunction

function LLIterator_reset takes integer this_1 returns nothing
	set LLIterator_dummy[this_1] = dispatch_LinkedList_LinkedList_LinkedList_getDummy(LLIterator_parent[this_1])
	set LLIterator_current[this_1] = LLIterator_dummy[this_1]
endfunction

function dispatch_LLIterator_LinkedList_LLIterator_reset takes integer this_1 returns nothing
	if LLIterator_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LLIterator.reset")
		else
			call error("Called LLIterator.reset on invalid object.")
		endif
	endif
	call LLIterator_reset(this_1)
endfunction

function construct_LLIterator takes integer this_1, integer parent returns nothing
	call LLIterator_init(this_1)
	set LLIterator_parent[this_1] = parent
	call dispatch_LLIterator_LinkedList_LLIterator_reset(this_1)
endfunction

function new_LLIterator takes integer parent returns integer
	local integer this_1 = alloc_LLIterator()
	call construct_LLIterator(this_1, parent)
	return this_1
endfunction

function LinkedList_iterator takes integer this_1 returns integer
	return new_LLIterator(this_1)
endfunction

function alloc_LLEntry takes nothing returns integer
	local integer this_1
	if LLEntry_firstFree == 0 then
		if LLEntry_maxIndex < 32768 then
			set LLEntry_maxIndex = LLEntry_maxIndex + 1
			set this_1 = LLEntry_maxIndex
			set LLEntry_typeId[this_1] = 742
		else
			call error("Out of memory: Could not create LLEntry.")
			set this_1 = 0
		endif
	else
		set LLEntry_firstFree = LLEntry_firstFree - 1
		set this_1 = LLEntry_nextFree[LLEntry_firstFree]
		set LLEntry_typeId[this_1] = 742
	endif
	return this_1
endfunction

function LLEntry_init takes integer this_1 returns nothing
endfunction

function construct_LLEntry takes integer this_1, integer elem, integer prev, integer next returns nothing
	call LLEntry_init(this_1)
	set LLEntry_elem[this_1] = elem
	set LLEntry_prev[this_1] = prev
	set LLEntry_next[this_1] = next
endfunction

function new_LLEntry takes integer elem, integer prev, integer next returns integer
	local integer this_1 = alloc_LLEntry()
	call construct_LLEntry(this_1, elem, prev, next)
	return this_1
endfunction

function LinkedList_add_1 takes integer this_1, integer elems_0 returns nothing
	local integer entry = new_LLEntry(elems_0, LLEntry_prev[LinkedList_dummy[this_1]], LinkedList_dummy[this_1])
	set LLEntry_next[LLEntry_prev[LinkedList_dummy[this_1]]] = entry
	set LLEntry_prev[LinkedList_dummy[this_1]] = entry
	set LinkedList_size[this_1] = LinkedList_size[this_1] + 1
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_add_1 takes integer this_1, integer elems_0 returns nothing
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.add")
		else
			call error("Called LinkedList.add on invalid object.")
		endif
	endif
	call LinkedList_add_1(this_1, elems_0)
endfunction

function LinkedList_replace takes integer this_1, integer whichElement, integer newElement returns boolean
	local integer current = LLEntry_next[LinkedList_dummy[this_1]]
	loop
		exitwhen  not (current != LinkedList_dummy[this_1])
		if LLEntry_elem[current] == whichElement then
			set LLEntry_elem[current] = newElement
			return true
		endif
		set current = LLEntry_next[current]
	endloop
	return false
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_replace takes integer this_1, integer whichElement, integer newElement returns boolean
	local boolean LinkedList_LinkedList_replace_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.replace")
		else
			call error("Called LinkedList.replace on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_replace_result = LinkedList_replace(this_1, whichElement, newElement)
	return LinkedList_LinkedList_replace_result
endfunction

function wareFromIndex takes integer index returns integer
	local integer count = ModuloInteger(index, Stock_MAX_WARE_COUNT + 1)
	local integer wareType = (index - count) / (Stock_MAX_WARE_COUNT + 1)
	set wareFromIndex_return_wareType = wareType
	set wareFromIndex_return_count = count
	return wareFromIndex_return_wareType
endfunction

function int_toString takes integer this_1 returns string
	return I2S(this_1)
endfunction

function wareToIndex takes integer w_wareType, integer w_count returns integer
	local integer wareTypeInt = w_wareType
	if w_count < 1 or w_count > Stock_MAX_WARE_COUNT then
		call Log_error("ERROR: Ware count (" + int_toString(w_count) + ") isn't allowed to be smaller than 1 or bigger than " + int_toString(Stock_MAX_WARE_COUNT))
	elseif wareTypeInt < 0 or wareTypeInt > Stock_MAX_WARE_TYPES then
		call Log_error("ERROR: Ware type (" + int_toString(wareTypeInt) + ") isn't allowed to be smaller than 0 or bigger than " + int_toString(Stock_MAX_WARE_TYPES))
	endif
	return w_count + wareTypeInt * (Stock_MAX_WARE_COUNT + 1)
endfunction

function ware_changedCopy takes integer this_wareType, integer this_count, integer countChange returns integer
	set ware_changedCopy_return_wareType = this_wareType
	set ware_changedCopy_return_count = this_count + countChange
	return ware_changedCopy_return_wareType
endfunction

function ware_hasSameType takes integer this_wareType, integer this_count, integer otherWare_wareType, integer otherWare_count returns boolean
	return this_wareType == otherWare_wareType
endfunction

function Stock_addWare takes integer this_1, integer w_wareType, integer w_count returns nothing
	local integer iterator = LinkedList_iterator(Stock_wares[this_1])
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		if ware_hasSameType(iWare_wareType, iWare_count, w_wareType, w_count) then
			call dispatch_LinkedList_LinkedList_LinkedList_replace(Stock_wares[this_1], wareToIndex(iWare_wareType, iWare_count), wareToIndex(ware_changedCopy(iWare_wareType, iWare_count, w_count), ware_changedCopy_return_count))
			call LLIterator_close(iterator)
			return
		endif
	endloop
	call LLIterator_close(iterator)
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(Stock_wares[this_1], wareToIndex(w_wareType, w_count))
endfunction

function Storage_getFreeCapacity takes integer this_1 returns integer
	return Storage_maxCapacity[this_1] - Storage_usedCapacity[this_1]
endfunction

function dispatch_Storage_StorageSystem_Storage_getFreeCapacity takes integer this_1 returns integer
	local integer StorageSystem_Storage_getFreeCapacity_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.getFreeCapacity")
		else
			call error("Called Storage.getFreeCapacity on invalid object.")
		endif
	endif
	set StorageSystem_Storage_getFreeCapacity_result = Storage_getFreeCapacity(this_1)
	return StorageSystem_Storage_getFreeCapacity_result
endfunction

function unit_getName takes unit this_1 returns string
	return GetUnitName(this_1)
endfunction

function Storage_addWare takes integer this_1, integer w_wareType, integer w_count returns nothing
	if w_count > dispatch_Storage_StorageSystem_Storage_getFreeCapacity(this_1) then
		call Log_error("ERROR: Not enough free capacity to add given ware to storage of " + unit_getName(Stock_user[this_1]))
	endif
	set Storage_usedCapacity[this_1] = Storage_usedCapacity[this_1] + w_count
	call Stock_addWare(this_1, w_wareType, w_count)
endfunction

function dispatch_Stock_Stock_Stock_addWare takes integer this_1, integer w_wareType, integer w_count returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.addWare")
		else
			call error("Called Stock.addWare on invalid object.")
		endif
	endif
	if Stock_typeId[this_1] <= 804 then
		if Stock_typeId[this_1] <= 803 then
			call Stock_addWare(this_1, w_wareType, w_count)
		else
			call Storage_addWare(this_1, w_wareType, w_count)
		endif
	else
		call Stock_addWare(this_1, w_wareType, w_count)
	endif
endfunction

function Stock_addWares takes integer this_1, integer wares returns nothing
	local integer iterator = LinkedList_iterator(wares)
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		call dispatch_Stock_Stock_Stock_addWare(this_1, iWare_wareType, iWare_count)
	endloop
	call LLIterator_close(iterator)
endfunction

function dispatch_Storage_StorageSystem_Storage_addWare takes integer this_1, integer w_wareType, integer w_count returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.addWare")
		else
			call error("Called Storage.addWare on invalid object.")
		endif
	endif
	call Storage_addWare(this_1, w_wareType, w_count)
endfunction

function Storage_addWares takes integer this_1, integer wares returns nothing
	local integer iterator = LinkedList_iterator(wares)
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		call dispatch_Storage_StorageSystem_Storage_addWare(this_1, iWare_wareType, iWare_count)
	endloop
	call LLIterator_close(iterator)
endfunction

function dispatch_Stock_Stock_Stock_addWares takes integer this_1, integer wares returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.addWares")
		else
			call error("Called Stock.addWares on invalid object.")
		endif
	endif
	if Stock_typeId[this_1] <= 804 then
		if Stock_typeId[this_1] <= 803 then
			call Stock_addWares(this_1, wares)
		else
			call Storage_addWares(this_1, wares)
		endif
	else
		call Stock_addWares(this_1, wares)
	endif
endfunction

function alloc_LinkedList takes nothing returns integer
	local integer this_1
	if LinkedList_firstFree == 0 then
		if LinkedList_maxIndex < 32768 then
			set LinkedList_maxIndex = LinkedList_maxIndex + 1
			set this_1 = LinkedList_maxIndex
			set LinkedList_typeId[this_1] = 746
		else
			call error("Out of memory: Could not create LinkedList.")
			set this_1 = 0
		endif
	else
		set LinkedList_firstFree = LinkedList_firstFree - 1
		set this_1 = LinkedList_nextFree[LinkedList_firstFree]
		set LinkedList_typeId[this_1] = 746
	endif
	return this_1
endfunction

function LinkedList_init takes integer this_1 returns nothing
	set LinkedList_dummy[this_1] = new_LLEntry(0, 0, 0)
	set LinkedList_size[this_1] = 0
	set LinkedList_staticItr[this_1] = 0
	set LinkedList_staticBackItr[this_1] = 0
endfunction

function construct_LinkedList2 takes integer this_1 returns nothing
	call LinkedList_init(this_1)
	set LLEntry_next[LinkedList_dummy[this_1]] = LinkedList_dummy[this_1]
	set LLEntry_prev[LinkedList_dummy[this_1]] = LinkedList_dummy[this_1]
endfunction

function new_LinkedList takes nothing returns integer
	local integer this_1 = alloc_LinkedList()
	call construct_LinkedList2(this_1)
	return this_1
endfunction

function getWorkshopProducts takes integer workshopUnitId, integer productionVariant returns integer
	local integer wares = new_LinkedList()
	local integer temp = workshopUnitId
	local integer temp_1
	local integer temp_2
	if temp == Melee_lumberMill then
		set temp_1 = productionVariant
		if temp_1 == 1 then
			call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(6, 2))
		elseif temp_1 == 2 then
			call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(7, 1))
		endif
	elseif temp == Melee_blacksmith then
		set temp_2 = productionVariant
		if temp_2 == 1 then
			call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(2, 1))
		endif
	endif
	return wares
endfunction

function unit_getUnitId takes unit this_1 returns integer
	local integer id = GetUnitTypeId(this_1)
	if dispatch_HashMap_HashMap_HashMap_has(UtilityFunctions_BASE_UNIT_TYPE_ID_MAP, id) then
		return dispatch_HashMap_HashMap_HashMap_get(UtilityFunctions_BASE_UNIT_TYPE_ID_MAP, id)
	endif
	return id
endfunction

function Workshop_getProducts takes integer this_1 returns integer
	return getWorkshopProducts(unit_getUnitId(Stock_user[this_1]), Workshop_productionVariant[this_1])
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_getProducts takes integer this_1 returns integer
	local integer WorkshopSystem_Workshop_getProducts_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.getProducts")
		else
			call error("Called Workshop.getProducts on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_getProducts_result = Workshop_getProducts(this_1)
	return WorkshopSystem_Workshop_getProducts_result
endfunction

function Stock_getWareCount takes integer this_1, integer wt returns integer
	local integer iterator = LinkedList_iterator(Stock_wares[this_1])
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		if iWare_wareType == wt then
			call LLIterator_close(iterator)
			return iWare_count
		endif
	endloop
	call LLIterator_close(iterator)
	return 0
endfunction

function dispatch_Stock_Stock_Stock_getWareCount takes integer this_1, integer wt returns integer
	local integer Stock_Stock_getWareCount_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.getWareCount")
		else
			call error("Called Stock.getWareCount on invalid object.")
		endif
	endif
	set Stock_Stock_getWareCount_result = Stock_getWareCount(this_1, wt)
	return Stock_Stock_getWareCount_result
endfunction

function Stock_hasWare takes integer this_1, integer w_wareType, integer w_count returns boolean
	local integer iterator = LinkedList_iterator(Stock_wares[this_1])
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		if ware_hasSameType(iWare_wareType, iWare_count, w_wareType, w_count) then
			if iWare_count >= w_count then
				call LLIterator_close(iterator)
				return true
			else
				call LLIterator_close(iterator)
				return false
			endif
		endif
	endloop
	call LLIterator_close(iterator)
	return false
endfunction

function dispatch_Stock_Stock_Stock_hasWare takes integer this_1, integer w_wareType, integer w_count returns boolean
	local boolean Stock_Stock_hasWare_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.hasWare")
		else
			call error("Called Stock.hasWare on invalid object.")
		endif
	endif
	set Stock_Stock_hasWare_result = Stock_hasWare(this_1, w_wareType, w_count)
	return Stock_Stock_hasWare_result
endfunction

function Stock_hasWares takes integer this_1, integer wares returns boolean
	local integer iterator = LinkedList_iterator(wares)
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		if dispatch_Stock_Stock_Stock_hasWare(this_1, iWare_wareType, iWare_count) == false then
			call LLIterator_close(iterator)
			return false
		endif
	endloop
	call LLIterator_close(iterator)
	return true
endfunction

function dispatch_Stock_Stock_Stock_hasWares takes integer this_1, integer wares returns boolean
	local boolean Stock_Stock_hasWares_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.hasWares")
		else
			call error("Called Stock.hasWares on invalid object.")
		endif
	endif
	set Stock_Stock_hasWares_result = Stock_hasWares(this_1, wares)
	return Stock_Stock_hasWares_result
endfunction

function LinkedList_removeEntry takes integer this_1, integer entry returns nothing
	set LLEntry_next[LLEntry_prev[entry]] = LLEntry_next[entry]
	set LLEntry_prev[LLEntry_next[entry]] = LLEntry_prev[entry]
	call dispatch_LLEntry_destroyLLEntry(entry)
	set LinkedList_size[this_1] = LinkedList_size[this_1] - 1
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_removeEntry takes integer this_1, integer entry returns nothing
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.removeEntry")
		else
			call error("Called LinkedList.removeEntry on invalid object.")
		endif
	endif
	call LinkedList_removeEntry(this_1, entry)
endfunction

function LinkedList_remove takes integer this_1, integer elem returns boolean
	local boolean result_1 = false
	local integer entry = LLEntry_next[LinkedList_dummy[this_1]]
	loop
		exitwhen  not (entry != LinkedList_dummy[this_1])
		if LLEntry_elem[entry] == elem then
			call dispatch_LinkedList_LinkedList_LinkedList_removeEntry(this_1, entry)
			set result_1 = true
			exitwhen true
		endif
		set entry = LLEntry_next[entry]
	endloop
	return result_1
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_remove takes integer this_1, integer elem returns boolean
	local boolean LinkedList_LinkedList_remove_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.remove")
		else
			call error("Called LinkedList.remove on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_remove_result = LinkedList_remove(this_1, elem)
	return LinkedList_LinkedList_remove_result
endfunction

function Stock_removeWare takes integer this_1, integer w_wareType, integer w_count returns nothing
	local integer iterator = LinkedList_iterator(Stock_wares[this_1])
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		if ware_hasSameType(iWare_wareType, iWare_count, w_wareType, w_count) then
			if iWare_count <= w_count then
				call dispatch_LinkedList_LinkedList_LinkedList_remove(Stock_wares[this_1], wareToIndex(iWare_wareType, iWare_count))
			else
				call dispatch_LinkedList_LinkedList_LinkedList_replace(Stock_wares[this_1], wareToIndex(iWare_wareType, iWare_count), wareToIndex(ware_changedCopy(iWare_wareType, iWare_count,  - w_count), ware_changedCopy_return_count))
			endif
		endif
	endloop
	call LLIterator_close(iterator)
endfunction

function Storage_removeWare takes integer this_1, integer w_wareType, integer w_count returns nothing
	local integer iterator = LinkedList_iterator(Stock_wares[this_1])
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		if ware_hasSameType(iWare_wareType, iWare_count, w_wareType, w_count) then
			if iWare_count < w_count then
				call Log_error("ERROR: Can not remove given ware from storage of " + unit_getName(Stock_user[this_1]) + " because ware count is to low")
			elseif iWare_count == w_count then
				call dispatch_LinkedList_LinkedList_LinkedList_remove(Stock_wares[this_1], wareToIndex(iWare_wareType, iWare_count))
			else
				call dispatch_LinkedList_LinkedList_LinkedList_replace(Stock_wares[this_1], wareToIndex(iWare_wareType, iWare_count), wareToIndex(ware_changedCopy(iWare_wareType, iWare_count,  - w_count), ware_changedCopy_return_count))
			endif
			set Storage_usedCapacity[this_1] = Storage_usedCapacity[this_1] - w_count
			call LLIterator_close(iterator)
			return
		endif
	endloop
	call LLIterator_close(iterator)
	call Log_error("ERROR: Can not remove given ware from storage of " + unit_getName(Stock_user[this_1]) + " because ware type is not available")
endfunction

function dispatch_Stock_Stock_Stock_removeWare takes integer this_1, integer w_wareType, integer w_count returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.removeWare")
		else
			call error("Called Stock.removeWare on invalid object.")
		endif
	endif
	if Stock_typeId[this_1] <= 804 then
		if Stock_typeId[this_1] <= 803 then
			call Stock_removeWare(this_1, w_wareType, w_count)
		else
			call Storage_removeWare(this_1, w_wareType, w_count)
		endif
	else
		call Stock_removeWare(this_1, w_wareType, w_count)
	endif
endfunction

function Stock_removeWares takes integer this_1, integer wares returns nothing
	local integer iterator = LinkedList_iterator(wares)
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		call dispatch_Stock_Stock_Stock_removeWare(this_1, iWare_wareType, iWare_count)
	endloop
	call LLIterator_close(iterator)
endfunction

function dispatch_Storage_StorageSystem_Storage_removeWare takes integer this_1, integer w_wareType, integer w_count returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.removeWare")
		else
			call error("Called Storage.removeWare on invalid object.")
		endif
	endif
	call Storage_removeWare(this_1, w_wareType, w_count)
endfunction

function Storage_removeWares takes integer this_1, integer wares returns nothing
	local integer iterator = LinkedList_iterator(wares)
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		call dispatch_Storage_StorageSystem_Storage_removeWare(this_1, iWare_wareType, iWare_count)
	endloop
	call LLIterator_close(iterator)
endfunction

function dispatch_Stock_Stock_Stock_removeWares takes integer this_1, integer wares returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.removeWares")
		else
			call error("Called Stock.removeWares on invalid object.")
		endif
	endif
	if Stock_typeId[this_1] <= 804 then
		if Stock_typeId[this_1] <= 803 then
			call Stock_removeWares(this_1, wares)
		else
			call Storage_removeWares(this_1, wares)
		endif
	else
		call Stock_removeWares(this_1, wares)
	endif
endfunction

function getWorkshopEducts takes integer workshopUnitId, integer productionVariant returns integer
	local integer wares = new_LinkedList()
	local integer temp = workshopUnitId
	local integer temp_1
	local integer temp_2
	if temp == Melee_lumberMill then
		set temp_1 = productionVariant
		if temp_1 == 1 then
			call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 3))
		elseif temp_1 == 2 then
			call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 1))
		endif
	elseif temp == Melee_blacksmith then
		set temp_2 = productionVariant
		if temp_2 == 1 then
			call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(4, 1))
			call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(5, 1))
		endif
	endif
	return wares
endfunction

function Workshop_getEducts takes integer this_1 returns integer
	return getWorkshopEducts(unit_getUnitId(Stock_user[this_1]), Workshop_productionVariant[this_1])
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_getEducts takes integer this_1 returns integer
	local integer WorkshopSystem_Workshop_getEducts_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.getEducts")
		else
			call error("Called Workshop.getEducts on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_getEducts_result = Workshop_getEducts(this_1)
	return WorkshopSystem_Workshop_getEducts_result
endfunction

function Workshop_startProduction takes integer this_1 returns boolean
	local integer educts = dispatch_Workshop_WorkshopSystem_Workshop_getEducts(this_1)
	local integer products
	local integer iterator
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	if dispatch_Stock_Stock_Stock_hasWares(this_1, educts) then
		set products = dispatch_Workshop_WorkshopSystem_Workshop_getProducts(this_1)
		set iterator = LinkedList_iterator(products)
		loop
			exitwhen  not LLIterator_hasNext(iterator)
			set tuple_temp = wareFromIndex(LLIterator_next(iterator))
			set tuple_temp_1 = wareFromIndex_return_count
			set iWare_wareType = tuple_temp
			set iWare_count = tuple_temp_1
			if dispatch_Stock_Stock_Stock_getWareCount(this_1, iWare_wareType) > iWare_count * (WorkshopSystem_MAX_STORABLE_PRODUCTS - 1) then
				call dispatch_LinkedList_destroyLinkedList(products)
				call LLIterator_close(iterator)
				return false
			endif
		endloop
		call LLIterator_close(iterator)
		call dispatch_LinkedList_destroyLinkedList(products)
		call dispatch_Stock_Stock_Stock_removeWares(this_1, educts)
		call dispatch_LinkedList_destroyLinkedList(educts)
		return true
	else
		call dispatch_LinkedList_destroyLinkedList(educts)
		return false
	endif
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_startProduction takes integer this_1 returns boolean
	local boolean WorkshopSystem_Workshop_startProduction_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.startProduction")
		else
			call error("Called Workshop.startProduction on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_startProduction_result = Workshop_startProduction(this_1)
	return WorkshopSystem_Workshop_startProduction_result
endfunction

function Workshop_adjustProgress takes integer this_1 returns boolean
	local integer products
	if Workshop_workPower[this_1] > 0. then
		if Workshop_workProgressCurrent[this_1] <= 0. and dispatch_Workshop_WorkshopSystem_Workshop_startProduction(this_1) == false then
			return false
		endif
		set Workshop_workProgressCurrent[this_1] = Workshop_workProgressCurrent[this_1] + Workshop_workPower[this_1] * WorkshopSystem_PRODUCTION_ADJUSTMENT_RATE
		if Workshop_workProgressCurrent[this_1] >= Workshop_workProgressFinished[this_1] then
			set products = dispatch_Workshop_WorkshopSystem_Workshop_getProducts(this_1)
			call dispatch_Stock_Stock_Stock_addWares(this_1, products)
			call dispatch_LinkedList_destroyLinkedList(products)
			if dispatch_Workshop_WorkshopSystem_Workshop_startProduction(this_1) then
				set Workshop_workProgressCurrent[this_1] = Workshop_workProgressCurrent[this_1] - Workshop_workProgressFinished[this_1]
			else
				set Workshop_workProgressCurrent[this_1] = 0.
			endif
			return true
		endif
	endif
	return false
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_adjustProgress takes integer this_1 returns boolean
	local boolean WorkshopSystem_Workshop_adjustProgress_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.adjustProgress")
		else
			call error("Called Workshop.adjustProgress on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_adjustProgress_result = Workshop_adjustProgress(this_1)
	return WorkshopSystem_Workshop_adjustProgress_result
endfunction

function call_doPeriodically_WorkshopSystem takes integer this_1, integer cb returns nothing
	local integer iterator = IterableUnitHashMap_iterator(WorkshopSystem_WORKSHOP_MAP)
	local unit building_1
	loop
		exitwhen  not HLIterator_hasNext(iterator)
		set building_1 = unitFromIndex(HLIterator_next(iterator))
		if building_1 != null then
			call dispatch_Workshop_WorkshopSystem_Workshop_adjustProgress(dispatch_UnitHashMap_UnitMap_UnitHashMap_get(WorkshopSystem_WORKSHOP_MAP, building_1))
		endif
	endloop
	call HLIterator_close(iterator)
	set building_1 = null
endfunction

function dispatch_CallbackPeriodic_ClosureTimers_CallbackPeriodic_call takes integer this_1, integer cb returns nothing
	if CallbackPeriodic_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling CallbackPeriodic.call")
		else
			call error("Called CallbackPeriodic.call on invalid object.")
		endif
	endif
	if CallbackPeriodic_typeId[this_1] <= 648 then
		if CallbackPeriodic_typeId[this_1] <= 647 then
			call call_doPeriodically_BuildingSystem(this_1, cb)
		else
			call call_doPeriodically_PersonSystem(this_1, cb)
		endif
	else
		call call_doPeriodically_WorkshopSystem(this_1, cb)
	endif
endfunction

function timer_getHandleId takes timer this_1 returns integer
	return GetHandleId(this_1)
endfunction

function timer_getData takes timer this_1 returns integer
	return dispatch_Table_Table_Table_loadInt(TimerUtils_timerData, timer_getHandleId(this_1))
endfunction

function CallbackPeriodic_staticCallback takes nothing returns nothing
	local integer cb = timer_getData(GetExpiredTimer())
	call dispatch_CallbackPeriodic_ClosureTimers_CallbackPeriodic_call(cb, cb)
endfunction

function ArrayQueue_units_set takes integer instanceId, integer arrayIndex, unit value returns nothing
	if arrayIndex < 0 or arrayIndex >= 6 then
		call error("Index out of Bounds")
	elseif arrayIndex <= 2 then
		if arrayIndex <= 1 then
			if arrayIndex <= 0 then
			endif
		endif
	elseif arrayIndex <= 4 then
		if arrayIndex <= 3 then
		endif
	endif
endfunction

function ArrayQueue_enqueue takes integer this_1, unit u_1 returns nothing
	if ArrayQueue_size[this_1] < DummyRecycler_SAVED_UNITS_PER_ANGLE then
		set ArrayQueue_size[this_1] = ArrayQueue_size[this_1] + 1
		set ArrayQueue_rp[this_1] = ModuloInteger(ArrayQueue_rp[this_1] + 1, DummyRecycler_SAVED_UNITS_PER_ANGLE)
		call ArrayQueue_units_set(this_1, ArrayQueue_rp[this_1], u_1)
	else
		call error("Queue Overflow")
	endif
endfunction

function dispatch_ArrayQueue_DummyRecycler_ArrayQueue_enqueue takes integer this_1, unit u_1 returns nothing
	if ArrayQueue_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling ArrayQueue.enqueue")
		else
			call error("Called ArrayQueue.enqueue on invalid object.")
		endif
	endif
	call ArrayQueue_enqueue(this_1, u_1)
endfunction

function real_asAngleDegrees takes real this_1 returns real
	set real_asAngleDegrees_return_radians = this_1 * Angle_DEGTORAD
	return real_asAngleDegrees_return_radians
endfunction

function unit_pause takes unit this_1 returns nothing
	call PauseUnit(this_1, true)
endfunction

function unit_remove takes unit this_1 returns nothing
	call RemoveUnit(this_1)
endfunction

function angle_degrees takes real this_radians returns real
	return this_radians * Angle_RADTODEG
endfunction

function unit_setFacing takes unit this_1, real a_radians returns nothing
	call SetUnitFacing(this_1, angle_degrees(a_radians))
endfunction

function unit_setScale takes unit this_1, real scale returns nothing
	call SetUnitScale(this_1, scale, scale, scale)
endfunction

function unit_setVertexColor takes unit this_1, integer col_red, integer col_green, integer col_blue, integer col_alpha returns nothing
	call SetUnitVertexColor(this_1, col_red, col_green, col_blue, col_alpha)
endfunction

function unit_setX takes unit this_1, real x returns nothing
	call SetUnitX(this_1, x)
endfunction

function unit_setY takes unit this_1, real y returns nothing
	call SetUnitY(this_1, y)
endfunction

function unit_setXY takes unit this_1, real pos_x, real pos_y returns nothing
	local unit receiver = this_1
	local unit receiver_1
	call unit_setX(receiver, pos_x)
	set receiver_1 = receiver
	call unit_setY(receiver_1, pos_y)
	set receiver = null
	set receiver_1 = null
endfunction

function vec2_op_minus takes real this_x, real this_y, real v_x, real v_y returns real
	set vec2_op_minus_return_x = this_x - v_x
	set vec2_op_minus_return_y = this_y - v_y
	return vec2_op_minus_return_x
endfunction

function DummyRecycler_recycle takes unit u_1 returns nothing
	local integer smallestQueue = 0
	local integer i = 1
	local integer temp = DummyRecycler_DIFFERENT_ANGLES - 1
	local unit receiver
	local unit receiver_1
	local unit receiver_2
	local unit receiver_3
	local unit receiver_4
	loop
		exitwhen i > temp
		if ArrayQueue_size[DummyRecycler_angleQueues[smallestQueue]] > ArrayQueue_size[DummyRecycler_angleQueues[i]] then
			set smallestQueue = i
		endif
		set i = i + 1
	endloop
	if ArrayQueue_size[DummyRecycler_angleQueues[smallestQueue]] >= DummyRecycler_SAVED_UNITS_PER_ANGLE then
		call unit_remove(u_1)
	else
		call dispatch_ArrayQueue_DummyRecycler_ArrayQueue_enqueue(DummyRecycler_angleQueues[smallestQueue], u_1)
		set receiver = u_1
		call unit_setXY(receiver, vec2_op_minus(MapBounds_boundMax_x, MapBounds_boundMax_y, 16., 16.), vec2_op_minus_return_y)
		set receiver_1 = receiver
		call unit_pause(receiver_1)
		set receiver_2 = receiver_1
		call unit_setFacing(receiver_2, real_asAngleDegrees(smallestQueue * DummyRecycler_ANGLE_DEGREE))
		set receiver_3 = receiver_2
		call unit_setScale(receiver_3, 1.)
		set receiver_4 = receiver_3
		call unit_setVertexColor(receiver_4, Colors_COLOR_WHITE_red, Colors_COLOR_WHITE_green, Colors_COLOR_WHITE_blue, Colors_COLOR_WHITE_alpha)
	endif
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
	set receiver_3 = null
	set receiver_4 = null
endfunction

function DelayNode_onDestroy takes integer this_1 returns nothing
endfunction

function dealloc_DelayNode takes integer obj returns nothing
	if DelayNode_typeId[obj] == 0 then
		call error("Double free: object of type DelayNode")
	else
		set DelayNode_firstFree = DelayNode_firstFree + 1
		set DelayNode_typeId[obj] = 0
	endif
endfunction

function destroyDelayNode takes integer this_1 returns nothing
	call DelayNode_onDestroy(this_1)
	call dealloc_DelayNode(this_1)
endfunction

function dispatch_DelayNode_destroyDelayNode takes integer this_1 returns nothing
	if DelayNode_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling DelayNode.DelayNode")
		else
			call error("Called DelayNode.DelayNode on invalid object.")
		endif
	endif
	call destroyDelayNode(this_1)
endfunction

function timer_getElapsed takes timer this_1 returns real
	return TimerGetElapsed(this_1)
endfunction

function getElapsedGameTime takes nothing returns real
	return timer_getElapsed(GameTimer_gameTimer)
endfunction

function timer_start takes timer this_1, real time, code timerCallBack returns nothing
	call TimerStart(this_1, time, false, timerCallBack)
endfunction

function DelayNode_recycle takes nothing returns nothing
	local integer tmp
	call DummyRecycler_recycle(DelayNode_u[DelayNode_first])
	set tmp = DelayNode_first
	if DelayNode_next[DelayNode_first] == 0 then
		set DelayNode_first = 0
	else
		set DelayNode_first = DelayNode_next[DelayNode_first]
		call timer_start(DelayNode_t, DelayNode_delayTime[DelayNode_first] - getElapsedGameTime(), ref_function_DelayNode_recycle)
	endif
	call dispatch_DelayNode_destroyDelayNode(tmp)
endfunction

function LinkedList_isEmpty takes integer this_1 returns boolean
	return LinkedList_size[this_1] == 0
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_isEmpty takes integer this_1 returns boolean
	local boolean LinkedList_LinkedList_isEmpty_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.isEmpty")
		else
			call error("Called LinkedList.isEmpty on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_isEmpty_result = LinkedList_isEmpty(this_1)
	return LinkedList_LinkedList_isEmpty_result
endfunction

function Stock_isEmpty takes integer this_1 returns boolean
	return dispatch_LinkedList_LinkedList_LinkedList_isEmpty(Stock_wares[this_1])
endfunction

function dispatch_Stock_Stock_Stock_isEmpty takes integer this_1 returns boolean
	local boolean Stock_Stock_isEmpty_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.isEmpty")
		else
			call error("Called Stock.isEmpty on invalid object.")
		endif
	endif
	set Stock_Stock_isEmpty_result = Stock_isEmpty(this_1)
	return Stock_Stock_isEmpty_result
endfunction

function UnitHashMap_tryGet takes integer this_1, unit key returns integer
	if dispatch_HashMap_HashMap_HashMap_has(UnitHashMap_map[this_1], unitToIndex(key)) then
		return dispatch_HashMap_HashMap_HashMap_get(UnitHashMap_map[this_1], unitToIndex(key))
	else
		return UnitHashMap_nullElem[this_1]
	endif
endfunction

function dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet takes integer this_1, unit key returns integer
	local integer UnitMap_UnitHashMap_tryGet_result
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitHashMap.tryGet")
		else
			call error("Called UnitHashMap.tryGet on invalid object.")
		endif
	endif
	set UnitMap_UnitHashMap_tryGet_result = UnitHashMap_tryGet(this_1, key)
	return UnitMap_UnitHashMap_tryGet_result
endfunction

function unit_getBuildingSite takes unit this_1 returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(BuildingSystem_BUILDING_SITE_MAP, this_1)
endfunction

function code__Filter_BuildingSystem takes nothing returns boolean
	local boolean conditionsFulfilled = false
	local integer buildingSite = unit_getBuildingSite(GetFilterUnit())
	if buildingSite != 0 and dispatch_Stock_Stock_Stock_isEmpty(buildingSite) then
		set conditionsFulfilled = true
	endif
	return conditionsFulfilled
endfunction

function currentCallback takes nothing returns integer
	return ClosureForGroups_tempCallbacks[ClosureForGroups_tempCallbacksCount - 1]
endfunction

function callback_forEachFrom_LinkedList takes integer this_1, unit u_1 returns nothing
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(result[this_1], unitToIndex(u_1))
endfunction

function callback_forEachFrom_Preloader takes integer this_1, unit u_1 returns nothing
	call unit_remove(u_1)
endfunction

function dispatch_ForGroupCallback_ClosureForGroups_ForGroupCallback_callback takes integer this_1, unit u_1 returns nothing
	if ForGroupCallback_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling ForGroupCallback.callback")
		else
			call error("Called ForGroupCallback.callback on invalid object.")
		endif
	endif
	if ForGroupCallback_typeId[this_1] <= 689 then
		call callback_forEachFrom_LinkedList(this_1, u_1)
	else
		call callback_forEachFrom_Preloader(this_1, u_1)
	endif
endfunction

function filterCallback takes unit filter returns nothing
	if ClosureForGroups_iterCount < ClosureForGroups_maxCount then
		call dispatch_ForGroupCallback_ClosureForGroups_ForGroupCallback_callback(currentCallback(), filter)
	endif
	set ClosureForGroups_iterCount = ClosureForGroups_iterCount + 1
endfunction

function code__Filter_ClosureForGroups takes nothing returns nothing
	call filterCallback(GetFilterUnit())
endfunction

function getMaxWorkerCount takes integer resourceUnitId returns integer
	local integer temp = resourceUnitId
	if temp == Trees_beech then
		return 1
	elseif temp == Trees_birch then
		return 1
	elseif temp == Trees_greyOak then
		return 2
	elseif temp == Trees_chestnut then
		return 2
	endif
	return 99
endfunction

function Resource_getFreeWorkerSlots takes integer this_1 returns integer
	return getMaxWorkerCount(unit_getUnitId(Stock_user[this_1])) - Resource_workerCount[this_1]
endfunction

function dispatch_Resource_ResourceSystem_Resource_getFreeWorkerSlots takes integer this_1 returns integer
	local integer ResourceSystem_Resource_getFreeWorkerSlots_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Resource.getFreeWorkerSlots")
		else
			call error("Called Resource.getFreeWorkerSlots on invalid object.")
		endif
	endif
	set ResourceSystem_Resource_getFreeWorkerSlots_result = Resource_getFreeWorkerSlots(this_1)
	return ResourceSystem_Resource_getFreeWorkerSlots_result
endfunction

function getHarvestPriority takes integer resourceUnitId returns integer
	local integer temp = resourceUnitId
	if temp == Trees_beech then
		return 2
	elseif temp == Trees_birch then
		return 1
	elseif temp == Trees_greyOak then
		return 3
	elseif temp == Trees_chestnut then
		return 2
	endif
	return 0
endfunction

function unit_getResource takes unit this_1 returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(ResourceSystem_RESOURCE_MAP, this_1)
endfunction

function code__Filter_ResourceSystem takes nothing returns boolean
	local boolean conditionsFulfilled = false
	local unit filterUnit = GetFilterUnit()
	local integer resource = unit_getResource(filterUnit)
	local integer priority = getHarvestPriority(unit_getUnitId(filterUnit))
	if resource != 0 and dispatch_Stock_Stock_Stock_isEmpty(resource) == false and dispatch_Resource_ResourceSystem_Resource_getFreeWorkerSlots(resource) > 0 and priority >= ResourceSystem_findNextResource_Priority then
		set ResourceSystem_findNextResource_Priority = priority
		set conditionsFulfilled = true
	endif
	set filterUnit = null
	return conditionsFulfilled
endfunction

function popUnit takes nothing returns nothing
	set OnUnitEnterLeave_tempUnitsCount = OnUnitEnterLeave_tempUnitsCount - 1
endfunction

function pushUnit takes unit u_1 returns nothing
	set OnUnitEnterLeave_tempUnits[OnUnitEnterLeave_tempUnitsCount] = u_1
	set OnUnitEnterLeave_tempUnitsCount = OnUnitEnterLeave_tempUnitsCount + 1
endfunction

function trigger_evaluate takes trigger this_1 returns boolean
	return TriggerEvaluate(this_1)
endfunction

function unit_addAbility takes unit this_1, integer abil returns boolean
	return UnitAddAbility(this_1, abil)
endfunction

function unit_makeAbilityPermanent takes unit this_1, integer abil, boolean flag returns boolean
	return UnitMakeAbilityPermanent(this_1, flag, abil)
endfunction

function prepareUnit takes unit u_1 returns nothing
	local unit receiver = u_1
	local unit receiver_1
	call unit_addAbility(receiver, OnUnitEnterLeave_ABILITY_ID)
	set receiver_1 = receiver
	call unit_makeAbilityPermanent(receiver_1, OnUnitEnterLeave_ABILITY_ID, true)
	call pushUnit(u_1)
	call trigger_evaluate(OnUnitEnterLeave_eventTrigger)
	call popUnit()
	set receiver = null
	set receiver_1 = null
endfunction

function code__Filter_registerEnterRegion_nullTimer_OnUnitEnterLeave takes nothing returns nothing
	call prepareUnit(GetFilterUnit())
endfunction

function code__ForGroup_BuildingSystem takes nothing returns nothing
	call unit_remove(GetEnumUnit())
endfunction

function code__ForGroup_Group takes nothing returns nothing
	call group_addUnit_1(Group_iterGroup, GetEnumUnit())
endfunction

function code__ForGroup_nullTimer_OnUnitEnterLeave takes nothing returns nothing
	call prepareUnit(GetEnumUnit())
endfunction

function getEnterLeaveUnit takes nothing returns unit
	return OnUnitEnterLeave_tempUnits[OnUnitEnterLeave_tempUnitsCount - 1]
endfunction

function getRandomForename takes nothing returns string
	local integer i = GetRandomInt(1, 4)
	local integer temp = i
	if temp == 1 then
		return "Peter"
	elseif temp == 2 then
		return "Hans"
	elseif temp == 3 then
		return "Theodor"
	elseif temp == 4 then
		return "Michael"
	else
		call error("Wrong configuration for getRandomForename")
		return null
	endif
endfunction

function getRandomSurname takes nothing returns string
	local integer temp
	set PersonSystem_surnameCounter = PersonSystem_surnameCounter + 1
	if PersonSystem_surnameCounter > 4 then
		set PersonSystem_surnameCounter = 1
	endif
	set temp = PersonSystem_surnameCounter
	if temp == 1 then
		return "Smith"
	elseif temp == 2 then
		return "Miller"
	elseif temp == 3 then
		return "Baker"
	elseif temp == 4 then
		return "Wolf"
	else
		call error("Wrong configuration for getRandomSurname")
		return null
	endif
endfunction

function getRandomName takes nothing returns string
	return getRandomForename() + " " + getRandomSurname()
endfunction

function Table_saveInt takes integer this_1, integer parentKey, integer value returns nothing
	call hashtable_saveInt(Table_ht, this_1, parentKey, value)
endfunction

function dispatch_Table_Table_Table_saveInt takes integer this_1, integer parentKey, integer value returns nothing
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.saveInt")
		else
			call error("Called Table.saveInt on invalid object.")
		endif
	endif
	call Table_saveInt(this_1, parentKey, value)
endfunction

function HashMap_put takes integer this_1, integer key, integer value returns nothing
	if  not dispatch_HashMap_HashMap_HashMap_has(this_1, key) then
		set HashMap_size[this_1] = HashMap_size[this_1] + 1
	endif
	call dispatch_Table_Table_Table_saveInt(this_1, key, value)
endfunction

function HashList_incrOccurences takes integer this_1, integer elem returns nothing
	call hashtable_saveInt(HashList_occurences, this_1, elem, dispatch_HashList_HashList_HashList_count(this_1, elem) + 1)
endfunction

function dispatch_HashList_HashList_HashList_incrOccurences takes integer this_1, integer elem returns nothing
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.incrOccurences")
		else
			call error("Called HashList.incrOccurences on invalid object.")
		endif
	endif
	call HashList_incrOccurences(this_1, elem)
endfunction

function HashList_add_1 takes integer this_1, integer elems_0 returns nothing
	call hashtable_saveInt(HashList_ht, this_1, HashList_size[this_1], elems_0)
	call dispatch_HashList_HashList_HashList_incrOccurences(this_1, elems_0)
	set HashList_size[this_1] = HashList_size[this_1] + 1
endfunction

function dispatch_HashList_HashList_HashList_add_1 takes integer this_1, integer elems_0 returns nothing
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.add")
		else
			call error("Called HashList.add on invalid object.")
		endif
	endif
	call HashList_add_1(this_1, elems_0)
endfunction

function IterableMap_put takes integer this_1, integer key, integer value returns nothing
	call HashMap_put(this_1, key, value)
	if  not dispatch_IterableMap_HashMap_IterableMap_hasKey(this_1, key) then
		call dispatch_HashList_HashList_HashList_add_1(IterableMap_keys[this_1], key)
	endif
endfunction

function dispatch_HashMap_HashMap_HashMap_put takes integer this_1, integer key, integer value returns nothing
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashMap.put")
		else
			call error("Called HashMap.put on invalid object.")
		endif
	endif
	if Table_typeId[this_1] <= 821 then
		call HashMap_put(this_1, key, value)
	else
		call IterableMap_put(this_1, key, value)
	endif
endfunction

function UnitHashMap_put takes integer this_1, unit key, integer value returns nothing
	call dispatch_HashMap_HashMap_HashMap_put(UnitHashMap_map[this_1], unitToIndex(key), value)
endfunction

function IterableUnitHashMap_put takes integer this_1, unit key, integer value returns nothing
	call UnitHashMap_put(this_1, key, value)
	if dispatch_HashList_HashList_HashList_has(IterableUnitHashMap_keys[this_1], unitToIndex(key)) == false then
		call dispatch_HashList_HashList_HashList_add_1(IterableUnitHashMap_keys[this_1], unitToIndex(key))
	endif
endfunction

function dispatch_IterableUnitHashMap_UnitMap_IterableUnitHashMap_put takes integer this_1, unit key, integer value returns nothing
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling IterableUnitHashMap.put")
		else
			call error("Called IterableUnitHashMap.put on invalid object.")
		endif
	endif
	call IterableUnitHashMap_put(this_1, key, value)
endfunction

function UnitHashMap_has takes integer this_1, unit key returns boolean
	return dispatch_HashMap_HashMap_HashMap_has(UnitHashMap_map[this_1], unitToIndex(key))
endfunction

function dispatch_UnitHashMap_UnitMap_UnitHashMap_has takes integer this_1, unit key returns boolean
	local boolean UnitMap_UnitHashMap_has_result
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitHashMap.has")
		else
			call error("Called UnitHashMap.has on invalid object.")
		endif
	endif
	set UnitMap_UnitHashMap_has_result = UnitHashMap_has(this_1, key)
	return UnitMap_UnitHashMap_has_result
endfunction

function isPersonType takes integer unitId returns boolean
	local integer temp = unitId
	if temp == Melee_peasant then
		return true
	elseif temp == Melee_footman then
		return true
	else
		return false
	endif
endfunction

function alloc_Person takes nothing returns integer
	local integer this_1
	if Person_firstFree == 0 then
		if Person_maxIndex < 32768 then
			set Person_maxIndex = Person_maxIndex + 1
			set this_1 = Person_maxIndex
			set Person_typeId[this_1] = 762
		else
			call error("Out of memory: Could not create Person.")
			set this_1 = 0
		endif
	else
		set Person_firstFree = Person_firstFree - 1
		set this_1 = Person_nextFree[Person_firstFree]
		set Person_typeId[this_1] = 762
	endif
	return this_1
endfunction

function Person_init takes integer this_1 returns nothing
endfunction

function construct_Person takes integer this_1, unit person, string name returns nothing
	call Person_init(this_1)
	set Person_name[this_1] = name
	set Person_food[this_1] = PersonSystem_MAX_FOOD
	set Person_sleep[this_1] = PersonSystem_MAX_SLEEP
	set Person_house[this_1] = null
	set Person_workplace[this_1] = null
endfunction

function new_Person takes unit person, string name returns integer
	local integer this_1 = alloc_Person()
	call construct_Person(this_1, person, name)
	return this_1
endfunction

function unit_addPerson takes unit this_1, string name returns nothing
	local integer person
	if dispatch_UnitHashMap_UnitMap_UnitHashMap_has(PersonSystem_PERSON_MAP, this_1) == false then
		if isPersonType(GetUnitTypeId(this_1)) then
			set person = new_Person(this_1, name)
			call dispatch_IterableUnitHashMap_UnitMap_IterableUnitHashMap_put(PersonSystem_PERSON_MAP, this_1, person)
		endif
	endif
endfunction

function code__onEnter_PersonSystem takes nothing returns nothing
	call unit_addPerson(getEnterLeaveUnit(), getRandomName())
endfunction

function dispatch_UnitHashMap_UnitMap_UnitHashMap_put takes integer this_1, unit key, integer value returns nothing
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitHashMap.put")
		else
			call error("Called UnitHashMap.put on invalid object.")
		endif
	endif
	if UnitMap_typeId[this_1] <= 849 then
		call UnitHashMap_put(this_1, key, value)
	else
		call IterableUnitHashMap_put(this_1, key, value)
	endif
endfunction

function getDefaultInitWares takes integer resourceUnitId returns integer
	local integer wares = new_LinkedList()
	local integer temp = resourceUnitId
	if temp == Trees_beech then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, GetRandomInt(6, 8)))
	elseif temp == Trees_birch then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, GetRandomInt(4, 6)))
	elseif temp == Trees_greyOak then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, GetRandomInt(6, 8)))
	elseif temp == Trees_chestnut then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, GetRandomInt(4, 6)))
	endif
	return wares
endfunction

function isKilledWhenDepleted takes integer resourceUnitId returns boolean
	local integer temp = resourceUnitId
	if temp == Trees_beech then
		return true
	elseif temp == Trees_birch then
		return true
	elseif temp == Trees_greyOak then
		return true
	elseif temp == Trees_chestnut then
		return true
	else
		return false
	endif
endfunction

function alloc_Resource takes nothing returns integer
	local integer this_1
	if Stock_firstFree == 0 then
		if Stock_maxIndex < 32768 then
			set Stock_maxIndex = Stock_maxIndex + 1
			set this_1 = Stock_maxIndex
			set Stock_typeId[this_1] = 803
		else
			call error("Out of memory: Could not create Resource.")
			set this_1 = 0
		endif
	else
		set Stock_firstFree = Stock_firstFree - 1
		set this_1 = Stock_nextFree[Stock_firstFree]
		set Stock_typeId[this_1] = 803
	endif
	return this_1
endfunction

function Resource_init takes integer this_1 returns nothing
endfunction

function Stock_init takes integer this_1 returns nothing
endfunction

function construct_Stock takes integer this_1, integer wares returns nothing
	call Stock_init(this_1)
	set Stock_wares[this_1] = wares
endfunction

function construct_Resource takes integer this_1, unit resource, boolean isKilledWhenDepleted_1, integer initWares returns nothing
	call construct_Stock(this_1, initWares)
	call Resource_init(this_1)
	set Stock_user[this_1] = resource
	set Resource_isKilledWhenDepleted[this_1] = isKilledWhenDepleted_1
	set Resource_workProgress[this_1] = 0.
	set Resource_workerCount[this_1] = 0
endfunction

function new_Resource takes unit resource, boolean isKilledWhenDepleted_1, integer initWares returns integer
	local integer this_1 = alloc_Resource()
	call construct_Resource(this_1, resource, isKilledWhenDepleted_1, initWares)
	return this_1
endfunction

function unit_addResource takes unit this_1 returns nothing
	local integer unitId
	local integer wares
	if dispatch_UnitHashMap_UnitMap_UnitHashMap_has(ResourceSystem_RESOURCE_MAP, this_1) == false then
		set unitId = unit_getUnitId(this_1)
		set wares = getDefaultInitWares(unitId)
		if dispatch_LinkedList_LinkedList_LinkedList_isEmpty(wares) then
			call dispatch_LinkedList_destroyLinkedList(wares)
		else
			call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(ResourceSystem_RESOURCE_MAP, this_1, new_Resource(this_1, isKilledWhenDepleted(unitId), wares))
		endif
	endif
endfunction

function code__onEnter_ResourceSystem takes nothing returns nothing
	call unit_addResource(getEnterLeaveUnit())
endfunction

function getStorageMaxCapacity takes integer unitId returns integer
	local integer temp = unitId
	if temp == Melee_peasant then
		return 100
	elseif temp == Melee_lumberMill then
		return 50
	elseif temp == Melee_blacksmith then
		return 50
	else
		return 0
	endif
endfunction

function alloc_Storage takes nothing returns integer
	local integer this_1
	if Stock_firstFree == 0 then
		if Stock_maxIndex < 32768 then
			set Stock_maxIndex = Stock_maxIndex + 1
			set this_1 = Stock_maxIndex
			set Stock_typeId[this_1] = 804
		else
			call error("Out of memory: Could not create Storage.")
			set this_1 = 0
		endif
	else
		set Stock_firstFree = Stock_firstFree - 1
		set this_1 = Stock_nextFree[Stock_firstFree]
		set Stock_typeId[this_1] = 804
	endif
	return this_1
endfunction

function Storage_init takes integer this_1 returns nothing
endfunction

function construct_Storage takes integer this_1, unit storage, integer maxCapacity returns nothing
	call construct_Stock(this_1, new_LinkedList())
	call Storage_init(this_1)
	set Stock_user[this_1] = storage
	set Storage_maxCapacity[this_1] = maxCapacity
	set Storage_usedCapacity[this_1] = 0
endfunction

function new_Storage takes unit storage, integer maxCapacity returns integer
	local integer this_1 = alloc_Storage()
	call construct_Storage(this_1, storage, maxCapacity)
	return this_1
endfunction

function unit_addStorage takes unit this_1 returns nothing
	local integer maxCapacity = getStorageMaxCapacity(GetUnitTypeId(this_1))
	if dispatch_UnitHashMap_UnitMap_UnitHashMap_has(StorageSystem_STORAGE_MAP, this_1) == false and maxCapacity > 0 then
		call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(StorageSystem_STORAGE_MAP, this_1, new_Storage(this_1, maxCapacity))
	endif
endfunction

function code__onEnter_StorageSystem takes nothing returns nothing
	call unit_addStorage(getEnterLeaveUnit())
endfunction

function shouldIndex takes unit w_u returns boolean
	return true
endfunction

function alloc_UnitIndex takes nothing returns integer
	local integer this_1
	if UnitIndex_firstFree == 0 then
		if UnitIndex_maxIndex < 32768 then
			set UnitIndex_maxIndex = UnitIndex_maxIndex + 1
			set this_1 = UnitIndex_maxIndex
			set UnitIndex_typeId[this_1] = 846
		else
			call error("Out of memory: Could not create UnitIndex.")
			set this_1 = 0
		endif
	else
		set UnitIndex_firstFree = UnitIndex_firstFree - 1
		set this_1 = UnitIndex_nextFree[UnitIndex_firstFree]
		set UnitIndex_typeId[this_1] = 846
	endif
	return this_1
endfunction

function UnitIndex_init takes integer this_1 returns nothing
endfunction

function popUnit_1096 takes nothing returns nothing
	set UnitIndexer_tempUnitsCount = UnitIndexer_tempUnitsCount - 1
endfunction

function pushUnit_1103 takes unit u_1 returns nothing
	set UnitIndexer_tempUnits[UnitIndexer_tempUnitsCount] = u_1
	set UnitIndexer_tempUnitsCount = UnitIndexer_tempUnitsCount + 1
endfunction

function unit_setUserData takes unit this_1, integer data returns nothing
	call SetUnitUserData(this_1, data)
endfunction

function construct_UnitIndex takes integer this_1, unit whichUnit returns nothing
	call UnitIndex_init(this_1)
	set UnitIndex__unit[this_1] = whichUnit
	call unit_setUserData(UnitIndex__unit[this_1], this_1)
	call pushUnit_1103(whichUnit)
	call trigger_evaluate(UnitIndexer_onIndexTrigger)
	call popUnit_1096()
endfunction

function new_UnitIndex takes unit whichUnit returns integer
	local integer this_1 = alloc_UnitIndex()
	call construct_UnitIndex(this_1, whichUnit)
	return this_1
endfunction

function unit_getUserData takes unit this_1 returns integer
	return GetUnitUserData(this_1)
endfunction

function unit_toUnitIndex takes unit this_1 returns integer
	local integer instance = unit_getUserData(this_1)
	if instance == 0 then
		set instance = new_UnitIndex(this_1)
	endif
	return instance
endfunction

function code__onEnter_UnitIndexer takes nothing returns nothing
	if shouldIndex(getEnterLeaveUnit()) then
		call unit_toUnitIndex(getEnterLeaveUnit())
	endif
endfunction

function getRequiredWorkPower_890 takes integer buildingUnitId, integer productionVariant returns real
	local integer temp = buildingUnitId
	local integer temp_1
	local integer temp_2
	if temp == Melee_lumberMill then
		set temp_1 = productionVariant
		if temp_1 == 1 then
			return 15.
		elseif temp_1 == 2 then
			return 10.
		endif
	elseif temp == Melee_blacksmith then
		set temp_2 = productionVariant
		if temp_2 == 1 then
			return 20.
		endif
	endif
	return 0.
endfunction

function alloc_Workshop takes nothing returns integer
	local integer this_1
	if Stock_firstFree == 0 then
		if Stock_maxIndex < 32768 then
			set Stock_maxIndex = Stock_maxIndex + 1
			set this_1 = Stock_maxIndex
			set Stock_typeId[this_1] = 805
		else
			call error("Out of memory: Could not create Workshop.")
			set this_1 = 0
		endif
	else
		set Stock_firstFree = Stock_firstFree - 1
		set this_1 = Stock_nextFree[Stock_firstFree]
		set Stock_typeId[this_1] = 805
	endif
	return this_1
endfunction

function Workshop_init takes integer this_1 returns nothing
endfunction

function construct_Workshop takes integer this_1, unit workshop returns nothing
	call construct_Stock(this_1, new_LinkedList())
	call Workshop_init(this_1)
	set Stock_user[this_1] = workshop
	set Workshop_productionVariant[this_1] = 1
	set Workshop_workProgressCurrent[this_1] = 0.
	set Workshop_workProgressFinished[this_1] = getRequiredWorkPower_890(unit_getUnitId(workshop), Workshop_productionVariant[this_1])
	set Workshop_workPower[this_1] = 0.
	set Workshop_workers[this_1] = CreateGroup()
endfunction

function new_Workshop takes unit workshop returns integer
	local integer this_1 = alloc_Workshop()
	call construct_Workshop(this_1, workshop)
	return this_1
endfunction

function unit_addWorkshop takes unit this_1 returns nothing
	if dispatch_UnitHashMap_UnitMap_UnitHashMap_has(WorkshopSystem_WORKSHOP_MAP, this_1) == false and getRequiredWorkPower_890(unit_getUnitId(this_1), 1) > 0. then
		call dispatch_IterableUnitHashMap_UnitMap_IterableUnitHashMap_put(WorkshopSystem_WORKSHOP_MAP, this_1, new_Workshop(this_1))
	endif
endfunction

function code__onEnter_WorkshopSystem takes nothing returns nothing
	call unit_addWorkshop(getEnterLeaveUnit())
endfunction

function alloc_CallbackSingle_doAfter_registerPlayerUnitEvent_AbilitySystem takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 672
		else
			call error("Out of memory: Could not create CallbackSingle_doAfter_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 672
	endif
	return this_1
endfunction

function CallbackSingle_init takes integer this_1 returns nothing
endfunction

function construct_CallbackSingle takes integer this_1 returns nothing
	call CallbackSingle_init(this_1)
endfunction

function timer_setData takes timer this_1, integer data returns nothing
	call dispatch_Table_Table_Table_saveInt(TimerUtils_timerData, timer_getHandleId(this_1), data)
endfunction

function getTimer takes nothing returns timer
	local timer receiver
	if TimerUtils_freeTimersCount > 0 then
		set TimerUtils_freeTimersCount = TimerUtils_freeTimersCount - 1
		call timer_setData(TimerUtils_freeTimers[TimerUtils_freeTimersCount], 0)
		set receiver = null
		return TimerUtils_freeTimers[TimerUtils_freeTimersCount]
	else
		set receiver = CreateTimer()
		call timer_setData(receiver, 0)
		set getTimertempReturn = receiver
		set receiver = null
		return getTimertempReturn
	endif
endfunction

function CallbackSingle_start takes integer this_1, timer whichTimer, real time returns nothing
	local timer receiver = whichTimer
	local timer receiver_1
	call timer_setData(receiver, this_1)
	set receiver_1 = receiver
	call timer_start(receiver_1, time, ref_function_code__start_CallbackSingle_ClosureTimers)
	set CallbackSingle_t[this_1] = receiver_1
	set receiver = null
	set receiver_1 = null
endfunction

function dispatch_CallbackSingle_ClosureTimers_CallbackSingle_start takes integer this_1, timer whichTimer, real time returns nothing
	if CallbackSingle_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling CallbackSingle.start")
		else
			call error("Called CallbackSingle.start on invalid object.")
		endif
	endif
	call CallbackSingle_start(this_1, whichTimer, time)
endfunction

function timer_doAfter takes timer this_1, real timeToWait, integer cb returns integer
	call dispatch_CallbackSingle_ClosureTimers_CallbackSingle_start(cb, this_1, timeToWait)
	return cb
endfunction

function doAfter takes real timeToWait, integer cb returns integer
	return timer_doAfter(getTimer(), timeToWait, cb)
endfunction

function call_registerPlayerUnitEvent_AbilitySystem takes integer this_1 returns nothing
	local real temp = UtilityFunctions_MIN_TRIGGER_SLEEP_TIME
	local integer clVar = alloc_CallbackSingle_doAfter_registerPlayerUnitEvent_AbilitySystem()
	call construct_CallbackSingle(clVar)
	set source_716[clVar] = source[this_1]
	call doAfter(temp, clVar)
endfunction

function IterableUnitHashMap_remove takes integer this_1, unit key returns nothing
	call UnitHashMap_remove(this_1, key)
	call dispatch_HashList_HashList_HashList_remove(IterableUnitHashMap_keys[this_1], unitToIndex(key))
endfunction

function dispatch_UnitHashMap_UnitMap_UnitHashMap_remove takes integer this_1, unit key returns nothing
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitHashMap.remove")
		else
			call error("Called UnitHashMap.remove on invalid object.")
		endif
	endif
	if UnitMap_typeId[this_1] <= 849 then
		call UnitHashMap_remove(this_1, key)
	else
		call IterableUnitHashMap_remove(this_1, key)
	endif
endfunction

function getUnitWorkPower takes integer workerUnitId, integer buildingUnitId returns real
	local integer temp = workerUnitId
	local integer temp_1
	if temp == Melee_peasant then
		set temp_1 = buildingUnitId
		if temp_1 == Melee_townHall then
			return 1.
		elseif temp_1 == Melee_farm then
			return 1.
		elseif temp_1 == Melee_blacksmith then
			return 1.
		elseif temp_1 == Melee_lumberMill then
			return 1.
		elseif temp_1 == Melee_arcaneVault then
			return 1.
		elseif temp_1 == Melee_scoutTower then
			return 1.
		elseif temp_1 == Melee_barracks then
			return 1.
		elseif temp_1 == Melee_altarOfKings then
			return 1.
		elseif temp_1 == Melee_workshop then
			return 1.
		elseif temp_1 == Melee_arcaneSanctum then
			return 1.
		elseif temp_1 == Melee_gryphonAviary then
			return 1.
		endif
	endif
	return 0.
endfunction

function unit_removeAbility takes unit this_1, integer abil returns boolean
	return UnitRemoveAbility(this_1, abil)
endfunction

function BuildingSite_removeWorker takes integer this_1, unit worker_1 returns nothing
	if BuildingSite_workerCount[this_1] <= 0 then
		call Log_error("ERROR: Can not remove more workers from building site (" + unit_getName(Stock_user[this_1]) + ")")
	elseif dispatch_UnitHashMap_UnitMap_UnitHashMap_get(BuildingSystem_WORKER_MAP, worker_1) == this_1 then
		call dispatch_UnitHashMap_UnitMap_UnitHashMap_remove(BuildingSystem_WORKER_MAP, worker_1)
		set BuildingSite_workPower[this_1] = BuildingSite_workPower[this_1] - getUnitWorkPower(unit_getUnitId(worker_1), unit_getUnitId(Stock_user[this_1]))
		set BuildingSite_workerCount[this_1] = BuildingSite_workerCount[this_1] - 1
		call ResetUnitAnimation(worker_1)
		call unit_removeAbility(worker_1, BuffIdsCustom_building)
	else
		call Log_error("ERROR: Can't remove worker from this building site")
	endif
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_removeWorker takes integer this_1, unit worker_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.removeWorker")
		else
			call error("Called BuildingSite.removeWorker on invalid object.")
		endif
	endif
	call BuildingSite_removeWorker(this_1, worker_1)
endfunction

function call_registerPlayerUnitEvent_AbilitySystem_570 takes integer this_1 returns nothing
	call dispatch_BuildingSite_BuildingSystem_BuildingSite_removeWorker(targetBuildingSite[this_1], source_717[this_1])
endfunction

function boolexpr_destr takes boolexpr this_1 returns nothing
	call DestroyBoolExpr(this_1)
endfunction

function group_enumUnitsInRange takes group this_1, real pos_x, real pos_y, real range, boolexpr filter returns nothing
	call GroupEnumUnitsInRange(this_1, pos_x, pos_y, range, filter)
endfunction

function unit_getX takes unit this_1 returns real
	return GetUnitX(this_1)
endfunction

function unit_getY takes unit this_1 returns real
	return GetUnitY(this_1)
endfunction

function unit_getPos takes unit this_1 returns real
	set unit_getPos_return_x = unit_getX(this_1)
	set unit_getPos_return_y = unit_getY(this_1)
	return unit_getPos_return_x
endfunction

function unit_getStorage takes unit this_1 returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(StorageSystem_STORAGE_MAP, this_1)
endfunction

function unit_getOwner takes unit this_1 returns player
	return GetOwningPlayer(this_1)
endfunction

function real_squared takes real this_1 returns real
	return this_1 * this_1
endfunction

function vec2_distanceToSq takes real this_x, real this_y, real v_x, real v_y returns real
	return real_squared(v_x - this_x) + real_squared(v_y - this_y)
endfunction

function vec2_getNearestUnit takes real this_x, real this_y, group validUnits, player owner returns unit
	local real bestDistanceSq = Real_REAL_MAX
	local unit nearestUnit = null
	local group from = validUnits
	local unit target_1
	local real distanceSq
	loop
		exitwhen  not group_hasNext(from)
		set target_1 = group_next(from)
		if owner == null or unit_getOwner(target_1) == owner then
			set distanceSq = vec2_distanceToSq(this_x, this_y, unit_getPos(target_1), unit_getPos_return_y)
			if distanceSq < bestDistanceSq then
				set bestDistanceSq = distanceSq
				set nearestUnit = target_1
			endif
		endif
	endloop
	set vec2_getNearestUnittempReturn = nearestUnit
	set nearestUnit = null
	set target_1 = null
	set from = null
	return vec2_getNearestUnittempReturn
endfunction

function vec2_getNearestUnit_1246 takes real this_x, real this_y, group validUnits returns unit
	return vec2_getNearestUnit(this_x, this_y, validUnits, null)
endfunction

function unit_findNextResource takes unit this_1 returns unit
	local real pos_x
	local real pos_y
	local filterfunc filter
	local unit target_1
	local group from
	local real tuple_temp
	local real tuple_temp_1
	if dispatch_Storage_StorageSystem_Storage_getFreeCapacity(unit_getStorage(this_1)) > 0 then
		set tuple_temp = unit_getPos(this_1)
		set tuple_temp_1 = unit_getPos_return_y
		set pos_x = tuple_temp
		set pos_y = tuple_temp_1
		set ResourceSystem_findNextResource_Priority = 0
		set filter = Filter(ref_function_code__Filter_ResourceSystem)
		call group_enumUnitsInRange(Group_ENUM_GROUP, pos_x, pos_y, ResourceSystem_MAX_AUTO_ORDER_RANGE, filter)
		call boolexpr_destr(filter)
		set from = Group_ENUM_GROUP
		loop
			exitwhen  not group_hasNext(from)
			set target_1 = group_next(from)
			if getHarvestPriority(unit_getUnitId(target_1)) == ResourceSystem_findNextResource_Priority then
				call group_addUnit_1(ResourceSystem_findNextResource_ValidUnits, target_1)
			endif
		endloop
		set filter = null
		set target_1 = null
		set from = null
		return vec2_getNearestUnit_1246(pos_x, pos_y, ResourceSystem_findNextResource_ValidUnits)
	else
		set filter = null
		set target_1 = null
		set from = null
		return null
	endif
endfunction

function int_getAbilityOrder takes integer this_1 returns string
	local integer temp = this_1
	if temp == AbilityIdsCustom_harvest then
		return "thunderbolt"
	elseif temp == AbilityIdsCustom_build then
		return "shadowstrike"
	elseif temp == AbilityIdsCustom_showTargetInfo then
		return "thunderbolt"
	elseif temp == AbilityIdsCustom_transferWares then
		return "frostnova"
	elseif temp == AbilityIdsCustom_addBuildingBuff then
		return "innerfire"
	else
		call Log_error("ERROR: Unmapped ability id (" + int_toString(this_1) + ")")
		return null
	endif
endfunction

function unit_issueTargetOrder takes unit this_1, string order, widget targetWidget returns boolean
	return IssueTargetOrder(this_1, order, targetWidget)
endfunction

function unit_issueTargetAbilityOrder takes unit this_1, integer abilityId, widget target_1, boolean resetAbility returns boolean
	if resetAbility then
		call unit_removeAbility(this_1, abilityId)
		call unit_addAbility(this_1, abilityId)
	endif
	return unit_issueTargetOrder(this_1, int_getAbilityOrder(abilityId), target_1)
endfunction

function call_registerPlayerUnitEvent_AbilitySystem_571 takes integer this_1 returns nothing
	call unit_issueTargetAbilityOrder(source_718[this_1], AbilityIdsCustom_harvest, unit_findNextResource(source_718[this_1]), true)
endfunction

function Resource_removeWorker takes integer this_1 returns nothing
	if Resource_workerCount[this_1] <= 0 then
		call Log_error("ERROR: Can not remove more workers from resource (" + unit_getName(Stock_user[this_1]) + ")")
	endif
	set Resource_workerCount[this_1] = Resource_workerCount[this_1] - 1
endfunction

function dispatch_Resource_ResourceSystem_Resource_removeWorker takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Resource.removeWorker")
		else
			call error("Called Resource.removeWorker on invalid object.")
		endif
	endif
	call Resource_removeWorker(this_1)
endfunction

function call_registerPlayerUnitEvent_AbilitySystem_572 takes integer this_1 returns nothing
	call dispatch_Resource_ResourceSystem_Resource_removeWorker(targetResource[this_1])
endfunction

function Resource_checkForDepletionKill takes integer this_1 returns boolean
	if Resource_isKilledWhenDepleted[this_1] and dispatch_LinkedList_LinkedList_LinkedList_isEmpty(Stock_wares[this_1]) then
		return true
	endif
	return false
endfunction

function dispatch_Resource_ResourceSystem_Resource_checkForDepletionKill takes integer this_1 returns boolean
	local boolean ResourceSystem_Resource_checkForDepletionKill_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Resource.checkForDepletionKill")
		else
			call error("Called Resource.checkForDepletionKill on invalid object.")
		endif
	endif
	set ResourceSystem_Resource_checkForDepletionKill_result = Resource_checkForDepletionKill(this_1)
	return ResourceSystem_Resource_checkForDepletionKill_result
endfunction

function Resource_work takes integer this_1, real workProgress returns boolean
	set Resource_workProgress[this_1] = Resource_workProgress[this_1] + workProgress
	if Resource_workProgress[this_1] >= 1. then
		set Resource_workProgress[this_1] = Resource_workProgress[this_1] - 1.
		return true
	else
		return false
	endif
endfunction

function dispatch_Resource_ResourceSystem_Resource_work takes integer this_1, real workProgress returns boolean
	local boolean ResourceSystem_Resource_work_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Resource.work")
		else
			call error("Called Resource.work on invalid object.")
		endif
	endif
	set ResourceSystem_Resource_work_result = Resource_work(this_1, workProgress)
	return ResourceSystem_Resource_work_result
endfunction

function getWaresPerFinishedWork takes integer resourceUnitId returns integer
	local integer wares = new_LinkedList()
	local integer temp = resourceUnitId
	if temp == Trees_beech then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 1))
	elseif temp == Trees_birch then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 1))
	elseif temp == Trees_greyOak then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 1))
	elseif temp == Trees_chestnut then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 1))
	endif
	return wares
endfunction

function getWorkProgressPerHarvest takes integer workerUnitId, integer resourceUnitId returns real
	local integer temp = resourceUnitId
	local integer temp_1
	if temp == Trees_beech then
		set temp_1 = workerUnitId
		if temp_1 == Melee_peasant then
			return 0.67
		endif
		return 0.5
	elseif temp == Trees_birch then
		return 0.5
	elseif temp == Trees_greyOak then
		return 0.5
	elseif temp == Trees_chestnut then
		return 0.5
	else
		return 0.
	endif
endfunction

function Resource_harvest takes integer this_1, integer workerUnitId returns integer
	local integer resourceUnitId = unit_getUnitId(Stock_user[this_1])
	if dispatch_Resource_ResourceSystem_Resource_work(this_1, getWorkProgressPerHarvest(workerUnitId, resourceUnitId)) then
		return getWaresPerFinishedWork(resourceUnitId)
	endif
	return 0
endfunction

function dispatch_Resource_ResourceSystem_Resource_harvest takes integer this_1, integer workerUnitId returns integer
	local integer ResourceSystem_Resource_harvest_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Resource.harvest")
		else
			call error("Called Resource.harvest on invalid object.")
		endif
	endif
	set ResourceSystem_Resource_harvest_result = Resource_harvest(this_1, workerUnitId)
	return ResourceSystem_Resource_harvest_result
endfunction

function Stock_hasWaresAny takes integer this_1, integer wares returns boolean
	local integer iterator = LinkedList_iterator(wares)
	local integer iWare_wareType
	local integer tuple_temp
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set iWare_wareType = tuple_temp
		if dispatch_Stock_Stock_Stock_getWareCount(this_1, iWare_wareType) > 0 then
			call LLIterator_close(iterator)
			return true
		endif
	endloop
	call LLIterator_close(iterator)
	return false
endfunction

function dispatch_Stock_Stock_Stock_hasWaresAny takes integer this_1, integer wares returns boolean
	local boolean Stock_Stock_hasWaresAny_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.hasWaresAny")
		else
			call error("Called Stock.hasWaresAny on invalid object.")
		endif
	endif
	set Stock_Stock_hasWaresAny_result = Stock_hasWaresAny(this_1, wares)
	return Stock_Stock_hasWaresAny_result
endfunction

function Storage_getUsedCapacity takes integer this_1 returns integer
	return Storage_usedCapacity[this_1]
endfunction

function dispatch_Storage_StorageSystem_Storage_getUsedCapacity takes integer this_1 returns integer
	local integer StorageSystem_Storage_getUsedCapacity_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.getUsedCapacity")
		else
			call error("Called Storage.getUsedCapacity on invalid object.")
		endif
	endif
	set StorageSystem_Storage_getUsedCapacity_result = Storage_getUsedCapacity(this_1)
	return StorageSystem_Storage_getUsedCapacity_result
endfunction

function group_size takes group this_1 returns integer
	return BlzGroupGetSize(this_1)
endfunction

function Workshop_getWorkerCount takes integer this_1 returns integer
	return group_size(Workshop_workers[this_1])
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_getWorkerCount takes integer this_1 returns integer
	local integer WorkshopSystem_Workshop_getWorkerCount_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.getWorkerCount")
		else
			call error("Called Workshop.getWorkerCount on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_getWorkerCount_result = Workshop_getWorkerCount(this_1)
	return WorkshopSystem_Workshop_getWorkerCount_result
endfunction

function getUnitWorkPower_896 takes integer workerUnitId, integer buildingUnitId returns real
	local integer temp = workerUnitId
	local integer temp_1
	if temp == Melee_peasant then
		set temp_1 = buildingUnitId
		if temp_1 == Melee_lumberMill then
			return 1.
		elseif temp_1 == Melee_blacksmith then
			return 1.
		endif
	endif
	return 0.
endfunction

function Workshop_isValidWorkerType takes integer this_1, integer unitId returns boolean
	return getUnitWorkPower_896(unitId, unit_getUnitId(Stock_user[this_1])) > 0.
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_isValidWorkerType takes integer this_1, integer unitId returns boolean
	local boolean WorkshopSystem_Workshop_isValidWorkerType_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.isValidWorkerType")
		else
			call error("Called Workshop.isValidWorkerType on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_isValidWorkerType_result = Workshop_isValidWorkerType(this_1, unitId)
	return WorkshopSystem_Workshop_isValidWorkerType_result
endfunction

function getMaxWorkers takes integer buildingUnitId returns integer
	local integer temp = buildingUnitId
	if temp == Melee_lumberMill then
		return 3
	elseif temp == Melee_blacksmith then
		return 3
	endif
	return 0
endfunction

function int_isValidWorkerType takes integer this_1, integer workerUnitId returns boolean
	return getUnitWorkPower(workerUnitId, this_1) > 0.
endfunction

function unit_getBuildingSiteOfWorker takes unit this_1 returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(BuildingSystem_WORKER_MAP, this_1)
endfunction

function unit_getWorkshop takes unit this_1 returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(WorkshopSystem_WORKSHOP_MAP, this_1)
endfunction

function unit_getAbilityValidity takes unit this_1, integer abilityId, unit target_1 returns integer
	local integer sourceStorage
	local integer targetStorage
	local integer targetWorkshop
	local integer targetBuildingSite_1
	local integer educts
	local boolean hasAnyEducts
	local integer buildingSite
	local integer storage
	local integer resource
	local integer targetWorkshop_1
	local integer sourceWorkshop
	local integer sourceWorkshop_1
	if abilityId == AbilityIdsCustom_transferWares then
		set sourceStorage = unit_getStorage(this_1)
		if sourceStorage == 0 then
			return 3
		endif
		set targetStorage = unit_getStorage(target_1)
		set targetWorkshop = unit_getWorkshop(target_1)
		set targetBuildingSite_1 = unit_getBuildingSite(target_1)
		if targetStorage == 0 and targetWorkshop == 0 and targetBuildingSite_1 == 0 then
			return 4
		endif
		if dispatch_Storage_StorageSystem_Storage_getUsedCapacity(sourceStorage) <= 0 then
			return 5
		endif
		if targetStorage != 0 and dispatch_Storage_StorageSystem_Storage_getFreeCapacity(targetStorage) <= 0 then
			return 8
		endif
		if targetBuildingSite_1 != 0 and dispatch_Stock_Stock_Stock_isEmpty(targetBuildingSite_1) then
			return 9
		endif
		if targetWorkshop != 0 then
			set educts = dispatch_Workshop_WorkshopSystem_Workshop_getEducts(targetWorkshop)
			set hasAnyEducts = dispatch_Stock_Stock_Stock_hasWaresAny(sourceStorage, educts)
			call dispatch_LinkedList_destroyLinkedList(educts)
			if hasAnyEducts == false then
				return 9
			endif
		endif
	elseif abilityId == AbilityIdsCustom_build then
		if int_isValidWorkerType(unit_getUnitId(target_1), unit_getUnitId(this_1)) == false then
			return 3
		endif
		set buildingSite = unit_getBuildingSite(target_1)
		if buildingSite == 0 then
			return 4
		endif
		if dispatch_Stock_Stock_Stock_isEmpty(buildingSite) == false then
			return 5
		endif
		if unit_getBuildingSiteOfWorker(this_1) != 0 then
			return 10
		endif
	elseif abilityId == AbilityIdsCustom_harvest then
		set storage = unit_getStorage(this_1)
		if storage == 0 then
			return 3
		endif
		set resource = unit_getResource(target_1)
		if resource == 0 then
			return 4
		endif
		if dispatch_Storage_StorageSystem_Storage_getFreeCapacity(storage) <= 0 then
			return 8
		elseif dispatch_Stock_Stock_Stock_isEmpty(resource) then
			return 11
		elseif dispatch_Resource_ResourceSystem_Resource_getFreeWorkerSlots(resource) <= 0 then
			return 7
		endif
	elseif abilityId == AbilityIdsCustom_enterBuilding then
		set targetWorkshop_1 = unit_getWorkshop(target_1)
		if targetWorkshop_1 == 0 then
			return 4
		endif
		if dispatch_Workshop_WorkshopSystem_Workshop_isValidWorkerType(targetWorkshop_1, unit_getUnitId(this_1)) then
			return 3
		endif
		if dispatch_Workshop_WorkshopSystem_Workshop_getWorkerCount(targetWorkshop_1) >= getMaxWorkers(unit_getUnitId(target_1)) then
			return 7
		endif
	elseif abilityId == AbilityIdsCustom_removeWorker then
		set sourceWorkshop = unit_getWorkshop(this_1)
		if sourceWorkshop == 0 then
			call Log_error("ERROR: Casting building is no workshop (" + unit_getName(this_1) + ")")
			return 2
		endif
		if dispatch_Workshop_WorkshopSystem_Workshop_getWorkerCount(sourceWorkshop) <= 0 then
			return 6
		endif
	elseif abilityId == AbilityIdsCustom_changeProduct then
		set sourceWorkshop_1 = unit_getWorkshop(this_1)
		if sourceWorkshop_1 == 0 then
			call Log_error("ERROR: Casting building is no workshop (" + unit_getName(this_1) + ")")
			return 2
		endif
	else
		return 1
	endif
	return 0
endfunction

function unit_isAbilityValid takes unit this_1, integer abilityId, unit target_1 returns boolean
	return unit_getAbilityValidity(this_1, abilityId, target_1) == 0
endfunction

function unit_kill takes unit this_1 returns nothing
	call KillUnit(this_1)
endfunction

function unit_harvest takes unit this_1, unit target_1 returns boolean
	local integer storage = unit_getStorage(this_1)
	local integer resource = unit_getResource(target_1)
	local integer wares = dispatch_Resource_ResourceSystem_Resource_harvest(resource, unit_getUnitId(this_1))
	local integer iterator
	local integer iWare_wareType
	local integer iWare_count
	local integer resourceWareCount
	local integer freeCapacity
	local integer tuple_temp
	local integer tuple_temp_1
	if wares != 0 then
		set iterator = LinkedList_iterator(wares)
		loop
			exitwhen  not LLIterator_hasNext(iterator)
			set tuple_temp = wareFromIndex(LLIterator_next(iterator))
			set tuple_temp_1 = wareFromIndex_return_count
			set iWare_wareType = tuple_temp
			set iWare_count = tuple_temp_1
			set resourceWareCount = dispatch_Stock_Stock_Stock_getWareCount(resource, iWare_wareType)
			set freeCapacity = dispatch_Storage_StorageSystem_Storage_getFreeCapacity(storage)
			if resourceWareCount > 0 and freeCapacity > 0 then
				if resourceWareCount < iWare_count then
					set iWare_count = resourceWareCount
				endif
				if freeCapacity < iWare_count then
					set iWare_count = freeCapacity
				endif
				call dispatch_Storage_StorageSystem_Storage_addWare(storage, iWare_wareType, iWare_count)
				call dispatch_Stock_Stock_Stock_removeWare(resource, iWare_wareType, iWare_count)
			endif
		endloop
		call LLIterator_close(iterator)
		call dispatch_LinkedList_destroyLinkedList(wares)
		if dispatch_Resource_ResourceSystem_Resource_checkForDepletionKill(resource) then
			call unit_kill(target_1)
			return false
		endif
	endif
	return unit_isAbilityValid(this_1, AbilityIdsCustom_harvest, target_1)
endfunction

function call_registerPlayerUnitEvent_AbilitySystem_573 takes integer this_1 returns nothing
	call dispatch_Resource_ResourceSystem_Resource_removeWorker(targetResource_732[this_1])
	if unit_harvest(source_719[this_1], target[this_1]) then
		call unit_issueTargetAbilityOrder(source_719[this_1], AbilityIdsCustom_harvest, target[this_1], true)
	else
		call unit_issueTargetAbilityOrder(source_719[this_1], AbilityIdsCustom_harvest, unit_findNextResource(source_719[this_1]), true)
	endif
endfunction

function call_setOrder_registerPlayerUnitEvent_AbilitySystem takes integer this_1 returns boolean
	return unit_issueTargetAbilityOrder(source_720[this_1], AbilityIdsCustom_harvest, unit_findNextResource(source_720[this_1]), true)
endfunction

function call_setOrder_registerPlayerUnitEvent_AbilitySystem_576 takes integer this_1 returns nothing
	call dispatch_Resource_ResourceSystem_Resource_removeWorker(targetResource_733[this_1])
endfunction

function findNextBuildingSite_GetFilter takes nothing returns filterfunc
	return Filter(ref_function_code__Filter_BuildingSystem)
endfunction

function unit_findNextBuildingSite takes unit this_1 returns unit
	local player owner = unit_getOwner(this_1)
	local real tuple_temp = unit_getPos(this_1)
	local real tuple_temp_1 = unit_getPos_return_y
	local real pos_x = tuple_temp
	local real pos_y = tuple_temp_1
	local integer workerUnitId = unit_getUnitId(this_1)
	local filterfunc filter = findNextBuildingSite_GetFilter()
	local real bestDistanceSq = Real_REAL_MAX
	local unit nearestBuilding = null
	local unit target_1
	local group from
	local real distanceSq
	call group_enumUnitsInRange(Group_ENUM_GROUP, pos_x, pos_y, BuildingSystem_MAX_AUTO_ORDER_RANGE, filter)
	set from = Group_ENUM_GROUP
	loop
		exitwhen  not group_hasNext(from)
		set target_1 = group_next(from)
		if unit_getOwner(target_1) == owner and int_isValidWorkerType(unit_getUnitId(target_1), workerUnitId) then
			set distanceSq = vec2_distanceToSq(pos_x, pos_y, unit_getPos(target_1), unit_getPos_return_y)
			if distanceSq < bestDistanceSq then
				set bestDistanceSq = distanceSq
				set nearestBuilding = target_1
			endif
		endif
	endloop
	call boolexpr_destr(filter)
	set unit_findNextBuildingSitetempReturn = nearestBuilding
	set owner = null
	set filter = null
	set nearestBuilding = null
	set target_1 = null
	set from = null
	return unit_findNextBuildingSitetempReturn
endfunction

function call_setOrder_registerPlayerUnitEvent_AbilitySystem_577 takes integer this_1 returns boolean
	return unit_issueTargetAbilityOrder(source_721[this_1], AbilityIdsCustom_build, unit_findNextBuildingSite(source_721[this_1]), true)
endfunction

function dealloc_OrderAction takes integer obj returns nothing
	if OrderAction_typeId[obj] == 0 then
		call error("Double free: object of type OrderAction")
	else
		set OrderAction_nextFree[OrderAction_firstFree] = obj
		set OrderAction_firstFree = OrderAction_firstFree + 1
		set OrderAction_typeId[obj] = 0
	endif
endfunction

function dealloc_OrderSource takes integer obj returns nothing
	if OrderSource_typeId[obj] == 0 then
		call error("Double free: object of type OrderSource")
	else
		set OrderSource_nextFree[OrderSource_firstFree] = obj
		set OrderSource_firstFree = OrderSource_firstFree + 1
		set OrderSource_typeId[obj] = 0
	endif
endfunction

function dealloc_OrderSourceU takes integer obj returns nothing
	if OrderSource_typeId[obj] == 0 then
		call error("Double free: object of type OrderSourceU")
	else
		set OrderSource_nextFree[OrderSource_firstFree] = obj
		set OrderSource_firstFree = OrderSource_firstFree + 1
		set OrderSource_typeId[obj] = 0
	endif
endfunction

function dealloc_CallbackCondition takes integer obj returns nothing
	if CallbackCondition_typeId[obj] == 0 then
		call error("Double free: object of type CallbackCondition")
	else
		set CallbackCondition_nextFree[CallbackCondition_firstFree] = obj
		set CallbackCondition_firstFree = CallbackCondition_firstFree + 1
		set CallbackCondition_typeId[obj] = 0
	endif
endfunction

function destroyCallbackCondition takes integer this_1 returns nothing
	call dealloc_CallbackCondition(this_1)
endfunction

function dispatch_CallbackCondition_destroyCallbackCondition takes integer this_1 returns nothing
	if CallbackCondition_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling CallbackCondition.CallbackCondition")
		else
			call error("Called CallbackCondition.CallbackCondition on invalid object.")
		endif
	endif
	call destroyCallbackCondition(this_1)
endfunction

function dealloc_CallbackSimple takes integer obj returns nothing
	if CallbackSimple_typeId[obj] == 0 then
		call error("Double free: object of type CallbackSimple")
	else
		set CallbackSimple_nextFree[CallbackSimple_firstFree] = obj
		set CallbackSimple_firstFree = CallbackSimple_firstFree + 1
		set CallbackSimple_typeId[obj] = 0
	endif
endfunction

function destroyCallbackSimple takes integer this_1 returns nothing
	call dealloc_CallbackSimple(this_1)
endfunction

function dispatch_CallbackSimple_destroyCallbackSimple takes integer this_1 returns nothing
	if CallbackSimple_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling CallbackSimple.CallbackSimple")
		else
			call error("Called CallbackSimple.CallbackSimple on invalid object.")
		endif
	endif
	call destroyCallbackSimple(this_1)
endfunction

function LinkedList_has takes integer this_1, integer elem returns boolean
	local integer entry = LLEntry_next[LinkedList_dummy[this_1]]
	loop
		exitwhen  not (entry != LinkedList_dummy[this_1])
		if LLEntry_elem[entry] == elem then
			return true
		endif
		set entry = LLEntry_next[entry]
	endloop
	return false
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_has takes integer this_1, integer elem returns boolean
	local boolean LinkedList_LinkedList_has_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.has")
		else
			call error("Called LinkedList.has on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_has_result = LinkedList_has(this_1, elem)
	return LinkedList_LinkedList_has_result
endfunction

function OrderTarget_removeSource takes integer this_1, integer source_1 returns nothing
	if dispatch_LinkedList_LinkedList_LinkedList_has(OrderTarget_sources[this_1], source_1) then
		call dispatch_LinkedList_LinkedList_LinkedList_remove(OrderTarget_sources[this_1], source_1)
	else
		call Log_error("ERROR: Source does not have that target")
	endif
endfunction

function dispatch_OrderTarget_OrderSystem_OrderTarget_removeSource takes integer this_1, integer source_1 returns nothing
	if OrderTarget_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling OrderTarget.removeSource")
		else
			call error("Called OrderTarget.removeSource on invalid object.")
		endif
	endif
	call OrderTarget_removeSource(this_1, source_1)
endfunction

function UnitHashMap_tryRemove takes integer this_1, unit key returns integer
	local integer value
	if dispatch_HashMap_HashMap_HashMap_has(UnitHashMap_map[this_1], unitToIndex(key)) then
		set value = dispatch_HashMap_HashMap_HashMap_get(UnitHashMap_map[this_1], unitToIndex(key))
		call dispatch_HashMap_HashMap_HashMap_remove(UnitHashMap_map[this_1], unitToIndex(key))
		return value
	else
		return UnitHashMap_nullElem[this_1]
	endif
endfunction

function dispatch_UnitHashMap_UnitMap_UnitHashMap_tryRemove takes integer this_1, unit key returns integer
	local integer UnitMap_UnitHashMap_tryRemove_result
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitHashMap.tryRemove")
		else
			call error("Called UnitHashMap.tryRemove on invalid object.")
		endif
	endif
	if UnitMap_typeId[this_1] <= 849 then
		set UnitMap_UnitHashMap_tryRemove_result = UnitHashMap_tryRemove(this_1, key)
	else
		set UnitMap_UnitHashMap_tryRemove_result = IterableUnitHashMap_tryRemove(this_1, key)
	endif
	return UnitMap_UnitHashMap_tryRemove_result
endfunction

function timer_pause takes timer this_1 returns nothing
	call PauseTimer(this_1)
endfunction

function timer_release takes timer this_1 returns nothing
	if this_1 == null then
		call error("Trying to release a null timer")
		return
	endif
	if timer_getData(this_1) == TimerUtils_HELD then
		call error("ReleaseTimer: Double free!")
		return
	endif
	call timer_setData(this_1, TimerUtils_HELD)
	call timer_pause(this_1)
	set TimerUtils_freeTimers[TimerUtils_freeTimersCount] = this_1
	set TimerUtils_freeTimersCount = TimerUtils_freeTimersCount + 1
endfunction

function cyc_unit_removeSourceOrder takes integer funcChoice, unit this_1, integer this_2 returns nothing
	local integer orderSource
	local integer orderTarget
	if funcChoice == 0 then
		set orderSource = dispatch_UnitHashMap_UnitMap_UnitHashMap_tryRemove(OrderSystem_ORDER_SOURCE_MAP, this_1)
		if orderSource != 0 then
			call cyc_unit_removeSourceOrder(11, null, orderSource)
		endif
	elseif funcChoice == 1 then
		call cyc_unit_removeSourceOrder(0, source_726[this_2], 0)
	elseif funcChoice == 2 then
		call cyc_unit_removeSourceOrder(0, source_727[this_2], 0)
	elseif funcChoice == 3 then
		set orderTarget = dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(OrderSystem_ORDER_TARGET_MAP, OrderSourceU_target[this_2])
		if orderTarget != 0 then
			call dispatch_OrderTarget_OrderSystem_OrderTarget_removeSource(orderTarget, this_2)
		endif
		call cyc_unit_removeSourceOrder(12, null, this_2)
	elseif funcChoice == 4 then
		call cyc_unit_removeSourceOrder(0, source_722[this_2], 0)
	elseif funcChoice == 5 then
		if CallbackSimple_typeId[this_2] == 0 then
			if this_2 == 0 then
				call error("Nullpointer exception when calling CallbackSimple.call")
			else
				call error("Called CallbackSimple.call on invalid object.")
			endif
		endif
		if CallbackSimple_typeId[this_2] <= 657 then
			if CallbackSimple_typeId[this_2] <= 654 then
				if CallbackSimple_typeId[this_2] <= 652 then
					if CallbackSimple_typeId[this_2] <= 651 then
						call call_registerPlayerUnitEvent_AbilitySystem(this_2)
					else
						call call_registerPlayerUnitEvent_AbilitySystem_570(this_2)
					endif
				elseif CallbackSimple_typeId[this_2] <= 653 then
					call call_registerPlayerUnitEvent_AbilitySystem_571(this_2)
				else
					call call_registerPlayerUnitEvent_AbilitySystem_572(this_2)
				endif
			elseif CallbackSimple_typeId[this_2] <= 656 then
				if CallbackSimple_typeId[this_2] <= 655 then
					call call_registerPlayerUnitEvent_AbilitySystem_573(this_2)
				else
					call cyc_unit_removeSourceOrder(4, null, this_2)
				endif
			else
				call cyc_unit_removeSourceOrder(6, null, this_2)
			endif
		elseif CallbackSimple_typeId[this_2] <= 660 then
			if CallbackSimple_typeId[this_2] <= 659 then
				if CallbackSimple_typeId[this_2] <= 658 then
					call cyc_unit_removeSourceOrder(9, null, this_2)
				else
					call cyc_unit_removeSourceOrder(1, null, this_2)
				endif
			else
				call cyc_unit_removeSourceOrder(2, null, this_2)
			endif
		elseif CallbackSimple_typeId[this_2] <= 662 then
			if CallbackSimple_typeId[this_2] <= 661 then
				call call_setOrder_registerPlayerUnitEvent_AbilitySystem(this_2)
			else
				call call_setOrder_registerPlayerUnitEvent_AbilitySystem_576(this_2)
			endif
		else
			call call_setOrder_registerPlayerUnitEvent_AbilitySystem_577(this_2)
		endif
	elseif funcChoice == 6 then
		call cyc_unit_removeSourceOrder(0, source_723[this_2], 0)
	elseif funcChoice == 7 then
		call cyc_unit_removeSourceOrder(3, null, this_2)
		call dealloc_OrderSourceU(this_2)
	elseif funcChoice == 8 then
		if OrderAction_typeId[this_2] == 0 then
			if this_2 == 0 then
				call error("Nullpointer exception when calling OrderAction.OrderAction")
			else
				call error("Called OrderAction.OrderAction on invalid object.")
			endif
		endif
		call cyc_unit_removeSourceOrder(13, null, this_2)
	elseif funcChoice == 9 then
		call cyc_unit_removeSourceOrder(0, source_724[this_2], 0)
	elseif funcChoice == 10 then
		if OrderAction_t[this_2] != null then
			call timer_release(OrderAction_t[this_2])
		endif
		if OrderAction_invalidateCb[this_2] != 0 then
			call dispatch_CallbackSimple_destroyCallbackSimple(OrderAction_invalidateCb[this_2])
		endif
		if OrderAction_cancelCb[this_2] != 0 then
			call cyc_unit_removeSourceOrder(5, null, OrderAction_cancelCb[this_2])
			call dispatch_CallbackSimple_destroyCallbackSimple(OrderAction_cancelCb[this_2])
		endif
		if OrderAction_finishCb[this_2] != 0 then
			call dispatch_CallbackSimple_destroyCallbackSimple(OrderAction_finishCb[this_2])
		endif
		if OrderAction_finishCondition[this_2] != 0 then
			call dispatch_CallbackCondition_destroyCallbackCondition(OrderAction_finishCondition[this_2])
		endif
	elseif funcChoice == 11 then
		if OrderSource_typeId[this_2] == 0 then
			if this_2 == 0 then
				call error("Nullpointer exception when calling OrderSource.OrderSource")
			else
				call error("Called OrderSource.OrderSource on invalid object.")
			endif
		endif
		if OrderSource_typeId[this_2] <= 759 then
			if OrderSource_typeId[this_2] <= 758 then
				call cyc_unit_removeSourceOrder(14, null, this_2)
			else
				call cyc_unit_removeSourceOrder(7, null, this_2)
			endif
		else
			call cyc_unit_removeSourceOrder(14, null, this_2)
		endif
	elseif funcChoice == 12 then
		if OrderSource_orderAction[this_2] != 0 then
			call cyc_unit_removeSourceOrder(8, null, OrderSource_orderAction[this_2])
		endif
	elseif funcChoice == 13 then
		call cyc_unit_removeSourceOrder(10, null, this_2)
		call dealloc_OrderAction(this_2)
	elseif funcChoice == 14 then
		call cyc_unit_removeSourceOrder(12, null, this_2)
		call dealloc_OrderSource(this_2)
	endif
endfunction

function LinkedList_copy takes integer this_1 returns integer
	local integer list = new_LinkedList()
	local integer iterator = LinkedList_iterator(this_1)
	local integer elem
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set elem = LLIterator_next(iterator)
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(list, elem)
	endloop
	call LLIterator_close(iterator)
	return list
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_copy takes integer this_1 returns integer
	local integer LinkedList_LinkedList_copy_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.copy")
		else
			call error("Called LinkedList.copy on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_copy_result = LinkedList_copy(this_1)
	return LinkedList_LinkedList_copy_result
endfunction

function LinkedList_pop takes integer this_1 returns integer
	local integer top = LLEntry_prev[LinkedList_dummy[this_1]]
	local integer result_1 = 0
	if top != LinkedList_dummy[this_1] then
		set result_1 = LLEntry_elem[top]
		call dispatch_LinkedList_LinkedList_LinkedList_removeEntry(this_1, top)
	endif
	return result_1
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_pop takes integer this_1 returns integer
	local integer LinkedList_LinkedList_pop_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.pop")
		else
			call error("Called LinkedList.pop on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_pop_result = LinkedList_pop(this_1)
	return LinkedList_LinkedList_pop_result
endfunction

function OrderAction_invalidate takes integer this_1 returns nothing
	if OrderAction_invalidateCb[this_1] != 0 then
		call cyc_unit_removeSourceOrder(5, null, OrderAction_invalidateCb[this_1])
	endif
	call cyc_unit_removeSourceOrder(8, null, this_1)
endfunction

function dispatch_OrderAction_OrderSystem_OrderAction_invalidate takes integer this_1 returns nothing
	if OrderAction_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling OrderAction.invalidate")
		else
			call error("Called OrderAction.invalidate on invalid object.")
		endif
	endif
	call OrderAction_invalidate(this_1)
endfunction

function OrderSource_invalidate takes integer this_1 returns nothing
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(OrderSystem_ORDER_SOURCE_MAP, OrderSource_source[this_1], 0)
	if OrderSource_orderAction[this_1] != 0 then
		call dispatch_OrderAction_OrderSystem_OrderAction_invalidate(OrderSource_orderAction[this_1])
		set OrderSource_orderAction[this_1] = 0
	endif
	call cyc_unit_removeSourceOrder(11, null, this_1)
endfunction

function dispatch_OrderSource_OrderSystem_OrderSource_invalidate takes integer this_1 returns nothing
	if OrderSource_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling OrderSource.invalidate")
		else
			call error("Called OrderSource.invalidate on invalid object.")
		endif
	endif
	call OrderSource_invalidate(this_1)
endfunction

function OrderTarget_onDestroy takes integer this_1 returns nothing
	local integer cancelList = dispatch_LinkedList_LinkedList_LinkedList_copy(OrderTarget_sources[this_1])
	loop
		exitwhen  not (dispatch_LinkedList_LinkedList_LinkedList_isEmpty(cancelList) == false)
		call dispatch_OrderSource_OrderSystem_OrderSource_invalidate(dispatch_LinkedList_LinkedList_LinkedList_pop(cancelList))
	endloop
	call dispatch_LinkedList_destroyLinkedList(cancelList)
	call dispatch_LinkedList_destroyLinkedList(OrderTarget_sources[this_1])
endfunction

function dealloc_OrderTarget takes integer obj returns nothing
	if OrderTarget_typeId[obj] == 0 then
		call error("Double free: object of type OrderTarget")
	else
		set OrderTarget_nextFree[OrderTarget_firstFree] = obj
		set OrderTarget_firstFree = OrderTarget_firstFree + 1
		set OrderTarget_typeId[obj] = 0
	endif
endfunction

function destroyOrderTarget takes integer this_1 returns nothing
	call OrderTarget_onDestroy(this_1)
	call dealloc_OrderTarget(this_1)
endfunction

function dispatch_OrderTarget_destroyOrderTarget takes integer this_1 returns nothing
	if OrderTarget_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling OrderTarget.OrderTarget")
		else
			call error("Called OrderTarget.OrderTarget on invalid object.")
		endif
	endif
	call destroyOrderTarget(this_1)
endfunction

function unit_removeAllOrders takes unit this_1 returns nothing
	local integer orderSource = dispatch_UnitHashMap_UnitMap_UnitHashMap_tryRemove(OrderSystem_ORDER_SOURCE_MAP, this_1)
	local integer orderTarget
	if orderSource != 0 then
		call cyc_unit_removeSourceOrder(11, null, orderSource)
	endif
	set orderTarget = dispatch_UnitHashMap_UnitMap_UnitHashMap_tryRemove(OrderSystem_ORDER_TARGET_MAP, this_1)
	if orderTarget != 0 then
		call dispatch_OrderTarget_destroyOrderTarget(orderTarget)
	endif
endfunction

function code__onLeave_OrderSystem takes nothing returns nothing
	call unit_removeAllOrders(getEnterLeaveUnit())
endfunction

function Person_onDestroy takes integer this_1 returns nothing
endfunction

function dealloc_Person takes integer obj returns nothing
	if Person_typeId[obj] == 0 then
		call error("Double free: object of type Person")
	else
		set Person_nextFree[Person_firstFree] = obj
		set Person_firstFree = Person_firstFree + 1
		set Person_typeId[obj] = 0
	endif
endfunction

function destroyPerson takes integer this_1 returns nothing
	call Person_onDestroy(this_1)
	call dealloc_Person(this_1)
endfunction

function dispatch_Person_destroyPerson takes integer this_1 returns nothing
	if Person_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Person.Person")
		else
			call error("Called Person.Person on invalid object.")
		endif
	endif
	call destroyPerson(this_1)
endfunction

function unit_removePerson takes unit this_1 returns nothing
	local integer person = dispatch_IterableUnitHashMap_UnitMap_IterableUnitHashMap_tryRemove(PersonSystem_PERSON_MAP, this_1)
	if person != 0 then
		call dispatch_Person_destroyPerson(person)
	endif
endfunction

function code__onLeave_PersonSystem takes nothing returns nothing
	call unit_removePerson(getEnterLeaveUnit())
endfunction

function Storage_onDestroy takes integer this_1 returns nothing
	call Stock_onDestroy(this_1)
endfunction

function dealloc_Storage takes integer obj returns nothing
	if Stock_typeId[obj] == 0 then
		call error("Double free: object of type Storage")
	else
		set Stock_nextFree[Stock_firstFree] = obj
		set Stock_firstFree = Stock_firstFree + 1
		set Stock_typeId[obj] = 0
	endif
endfunction

function destroyStorage takes integer this_1 returns nothing
	call Storage_onDestroy(this_1)
	call dealloc_Storage(this_1)
endfunction

function dispatch_Storage_destroyStorage takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.Storage")
		else
			call error("Called Storage.Storage on invalid object.")
		endif
	endif
	call destroyStorage(this_1)
endfunction

function unit_removeStorage takes unit this_1 returns nothing
	local integer storage = dispatch_UnitHashMap_UnitMap_UnitHashMap_tryRemove(StorageSystem_STORAGE_MAP, this_1)
	if storage != 0 then
		call dispatch_Storage_destroyStorage(storage)
	endif
endfunction

function code__onLeave_StorageSystem takes nothing returns nothing
	call unit_removeStorage(getEnterLeaveUnit())
endfunction

function UnitIndex_onDestroy takes integer this_1 returns nothing
	call pushUnit_1103(UnitIndex__unit[this_1])
	call trigger_evaluate(UnitIndexer_onDeindexTrigger)
	call popUnit_1096()
	call unit_setUserData(UnitIndex__unit[this_1], 0)
endfunction

function dealloc_UnitIndex takes integer obj returns nothing
	if UnitIndex_typeId[obj] == 0 then
		call error("Double free: object of type UnitIndex")
	else
		set UnitIndex_nextFree[UnitIndex_firstFree] = obj
		set UnitIndex_firstFree = UnitIndex_firstFree + 1
		set UnitIndex_typeId[obj] = 0
	endif
endfunction

function destroyUnitIndex takes integer this_1 returns nothing
	call UnitIndex_onDestroy(this_1)
	call dealloc_UnitIndex(this_1)
endfunction

function dispatch_UnitIndex_destroyUnitIndex takes integer this_1 returns nothing
	if UnitIndex_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitIndex.UnitIndex")
		else
			call error("Called UnitIndex.UnitIndex on invalid object.")
		endif
	endif
	call destroyUnitIndex(this_1)
endfunction

function unit_deindex takes unit this_1 returns boolean
	if unit_getUserData(this_1) == 0 then
		return false
	else
		call dispatch_UnitIndex_destroyUnitIndex(unit_toUnitIndex(this_1))
		return true
	endif
endfunction

function code__onLeave_UnitIndexer takes nothing returns nothing
	if shouldIndex(getEnterLeaveUnit()) then
		call unit_deindex(getEnterLeaveUnit())
	endif
endfunction

function getIndexingUnit takes nothing returns unit
	return UnitIndexer_tempUnits[UnitIndexer_tempUnitsCount - 1]
endfunction

function code__onUnitDeindex_BuildingSystem takes nothing returns nothing
	call unit_removeBuildingSite(getIndexingUnit())
endfunction

function Resource_onDestroy takes integer this_1 returns nothing
	call Stock_onDestroy(this_1)
endfunction

function dealloc_Resource takes integer obj returns nothing
	if Stock_typeId[obj] == 0 then
		call error("Double free: object of type Resource")
	else
		set Stock_nextFree[Stock_firstFree] = obj
		set Stock_firstFree = Stock_firstFree + 1
		set Stock_typeId[obj] = 0
	endif
endfunction

function destroyResource takes integer this_1 returns nothing
	call Resource_onDestroy(this_1)
	call dealloc_Resource(this_1)
endfunction

function dispatch_Resource_destroyResource takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Resource.Resource")
		else
			call error("Called Resource.Resource on invalid object.")
		endif
	endif
	call destroyResource(this_1)
endfunction

function unit_removeResource takes unit this_1 returns nothing
	local integer resource = dispatch_UnitHashMap_UnitMap_UnitHashMap_tryRemove(ResourceSystem_RESOURCE_MAP, this_1)
	if resource != 0 then
		call dispatch_Resource_destroyResource(resource)
	endif
endfunction

function code__onUnitDeindex_ResourceSystem takes nothing returns nothing
	call unit_removeResource(getIndexingUnit())
endfunction

function group_clear takes group this_1 returns nothing
	call GroupClear(this_1)
endfunction

function group_destr takes group this_1 returns nothing
	call DestroyGroup(this_1)
endfunction

function group_close takes group this_1 returns nothing
	call group_clear(this_1)
	call group_destr(this_1)
endfunction

function group_iterator takes group this_1 returns group
	set Group_iterGroup = CreateGroup()
	call ForGroup(this_1, ref_function_code__ForGroup_Group)
	return Group_iterGroup
endfunction

function unit_show takes unit this_1 returns nothing
	call ShowUnit(this_1, true)
endfunction

function Workshop_onDestroy takes integer this_1 returns nothing
	local group iterator = group_iterator(Workshop_workers[this_1])
	local unit worker_1
	loop
		exitwhen  not group_hasNext(iterator)
		set worker_1 = group_next(iterator)
		call unit_show(worker_1)
	endloop
	call group_close(iterator)
	call group_destr(Workshop_workers[this_1])
	call Stock_onDestroy(this_1)
	set iterator = null
	set worker_1 = null
endfunction

function dealloc_Workshop takes integer obj returns nothing
	if Stock_typeId[obj] == 0 then
		call error("Double free: object of type Workshop")
	else
		set Stock_nextFree[Stock_firstFree] = obj
		set Stock_firstFree = Stock_firstFree + 1
		set Stock_typeId[obj] = 0
	endif
endfunction

function destroyWorkshop takes integer this_1 returns nothing
	call Workshop_onDestroy(this_1)
	call dealloc_Workshop(this_1)
endfunction

function dispatch_Workshop_destroyWorkshop takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.Workshop")
		else
			call error("Called Workshop.Workshop on invalid object.")
		endif
	endif
	call destroyWorkshop(this_1)
endfunction

function unit_removeWorkshop takes unit this_1 returns nothing
	local integer workshop = dispatch_IterableUnitHashMap_UnitMap_IterableUnitHashMap_tryRemove(WorkshopSystem_WORKSHOP_MAP, this_1)
	if workshop != 0 then
		call dispatch_Workshop_destroyWorkshop(workshop)
	endif
endfunction

function code__onUnitDeindex_WorkshopSystem takes nothing returns nothing
	call unit_removeWorkshop(getIndexingUnit())
endfunction

function Log_warn takes string msg returns nothing
	call printLog_1100(Player_localPlayer, 3, msg)
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 651
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 651
	endif
	return this_1
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem_495 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 652
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 652
	endif
	return this_1
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem_496 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 653
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 653
	endif
	return this_1
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem_497 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 654
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 654
	endif
	return this_1
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem_498 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 655
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 655
	endif
	return this_1
endfunction

function unit_setOwner takes unit this_1, player p, boolean changeColor returns nothing
	call SetUnitOwner(this_1, p, changeColor)
endfunction

function unit_setPos takes unit this_1, real pos_x, real pos_y returns nothing
	call SetUnitPosition(this_1, pos_x, pos_y)
endfunction

function InstantDummyCaster_finish takes integer id returns nothing
	call unit_setOwner(InstantDummyCaster_caster, Basics_DUMMY_PLAYER, false)
	call unit_removeAbility(InstantDummyCaster_caster, id)
	call unit_setPos(InstantDummyCaster_caster, MapBounds_boundMax_x, MapBounds_boundMax_y)
endfunction

function unit_setAbilityLevel takes unit this_1, integer abilId, integer lvl returns nothing
	call SetUnitAbilityLevel(this_1, abilId, lvl)
endfunction

function unit_setState takes unit this_1, unitstate state, real value returns nothing
	call SetUnitState(this_1, state, value)
endfunction

function unit_setMana takes unit this_1, real wval returns nothing
	call unit_setState(this_1, UNIT_STATE_MANA, wval)
endfunction

function unit_setFlyHeight takes unit this_1, real height, real rate returns nothing
	call SetUnitFlyHeight(this_1, height, rate)
endfunction

function unit_setXYZ takes unit this_1, real pos_x, real pos_y, real pos_z returns nothing
	local unit receiver = this_1
	local unit receiver_1
	local unit receiver_2
	call unit_setX(receiver, pos_x)
	set receiver_1 = receiver
	call unit_setY(receiver_1, pos_y)
	set receiver_2 = receiver_1
	call unit_setFlyHeight(receiver_2, pos_z, 0.)
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
endfunction

function inBoundsXY takes real x, real y returns boolean
	return x > MapBounds_boundMin_x and x < MapBounds_boundMax_x and y > MapBounds_boundMin_y and y < MapBounds_boundMax_y
endfunction

function vec3_inBounds takes real this_x, real this_y, real this_z returns boolean
	return inBoundsXY(this_x, this_y)
endfunction

function InstantDummyCaster_prepare takes player owner, integer id, integer lvl, real pos_x, real pos_y, real pos_z returns nothing
	local unit receiver = InstantDummyCaster_caster
	local unit receiver_1
	call unit_addAbility(receiver, id)
	set receiver_1 = receiver
	call unit_setMana(receiver_1, 1000000.)
	if vec3_inBounds(pos_x, pos_y, pos_z) then
		call unit_setXYZ(InstantDummyCaster_caster, pos_x, pos_y, pos_z)
	endif
	if lvl > 1 then
		call unit_setAbilityLevel(InstantDummyCaster_caster, id, lvl)
	endif
	if owner != null then
		call unit_setOwner(InstantDummyCaster_caster, owner, false)
	endif
	set receiver = null
	set receiver_1 = null
endfunction

function unit_issueTargetOrderById takes unit this_1, integer id, widget target_1 returns boolean
	return IssueTargetOrderById(this_1, id, target_1)
endfunction

function real_asAngleRadians takes real this_1 returns real
	set real_asAngleRadians_return_radians = this_1
	return real_asAngleRadians_return_radians
endfunction

function vec2_angleTo takes real this_x, real this_y, real v_x, real v_y returns real
	set vec2_angleTo_return_radians = real_asAngleRadians(Atan2(v_y - this_y, v_x - this_x))
	return vec2_angleTo_return_radians
endfunction

function widget_getX takes widget this_1 returns real
	return GetWidgetX(this_1)
endfunction

function widget_getY takes widget this_1 returns real
	return GetWidgetY(this_1)
endfunction

function widget_getPos takes widget this_1 returns real
	set widget_getPos_return_x = widget_getX(this_1)
	set widget_getPos_return_y = widget_getY(this_1)
	return widget_getPos_return_x
endfunction

function InstantDummyCaster_castTarget takes player owner, integer abilityId, integer lvl, integer orderId, widget target_1, real casterPos_x, real casterPos_y, real casterPos_z returns boolean
	local boolean success
	call InstantDummyCaster_prepare(owner, abilityId, lvl, casterPos_x, casterPos_y, casterPos_z)
	call unit_setFacing(InstantDummyCaster_caster, vec2_angleTo(unit_getPos(InstantDummyCaster_caster), unit_getPos_return_y, widget_getPos(target_1), widget_getPos_return_y))
	set success = unit_issueTargetOrderById(InstantDummyCaster_caster, orderId, target_1)
	call InstantDummyCaster_finish(abilityId)
	return success
endfunction

function vec2_toVec3 takes real this_x, real this_y returns real
	set vec2_toVec3_return_x = this_x
	set vec2_toVec3_return_y = this_y
	set vec2_toVec3_return_z = 0.
	return vec2_toVec3_return_x
endfunction

function InstantDummyCaster_castTarget_199 takes player owner, integer abilityId, integer lvl, integer orderId, widget target_1 returns boolean
	return InstantDummyCaster_castTarget(owner, abilityId, lvl, orderId, target_1, vec2_toVec3(GetWidgetX(target_1), GetWidgetY(target_1)), vec2_toVec3_return_y, vec2_toVec3_return_z)
endfunction

function InstantDummyCaster_castTarget_200 takes player owner, integer abilityId, integer lvl, string order, widget target_1 returns boolean
	return InstantDummyCaster_castTarget_199(owner, abilityId, lvl, OrderId(order), target_1)
endfunction

function alloc_CallbackSingle_doAfter_BuildingSite_BuildingSystem takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 665
		else
			call error("Out of memory: Could not create CallbackSingle_doAfter_BuildingSite_BuildingSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 665
	endif
	return this_1
endfunction

function BuildingSite_addWorker takes integer this_1, unit worker_1 returns nothing
	local integer clVar
	local real temp
	if dispatch_UnitHashMap_UnitMap_UnitHashMap_has(BuildingSystem_WORKER_MAP, worker_1) == false then
		call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(BuildingSystem_WORKER_MAP, worker_1, this_1)
		set BuildingSite_workPower[this_1] = BuildingSite_workPower[this_1] + getUnitWorkPower(unit_getUnitId(worker_1), unit_getUnitId(Stock_user[this_1]))
		set BuildingSite_workerCount[this_1] = BuildingSite_workerCount[this_1] + 1
		call InstantDummyCaster_castTarget_200(null, AbilityIdsCustom_addBuildingBuff, 1, int_getAbilityOrder(AbilityIdsCustom_addBuildingBuff), worker_1)
		set temp = UtilityFunctions_MIN_TRIGGER_SLEEP_TIME
		set clVar = alloc_CallbackSingle_doAfter_BuildingSite_BuildingSystem()
		call construct_CallbackSingle(clVar)
		set worker[clVar] = worker_1
		call doAfter(temp, clVar)
	else
		call Log_error("ERROR: Can't add worker to this building site")
	endif
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_addWorker takes integer this_1, unit worker_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.addWorker")
		else
			call error("Called BuildingSite.addWorker on invalid object.")
		endif
	endif
	call BuildingSite_addWorker(this_1, worker_1)
endfunction

function OrderSource_cancel takes integer this_1 returns nothing
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(OrderSystem_ORDER_SOURCE_MAP, OrderSource_source[this_1], 0)
	call cyc_unit_removeSourceOrder(11, null, this_1)
endfunction

function dispatch_OrderSource_OrderSystem_OrderSource_cancel takes integer this_1 returns nothing
	if OrderSource_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling OrderSource.cancel")
		else
			call error("Called OrderSource.cancel on invalid object.")
		endif
	endif
	call OrderSource_cancel(this_1)
endfunction

function Resource_addWorker takes integer this_1 returns nothing
	if Resource_workerCount[this_1] >= getMaxWorkerCount(unit_getUnitId(Stock_user[this_1])) then
		call Log_error("ERROR: Can not add more workers to resource (" + unit_getName(Stock_user[this_1]) + ")")
	endif
	set Resource_workerCount[this_1] = Resource_workerCount[this_1] + 1
endfunction

function dispatch_Resource_ResourceSystem_Resource_addWorker takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Resource.addWorker")
		else
			call error("Called Resource.addWorker on invalid object.")
		endif
	endif
	call Resource_addWorker(this_1)
endfunction

function group_contains takes group this_1, unit u_1 returns boolean
	return IsUnitInGroup(u_1, this_1)
endfunction

function unit_hide takes unit this_1 returns nothing
	call ShowUnit(this_1, false)
endfunction

function Workshop_addWorker takes integer this_1, unit worker_1 returns nothing
	if group_contains(Workshop_workers[this_1], worker_1) == false and group_size(Workshop_workers[this_1]) < getMaxWorkers(unit_getUnitId(Stock_user[this_1])) then
		call group_addUnit_1(Workshop_workers[this_1], worker_1)
		set Workshop_workPower[this_1] = Workshop_workPower[this_1] + getUnitWorkPower_896(unit_getUnitId(worker_1), unit_getUnitId(Stock_user[this_1]))
		call unit_hide(worker_1)
	else
		call Log_error("ERROR: Can't add worker to this workshop")
	endif
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_addWorker takes integer this_1, unit worker_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.addWorker")
		else
			call error("Called Workshop.addWorker on invalid object.")
		endif
	endif
	call Workshop_addWorker(this_1, worker_1)
endfunction

function Workshop_cancelProduction takes integer this_1 returns nothing
	local integer educts
	if Workshop_workProgressCurrent[this_1] > 0. then
		set Workshop_workProgressCurrent[this_1] = 0.
		set educts = dispatch_Workshop_WorkshopSystem_Workshop_getEducts(this_1)
		call dispatch_Stock_Stock_Stock_addWares(this_1, educts)
		call dispatch_LinkedList_destroyLinkedList(educts)
	endif
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_cancelProduction takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.cancelProduction")
		else
			call error("Called Workshop.cancelProduction on invalid object.")
		endif
	endif
	call Workshop_cancelProduction(this_1)
endfunction

function Workshop_changeProduct takes integer this_1 returns nothing
	if getRequiredWorkPower_890(unit_getUnitId(Stock_user[this_1]), Workshop_productionVariant[this_1] + 1) > 0. then
		call dispatch_Workshop_WorkshopSystem_Workshop_cancelProduction(this_1)
		set Workshop_productionVariant[this_1] = Workshop_productionVariant[this_1] + 1
	elseif Workshop_productionVariant[this_1] != 1 then
		call dispatch_Workshop_WorkshopSystem_Workshop_cancelProduction(this_1)
		set Workshop_productionVariant[this_1] = 1
	endif
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_changeProduct takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.changeProduct")
		else
			call error("Called Workshop.changeProduct on invalid object.")
		endif
	endif
	call Workshop_changeProduct(this_1)
endfunction

function Workshop_removeWorker takes integer this_1 returns nothing
	local unit worker_1
	if group_size(Workshop_workers[this_1]) > 0 then
		set worker_1 = group_next(Workshop_workers[this_1])
		set Workshop_workPower[this_1] = Workshop_workPower[this_1] - getUnitWorkPower_896(unit_getUnitId(worker_1), unit_getUnitId(Stock_user[this_1]))
		call unit_show(worker_1)
	else
		call Log_error("ERROR: Can't remove worker from this workshop")
	endif
	set worker_1 = null
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_removeWorker takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.removeWorker")
		else
			call error("Called Workshop.removeWorker on invalid object.")
		endif
	endif
	call Workshop_removeWorker(this_1)
endfunction

function int_getOrderName takes integer this_1 returns string
	local integer temp = this_1
	if temp == SpecialOrders_smart then
		return "smart"
	elseif temp == OrderIds_move then
		return "move"
	elseif temp == OrderIds_stop then
		return "stop"
	elseif temp == OrderIds_attack then
		return "attack"
	elseif temp == OrderIds_attackground then
		return "attack ground"
	elseif temp == OrderIds_holdposition then
		return "hold position"
	elseif temp == OrderIds_patrol then
		return "patrol"
	elseif temp == OrderIds_repair then
		return "repair"
	elseif temp == OrderIds_repairon then
		return "repair on"
	elseif temp == OrderIds_repairoff then
		return "repair off"
	elseif temp == SpecialOrders_stunned then
		return "stunned"
	elseif temp == OrderIds_undefend then
		return null
	elseif temp == AbilityIdsCustom_harvest then
		return "harvest"
	elseif temp == AbilityIdsCustom_showTargetInfo then
		return "show target info"
	elseif temp == AbilityIdsCustom_build then
		return "build"
	elseif temp == AbilityIdsCustom_transferWares then
		return "transfer wares"
	elseif temp == AbilityIdsCustom_addBuildingBuff then
		return "add building buff"
	else
		if this_1 < 2013265920 then
			call Log_error("ERROR: Unmapped order/ability id (" + int_toString(this_1) + ")")
		endif
		return null
	endif
endfunction

function alloc_OrderAction takes nothing returns integer
	local integer this_1
	if OrderAction_firstFree == 0 then
		if OrderAction_maxIndex < 32768 then
			set OrderAction_maxIndex = OrderAction_maxIndex + 1
			set this_1 = OrderAction_maxIndex
			set OrderAction_typeId[this_1] = 755
		else
			call error("Out of memory: Could not create OrderAction.")
			set this_1 = 0
		endif
	else
		set OrderAction_firstFree = OrderAction_firstFree - 1
		set this_1 = OrderAction_nextFree[OrderAction_firstFree]
		set OrderAction_typeId[this_1] = 755
	endif
	return this_1
endfunction

function OrderAction_init takes integer this_1 returns nothing
endfunction

function construct_OrderAction takes integer this_1, integer invalidateCb, integer cancelCb returns nothing
	call OrderAction_init(this_1)
	set OrderAction_invalidateCb[this_1] = invalidateCb
	set OrderAction_cancelCb[this_1] = cancelCb
	set OrderAction_finishCb[this_1] = 0
	set OrderAction_finishCondition[this_1] = 0
	set OrderAction_t[this_1] = null
endfunction

function new_OrderAction takes integer invalidateCb, integer cancelCb returns integer
	local integer this_1 = alloc_OrderAction()
	call construct_OrderAction(this_1, invalidateCb, cancelCb)
	return this_1
endfunction

function timer_startPeriodic takes timer this_1, real time, code timerCallBack returns nothing
	call TimerStart(this_1, time, true, timerCallBack)
endfunction

function construct_OrderAction2 takes integer this_1, integer invalidateCb, integer cancelCb, integer finishCb, real duration, integer finishCondition returns nothing
	call OrderAction_init(this_1)
	set OrderAction_invalidateCb[this_1] = invalidateCb
	set OrderAction_cancelCb[this_1] = cancelCb
	set OrderAction_finishCb[this_1] = finishCb
	set OrderAction_finishCondition[this_1] = finishCondition
	set OrderAction_t[this_1] = getTimer()
	call timer_setData(OrderAction_t[this_1], this_1)
	if finishCondition == 0 then
		call timer_start(OrderAction_t[this_1], duration, ref_function_code__start_OrderAction_OrderSystem)
	else
		call timer_startPeriodic(OrderAction_t[this_1], duration, ref_function_code__startPeriodic_OrderAction_OrderSystem)
	endif
endfunction

function new_OrderAction_1075 takes integer invalidateCb, integer cancelCb, integer finishCb, real duration, integer finishCondition returns integer
	local integer this_1 = alloc_OrderAction()
	call construct_OrderAction2(this_1, invalidateCb, cancelCb, finishCb, duration, finishCondition)
	return this_1
endfunction

function unit_getOrderSource takes unit this_1 returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(OrderSystem_ORDER_SOURCE_MAP, this_1)
endfunction

function getInvalidMessageText takes integer abilityId, integer wval returns string
	local integer temp = abilityId
	local integer temp_1
	local integer temp_2
	local integer temp_3
	local integer temp_4
	local integer temp_5
	if temp == AbilityIdsCustom_transferWares then
		set temp_1 = wval
		if temp_1 == 3 then
			return "Unit can't transfer wares"
		elseif temp_1 == 4 then
			return "Can't transfer wares to this kind of target"
		elseif temp_1 == 5 then
			return "No wares to transfer are available"
		elseif temp_1 == 8 then
			return "Target has no free storage for transfer"
		elseif temp_1 == 9 then
			return "Target has no required wares left"
		else
			return null
		endif
	elseif temp == AbilityIdsCustom_build then
		set temp_2 = wval
		if temp_2 == 3 then
			return "Worker can't build at target building site type"
		elseif temp_2 == 4 then
			return "Build target is no building site"
		elseif temp_2 == 5 then
			return "Not all required wares are available for building"
		elseif temp_2 == 10 then
			return "Worker is already building"
		else
			return null
		endif
	elseif temp == AbilityIdsCustom_harvest then
		set temp_3 = wval
		if temp_3 == 3 then
			return "No storage for harvest"
		elseif temp_3 == 4 then
			return "Harvest target is no resource"
		elseif temp_3 == 7 then
			return "Target already reached its maximum of concurrent harvesters"
		elseif temp_3 == 8 then
			return "No free storage for harvest"
		elseif temp_3 == 11 then
			return "Harvest target is already depleted"
		else
			return null
		endif
	elseif temp == AbilityIdsCustom_enterBuilding then
		set temp_4 = wval
		if temp_4 == 3 then
			return "Unit can't enter target building type"
		elseif temp_4 == 4 then
			return "Target building is no workshop"
		elseif temp_4 == 7 then
			return "Target already reached its maximum of concurrent units"
		else
			return null
		endif
	elseif temp == AbilityIdsCustom_removeWorker then
		set temp_5 = wval
		if temp_5 == 6 then
			return "No workers left to remove"
		else
			return null
		endif
	endif
	return null
endfunction

function printTimedToPlayer takes string msg, real duration, player p returns nothing
	call DisplayTimedTextToPlayer(p, 0., 0., duration, msg)
endfunction

function unit_abortOrder takes unit this_1 returns boolean
	if IsUnitPaused(this_1) then
		return false
	else
		call PauseUnit(this_1, true)
		call IssueImmediateOrder(this_1, "stop")
		call PauseUnit(this_1, false)
	endif
	return true
endfunction

function unit_reactOnInvalidAbility takes unit this_1, integer abilityId, integer wval returns nothing
	local player owner
	local string messageText
	if wval == 0 or wval == 1 then
		call Log_error("ERROR: Given validity is not invalid (" + int_toString(wval) + ")")
	endif
	set owner = unit_getOwner(this_1)
	if IsUnitSelected(this_1, owner) then
		set messageText = getInvalidMessageText(abilityId, wval)
		if messageText == null then
			call Log_error("ERROR: Unregistered invalidity message text for " + int_toString(abilityId) + " / " + int_toString(wval))
		endif
		call printTimedToPlayer("Invalid: " + messageText, AbilitySystem_INFO_MSG_TIME, owner)
	endif
	call unit_abortOrder(this_1)
	set owner = null
endfunction

function alloc_OrderSourceU takes nothing returns integer
	local integer this_1
	if OrderSource_firstFree == 0 then
		if OrderSource_maxIndex < 32768 then
			set OrderSource_maxIndex = OrderSource_maxIndex + 1
			set this_1 = OrderSource_maxIndex
			set OrderSource_typeId[this_1] = 759
		else
			call error("Out of memory: Could not create OrderSourceU.")
			set this_1 = 0
		endif
	else
		set OrderSource_firstFree = OrderSource_firstFree - 1
		set this_1 = OrderSource_nextFree[OrderSource_firstFree]
		set OrderSource_typeId[this_1] = 759
	endif
	return this_1
endfunction

function OrderSourceU_init takes integer this_1 returns nothing
endfunction

function OrderSource_init takes integer this_1 returns nothing
endfunction

function construct_OrderSource takes integer this_1, unit source_1, integer orderId, integer orderAction returns nothing
	call OrderSource_init(this_1)
	set OrderSource_source[this_1] = source_1
	set OrderSource_orderId[this_1] = orderId
	set OrderSource_orderAction[this_1] = orderAction
endfunction

function OrderTarget_addSource takes integer this_1, integer source_1 returns nothing
	if dispatch_LinkedList_LinkedList_LinkedList_has(OrderTarget_sources[this_1], source_1) == false then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(OrderTarget_sources[this_1], source_1)
	else
		call Log_error("ERROR: Source already has that target")
	endif
endfunction

function dispatch_OrderTarget_OrderSystem_OrderTarget_addSource takes integer this_1, integer source_1 returns nothing
	if OrderTarget_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling OrderTarget.addSource")
		else
			call error("Called OrderTarget.addSource on invalid object.")
		endif
	endif
	call OrderTarget_addSource(this_1, source_1)
endfunction

function alloc_OrderTarget takes nothing returns integer
	local integer this_1
	if OrderTarget_firstFree == 0 then
		if OrderTarget_maxIndex < 32768 then
			set OrderTarget_maxIndex = OrderTarget_maxIndex + 1
			set this_1 = OrderTarget_maxIndex
			set OrderTarget_typeId[this_1] = 761
		else
			call error("Out of memory: Could not create OrderTarget.")
			set this_1 = 0
		endif
	else
		set OrderTarget_firstFree = OrderTarget_firstFree - 1
		set this_1 = OrderTarget_nextFree[OrderTarget_firstFree]
		set OrderTarget_typeId[this_1] = 761
	endif
	return this_1
endfunction

function OrderTarget_init takes integer this_1 returns nothing
endfunction

function construct_OrderTarget takes integer this_1, unit target_1, integer source_1 returns nothing
	call OrderTarget_init(this_1)
	set OrderTarget_sources[this_1] = new_LinkedList()
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(OrderTarget_sources[this_1], source_1)
endfunction

function new_OrderTarget takes unit target_1, integer source_1 returns integer
	local integer this_1 = alloc_OrderTarget()
	call construct_OrderTarget(this_1, target_1, source_1)
	return this_1
endfunction

function construct_OrderSourceU takes integer this_1, unit source_1, integer orderId, unit target_1, integer orderAction returns nothing
	local integer orderTarget
	call construct_OrderSource(this_1, source_1, orderId, orderAction)
	call OrderSourceU_init(this_1)
	set OrderSourceU_target[this_1] = target_1
	set orderTarget = dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(OrderSystem_ORDER_TARGET_MAP, target_1)
	if orderTarget != 0 then
		call dispatch_OrderTarget_OrderSystem_OrderTarget_addSource(orderTarget, this_1)
	else
		call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(OrderSystem_ORDER_TARGET_MAP, target_1, new_OrderTarget(target_1, this_1))
	endif
endfunction

function new_OrderSourceU takes unit source_1, integer orderId, unit target_1, integer orderAction returns integer
	local integer this_1 = alloc_OrderSourceU()
	call construct_OrderSourceU(this_1, source_1, orderId, target_1, orderAction)
	return this_1
endfunction

function unit_setOrder takes unit this_1, integer order returns nothing
	local integer orderSource = dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(OrderSystem_ORDER_SOURCE_MAP, this_1)
	if orderSource != 0 then
		call cyc_unit_removeSourceOrder(11, null, orderSource)
	endif
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(OrderSystem_ORDER_SOURCE_MAP, this_1, order)
endfunction

function unit_setOrder_1224 takes unit this_1, integer orderId, unit target_1, integer orderAction returns nothing
	call unit_setOrder(this_1, new_OrderSourceU(this_1, orderId, target_1, orderAction))
endfunction

function BuildingSite_callOverIdleWorkers takes integer this_1, unit unconditionedOrderWorker returns nothing
	local player owner
	local unit worker_1
	local group from
	call group_enumUnitsInRange(Group_ENUM_GROUP, unit_getPos(Stock_user[this_1]), unit_getPos_return_y, BuildingSystem_MAX_AUTO_ORDER_RANGE, null)
	set owner = unit_getOwner(Stock_user[this_1])
	set from = Group_ENUM_GROUP
	loop
		exitwhen  not group_hasNext(from)
		set worker_1 = group_next(from)
		if int_isValidWorkerType(unit_getUnitId(Stock_user[this_1]), unit_getUnitId(worker_1)) and unit_getOwner(worker_1) == owner and unit_getOrderSource(worker_1) == 0 or worker_1 == unconditionedOrderWorker then
			call unit_issueTargetAbilityOrder(worker_1, AbilityIdsCustom_build, Stock_user[this_1], true)
		endif
	endloop
	set owner = null
	set worker_1 = null
	set from = null
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_callOverIdleWorkers takes integer this_1, unit unconditionedOrderWorker returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.callOverIdleWorkers")
		else
			call error("Called BuildingSite.callOverIdleWorkers on invalid object.")
		endif
	endif
	call BuildingSite_callOverIdleWorkers(this_1, unconditionedOrderWorker)
endfunction

function LinkedList_size_1 takes integer this_1 returns integer
	return LinkedList_size[this_1]
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_size takes integer this_1 returns integer
	local integer LinkedList_LinkedList_size_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.size")
		else
			call error("Called LinkedList.size on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_size_result = LinkedList_size_1(this_1)
	return LinkedList_LinkedList_size_result
endfunction

function Stock_getAmountOfWareTypes takes integer this_1 returns integer
	return dispatch_LinkedList_LinkedList_LinkedList_size(Stock_wares[this_1])
endfunction

function dispatch_Stock_Stock_Stock_getAmountOfWareTypes takes integer this_1 returns integer
	local integer Stock_Stock_getAmountOfWareTypes_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.getAmountOfWareTypes")
		else
			call error("Called Stock.getAmountOfWareTypes on invalid object.")
		endif
	endif
	set Stock_Stock_getAmountOfWareTypes_result = Stock_getAmountOfWareTypes(this_1)
	return Stock_Stock_getAmountOfWareTypes_result
endfunction

function LinkedList_getEntry takes integer this_1, integer index returns integer
	local integer entry = LinkedList_dummy[this_1]
	local integer i = 0
	local integer temp = index
	loop
		exitwhen i > temp
		set entry = LLEntry_next[entry]
		set i = i + 1
	endloop
	return entry
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_getEntry takes integer this_1, integer index returns integer
	local integer LinkedList_LinkedList_getEntry_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.getEntry")
		else
			call error("Called LinkedList.getEntry on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_getEntry_result = LinkedList_getEntry(this_1, index)
	return LinkedList_LinkedList_getEntry_result
endfunction

function LinkedList_get takes integer this_1, integer index returns integer
	return LLEntry_elem[dispatch_LinkedList_LinkedList_LinkedList_getEntry(this_1, index)]
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_get takes integer this_1, integer index returns integer
	local integer LinkedList_LinkedList_get_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.get")
		else
			call error("Called LinkedList.get on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_get_result = LinkedList_get(this_1, index)
	return LinkedList_LinkedList_get_result
endfunction

function Stock_getWare takes integer this_1, integer index returns integer
	if index >= dispatch_LinkedList_LinkedList_LinkedList_size(Stock_wares[this_1]) then
		call Log_error("ERROR: Index has to be smaller than list size")
	endif
	set Stock_getWare_return_wareType = wareFromIndex(dispatch_LinkedList_LinkedList_LinkedList_get(Stock_wares[this_1], index))
	set Stock_getWare_return_count = wareFromIndex_return_count
	return Stock_getWare_return_wareType
endfunction

function dispatch_Stock_Stock_Stock_getWare takes integer this_1, integer index returns integer
	local integer Stock_Stock_getWare_result_wareType
	local integer Stock_Stock_getWare_result_count
	local integer tuple_temp
	local integer tuple_temp_1
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.getWare")
		else
			call error("Called Stock.getWare on invalid object.")
		endif
	endif
	set tuple_temp = Stock_getWare(this_1, index)
	set tuple_temp_1 = Stock_getWare_return_count
	set Stock_Stock_getWare_result_wareType = tuple_temp
	set Stock_Stock_getWare_result_count = tuple_temp_1
	set dispatch_Stock_Stock_Stock_getWare_return_wareType = Stock_Stock_getWare_result_wareType
	set dispatch_Stock_Stock_Stock_getWare_return_count = Stock_Stock_getWare_result_count
	return dispatch_Stock_Stock_Stock_getWare_return_wareType
endfunction

function BuildingSite_transferWares takes integer this_1, integer source_1 returns nothing
	local integer leftRequiredWares = new_LinkedList()
	local integer i = 0
	local integer temp = dispatch_Stock_Stock_Stock_getAmountOfWareTypes(this_1) - 1
	local integer ware_wareType
	local integer ware_count
	local integer count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen i > temp
		set tuple_temp = dispatch_Stock_Stock_Stock_getWare(this_1, i)
		set tuple_temp_1 = dispatch_Stock_Stock_Stock_getWare_return_count
		set ware_wareType = tuple_temp
		set ware_count = tuple_temp_1
		set count = dispatch_Stock_Stock_Stock_getWareCount(source_1, ware_wareType)
		if count < ware_count then
			call dispatch_LinkedList_LinkedList_LinkedList_add_1(leftRequiredWares, wareToIndex(ware_wareType, ware_count - count))
		else
			set count = ware_count
		endif
		if count > 0 then
			call dispatch_Storage_StorageSystem_Storage_removeWare(source_1, ware_wareType, count)
		endif
		set i = i + 1
	endloop
	call dispatch_LinkedList_destroyLinkedList(Stock_wares[this_1])
	set Stock_wares[this_1] = leftRequiredWares
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_transferWares takes integer this_1, integer source_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.transferWares")
		else
			call error("Called BuildingSite.transferWares on invalid object.")
		endif
	endif
	call BuildingSite_transferWares(this_1, source_1)
endfunction

function LinkedList_peek takes integer this_1 returns integer
	return LLEntry_elem[LLEntry_prev[LinkedList_dummy[this_1]]]
endfunction

function dispatch_LinkedList_LinkedList_LinkedList_peek takes integer this_1 returns integer
	local integer LinkedList_LinkedList_peek_result
	if LinkedList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling LinkedList.peek")
		else
			call error("Called LinkedList.peek on invalid object.")
		endif
	endif
	set LinkedList_LinkedList_peek_result = LinkedList_peek(this_1)
	return LinkedList_LinkedList_peek_result
endfunction

function Stock_getLastWare takes integer this_1 returns integer
	set Stock_getLastWare_return_wareType = wareFromIndex(dispatch_LinkedList_LinkedList_LinkedList_peek(Stock_wares[this_1]))
	set Stock_getLastWare_return_count = wareFromIndex_return_count
	return Stock_getLastWare_return_wareType
endfunction

function dispatch_Stock_Stock_Stock_getLastWare takes integer this_1 returns integer
	local integer Stock_Stock_getLastWare_result_wareType
	local integer Stock_Stock_getLastWare_result_count
	local integer tuple_temp
	local integer tuple_temp_1
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.getLastWare")
		else
			call error("Called Stock.getLastWare on invalid object.")
		endif
	endif
	set tuple_temp = Stock_getLastWare(this_1)
	set tuple_temp_1 = Stock_getLastWare_return_count
	set Stock_Stock_getLastWare_result_wareType = tuple_temp
	set Stock_Stock_getLastWare_result_count = tuple_temp_1
	set dispatch_Stock_Stock_Stock_getLastWare_return_wareType = Stock_Stock_getLastWare_result_wareType
	set dispatch_Stock_Stock_Stock_getLastWare_return_count = Stock_Stock_getLastWare_result_count
	return dispatch_Stock_Stock_Stock_getLastWare_return_wareType
endfunction

function Storage_transferWares takes integer this_1, integer target_1 returns integer
	local integer targetFreeCapacity = dispatch_Storage_StorageSystem_Storage_getFreeCapacity(target_1)
	local integer ware_wareType
	local integer ware_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not (dispatch_Stock_Stock_Stock_isEmpty(this_1) == false)
		if targetFreeCapacity <= 0 then
			return Storage_usedCapacity[this_1]
		endif
		set tuple_temp = dispatch_Stock_Stock_Stock_getLastWare(this_1)
		set tuple_temp_1 = dispatch_Stock_Stock_Stock_getLastWare_return_count
		set ware_wareType = tuple_temp
		set ware_count = tuple_temp_1
		if targetFreeCapacity < ware_count then
			set ware_count = targetFreeCapacity
		endif
		set targetFreeCapacity = targetFreeCapacity - ware_count
		call dispatch_Storage_StorageSystem_Storage_addWare(target_1, ware_wareType, ware_count)
		call dispatch_Storage_StorageSystem_Storage_removeWare(this_1, ware_wareType, ware_count)
	endloop
	return 0
endfunction

function dispatch_Storage_StorageSystem_Storage_transferWares takes integer this_1, integer target_1 returns integer
	local integer StorageSystem_Storage_transferWares_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.transferWares")
		else
			call error("Called Storage.transferWares on invalid object.")
		endif
	endif
	set StorageSystem_Storage_transferWares_result = Storage_transferWares(this_1, target_1)
	return StorageSystem_Storage_transferWares_result
endfunction

function Workshop_transferWares takes integer this_1, integer source_1 returns nothing
	local integer educts = dispatch_Workshop_WorkshopSystem_Workshop_getEducts(this_1)
	local integer iterator = LinkedList_iterator(educts)
	local integer iWare_wareType
	local integer iWare_count
	local integer wareCount
	local integer products
	local integer iterator_1
	local integer iWare_wareType_1
	local integer wareCount_1
	local integer tuple_temp
	local integer tuple_temp_1
	local integer tuple_temp_2
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		set wareCount = min_2(iWare_count * WorkshopSystem_MAX_STORABLE_EDUCTS - dispatch_Stock_Stock_Stock_getWareCount(this_1, iWare_wareType), dispatch_Stock_Stock_Stock_getWareCount(source_1, iWare_wareType))
		if wareCount > 0 then
			call dispatch_Storage_StorageSystem_Storage_removeWare(source_1, iWare_wareType, wareCount)
			call dispatch_Stock_Stock_Stock_addWare(this_1, iWare_wareType, wareCount)
		endif
	endloop
	call LLIterator_close(iterator)
	call dispatch_LinkedList_destroyLinkedList(educts)
	set products = dispatch_Workshop_WorkshopSystem_Workshop_getProducts(this_1)
	set iterator_1 = LinkedList_iterator(products)
	loop
		exitwhen  not LLIterator_hasNext(iterator_1)
		set tuple_temp_2 = wareFromIndex(LLIterator_next(iterator_1))
		set iWare_wareType_1 = tuple_temp_2
		set wareCount_1 = min_2(dispatch_Stock_Stock_Stock_getWareCount(this_1, iWare_wareType_1), dispatch_Storage_StorageSystem_Storage_getFreeCapacity(source_1))
		if wareCount_1 > 0 then
			call dispatch_Stock_Stock_Stock_removeWare(this_1, iWare_wareType_1, wareCount_1)
			call dispatch_Storage_StorageSystem_Storage_addWare(source_1, iWare_wareType_1, wareCount_1)
		endif
	endloop
	call LLIterator_close(iterator_1)
	call dispatch_LinkedList_destroyLinkedList(products)
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_transferWares takes integer this_1, integer source_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.transferWares")
		else
			call error("Called Workshop.transferWares on invalid object.")
		endif
	endif
	call Workshop_transferWares(this_1, source_1)
endfunction

function unit_transferWares takes unit this_1, unit target_1 returns nothing
	local integer sourceStorage = unit_getStorage(this_1)
	local integer targetStorage
	local integer targetWorkshop
	local integer targetBuildingSite_1
	if sourceStorage != 0 then
		set targetStorage = unit_getStorage(target_1)
		if targetStorage != 0 then
			call dispatch_Storage_StorageSystem_Storage_transferWares(sourceStorage, targetStorage)
		endif
		set targetWorkshop = unit_getWorkshop(target_1)
		if targetWorkshop != 0 then
			call dispatch_Workshop_WorkshopSystem_Workshop_transferWares(targetWorkshop, sourceStorage)
		endif
		set targetBuildingSite_1 = unit_getBuildingSite(target_1)
		if targetBuildingSite_1 != 0 then
			call dispatch_BuildingSite_BuildingSystem_BuildingSite_transferWares(targetBuildingSite_1, sourceStorage)
			if dispatch_Stock_Stock_Stock_isEmpty(targetBuildingSite_1) then
				call dispatch_BuildingSite_BuildingSystem_BuildingSite_callOverIdleWorkers(targetBuildingSite_1, this_1)
			endif
		endif
	endif
endfunction

function code__registerPlayerUnitEvent_AbilitySystem takes nothing returns nothing
	local unit source_1 = GetTriggerUnit()
	local unit target_1 = GetSpellTargetUnit()
	local integer abilityId = GetSpellAbilityId()
	local integer sourceUnitId = unit_getUnitId(source_1)
	local integer orderSource
	local integer wval
	local integer temp
	local integer targetBuildingSite_1
	local integer invalidateCb
	local integer clVar
	local integer cancelCb
	local integer clVar_1
	local integer targetResource_1
	local integer invalidateCb_1
	local integer clVar_2
	local integer cancelCb_1
	local integer clVar_3
	local integer finishCb
	local integer clVar_4
	if sourceUnitId != InstantDummyCaster_DUMMY_CASTER_UNIT_ID and sourceUnitId != DummyRecycler_DUMMY_UNIT_ID then
		set orderSource = unit_getOrderSource(source_1)
		if orderSource == 0 then
			call Log_warn("WARNING: " + unit_getName(source_1) + " cast " + int_getOrderName(abilityId) + " on " + unit_getName(target_1) + " without being registered as an OrderSource")
		else
			call dispatch_OrderSource_OrderSystem_OrderSource_cancel(orderSource)
		endif
		set wval = unit_getAbilityValidity(source_1, abilityId, target_1)
		if wval == 0 then
			set temp = abilityId
			if temp == AbilityIdsCustom_transferWares then
				call unit_transferWares(source_1, target_1)
			elseif temp == AbilityIdsCustom_build then
				set targetBuildingSite_1 = unit_getBuildingSite(target_1)
				set clVar = alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem()
				set source[clVar] = source_1
				set invalidateCb = clVar
				set clVar_1 = alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem_495()
				set targetBuildingSite[clVar_1] = targetBuildingSite_1
				set source_717[clVar_1] = source_1
				set cancelCb = clVar_1
				call unit_setOrder_1224(source_1, AbilityIdsCustom_build, target_1, new_OrderAction(invalidateCb, cancelCb))
				call dispatch_BuildingSite_BuildingSystem_BuildingSite_addWorker(targetBuildingSite_1, source_1)
			elseif temp == AbilityIdsCustom_harvest then
				set targetResource_1 = unit_getResource(target_1)
				set clVar_2 = alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem_496()
				set source_718[clVar_2] = source_1
				set invalidateCb_1 = clVar_2
				set clVar_3 = alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem_497()
				set targetResource[clVar_3] = targetResource_1
				set cancelCb_1 = clVar_3
				set clVar_4 = alloc_CallbackSimple_registerPlayerUnitEvent_AbilitySystem_498()
				set targetResource_732[clVar_4] = targetResource_1
				set source_719[clVar_4] = source_1
				set target[clVar_4] = target_1
				set finishCb = clVar_4
				call unit_setOrder_1224(source_1, AbilityIdsCustom_harvest, target_1, new_OrderAction_1075(invalidateCb_1, cancelCb_1, finishCb, AbilityData_Harvest_cooldown, 0))
				call dispatch_Resource_ResourceSystem_Resource_addWorker(targetResource_1)
			elseif temp == AbilityIdsCustom_enterBuilding then
				call dispatch_Workshop_WorkshopSystem_Workshop_addWorker(unit_getWorkshop(target_1), source_1)
			elseif temp == AbilityIdsCustom_removeWorker then
				call dispatch_Workshop_WorkshopSystem_Workshop_removeWorker(unit_getWorkshop(source_1))
			elseif temp == AbilityIdsCustom_changeProduct then
				call dispatch_Workshop_WorkshopSystem_Workshop_changeProduct(unit_getWorkshop(source_1))
			endif
		elseif wval != 1 then
			call unit_reactOnInvalidAbility(source_1, abilityId, wval)
		endif
	endif
	set source_1 = null
	set target_1 = null
endfunction

function alloc_CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 661
		else
			call error("Out of memory: Could not create CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 661
	endif
	return this_1
endfunction

function alloc_CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem_505 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 662
		else
			call error("Out of memory: Could not create CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 662
	endif
	return this_1
endfunction

function alloc_CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem_506 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 663
		else
			call error("Out of memory: Could not create CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 663
	endif
	return this_1
endfunction

function unit_hasAbility takes unit this_1, integer id returns boolean
	return GetUnitAbilityLevel(this_1, id) > 0
endfunction

function int_getOrderName_1037 takes integer this_1, unit orderedUnit, boolean onlyCustomAbilities returns string
	local integer temp = this_1
	if temp == OrderIds_thunderbolt then
		if unit_hasAbility(orderedUnit, AbilityIdsCustom_harvest) then
			return "harvest"
		elseif unit_hasAbility(orderedUnit, AbilityIdsCustom_showTargetInfo) then
			return "show target info"
		endif
	elseif temp == OrderIds_shadowstrike then
		if unit_hasAbility(orderedUnit, AbilityIdsCustom_build) then
			return "build"
		endif
	elseif temp == OrderIds_frostnova then
		if unit_hasAbility(orderedUnit, AbilityIdsCustom_transferWares) then
			return "transfer wares"
		endif
	elseif temp == OrderIds_innerfire then
		if unit_hasAbility(orderedUnit, AbilityIdsCustom_addBuildingBuff) then
			return "add building buff"
		endif
	elseif onlyCustomAbilities then
		return null
	else
		return int_getOrderName(this_1)
	endif
	call Log_error("ERROR: Unmapped ability id (" + int_toString(this_1) + ")")
	return null
endfunction

function string_getOrderNameAbility takes string this_1 returns integer
	local string temp = this_1
	if temp == "harvest" then
		return AbilityIdsCustom_harvest
	elseif temp == "build" then
		return AbilityIdsCustom_build
	elseif temp == "show target info" then
		return AbilityIdsCustom_showTargetInfo
	elseif temp == "transfer wares" then
		return AbilityIdsCustom_transferWares
	elseif temp == "add building buff" then
		return AbilityIdsCustom_addBuildingBuff
	else
		call Log_error("ERROR: Unmapped order (" + this_1 + ")")
		return 0
	endif
endfunction

function code__registerPlayerUnitEvent_AbilitySystem_600 takes nothing returns nothing
	local integer issuedOrderId = GetIssuedOrderId()
	local unit source_1 = GetOrderedUnit()
	local string orderName = int_getOrderName_1037(issuedOrderId, source_1, true)
	local unit target_1
	local integer abilityId
	local integer wval
	local string temp
	local integer targetResource_1
	local integer clVar
	local integer clVar_1
	local integer clVar_2
	local integer temp_1
	local unit temp_2
	local integer temp_3
	local unit temp_4
	local unit temp_5
	local integer temp_6
	local unit temp_7
	if orderName != null then
		set target_1 = GetOrderTargetUnit()
		if target_1 != null then
			set abilityId = string_getOrderNameAbility(orderName)
			set wval = unit_getAbilityValidity(source_1, abilityId, target_1)
			if wval == 0 then
				set temp = orderName
				if temp == "harvest" then
					set targetResource_1 = unit_getResource(target_1)
					set temp_2 = source_1
					set temp_3 = issuedOrderId
					set temp_4 = target_1
					set clVar = alloc_CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem()
					set source_720[clVar] = source_1
					set temp_1 = clVar
					set clVar_1 = alloc_CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem_505()
					set targetResource_733[clVar_1] = targetResource_1
					call unit_setOrder_1224(temp_2, temp_3, temp_4, new_OrderAction(temp_1, clVar_1))
					call dispatch_Resource_ResourceSystem_Resource_addWorker(targetResource_1)
				elseif temp == "build" then
					set temp_5 = source_1
					set temp_6 = issuedOrderId
					set temp_7 = target_1
					set clVar_2 = alloc_CallbackSimple_setOrder_registerPlayerUnitEvent_AbilitySystem_506()
					set source_721[clVar_2] = source_1
					call unit_setOrder_1224(temp_5, temp_6, temp_7, new_OrderAction(clVar_2, 0))
				endif
			elseif wval != 1 then
				call unit_reactOnInvalidAbility(source_1, abilityId, wval)
			endif
		endif
	endif
	set source_1 = null
	set target_1 = null
	set temp_2 = null
	set temp_4 = null
	set temp_5 = null
	set temp_7 = null
endfunction

function alloc_CallbackSingle_doAfter_registerPlayerUnitEvent_BuildingSystem takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 673
		else
			call error("Out of memory: Could not create CallbackSingle_doAfter_registerPlayerUnitEvent_BuildingSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 673
	endif
	return this_1
endfunction

function getRequiredWorkPower takes integer buildingUnitId returns real
	local integer temp = buildingUnitId
	if temp == Melee_townHall then
		return 180.
	elseif temp == Melee_farm then
		return 35.
	elseif temp == Melee_blacksmith then
		return 70.
	elseif temp == Melee_lumberMill then
		return 60.
	elseif temp == Melee_arcaneVault then
		return 60.
	elseif temp == Melee_scoutTower then
		return 25.
	elseif temp == Melee_barracks then
		return 60.
	elseif temp == Melee_altarOfKings then
		return 60.
	elseif temp == Melee_workshop then
		return 60.
	elseif temp == Melee_arcaneSanctum then
		return 70.
	elseif temp == Melee_gryphonAviary then
		return 75.
	endif
	return 0.
endfunction

function code__registerPlayerUnitEvent_BuildingSystem takes nothing returns nothing
	local unit building_1 = GetConstructingStructure()
	local integer clVar
	local real temp
	if getRequiredWorkPower(unit_getUnitId(building_1)) > 0. then
		set temp = UtilityFunctions_MIN_TRIGGER_SLEEP_TIME
		set clVar = alloc_CallbackSingle_doAfter_registerPlayerUnitEvent_BuildingSystem()
		call construct_CallbackSingle(clVar)
		set building[clVar] = building_1
		call doAfter(temp, clVar)
	endif
	set building_1 = null
endfunction

function code__registerPlayerUnitEvent_BuildingSystem_602 takes nothing returns nothing
	local unit building_1 = GetTriggerUnit()
	call unit_removeBuildingSite(building_1)
	call unit_kill(building_1)
	call unit_remove(building_1)
	set building_1 = null
endfunction

function Dataset_setTimer takes integer this_1, real adjustingTime returns nothing
	if adjustingTime > 0. then
		call timer_setData(Dataset_adjustingTimer[this_1], Dataset_playerID[this_1])
		call timer_startPeriodic(Dataset_adjustingTimer[this_1], adjustingTime, ref_function_code__startPeriodic_Dataset_ObjectInfoSystem)
	else
		call timer_pause(Dataset_adjustingTimer[this_1])
	endif
endfunction

function dispatch_Dataset_ObjectInfoSystem_Dataset_setTimer takes integer this_1, real adjustingTime returns nothing
	if Dataset_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Dataset.setTimer")
		else
			call error("Called Dataset.setTimer on invalid object.")
		endif
	endif
	call Dataset_setTimer(this_1, adjustingTime)
endfunction

function alloc_PlayerIDClosure_enableBoard_ObjectInfoSystem takes nothing returns integer
	local integer this_1
	if PlayerIDClosure_firstFree == 0 then
		if PlayerIDClosure_maxIndex < 32768 then
			set PlayerIDClosure_maxIndex = PlayerIDClosure_maxIndex + 1
			set this_1 = PlayerIDClosure_maxIndex
			set PlayerIDClosure_typeId[this_1] = 764
		else
			call error("Out of memory: Could not create PlayerIDClosure_enableBoard_ObjectInfoSystem.")
			set this_1 = 0
		endif
	else
		set PlayerIDClosure_firstFree = PlayerIDClosure_firstFree - 1
		set this_1 = PlayerIDClosure_nextFree[PlayerIDClosure_firstFree]
		set PlayerIDClosure_typeId[this_1] = 764
	endif
	return this_1
endfunction

function Dataset_getMultiboard takes integer this_1 returns multiboard
	if Dataset_usedMultiboard[this_1] == null then
		set Dataset_usedMultiboard[this_1] = CreateMultiboard()
		call MultiboardSetTitleText(Dataset_usedMultiboard[this_1], "Object Informations")
		call MultiboardSetColumnCount(Dataset_usedMultiboard[this_1], 1)
		call MultiboardMinimize(Dataset_usedMultiboard[this_1], false)
	endif
	return Dataset_usedMultiboard[this_1]
endfunction

function dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboard takes integer this_1 returns multiboard
	local multiboard ObjectInfoSystem_Dataset_getMultiboard_result
	if Dataset_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Dataset.getMultiboard")
		else
			call error("Called Dataset.getMultiboard on invalid object.")
		endif
	endif
	set ObjectInfoSystem_Dataset_getMultiboard_result = Dataset_getMultiboard(this_1)
	set dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboardtempReturn = ObjectInfoSystem_Dataset_getMultiboard_result
	set ObjectInfoSystem_Dataset_getMultiboard_result = null
	return dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboardtempReturn
endfunction

function BuildingSite_getWorkPower takes integer this_1 returns real
	return BuildingSite_workPower[this_1]
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkPower takes integer this_1 returns real
	local real BuildingSystem_BuildingSite_getWorkPower_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.getWorkPower")
		else
			call error("Called BuildingSite.getWorkPower on invalid object.")
		endif
	endif
	set BuildingSystem_BuildingSite_getWorkPower_result = BuildingSite_getWorkPower(this_1)
	return BuildingSystem_BuildingSite_getWorkPower_result
endfunction

function BuildingSite_getWorkProgressLeft takes integer this_1 returns real
	return BuildingSite_workProgressFinished[this_1] - BuildingSite_workProgressCurrent[this_1]
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkProgressLeft takes integer this_1 returns real
	local real BuildingSystem_BuildingSite_getWorkProgressLeft_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.getWorkProgressLeft")
		else
			call error("Called BuildingSite.getWorkProgressLeft on invalid object.")
		endif
	endif
	set BuildingSystem_BuildingSite_getWorkProgressLeft_result = BuildingSite_getWorkProgressLeft(this_1)
	return BuildingSystem_BuildingSite_getWorkProgressLeft_result
endfunction

function BuildingSite_getWorkProgressPercentage takes integer this_1 returns real
	return 100. * BuildingSite_workProgressCurrent[this_1] / BuildingSite_workProgressFinished[this_1]
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkProgressPercentage takes integer this_1 returns real
	local real BuildingSystem_BuildingSite_getWorkProgressPercentage_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.getWorkProgressPercentage")
		else
			call error("Called BuildingSite.getWorkProgressPercentage on invalid object.")
		endif
	endif
	set BuildingSystem_BuildingSite_getWorkProgressPercentage_result = BuildingSite_getWorkProgressPercentage(this_1)
	return BuildingSystem_BuildingSite_getWorkProgressPercentage_result
endfunction

function BuildingSite_getWorkerCount takes integer this_1 returns integer
	return BuildingSite_workerCount[this_1]
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkerCount takes integer this_1 returns integer
	local integer BuildingSystem_BuildingSite_getWorkerCount_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.getWorkerCount")
		else
			call error("Called BuildingSite.getWorkerCount on invalid object.")
		endif
	endif
	set BuildingSystem_BuildingSite_getWorkerCount_result = BuildingSite_getWorkerCount(this_1)
	return BuildingSystem_BuildingSite_getWorkerCount_result
endfunction

function multiboard_addMultiboardLine takes multiboard this_1, string text, string iconPath returns nothing
	local integer lineNumber = MultiboardGetRowCount(this_1) + 1
	local multiboarditem multiboardItem
	call MultiboardSetRowCount(this_1, lineNumber)
	set multiboardItem = MultiboardGetItem(this_1, lineNumber - 1, 0)
	call MultiboardSetItemValue(multiboardItem, text)
	call MultiboardSetItemIcon(multiboardItem, iconPath)
	if iconPath == MultiboardPrioritySystem_HEADLINE_ICON_PATH then
		call MultiboardSetItemValueColor(multiboardItem, 255, 0, 0, 255)
	elseif iconPath == MultiboardPrioritySystem_SUB_HEADLINE_ICON_PATH then
		call MultiboardSetItemValueColor(multiboardItem, 255, 200, 0, 255)
	endif
	call MultiboardSetItemWidth(multiboardItem, 0.15)
	call MultiboardReleaseItem(multiboardItem)
	set multiboardItem = null
endfunction

function WareType_getIconPath takes integer this_1 returns string
	local integer temp = this_1
	if temp == 0 then
		return Icons_bTNBundleOfLumber
	elseif temp == 1 then
		return "Icons\\BTNINV_Stone_12.blp"
	elseif temp == 2 then
		return Icons_bTNHumanArmorUpOne
	elseif temp == 3 then
		return Icons_bTNMonsterLure
	elseif temp == 6 then
		return Icons_bTNHumanLumberUpgrade2
	elseif temp == 7 then
		return Icons_bTNHumanLumberUpgrade1
	elseif temp == 8 then
		return "Icons\\BTNStrawBunch.blp"
	else
		return null
	endif
endfunction

function ware_getIconPath takes integer this_wareType, integer this_count returns string
	return WareType_getIconPath(this_wareType)
endfunction

function WareType_toString takes integer this_1 returns string
	local integer temp = this_1
	if temp == 0 then
		return "wood"
	elseif temp == 1 then
		return "stone"
	elseif temp == 2 then
		return "metal"
	elseif temp == 3 then
		return "food"
	elseif temp == 4 then
		return "iron ore"
	elseif temp == 5 then
		return "coal"
	elseif temp == 6 then
		return "wooden boards"
	elseif temp == 7 then
		return "wooden sticks"
	elseif temp == 8 then
		return "straw"
	else
		return "undefined ware"
	endif
endfunction

function string_length takes string this_1 returns integer
	return StringLength(this_1)
endfunction

function string_substring takes string this_1, integer start, integer stop returns string
	return SubString(this_1, start, stop)
endfunction

function string_firstUpper takes string this_1 returns string
	if this_1 == "" then
		return ""
	endif
	return StringCase(string_substring(this_1, 0, 1), true) + string_substring(this_1, 1, string_length(this_1))
endfunction

function ware_toString takes integer this_wareType, integer this_count, boolean upperCase returns string
	if upperCase then
		return string_firstUpper(WareType_toString(this_wareType))
	else
		return WareType_toString(this_wareType)
	endif
endfunction

function multiboard_setObjectInfoMultiboard takes multiboard this_1, integer bs returns boolean
	local real workPower
	local integer amountOfWareTypes
	local integer i
	local integer temp
	local integer ware_wareType
	local integer ware_count
	local integer tuple_temp
	local integer tuple_temp_1
	call multiboard_addMultiboardLine(this_1, "Building site:", MultiboardPrioritySystem_HEADLINE_ICON_PATH)
	call multiboard_addMultiboardLine(this_1, "Build progress: " + int_toString(real_toInt(dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkProgressPercentage(bs))) + "%", BuildingSystem_BUILD_PROGRESS_ICON_PATH)
	set workPower = dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkPower(bs)
	if workPower > 0. then
		call multiboard_addMultiboardLine(this_1, "Build time left: " + int_toString(real_toInt(dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkProgressLeft(bs) / workPower)) + "s", BuildingSystem_BUILD_TIME_LEFT_ICON_PATH)
		call multiboard_addMultiboardLine(this_1, "Workers: " + int_toString(dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkerCount(bs)), BuildingSystem_WORKERS_ICON_PATH)
	endif
	set amountOfWareTypes = dispatch_Stock_Stock_Stock_getAmountOfWareTypes(bs)
	if amountOfWareTypes > 0 then
		call multiboard_addMultiboardLine(this_1, "Required wares:", MultiboardPrioritySystem_SUB_HEADLINE_ICON_PATH)
		set i = 0
		set temp = amountOfWareTypes - 1
		loop
			exitwhen i > temp
			set tuple_temp = dispatch_Stock_Stock_Stock_getWare(bs, i)
			set tuple_temp_1 = dispatch_Stock_Stock_Stock_getWare_return_count
			set ware_wareType = tuple_temp
			set ware_count = tuple_temp_1
			call multiboard_addMultiboardLine(this_1, int_toString(ware_count) + " " + ware_toString(ware_wareType, ware_count, true), ware_getIconPath(ware_wareType, ware_count))
			set i = i + 1
		endloop
	endif
	return true
endfunction

function int_getOrderName_1038 takes integer this_1, unit orderedUnit returns string
	return int_getOrderName_1037(this_1, orderedUnit, false)
endfunction

function multiboard_setObjectInfoMultiboard_1055 takes multiboard this_1, integer o returns boolean
	local string currentOrderName = int_getOrderName_1038(OrderSource_orderId[o], OrderSource_source[o])
	if currentOrderName == null then
		set currentOrderName = "none"
	endif
	call multiboard_addMultiboardLine(this_1, "Order:", MultiboardPrioritySystem_HEADLINE_ICON_PATH)
	call multiboard_addMultiboardLine(this_1, "Current: " + string_firstUpper(currentOrderName), OrderSystem_ORDER_ICON_PATH)
	return true
endfunction

function real_toString takes real this_1 returns string
	return R2S(this_1)
endfunction

function multiboard_setObjectInfoMultiboard_1056 takes multiboard this_1, integer p returns boolean
	call multiboard_addMultiboardLine(this_1, Person_name[p] + ":", MultiboardPrioritySystem_HEADLINE_ICON_PATH)
	call multiboard_addMultiboardLine(this_1, "Food: " + real_toString(Person_food[p]), PersonSystem_FOOD_ICON_PATH)
	call multiboard_addMultiboardLine(this_1, "Sleep: " + real_toString(Person_sleep[p]), PersonSystem_SLEEP_ICON_PATH)
	if Person_house[p] != null then
		call multiboard_addMultiboardLine(this_1, "House: " + unit_getName(Person_house[p]), PersonSystem_HOUSE_ICON_PATH)
	endif
	if Person_workplace[p] != null then
		call multiboard_addMultiboardLine(this_1, "Workplace: " + unit_getName(Person_workplace[p]), PersonSystem_WORKPLACE_ICON_PATH)
	endif
	return true
endfunction

function Resource_getWorkerCount takes integer this_1 returns integer
	return Resource_workerCount[this_1]
endfunction

function dispatch_Resource_ResourceSystem_Resource_getWorkerCount takes integer this_1 returns integer
	local integer ResourceSystem_Resource_getWorkerCount_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Resource.getWorkerCount")
		else
			call error("Called Resource.getWorkerCount on invalid object.")
		endif
	endif
	set ResourceSystem_Resource_getWorkerCount_result = Resource_getWorkerCount(this_1)
	return ResourceSystem_Resource_getWorkerCount_result
endfunction

function multiboard_setObjectInfoMultiboard_1057 takes multiboard this_1, integer r returns boolean
	local integer i
	local integer temp
	local integer ware_wareType
	local integer ware_count
	local integer tuple_temp
	local integer tuple_temp_1
	call multiboard_addMultiboardLine(this_1, "Resource:", MultiboardPrioritySystem_HEADLINE_ICON_PATH)
	call multiboard_addMultiboardLine(this_1, "Workers: " + int_toString(dispatch_Resource_ResourceSystem_Resource_getWorkerCount(r)) + "/" + int_toString(getMaxWorkerCount(unit_getUnitId(Stock_user[r]))), ResourceSystem_WORKERS_ICON_PATH)
	set i = 0
	set temp = dispatch_Stock_Stock_Stock_getAmountOfWareTypes(r) - 1
	loop
		exitwhen i > temp
		set tuple_temp = dispatch_Stock_Stock_Stock_getWare(r, i)
		set tuple_temp_1 = dispatch_Stock_Stock_Stock_getWare_return_count
		set ware_wareType = tuple_temp
		set ware_count = tuple_temp_1
		call multiboard_addMultiboardLine(this_1, int_toString(ware_count) + " " + ware_toString(ware_wareType, ware_count, true), ware_getIconPath(ware_wareType, ware_count))
		set i = i + 1
	endloop
	return true
endfunction

function Storage_getMaxCapacity takes integer this_1 returns integer
	return Storage_maxCapacity[this_1]
endfunction

function dispatch_Storage_StorageSystem_Storage_getMaxCapacity takes integer this_1 returns integer
	local integer StorageSystem_Storage_getMaxCapacity_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.getMaxCapacity")
		else
			call error("Called Storage.getMaxCapacity on invalid object.")
		endif
	endif
	set StorageSystem_Storage_getMaxCapacity_result = Storage_getMaxCapacity(this_1)
	return StorageSystem_Storage_getMaxCapacity_result
endfunction

function multiboard_setObjectInfoMultiboard_1058 takes multiboard this_1, integer s returns boolean
	local integer i
	local integer temp
	local integer ware_wareType
	local integer ware_count
	local integer tuple_temp
	local integer tuple_temp_1
	call multiboard_addMultiboardLine(this_1, "Storage:", MultiboardPrioritySystem_HEADLINE_ICON_PATH)
	call multiboard_addMultiboardLine(this_1, "Capacity: " + int_toString(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(s)) + "/" + int_toString(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(s)), StorageSystem_CAPACITY_ICON_PATH)
	set i = 0
	set temp = dispatch_Stock_Stock_Stock_getAmountOfWareTypes(s) - 1
	loop
		exitwhen i > temp
		set tuple_temp = dispatch_Stock_Stock_Stock_getWare(s, i)
		set tuple_temp_1 = dispatch_Stock_Stock_Stock_getWare_return_count
		set ware_wareType = tuple_temp
		set ware_count = tuple_temp_1
		call multiboard_addMultiboardLine(this_1, int_toString(ware_count) + " " + ware_toString(ware_wareType, ware_count, true), ware_getIconPath(ware_wareType, ware_count))
		set i = i + 1
	endloop
	return true
endfunction

function Workshop_getStoredEducts takes integer this_1 returns integer
	local integer amount = Stock_MAX_WARE_COUNT
	local integer educts = dispatch_Workshop_WorkshopSystem_Workshop_getEducts(this_1)
	local integer iterator = LinkedList_iterator(educts)
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		set amount = min_2(amount, dispatch_Stock_Stock_Stock_getWareCount(this_1, iWare_wareType) / iWare_count)
	endloop
	call LLIterator_close(iterator)
	call dispatch_LinkedList_destroyLinkedList(educts)
	return amount
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_getStoredEducts takes integer this_1 returns integer
	local integer WorkshopSystem_Workshop_getStoredEducts_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.getStoredEducts")
		else
			call error("Called Workshop.getStoredEducts on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_getStoredEducts_result = Workshop_getStoredEducts(this_1)
	return WorkshopSystem_Workshop_getStoredEducts_result
endfunction

function Workshop_getStoredProducts takes integer this_1 returns integer
	local integer amount = Stock_MAX_WARE_COUNT
	local integer products = dispatch_Workshop_WorkshopSystem_Workshop_getProducts(this_1)
	local integer iterator = LinkedList_iterator(products)
	local integer iWare_wareType
	local integer iWare_count
	local integer tuple_temp
	local integer tuple_temp_1
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set iWare_wareType = tuple_temp
		set iWare_count = tuple_temp_1
		set amount = min_2(amount, dispatch_Stock_Stock_Stock_getWareCount(this_1, iWare_wareType) / iWare_count)
	endloop
	call LLIterator_close(iterator)
	call dispatch_LinkedList_destroyLinkedList(products)
	return amount
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_getStoredProducts takes integer this_1 returns integer
	local integer WorkshopSystem_Workshop_getStoredProducts_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.getStoredProducts")
		else
			call error("Called Workshop.getStoredProducts on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_getStoredProducts_result = Workshop_getStoredProducts(this_1)
	return WorkshopSystem_Workshop_getStoredProducts_result
endfunction

function Workshop_getWorkPower takes integer this_1 returns real
	return Workshop_workPower[this_1]
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_getWorkPower takes integer this_1 returns real
	local real WorkshopSystem_Workshop_getWorkPower_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.getWorkPower")
		else
			call error("Called Workshop.getWorkPower on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_getWorkPower_result = Workshop_getWorkPower(this_1)
	return WorkshopSystem_Workshop_getWorkPower_result
endfunction

function Workshop_getWorkProgressLeft takes integer this_1 returns real
	return Workshop_workProgressFinished[this_1] - Workshop_workProgressCurrent[this_1]
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_getWorkProgressLeft takes integer this_1 returns real
	local real WorkshopSystem_Workshop_getWorkProgressLeft_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.getWorkProgressLeft")
		else
			call error("Called Workshop.getWorkProgressLeft on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_getWorkProgressLeft_result = Workshop_getWorkProgressLeft(this_1)
	return WorkshopSystem_Workshop_getWorkProgressLeft_result
endfunction

function Workshop_getWorkProgressPercentage takes integer this_1 returns real
	return Workshop_workProgressCurrent[this_1] / Workshop_workProgressFinished[this_1]
endfunction

function dispatch_Workshop_WorkshopSystem_Workshop_getWorkProgressPercentage takes integer this_1 returns real
	local real WorkshopSystem_Workshop_getWorkProgressPercentage_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Workshop.getWorkProgressPercentage")
		else
			call error("Called Workshop.getWorkProgressPercentage on invalid object.")
		endif
	endif
	set WorkshopSystem_Workshop_getWorkProgressPercentage_result = Workshop_getWorkProgressPercentage(this_1)
	return WorkshopSystem_Workshop_getWorkProgressPercentage_result
endfunction

function multiboard_setObjectInfoMultiboard_1059 takes multiboard this_1, integer ws returns boolean
	local real workPower
	local integer educts
	local integer iterator
	local integer ware_wareType
	local integer ware_count
	local integer products
	local integer iterator_1
	local integer ware_wareType_1
	local integer ware_count_1
	local integer tuple_temp
	local integer tuple_temp_1
	local integer tuple_temp_2
	local integer tuple_temp_3
	call multiboard_addMultiboardLine(this_1, "Workshop:", MultiboardPrioritySystem_HEADLINE_ICON_PATH)
	call multiboard_addMultiboardLine(this_1, "Production progress: " + int_toString(real_toInt(dispatch_Workshop_WorkshopSystem_Workshop_getWorkProgressPercentage(ws))) + "%", WorkshopSystem_PRODUCTION_PROGRESS_ICON_PATH)
	set workPower = dispatch_Workshop_WorkshopSystem_Workshop_getWorkPower(ws)
	if workPower > 0. then
		call multiboard_addMultiboardLine(this_1, "Production time left: " + int_toString(real_toInt(dispatch_Workshop_WorkshopSystem_Workshop_getWorkProgressLeft(ws) / workPower)) + "s", WorkshopSystem_PRODUCTION_TIME_LEFT_ICON_PATH)
		call multiboard_addMultiboardLine(this_1, "Workers: " + int_toString(dispatch_Workshop_WorkshopSystem_Workshop_getWorkerCount(ws)), WorkshopSystem_WORKERS_ICON_PATH)
	endif
	call multiboard_addMultiboardLine(this_1, "Educts (" + int_toString(dispatch_Workshop_WorkshopSystem_Workshop_getStoredEducts(ws)) + "/" + int_toString(WorkshopSystem_MAX_STORABLE_EDUCTS) + "):", MultiboardPrioritySystem_SUB_HEADLINE_ICON_PATH)
	set educts = dispatch_Workshop_WorkshopSystem_Workshop_getEducts(ws)
	set iterator = LinkedList_iterator(educts)
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set tuple_temp_1 = wareFromIndex_return_count
		set ware_wareType = tuple_temp
		set ware_count = tuple_temp_1
		call multiboard_addMultiboardLine(this_1, int_toString(ware_count) + " " + ware_toString(ware_wareType, ware_count, true), ware_getIconPath(ware_wareType, ware_count))
	endloop
	call LLIterator_close(iterator)
	call dispatch_LinkedList_destroyLinkedList(educts)
	call multiboard_addMultiboardLine(this_1, "Products (" + int_toString(dispatch_Workshop_WorkshopSystem_Workshop_getStoredProducts(ws)) + "/" + int_toString(WorkshopSystem_MAX_STORABLE_PRODUCTS) + ")", MultiboardPrioritySystem_SUB_HEADLINE_ICON_PATH)
	set products = dispatch_Workshop_WorkshopSystem_Workshop_getProducts(ws)
	set iterator_1 = LinkedList_iterator(products)
	loop
		exitwhen  not LLIterator_hasNext(iterator_1)
		set tuple_temp_2 = wareFromIndex(LLIterator_next(iterator_1))
		set tuple_temp_3 = wareFromIndex_return_count
		set ware_wareType_1 = tuple_temp_2
		set ware_count_1 = tuple_temp_3
		call multiboard_addMultiboardLine(this_1, int_toString(ware_count_1) + " " + ware_toString(ware_wareType_1, ware_count_1, true), ware_getIconPath(ware_wareType_1, ware_count_1))
	endloop
	call LLIterator_close(iterator_1)
	call dispatch_LinkedList_destroyLinkedList(products)
	return true
endfunction

function unit_getPerson takes unit this_1 returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(PersonSystem_PERSON_MAP, this_1)
endfunction

function createMultiboardLines takes integer playerID returns boolean
	local boolean hasInfo = false
	local integer resource = unit_getResource(Dataset_targetedUnit[ObjectInfoSystem_datasets[playerID]])
	local integer buildingSite
	local integer person
	local integer workshop
	local integer storage
	local integer orderSource
	if resource != 0 then
		set hasInfo = multiboard_setObjectInfoMultiboard_1057(dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboard(ObjectInfoSystem_datasets[playerID]), resource) or hasInfo
	endif
	if unit_getOwner(Dataset_targetedUnit[ObjectInfoSystem_datasets[playerID]]) == Player(playerID) then
		set buildingSite = unit_getBuildingSite(Dataset_targetedUnit[ObjectInfoSystem_datasets[playerID]])
		if buildingSite != 0 then
			set hasInfo = multiboard_setObjectInfoMultiboard(dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboard(ObjectInfoSystem_datasets[playerID]), buildingSite) or hasInfo
		endif
		set person = unit_getPerson(Dataset_targetedUnit[ObjectInfoSystem_datasets[playerID]])
		if person != 0 then
			set hasInfo = multiboard_setObjectInfoMultiboard_1056(dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboard(ObjectInfoSystem_datasets[playerID]), person) or hasInfo
		endif
		set workshop = unit_getWorkshop(Dataset_targetedUnit[ObjectInfoSystem_datasets[playerID]])
		if workshop != 0 then
			set hasInfo = multiboard_setObjectInfoMultiboard_1059(dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboard(ObjectInfoSystem_datasets[playerID]), workshop) or hasInfo
		endif
		set storage = unit_getStorage(Dataset_targetedUnit[ObjectInfoSystem_datasets[playerID]])
		if storage != 0 then
			set hasInfo = multiboard_setObjectInfoMultiboard_1058(dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboard(ObjectInfoSystem_datasets[playerID]), storage) or hasInfo
		endif
		set orderSource = unit_getOrderSource(Dataset_targetedUnit[ObjectInfoSystem_datasets[playerID]])
		if orderSource != 0 then
			set hasInfo = multiboard_setObjectInfoMultiboard_1055(dispatch_Dataset_ObjectInfoSystem_Dataset_getMultiboard(ObjectInfoSystem_datasets[playerID]), orderSource) or hasInfo
		endif
	endif
	return hasInfo
endfunction

function Dataset_displayMultiboard takes integer this_1, integer playerID, boolean show returns nothing
	if Dataset_usedMultiboard[this_1] != null then
		if GetLocalPlayer() == Player(playerID) then
			call MultiboardDisplay(Dataset_usedMultiboard[this_1], show)
		endif
	elseif show then
		call Log_error("ERROR: Empty multiboard can't be displayed")
	endif
endfunction

function dispatch_Dataset_ObjectInfoSystem_Dataset_displayMultiboard takes integer this_1, integer playerID, boolean show returns nothing
	if Dataset_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Dataset.displayMultiboard")
		else
			call error("Called Dataset.displayMultiboard on invalid object.")
		endif
	endif
	call Dataset_displayMultiboard(this_1, playerID, show)
endfunction

function deactivateDataset takes integer playerID returns nothing
	local integer dataset = ObjectInfoSystem_datasets[playerID]
	call dispatch_Dataset_ObjectInfoSystem_Dataset_setTimer(dataset, 0.)
	set Dataset_targetedUnit[dataset] = null
	set Dataset_targetedDestructable[dataset] = null
	call dispatch_Dataset_ObjectInfoSystem_Dataset_displayMultiboard(dataset, playerID, false)
endfunction

function run_enableBoard_ObjectInfoSystem takes integer this_1, integer playerID returns nothing
	call deactivateDataset(playerID)
endfunction

function dispatch_PlayerIDClosure_MultiboardPrioritySystem_PlayerIDClosure_run takes integer this_1, integer playerID returns nothing
	if PlayerIDClosure_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling PlayerIDClosure.run")
		else
			call error("Called PlayerIDClosure.run on invalid object.")
		endif
	endif
	call run_enableBoard_ObjectInfoSystem(this_1, playerID)
endfunction

function isBoardActiv takes integer playerID, string name returns boolean
	return name == Board_name[MultiboardPrioritySystem_currentBoards[playerID]]
endfunction

function disableBoard takes integer playerID, string name returns boolean
	local integer currentBoard
	if isBoardActiv(playerID, name) == false then
		return false
	endif
	set currentBoard = MultiboardPrioritySystem_currentBoards[playerID]
	if Board_disableFunc[currentBoard] != 0 then
		call dispatch_PlayerIDClosure_MultiboardPrioritySystem_PlayerIDClosure_run(Board_disableFunc[currentBoard], playerID)
	endif
	set Board_disableFunc[currentBoard] = 0
	set Board_priority[currentBoard] = 0
	set Board_name[currentBoard] = null
	return true
endfunction

function Dataset_resetMultiboard takes integer this_1 returns nothing
	if Dataset_usedMultiboard[this_1] != null then
		call DestroyMultiboard(Dataset_usedMultiboard[this_1])
		set Dataset_usedMultiboard[this_1] = null
	endif
endfunction

function dispatch_Dataset_ObjectInfoSystem_Dataset_resetMultiboard takes integer this_1 returns nothing
	if Dataset_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Dataset.resetMultiboard")
		else
			call error("Called Dataset.resetMultiboard on invalid object.")
		endif
	endif
	call Dataset_resetMultiboard(this_1)
endfunction

function enableBoard takes integer playerID, string name, integer priority, integer disableFunc returns boolean
	local integer currentBoard
	if isBoardActiv(playerID, name) then
		return true
	endif
	set currentBoard = MultiboardPrioritySystem_currentBoards[playerID]
	if priority >= Board_priority[currentBoard] then
		if Board_disableFunc[currentBoard] != 0 then
			call dispatch_PlayerIDClosure_MultiboardPrioritySystem_PlayerIDClosure_run(Board_disableFunc[currentBoard], playerID)
		endif
		set Board_disableFunc[currentBoard] = disableFunc
		set Board_priority[currentBoard] = priority
		set Board_name[currentBoard] = name
		return true
	endif
	return false
endfunction

function showObjectInfo takes integer playerID returns nothing
	local integer dataset = ObjectInfoSystem_datasets[playerID]
	local integer clVar
	local integer temp
	local string temp_1
	local integer temp_2
	if Dataset_targetedUnit[dataset] != null and IsUnitSelected(Dataset_targetedUnit[dataset], Player(playerID)) == false then
		call disableBoard(playerID, ObjectInfoSystem_MULTIBOARD_NAME)
	else
		set temp = playerID
		set temp_1 = ObjectInfoSystem_MULTIBOARD_NAME
		set temp_2 = ObjectInfoSystem_MULTIBOARD_PRIORITY
		set clVar = alloc_PlayerIDClosure_enableBoard_ObjectInfoSystem()
		if enableBoard(temp, temp_1, temp_2, clVar) then
			call dispatch_Dataset_ObjectInfoSystem_Dataset_resetMultiboard(dataset)
			if createMultiboardLines(playerID) then
				call dispatch_Dataset_ObjectInfoSystem_Dataset_displayMultiboard(dataset, playerID, true)
			else
				call disableBoard(playerID, ObjectInfoSystem_MULTIBOARD_NAME)
			endif
		else
			call dispatch_Dataset_ObjectInfoSystem_Dataset_setTimer(dataset, 0.)
		endif
	endif
endfunction

function code__registerPlayerUnitEvent_ObjectInfoSystem takes nothing returns nothing
	local integer playerID = GetPlayerId(GetTriggerPlayer())
	local integer dataset = ObjectInfoSystem_datasets[playerID]
	call dispatch_Dataset_ObjectInfoSystem_Dataset_setTimer(dataset, 0.)
	set Dataset_targetedUnit[dataset] = GetTriggerUnit()
	if Dataset_targetedUnit[dataset] != null then
		set Dataset_targetedDestructable[dataset] = null
		call dispatch_Dataset_ObjectInfoSystem_Dataset_setTimer(dataset, ObjectInfoSystem_ADJUSTING_TIME)
		call showObjectInfo(playerID)
	endif
endfunction

function print takes string msg returns nothing
	call DisplayTimedTextToPlayer(Player_localPlayer, 0., 0., Printing_DEBUG_MSG_DURATION, msg)
endfunction

function code__registerPlayerUnitEvent_ObjectInfoSystem_604 takes nothing returns nothing
	local integer playerID
	local unit targetUnit
	local integer dataset
	if GetSpellAbilityId() == AbilityIdsCustom_showTargetInfo then
		set playerID = GetPlayerId(GetTriggerPlayer())
		set targetUnit = GetSpellTargetUnit()
		set dataset = ObjectInfoSystem_datasets[playerID]
		call print("SHOW_TARGET_INFO cast")
		call dispatch_Dataset_ObjectInfoSystem_Dataset_setTimer(dataset, 0.)
		if GetLocalPlayer() == Player(playerID) then
			call ClearSelection()
		endif
		if targetUnit != null then
			if GetLocalPlayer() == Player(playerID) then
				call SelectUnit(targetUnit, true)
			endif
		else
			set Dataset_targetedDestructable[dataset] = GetSpellTargetDestructable()
			if Dataset_targetedDestructable[dataset] != null then
				set Dataset_targetedUnit[dataset] = null
				call dispatch_Dataset_ObjectInfoSystem_Dataset_setTimer(dataset, ObjectInfoSystem_ADJUSTING_TIME)
				call showObjectInfo(playerID)
			endif
		endif
	endif
	set targetUnit = null
endfunction

function code__registerPlayerUnitEvent_OrderSystem takes nothing returns nothing
	call unit_removeAllOrders(GetTriggerUnit())
endfunction

function code__registerPlayerUnitEvent_OrderSystem_606 takes nothing returns nothing
	call unit_removeAllOrders(GetTriggerUnit())
endfunction

function code__registerPlayerUnitEvent_OrderSystem_607 takes nothing returns nothing
	call unit_removeAllOrders(GetTriggerUnit())
endfunction

function alloc_CallbackCondition_registerPlayerUnitEvent_OrderSystem takes nothing returns integer
	local integer this_1
	if CallbackCondition_firstFree == 0 then
		if CallbackCondition_maxIndex < 32768 then
			set CallbackCondition_maxIndex = CallbackCondition_maxIndex + 1
			set this_1 = CallbackCondition_maxIndex
			set CallbackCondition_typeId[this_1] = 644
		else
			call error("Out of memory: Could not create CallbackCondition_registerPlayerUnitEvent_OrderSystem.")
			set this_1 = 0
		endif
	else
		set CallbackCondition_firstFree = CallbackCondition_firstFree - 1
		set this_1 = CallbackCondition_nextFree[CallbackCondition_firstFree]
		set CallbackCondition_typeId[this_1] = 644
	endif
	return this_1
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 656
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_OrderSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 656
	endif
	return this_1
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem_500 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 657
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_OrderSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 657
	endif
	return this_1
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem_501 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 658
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_OrderSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 658
	endif
	return this_1
endfunction

function alloc_CallbackCondition_OrderSystem takes nothing returns integer
	local integer this_1
	if CallbackCondition_firstFree == 0 then
		if CallbackCondition_maxIndex < 32768 then
			set CallbackCondition_maxIndex = CallbackCondition_maxIndex + 1
			set this_1 = CallbackCondition_maxIndex
			set CallbackCondition_typeId[this_1] = 643
		else
			call error("Out of memory: Could not create CallbackCondition_OrderSystem.")
			set this_1 = 0
		endif
	else
		set CallbackCondition_firstFree = CallbackCondition_firstFree - 1
		set this_1 = CallbackCondition_nextFree[CallbackCondition_firstFree]
		set CallbackCondition_typeId[this_1] = 643
	endif
	return this_1
endfunction

function unit_getFinishConditionNoMovement takes unit this_1 returns integer
	local real tuple_temp = unit_getPos(this_1)
	local real tuple_temp_1 = unit_getPos_return_y
	local real w_lastPos_x_1 = tuple_temp
	local real w_lastPos_y_1 = tuple_temp_1
	local integer clVar = alloc_CallbackCondition_OrderSystem()
	local integer finishCondition
	local real tuple_temp_2
	local real tuple_temp_3
	set this[clVar] = this_1
	set tuple_temp_2 = w_lastPos_x_1
	set tuple_temp_3 = w_lastPos_y_1
	set w_lastPos_x[clVar] = tuple_temp_2
	set w_lastPos_y[clVar] = tuple_temp_3
	set finishCondition = clVar
	return finishCondition
endfunction

function unit_isType takes unit this_1, unittype utype returns boolean
	return IsUnitType(this_1, utype)
endfunction

function alloc_OrderSourceD takes nothing returns integer
	local integer this_1
	if OrderSource_firstFree == 0 then
		if OrderSource_maxIndex < 32768 then
			set OrderSource_maxIndex = OrderSource_maxIndex + 1
			set this_1 = OrderSource_maxIndex
			set OrderSource_typeId[this_1] = 757
		else
			call error("Out of memory: Could not create OrderSourceD.")
			set this_1 = 0
		endif
	else
		set OrderSource_firstFree = OrderSource_firstFree - 1
		set this_1 = OrderSource_nextFree[OrderSource_firstFree]
		set OrderSource_typeId[this_1] = 757
	endif
	return this_1
endfunction

function OrderSourceD_init takes integer this_1 returns nothing
endfunction

function construct_OrderSourceD takes integer this_1, unit source_1, integer orderId, destructable target_1, integer orderAction returns nothing
	call construct_OrderSource(this_1, source_1, orderId, orderAction)
	call OrderSourceD_init(this_1)
endfunction

function new_OrderSourceD takes unit source_1, integer orderId, destructable target_1, integer orderAction returns integer
	local integer this_1 = alloc_OrderSourceD()
	call construct_OrderSourceD(this_1, source_1, orderId, target_1, orderAction)
	return this_1
endfunction

function unit_setOrder_1225 takes unit this_1, integer orderId, destructable target_1, integer orderAction returns nothing
	call unit_setOrder(this_1, new_OrderSourceD(this_1, orderId, target_1, orderAction))
endfunction

function alloc_OrderSourceI takes nothing returns integer
	local integer this_1
	if OrderSource_firstFree == 0 then
		if OrderSource_maxIndex < 32768 then
			set OrderSource_maxIndex = OrderSource_maxIndex + 1
			set this_1 = OrderSource_maxIndex
			set OrderSource_typeId[this_1] = 758
		else
			call error("Out of memory: Could not create OrderSourceI.")
			set this_1 = 0
		endif
	else
		set OrderSource_firstFree = OrderSource_firstFree - 1
		set this_1 = OrderSource_nextFree[OrderSource_firstFree]
		set OrderSource_typeId[this_1] = 758
	endif
	return this_1
endfunction

function OrderSourceI_init takes integer this_1 returns nothing
endfunction

function construct_OrderSourceI takes integer this_1, unit source_1, integer orderId, item target_1, integer orderAction returns nothing
	call construct_OrderSource(this_1, source_1, orderId, orderAction)
	call OrderSourceI_init(this_1)
endfunction

function new_OrderSourceI takes unit source_1, integer orderId, item target_1, integer orderAction returns integer
	local integer this_1 = alloc_OrderSourceI()
	call construct_OrderSourceI(this_1, source_1, orderId, target_1, orderAction)
	return this_1
endfunction

function unit_setOrder_1226 takes unit this_1, integer orderId, item target_1, integer orderAction returns nothing
	call unit_setOrder(this_1, new_OrderSourceI(this_1, orderId, target_1, orderAction))
endfunction

function code__registerPlayerUnitEvent_OrderSystem_608 takes nothing returns nothing
	local integer issuedOrderId = GetIssuedOrderId()
	local unit source_1
	local integer orderAction
	local unit targetU
	local integer sourceUnitId
	local integer clVar
	local destructable targetD
	local integer clVar_1
	local item targetI_1
	local integer clVar_2
	local integer clVar_3
	local integer temp
	local real temp_1
	if issuedOrderId != SpecialOrders_stunned then
		set source_1 = GetOrderedUnit()
		set orderAction = 0
		set targetU = GetOrderTargetUnit()
		if targetU != null then
			set sourceUnitId = unit_getUnitId(source_1)
			if sourceUnitId != InstantDummyCaster_DUMMY_CASTER_UNIT_ID and sourceUnitId != DummyRecycler_DUMMY_UNIT_ID then
				if (unit_isType(targetU, UNIT_TYPE_STRUCTURE) and issuedOrderId == SpecialOrders_smart) or issuedOrderId == OrderIds_move then
					set clVar = alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem()
					set source_722[clVar] = source_1
					set orderAction = new_OrderAction_1075(0, 0, clVar, OrderSystem_POS_CHECK_RATE, unit_getFinishConditionNoMovement(source_1))
				endif
				call unit_setOrder_1224(source_1, issuedOrderId, targetU, orderAction)
			endif
		else
			set targetD = GetOrderTargetDestructable()
			if targetD != null then
				if issuedOrderId == SpecialOrders_smart or issuedOrderId == OrderIds_move then
					set clVar_1 = alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem_500()
					set source_723[clVar_1] = source_1
					set orderAction = new_OrderAction_1075(0, 0, clVar_1, OrderSystem_POS_CHECK_RATE, unit_getFinishConditionNoMovement(source_1))
				endif
				call unit_setOrder_1225(source_1, issuedOrderId, targetD, orderAction)
			else
				set targetI_1 = GetOrderTargetItem()
				if targetI_1 != null then
					if issuedOrderId == SpecialOrders_smart or issuedOrderId == OrderIds_move then
						set clVar_2 = alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem_501()
						set source_724[clVar_2] = source_1
						set temp = clVar_2
						set temp_1 = OrderSystem_POS_CHECK_RATE
						set clVar_3 = alloc_CallbackCondition_registerPlayerUnitEvent_OrderSystem()
						set source_725[clVar_3] = source_1
						set targetI[clVar_3] = targetI_1
						set orderAction = new_OrderAction_1075(0, 0, temp, temp_1, clVar_3)
					endif
					call unit_setOrder_1226(source_1, issuedOrderId, targetI_1, orderAction)
				endif
			endif
		endif
	endif
	set source_1 = null
	set targetU = null
	set targetD = null
	set targetI_1 = null
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem_502 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 659
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_OrderSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 659
	endif
	return this_1
endfunction

function alloc_OrderSource takes nothing returns integer
	local integer this_1
	if OrderSource_firstFree == 0 then
		if OrderSource_maxIndex < 32768 then
			set OrderSource_maxIndex = OrderSource_maxIndex + 1
			set this_1 = OrderSource_maxIndex
			set OrderSource_typeId[this_1] = 756
		else
			call error("Out of memory: Could not create OrderSource.")
			set this_1 = 0
		endif
	else
		set OrderSource_firstFree = OrderSource_firstFree - 1
		set this_1 = OrderSource_nextFree[OrderSource_firstFree]
		set OrderSource_typeId[this_1] = 756
	endif
	return this_1
endfunction

function new_OrderSource takes unit source_1, integer orderId, integer orderAction returns integer
	local integer this_1 = alloc_OrderSource()
	call construct_OrderSource(this_1, source_1, orderId, orderAction)
	return this_1
endfunction

function unit_setOrder_1223 takes unit this_1, integer orderId, integer orderAction returns nothing
	call unit_setOrder(this_1, new_OrderSource(this_1, orderId, orderAction))
endfunction

function code__registerPlayerUnitEvent_OrderSystem_609 takes nothing returns nothing
	local integer issuedOrderId = GetIssuedOrderId()
	local unit source_1 = GetOrderedUnit()
	local integer orderAction = 0
	local integer clVar
	if issuedOrderId == OrderIds_stop then
		set clVar = alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem_502()
		set source_726[clVar] = source_1
		set orderAction = new_OrderAction_1075(0, 0, clVar, UtilityFunctions_MIN_ACTION_SLEEP_TIME, 0)
	endif
	call unit_setOrder_1223(source_1, issuedOrderId, orderAction)
	set source_1 = null
endfunction

function alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem_503 takes nothing returns integer
	local integer this_1
	if CallbackSimple_firstFree == 0 then
		if CallbackSimple_maxIndex < 32768 then
			set CallbackSimple_maxIndex = CallbackSimple_maxIndex + 1
			set this_1 = CallbackSimple_maxIndex
			set CallbackSimple_typeId[this_1] = 660
		else
			call error("Out of memory: Could not create CallbackSimple_registerPlayerUnitEvent_OrderSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSimple_firstFree = CallbackSimple_firstFree - 1
		set this_1 = CallbackSimple_nextFree[CallbackSimple_firstFree]
		set CallbackSimple_typeId[this_1] = 660
	endif
	return this_1
endfunction

function alloc_OrderSourceV takes nothing returns integer
	local integer this_1
	if OrderSource_firstFree == 0 then
		if OrderSource_maxIndex < 32768 then
			set OrderSource_maxIndex = OrderSource_maxIndex + 1
			set this_1 = OrderSource_maxIndex
			set OrderSource_typeId[this_1] = 760
		else
			call error("Out of memory: Could not create OrderSourceV.")
			set this_1 = 0
		endif
	else
		set OrderSource_firstFree = OrderSource_firstFree - 1
		set this_1 = OrderSource_nextFree[OrderSource_firstFree]
		set OrderSource_typeId[this_1] = 760
	endif
	return this_1
endfunction

function OrderSourceV_init takes integer this_1 returns nothing
endfunction

function construct_OrderSourceV takes integer this_1, unit source_1, integer orderId, real target_x, real target_y, integer orderAction returns nothing
	call construct_OrderSource(this_1, source_1, orderId, orderAction)
	call OrderSourceV_init(this_1)
endfunction

function new_OrderSourceV takes unit source_1, integer orderId, real target_x, real target_y, integer orderAction returns integer
	local integer this_1 = alloc_OrderSourceV()
	call construct_OrderSourceV(this_1, source_1, orderId, target_x, target_y, orderAction)
	return this_1
endfunction

function unit_setOrder_1227 takes unit this_1, integer orderId, real target_x, real target_y, integer orderAction returns nothing
	call unit_setOrder(this_1, new_OrderSourceV(this_1, orderId, target_x, target_y, orderAction))
endfunction

function code__registerPlayerUnitEvent_OrderSystem_610 takes nothing returns nothing
	local integer issuedOrderId = GetIssuedOrderId()
	local unit source_1 = GetOrderedUnit()
	local real tuple_temp = GetOrderPointX()
	local real tuple_temp_1 = GetOrderPointY()
	local real targetPos_x = tuple_temp
	local real targetPos_y = tuple_temp_1
	local integer orderAction = 0
	local integer clVar
	if issuedOrderId == SpecialOrders_smart or issuedOrderId == OrderIds_move or issuedOrderId == OrderIds_attack then
		set clVar = alloc_CallbackSimple_registerPlayerUnitEvent_OrderSystem_503()
		set source_727[clVar] = source_1
		set orderAction = new_OrderAction_1075(0, 0, clVar, OrderSystem_POS_CHECK_RATE, unit_getFinishConditionNoMovement(source_1))
	endif
	call unit_setOrder_1227(source_1, issuedOrderId, targetPos_x, targetPos_y, orderAction)
	set source_1 = null
endfunction

function hashtable_loadTriggerHandle takes hashtable this_1, integer parentKey, integer childKey returns trigger
	return LoadTriggerHandle(this_1, parentKey, childKey)
endfunction

function Table_loadTrigger takes integer this_1, integer parentKey returns trigger
	return hashtable_loadTriggerHandle(Table_ht, this_1, parentKey)
endfunction

function dispatch_Table_Table_Table_loadTrigger takes integer this_1, integer parentKey returns trigger
	local trigger Table_Table_loadTrigger_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.loadTrigger")
		else
			call error("Called Table.loadTrigger on invalid object.")
		endif
	endif
	set Table_Table_loadTrigger_result = Table_loadTrigger(this_1, parentKey)
	set dispatch_Table_Table_Table_loadTriggertempReturn = Table_Table_loadTrigger_result
	set Table_Table_loadTrigger_result = null
	return dispatch_Table_Table_Table_loadTriggertempReturn
endfunction

function triggerFromIndex takes integer index returns trigger
	call dispatch_Table_Table_Table_saveFogState(TypeCasting_typecastdata, 0, ConvertFogState(index))
	return dispatch_Table_Table_Table_loadTrigger(TypeCasting_typecastdata, 0)
endfunction

function code__registerPlayerUnitEvent_RegisterEvents takes nothing returns boolean
	return trigger_evaluate(triggerFromIndex(dispatch_HashMap_HashMap_HashMap_get(RegisterEvents_onCastMap, GetSpellAbilityId())))
endfunction

function unit_searchForValidAbility takes unit this_1, unit target_1, integer abilityIds returns nothing
	local integer iterator = LinkedList_iterator(abilityIds)
	local integer abilityId
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set abilityId = LLIterator_next(iterator)
		if unit_isAbilityValid(this_1, abilityId, target_1) then
			call unit_issueTargetAbilityOrder(this_1, abilityId, target_1, true)
			call LLIterator_close(iterator)
			return
		endif
	endloop
	call LLIterator_close(iterator)
endfunction

function code__registerPlayerUnitEvent_SmartOrderSystem takes nothing returns nothing
	if GetIssuedOrderId() == SpecialOrders_smart then
		call unit_searchForValidAbility(GetTriggerUnit(), GetOrderTargetUnit(), SmartOrderSystem_SMART_USED_ABILITY_IDS)
	endif
endfunction

function code__registerPlayerUnitEvent_WorkshopSystem takes nothing returns nothing
	call unit_addWorkshop(GetTriggerUnit())
endfunction

function trigger_execute takes trigger this_1 returns nothing
	call TriggerExecute(this_1)
endfunction

function unit_getAbilityLevel takes unit this_1, integer id returns integer
	return GetUnitAbilityLevel(this_1, id)
endfunction

function code__registerPlayerUnitEvent_nullTimer_OnUnitEnterLeave takes nothing returns nothing
	local unit leavingUnit = GetTriggerUnit()
	if unit_getAbilityLevel(leavingUnit, OnUnitEnterLeave_ABILITY_ID) == 0 and GetIssuedOrderId() == OrderIds_undefend then
		call pushUnit(leavingUnit)
		call trigger_execute(OnUnitEnterLeave_eventTrigger)
		call popUnit()
	endif
	set leavingUnit = null
endfunction

function code__startPeriodic_Dataset_ObjectInfoSystem takes nothing returns nothing
	call showObjectInfo(timer_getData(GetExpiredTimer()))
endfunction

function code__startPeriodic_GameTimer takes nothing returns nothing
	set GameTimer_currentTime = GameTimer_currentTime + Basics_ANIMATION_PERIOD
endfunction

function call_OrderSystem takes integer this_1 returns boolean
	local real tuple_temp = unit_getPos(this[this_1])
	local real tuple_temp_1 = unit_getPos_return_y
	local real newPos_x = tuple_temp
	local real newPos_y = tuple_temp_1
	local boolean noMomvement = true
	local real tuple_temp_2
	local real tuple_temp_3
	if vec2_distanceToSq(newPos_x, newPos_y, w_lastPos_x[this_1], w_lastPos_y[this_1]) > OrderSystem_POS_TOLERANCE_RANGE then
		set tuple_temp_2 = newPos_x
		set tuple_temp_3 = newPos_y
		set w_lastPos_x[this_1] = tuple_temp_2
		set w_lastPos_y[this_1] = tuple_temp_3
		set noMomvement = false
	endif
	return noMomvement
endfunction

function item_getX takes item this_1 returns real
	return GetItemX(this_1)
endfunction

function item_getY takes item this_1 returns real
	return GetItemY(this_1)
endfunction

function item_getPos takes item this_1 returns real
	set item_getPos_return_x = item_getX(this_1)
	set item_getPos_return_y = item_getY(this_1)
	return item_getPos_return_x
endfunction

function vec2_inRange takes real this_x, real this_y, real v2_x, real v2_y, real radius returns boolean
	return real_squared(this_x - v2_x) + real_squared(this_y - v2_y) <= real_squared(radius)
endfunction

function call_registerPlayerUnitEvent_OrderSystem takes integer this_1 returns boolean
	return vec2_inRange(unit_getPos(source_725[this_1]), unit_getPos_return_y, item_getPos(targetI[this_1]), item_getPos_return_y, OrderSystem_POS_TOLERANCE_RANGE)
endfunction

function dispatch_CallbackCondition_OrderSystem_CallbackCondition_call takes integer this_1 returns boolean
	local boolean OrderSystem_CallbackCondition_call_result
	if CallbackCondition_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling CallbackCondition.call")
		else
			call error("Called CallbackCondition.call on invalid object.")
		endif
	endif
	if CallbackCondition_typeId[this_1] <= 643 then
		set OrderSystem_CallbackCondition_call_result = call_OrderSystem(this_1)
	else
		set OrderSystem_CallbackCondition_call_result = call_registerPlayerUnitEvent_OrderSystem(this_1)
	endif
	return OrderSystem_CallbackCondition_call_result
endfunction

function OrderAction_finish takes nothing returns nothing
	local timer t = GetExpiredTimer()
	local integer cb = timer_getData(t)
	if OrderAction_finishCondition[cb] == 0 or dispatch_CallbackCondition_OrderSystem_CallbackCondition_call(OrderAction_finishCondition[cb]) then
		set OrderAction_t[cb] = null
		call timer_release(t)
		if OrderAction_invalidateCb[cb] != 0 then
			call dispatch_CallbackSimple_destroyCallbackSimple(OrderAction_invalidateCb[cb])
			set OrderAction_invalidateCb[cb] = 0
		endif
		if OrderAction_cancelCb[cb] != 0 then
			call dispatch_CallbackSimple_destroyCallbackSimple(OrderAction_cancelCb[cb])
			set OrderAction_cancelCb[cb] = 0
		endif
		if OrderAction_finishCb[cb] != 0 then
			call cyc_unit_removeSourceOrder(5, null, OrderAction_finishCb[cb])
		endif
	endif
	set t = null
endfunction

function code__startPeriodic_OrderAction_OrderSystem takes nothing returns nothing
	call OrderAction_finish()
endfunction

function call_doAfter_BuildingSite_BuildingSystem takes integer this_1 returns nothing
	call SetUnitAnimation(worker[this_1], "work")
endfunction

function printLog takes integer loglvl, string msg returns nothing
	call printLog_1100(Player_localPlayer, loglvl, msg)
endfunction

function testFail takes string msg returns nothing
endfunction

function hashtable_hasString takes hashtable this_1, integer parentKey, integer childKey returns boolean
	return HaveSavedString(this_1, parentKey, childKey)
endfunction

function Table_hasString takes integer this_1, integer parentKey returns boolean
	return hashtable_hasString(Table_ht, this_1, parentKey)
endfunction

function dispatch_Table_Table_Table_hasString takes integer this_1, integer parentKey returns boolean
	local boolean Table_Table_hasString_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.hasString")
		else
			call error("Called Table.hasString on invalid object.")
		endif
	endif
	set Table_Table_hasString_result = Table_hasString(this_1, parentKey)
	return Table_Table_hasString_result
endfunction

function hashtable_loadString takes hashtable this_1, integer parentKey, integer childKey returns string
	return LoadStr(this_1, parentKey, childKey)
endfunction

function Table_loadString takes integer this_1, integer parentKey returns string
	return hashtable_loadString(Table_ht, this_1, parentKey)
endfunction

function dispatch_Table_Table_Table_loadString takes integer this_1, integer parentKey returns string
	local string Table_Table_loadString_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.loadString")
		else
			call error("Called Table.loadString on invalid object.")
		endif
	endif
	set Table_Table_loadString_result = Table_loadString(this_1, parentKey)
	return Table_Table_loadString_result
endfunction

function hashtable_saveString takes hashtable this_1, integer parentKey, integer childKey, string value returns nothing
	call SaveStr(this_1, parentKey, childKey, value)
endfunction

function Table_saveString takes integer this_1, integer parentKey, string value returns nothing
	call hashtable_saveString(Table_ht, this_1, parentKey, value)
endfunction

function dispatch_Table_Table_Table_saveString takes integer this_1, integer parentKey, string value returns nothing
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.saveString")
		else
			call error("Called Table.saveString on invalid object.")
		endif
	endif
	call Table_saveString(this_1, parentKey, value)
endfunction

function stringToIndex takes string s returns integer
	local integer hash = string_getHash(s)
	loop
		exitwhen  not true
		if dispatch_Table_Table_Table_hasString(TypeCasting_typecastdata, hash) then
			if dispatch_Table_Table_Table_loadString(TypeCasting_typecastdata, hash) == s then
				exitwhen true
			endif
		else
			call dispatch_Table_Table_Table_saveString(TypeCasting_typecastdata, hash, s)
			exitwhen true
		endif
		set hash = hash + 1
	endloop
	return hash
endfunction

function useTestName takes string testName_1 returns string
	local integer testNameCounter = 1
	if dispatch_HashMap_HashMap_HashMap_has(UnitTest_TEST_NAME_MAP, stringToIndex(testName_1)) then
		set testNameCounter = dispatch_HashMap_HashMap_HashMap_get(UnitTest_TEST_NAME_MAP, stringToIndex(testName_1)) + 1
	elseif UnitTest_SHOW_START_TEST_MESSAGE then
		call printLog(0, "[Start test for: " + testName_1 + "]")
	endif
	call dispatch_HashMap_HashMap_HashMap_put(UnitTest_TEST_NAME_MAP, stringToIndex(testName_1), testNameCounter)
	return testName_1 + " " + int_toString(testNameCounter)
endfunction

function testFail_1134 takes string testName_1, string msg returns nothing
	if testName_1 == UnitTest_TEST_NAME_WURSTUNIT then
		call testFail(msg)
	else
		call printLog(4, "[" + useTestName(testName_1) + "] " + msg)
	endif
endfunction

function assertEquals takes string testName_1, integer a, integer b returns nothing
	if a != b then
		call testFail_1134(testName_1, "Assertion failed: References were not equal.")
	endif
endfunction

function assertNotNull takes string testName_1, integer t returns nothing
	if t == 0 then
		call testFail_1134(testName_1, "Assertion failed: Reference was null.")
	endif
endfunction

function boolean_toString takes boolean this_1 returns string
	local string cond_result
	if this_1 then
		set cond_result = "true"
	else
		set cond_result = "false"
	endif
	return cond_result
endfunction

function bool_assertEquals takes boolean this_1, string testName_1, boolean expected returns nothing
	if this_1 != expected then
		call testFail_1134(testName_1, "Expected <" + boolean_toString(expected) + ">, Actual <" + boolean_toString(this_1) + ">")
	endif
endfunction

function bool_assertTrue takes boolean this_1, string testName_1 returns nothing
	call bool_assertEquals(this_1, testName_1, true)
endfunction

function HashMap_size_1 takes integer this_1 returns integer
	return HashMap_size[this_1]
endfunction

function IterableMap_size takes integer this_1 returns integer
	return dispatch_HashList_HashList_HashList_size(IterableMap_keys[this_1])
endfunction

function dispatch_HashMap_HashMap_HashMap_size takes integer this_1 returns integer
	local integer HashMap_HashMap_size_result
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashMap.size")
		else
			call error("Called HashMap.size on invalid object.")
		endif
	endif
	if Table_typeId[this_1] <= 821 then
		set HashMap_HashMap_size_result = HashMap_size_1(this_1)
	else
		set HashMap_HashMap_size_result = IterableMap_size(this_1)
	endif
	return HashMap_HashMap_size_result
endfunction

function UnitHashMap_getValueCount takes integer this_1 returns integer
	return dispatch_HashMap_HashMap_HashMap_size(UnitHashMap_map[this_1])
endfunction

function dispatch_UnitHashMap_UnitMap_UnitHashMap_getValueCount takes integer this_1 returns integer
	local integer UnitMap_UnitHashMap_getValueCount_result
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitHashMap.getValueCount")
		else
			call error("Called UnitHashMap.getValueCount on invalid object.")
		endif
	endif
	set UnitMap_UnitHashMap_getValueCount_result = UnitHashMap_getValueCount(this_1)
	return UnitMap_UnitHashMap_getValueCount_result
endfunction

function getBuildingSiteCount takes nothing returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_getValueCount(BuildingSystem_BUILDING_SITE_MAP)
endfunction

function getWorkerCount takes nothing returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_getValueCount(BuildingSystem_WORKER_MAP)
endfunction

function int_assertEquals_1032 takes integer this_1, string testName_1, integer expected returns nothing
	if this_1 != expected then
		call testFail_1134(testName_1, "Expected <" + int_toString(expected) + ">, Actual <" + int_toString(this_1) + ">")
	endif
endfunction

function real_assertEquals takes real this_1, string testName_1, real expected returns nothing
	if this_1 != expected then
		call testFail_1134(testName_1, "Expected <" + real_toString(expected) + ">, Actual <" + real_toString(this_1) + ">")
	endif
endfunction

function testSuccess takes nothing returns nothing
endfunction

function testSuccess_1138 takes string testName_1 returns nothing
	if testName_1 == UnitTest_TEST_NAME_WURSTUNIT then
		call testSuccess()
	else
		call printLog(2, "[" + useTestName(testName_1) + "] " + "Test successful")
	endif
endfunction

function call_doAfter_BuildingSystem takes integer this_1 returns nothing
	local integer a
	call int_assertEquals_1032(getWorkerCount() - workerCount[this_1], testName[this_1], 1)
	call int_assertEquals_1032(getBuildingSiteCount() - buildingSiteCount[this_1], testName[this_1], 1)
	call bool_assertTrue(dispatch_UnitHashMap_UnitMap_UnitHashMap_has(BuildingSystem_WORKER_MAP, unitA[this_1]), testName[this_1])
	set a = unit_getBuildingSiteOfWorker(unitA[this_1])
	call assertNotNull(testName[this_1], a)
	set BuildingSystem_testBuildingSystem_Build_building = Stock_user[a]
	call assertNotNull(testName[this_1], unitToIndex(BuildingSystem_testBuildingSystem_Build_building))
	call assertEquals(testName[this_1], unit_getBuildingSite(BuildingSystem_testBuildingSystem_Build_building), a)
	call assertEquals(testName[this_1], unitToIndex(unit_findNextBuildingSite(unitA[this_1])), unitToIndex(BuildingSystem_testBuildingSystem_Build_building))
	call real_assertEquals(dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkProgressPercentage(a), testName[this_1], 0.)
	call real_assertEquals(dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkPower(a), testName[this_1], 0.05)
	call int_assertEquals_1032(dispatch_BuildingSite_BuildingSystem_BuildingSite_getWorkerCount(a), testName[this_1], 1)
	call bool_assertTrue(dispatch_Stock_Stock_Stock_isEmpty(a), testName[this_1])
	call testSuccess_1138(testName[this_1])
endfunction

function unit_issueImmediateOrderById takes unit this_1, integer id returns boolean
	return IssueImmediateOrderById(this_1, id)
endfunction

function call_doAfter_BuildingSystem_556 takes integer this_1 returns nothing
	call unit_issueImmediateOrderById(BuildingSystem_testBuildingSystem_Build_building, SpecialOrders_cancel)
endfunction

function call_doAfter_BuildingSystem_557 takes integer this_1 returns nothing
	call unit_kill(unitA_738[this_1])
	call unit_remove(unitA_738[this_1])
endfunction

function call_doAfter_ClosureTimers takes integer this_1 returns nothing
	set ClosureTimers_x = ClosureTimers_x + 50
endfunction

function call_doAfter_ClosureTimers_559 takes integer this_1 returns nothing
	set ClosureTimers_x = ClosureTimers_x * 2
endfunction

function int_assertEquals takes integer this_1, integer expected returns nothing
	if this_1 != expected then
		call testFail("Expected <" + int_toString(expected) + ">, Actual <" + int_toString(this_1) + ">")
	endif
endfunction

function call_doAfter_ClosureTimers_560 takes integer this_1 returns nothing
	set ClosureTimers_x = ClosureTimers_x / 2
	call int_assertEquals(ClosureTimers_x, 250)
endfunction

function call_doAfter_registerPlayerUnitEvent_AbilitySystem takes integer this_1 returns boolean
	return unit_issueTargetAbilityOrder(source_716[this_1], AbilityIdsCustom_build, unit_findNextBuildingSite(source_716[this_1]), true)
endfunction

function Stock_containsAny takes integer this_1, integer targetStock returns boolean
	local integer iterator = LinkedList_iterator(Stock_wares[this_1])
	local integer iWare_wareType
	local integer tuple_temp
	loop
		exitwhen  not LLIterator_hasNext(iterator)
		set tuple_temp = wareFromIndex(LLIterator_next(iterator))
		set iWare_wareType = tuple_temp
		if dispatch_Stock_Stock_Stock_getWareCount(targetStock, iWare_wareType) > 0 then
			call LLIterator_close(iterator)
			return true
		endif
	endloop
	call LLIterator_close(iterator)
	return false
endfunction

function dispatch_Stock_Stock_Stock_containsAny takes integer this_1, integer targetStock returns boolean
	local boolean Stock_Stock_containsAny_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.containsAny")
		else
			call error("Called Stock.containsAny on invalid object.")
		endif
	endif
	set Stock_Stock_containsAny_result = Stock_containsAny(this_1, targetStock)
	return Stock_Stock_containsAny_result
endfunction

function BuildingSite_hasCarrierRequiredResources takes integer this_1, unit carrier returns boolean
	local integer carrierStorage
	if dispatch_Stock_Stock_Stock_isEmpty(this_1) == false then
		set carrierStorage = unit_getStorage(carrier)
		if carrierStorage != 0 and dispatch_Stock_Stock_Stock_containsAny(carrierStorage, this_1) then
			return true
		endif
	endif
	return false
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_hasCarrierRequiredResources takes integer this_1, unit carrier returns boolean
	local boolean BuildingSystem_BuildingSite_hasCarrierRequiredResources_result
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.hasCarrierRequiredResources")
		else
			call error("Called BuildingSite.hasCarrierRequiredResources on invalid object.")
		endif
	endif
	set BuildingSystem_BuildingSite_hasCarrierRequiredResources_result = BuildingSite_hasCarrierRequiredResources(this_1, carrier)
	return BuildingSystem_BuildingSite_hasCarrierRequiredResources_result
endfunction

function BuildingSite_callOverIdleWareCarriers takes integer this_1 returns nothing
	local player owner
	local unit carrier
	local group from
	call group_enumUnitsInRange(Group_ENUM_GROUP, unit_getPos(Stock_user[this_1]), unit_getPos_return_y, BuildingSystem_MAX_NEAR_BY_RANGE, null)
	set owner = unit_getOwner(Stock_user[this_1])
	set from = Group_ENUM_GROUP
	loop
		exitwhen  not group_hasNext(from)
		set carrier = group_next(from)
		if unit_getOwner(carrier) == owner and unit_getOrderSource(carrier) == 0 and dispatch_BuildingSite_BuildingSystem_BuildingSite_hasCarrierRequiredResources(this_1, carrier) then
			call unit_issueTargetAbilityOrder(carrier, AbilityIdsCustom_transferWares, Stock_user[this_1], true)
		endif
	endloop
	set owner = null
	set carrier = null
	set from = null
endfunction

function dispatch_BuildingSite_BuildingSystem_BuildingSite_callOverIdleWareCarriers takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling BuildingSite.callOverIdleWareCarriers")
		else
			call error("Called BuildingSite.callOverIdleWareCarriers on invalid object.")
		endif
	endif
	call BuildingSite_callOverIdleWareCarriers(this_1)
endfunction

function getBuildingScaling takes integer buildingUnitId returns real
	local integer temp = buildingUnitId
	if temp == Melee_altarOfKings then
		return UnitData_AltarOfKings_scalingValue
	elseif temp == Melee_arcaneSanctum then
		return UnitData_ArcaneSanctum_scalingValue
	elseif temp == Melee_arcaneTower then
		return UnitData_ArcaneTower_scalingValue
	elseif temp == Melee_arcaneVault then
		return UnitData_ArcaneVault_scalingValue
	elseif temp == Melee_barracks then
		return UnitData_Barracks_scalingValue
	elseif temp == Melee_blacksmith then
		return UnitData_Blacksmith_scalingValue
	elseif temp == Melee_cannonTower then
		return UnitData_CannonTower_scalingValue
	elseif temp == Melee_castle then
		return UnitData_Castle_scalingValue
	elseif temp == Melee_guardTower then
		return UnitData_GuardTower_scalingValue
	elseif temp == Melee_keep then
		return UnitData_Keep_scalingValue
	elseif temp == Melee_lumberMill then
		return UnitData_LumberMill_scalingValue
	elseif temp == Melee_scoutTower then
		return UnitData_ScoutTower_scalingValue
	elseif temp == Melee_townHall then
		return UnitData_Townhall_scalingValue
	else
		return 1.
	endif
endfunction

function getRequiredWares takes integer buildingUnitId returns integer
	local integer wares = new_LinkedList()
	local integer temp = buildingUnitId
	if temp == Melee_farm then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 4))
	elseif temp == Melee_townHall then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 4))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(1, 3))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(2, 2))
	elseif temp == Melee_blacksmith then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(1, 3))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(2, 2))
	elseif temp == Melee_lumberMill then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 4))
	elseif temp == Melee_arcaneVault then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(2, 2))
	elseif temp == Melee_scoutTower then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 4))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(1, 3))
	elseif temp == Melee_barracks then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 4))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(1, 3))
	elseif temp == Melee_altarOfKings then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(1, 3))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(2, 2))
	elseif temp == Melee_workshop then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 4))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(2, 2))
	elseif temp == Melee_arcaneSanctum then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 4))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(1, 3))
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(2, 2))
	elseif temp == Melee_gryphonAviary then
		call dispatch_LinkedList_LinkedList_LinkedList_add_1(wares, wareToIndex(0, 4))
	endif
	return wares
endfunction

function getRandomInputInt_2 takes integer inputs_0, integer inputs_1 returns integer
	local integer count = 0
	local integer i
	set count = count + 1
	set count = count + 1
	set i = GetRandomInt(1, count)
	set count = 0
	set count = count + 1
	if i == count then
		return inputs_0
	endif
	set count = count + 1
	if i == count then
		return inputs_1
	endif
	return 0
endfunction

function getRandomInputInt_3 takes integer inputs_0, integer inputs_1, integer inputs_2 returns integer
	local integer count = 0
	local integer i
	set count = count + 1
	set count = count + 1
	set count = count + 1
	set i = GetRandomInt(1, count)
	set count = 0
	set count = count + 1
	if i == count then
		return inputs_0
	endif
	set count = count + 1
	if i == count then
		return inputs_1
	endif
	set count = count + 1
	if i == count then
		return inputs_2
	endif
	return 0
endfunction

function getRandomInputInt_4 takes integer inputs_0, integer inputs_1, integer inputs_2, integer inputs_3 returns integer
	local integer count = 0
	local integer i
	set count = count + 1
	set count = count + 1
	set count = count + 1
	set count = count + 1
	set i = GetRandomInt(1, count)
	set count = 0
	set count = count + 1
	if i == count then
		return inputs_0
	endif
	set count = count + 1
	if i == count then
		return inputs_1
	endif
	set count = count + 1
	if i == count then
		return inputs_2
	endif
	set count = count + 1
	if i == count then
		return inputs_3
	endif
	return 0
endfunction

function int_getUnitTypeId takes integer this_1 returns integer
	local integer temp = this_1
	if temp == Trees_beech then
		return getRandomInputInt_4(Trees_beech_Var1, Trees_beech_Var2, Trees_beech_Var3, Trees_beech_Var4)
	elseif temp == Trees_birch then
		return getRandomInputInt_3(Trees_birch_Var1, Trees_birch_Var2, Trees_birch_Var3)
	elseif temp == Trees_greyOak then
		return getRandomInputInt_4(Trees_greyOak_Var1, Trees_greyOak_Var2, Trees_greyOak_Var3, Trees_greyOak_Var4)
	elseif temp == Trees_chestnut then
		return getRandomInputInt_2(Trees_chestnut_Var1, Trees_chestnut_Var2)
	endif
	return this_1
endfunction

function alloc_BuildingSite takes nothing returns integer
	local integer this_1
	if Stock_firstFree == 0 then
		if Stock_maxIndex < 32768 then
			set Stock_maxIndex = Stock_maxIndex + 1
			set this_1 = Stock_maxIndex
			set Stock_typeId[this_1] = 802
		else
			call error("Out of memory: Could not create BuildingSite.")
			set this_1 = 0
		endif
	else
		set Stock_firstFree = Stock_firstFree - 1
		set this_1 = Stock_nextFree[Stock_firstFree]
		set Stock_typeId[this_1] = 802
	endif
	return this_1
endfunction

function BuildingSite_init takes integer this_1 returns nothing
endfunction

function construct_BuildingSite takes integer this_1, unit building_1, real fullHP, integer requiredWares returns nothing
	call construct_Stock(this_1, requiredWares)
	call BuildingSite_init(this_1)
	set Stock_user[this_1] = building_1
	set BuildingSite_fullHP[this_1] = fullHP
	set BuildingSite_workerCount[this_1] = 0
	set BuildingSite_workProgressCurrent[this_1] = 0.
	set BuildingSite_workProgressFinished[this_1] = getRequiredWorkPower(unit_getUnitId(building_1))
	set BuildingSite_workPower[this_1] = 0.
	set BuildingSite_upgradeProgress[this_1] = 1
endfunction

function new_BuildingSite takes unit building_1, real fullHP, integer requiredWares returns integer
	local integer this_1 = alloc_BuildingSite()
	call construct_BuildingSite(this_1, building_1, fullHP, requiredWares)
	return this_1
endfunction

function unit_getMaxHP takes unit this_1 returns real
	return unit_getState(this_1, UNIT_STATE_MAX_LIFE)
endfunction

function createUnit takes player p, integer unitId, real pos_x, real pos_y, real facing_radians returns unit
	return CreateUnit(p, unitId, pos_x, pos_y, angle_degrees(facing_radians))
endfunction

function unit_getFacingAngle takes unit this_1 returns real
	set unit_getFacingAngle_return_radians = real_asAngleDegrees(GetUnitFacing(this_1))
	return unit_getFacingAngle_return_radians
endfunction

function unit_replace takes unit this_1, integer unitTypeId returns unit
	local unit newUnit
	call unit_hide(this_1)
	set newUnit = createUnit(unit_getOwner(this_1), unitTypeId, unit_getPos(this_1), unit_getPos_return_y, unit_getFacingAngle(this_1))
	call unit_kill(this_1)
	call unit_remove(this_1)
	set unit_replacetempReturn = newUnit
	set newUnit = null
	return unit_replacetempReturn
endfunction

function unit_addBuildingSite takes unit this_1 returns nothing
	local integer targetUnitId
	local real fullHP
	local unit buildingGround
	local integer buildingSite
	if dispatch_UnitHashMap_UnitMap_UnitHashMap_has(BuildingSystem_BUILDING_SITE_MAP, this_1) == false then
		set targetUnitId = unit_getUnitId(this_1)
		set fullHP = unit_getMaxHP(this_1)
		set buildingGround = unit_replace(this_1, BuildingSystem_BUILDING_GROUND_UNIT_ID)
		call IssueImmediateOrderById(buildingGround, int_getUnitTypeId(targetUnitId))
		call unit_setScale(buildingGround, getBuildingScaling(targetUnitId))
		call unit_setMaxHP(buildingGround, max_2(1, real_toInt(fullHP * BuildingSystem_BUILDING_START_HP_PERCENTAGE)))
		set buildingSite = new_BuildingSite(buildingGround, fullHP, getRequiredWares(targetUnitId))
		call dispatch_IterableUnitHashMap_UnitMap_IterableUnitHashMap_put(BuildingSystem_BUILDING_SITE_MAP, buildingGround, buildingSite)
		if dispatch_Stock_Stock_Stock_isEmpty(buildingSite) then
			call dispatch_BuildingSite_BuildingSystem_BuildingSite_callOverIdleWorkers(buildingSite, null)
		else
			call dispatch_BuildingSite_BuildingSystem_BuildingSite_callOverIdleWareCarriers(buildingSite)
		endif
	endif
	set buildingGround = null
endfunction

function call_doAfter_registerPlayerUnitEvent_BuildingSystem takes integer this_1 returns nothing
	call unit_addBuildingSite(building[this_1])
endfunction

function group_enumUnitsInRect_909 takes group this_1, rect rec, boolexpr filter returns nothing
	call GroupEnumUnitsInRect(this_1, rec, filter)
endfunction

function group_enumUnitsInRect takes group this_1, rect rec returns nothing
	call group_enumUnitsInRect_909(this_1, rec, null)
endfunction

function trigger_addAction takes trigger this_1, code actionFunc returns triggeraction
	return TriggerAddAction(this_1, actionFunc)
endfunction

function trigger_addCondition takes trigger this_1, boolexpr condition returns triggercondition
	return TriggerAddCondition(this_1, condition)
endfunction

function trigger_registerPlayerUnitEvent takes trigger this_1, player whichPlayer, playerunitevent whichPlayerUnitEvent, boolexpr filter returns event
	return TriggerRegisterPlayerUnitEvent(this_1, whichPlayer, whichPlayerUnitEvent, filter)
endfunction

function registerPlayerUnitEvent_1117 takes playerunitevent p, code filter, code condition, code action returns nothing
	local integer hid = handle_getHandleId(p)
	local integer k
	local filterfunc cond_result
	local trigger temp
	local player temp_1
	local playerunitevent temp_2
	if RegisterEvents_t[hid] == null then
		set RegisterEvents_t[hid] = CreateTrigger()
		set k = bj_MAX_PLAYER_SLOTS - 1
		loop
			exitwhen k < 0
			set temp = RegisterEvents_t[hid]
			set temp_1 = Player_players[k]
			set temp_2 = p
			if filter != null then
				set cond_result = Filter(filter)
			else
				set cond_result = null
			endif
			call trigger_registerPlayerUnitEvent(temp, temp_1, temp_2, cond_result)
			set k = k - 1
		endloop
	endif
	if condition != null then
		call trigger_addCondition(RegisterEvents_t[hid], Filter(condition))
	endif
	if action != null then
		call trigger_addAction(RegisterEvents_t[hid], action)
	endif
	set cond_result = null
	set temp = null
	set temp_1 = null
	set temp_2 = null
endfunction

function registerPlayerUnitEvent takes playerunitevent p, code c returns nothing
	call registerPlayerUnitEvent_1117(p, null, c, null)
endfunction

function trigger_registerEnterRegion takes trigger this_1, region whichRegion, boolexpr filter returns event
	return TriggerRegisterEnterRegion(this_1, whichRegion, filter)
endfunction

function call_nullTimer_OnUnitEnterLeave takes integer this_1 returns nothing
	local trigger receiver = CreateTrigger()
	local group receiver_1
	local group receiver_2
	call trigger_registerEnterRegion(receiver, MapBounds_boundRegion, Filter(ref_function_code__Filter_registerEnterRegion_nullTimer_OnUnitEnterLeave))
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_ISSUED_ORDER, ref_function_code__registerPlayerUnitEvent_nullTimer_OnUnitEnterLeave)
	call group_enumUnitsInRect(OnUnitEnterLeave_preplacedUnits, MapBounds_boundRect)
	call ForGroup(OnUnitEnterLeave_preplacedUnits, ref_function_code__ForGroup_nullTimer_OnUnitEnterLeave)
	set receiver_1 = OnUnitEnterLeave_preplacedUnits
	call group_clear(receiver_1)
	set receiver_2 = receiver_1
	call group_destr(receiver_2)
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
endfunction

function alloc_ForGroupCallback_forEachFrom_Preloader takes nothing returns integer
	local integer this_1
	if ForGroupCallback_firstFree == 0 then
		if ForGroupCallback_maxIndex < 32768 then
			set ForGroupCallback_maxIndex = ForGroupCallback_maxIndex + 1
			set this_1 = ForGroupCallback_maxIndex
			set ForGroupCallback_typeId[this_1] = 690
		else
			call error("Out of memory: Could not create ForGroupCallback_forEachFrom_Preloader.")
			set this_1 = 0
		endif
	else
		set ForGroupCallback_firstFree = ForGroupCallback_firstFree - 1
		set this_1 = ForGroupCallback_nextFree[ForGroupCallback_firstFree]
		set ForGroupCallback_typeId[this_1] = 690
	endif
	return this_1
endfunction

function dealloc_ForGroupCallback takes integer obj returns nothing
	if ForGroupCallback_typeId[obj] == 0 then
		call error("Double free: object of type ForGroupCallback")
	else
		set ForGroupCallback_nextFree[ForGroupCallback_firstFree] = obj
		set ForGroupCallback_firstFree = ForGroupCallback_firstFree + 1
		set ForGroupCallback_typeId[obj] = 0
	endif
endfunction

function destroyForGroupCallback takes integer this_1 returns nothing
	call dealloc_ForGroupCallback(this_1)
endfunction

function dispatch_ForGroupCallback_destroyForGroupCallback takes integer this_1 returns nothing
	if ForGroupCallback_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling ForGroupCallback.ForGroupCallback")
		else
			call error("Called ForGroupCallback.ForGroupCallback on invalid object.")
		endif
	endif
	call destroyForGroupCallback(this_1)
endfunction

function group_forEachFrom takes group this_1, integer cb returns nothing
	local group from = this_1
	local unit u_1
	loop
		exitwhen  not group_hasNext(from)
		set u_1 = group_next(from)
		call dispatch_ForGroupCallback_ClosureForGroups_ForGroupCallback_callback(cb, u_1)
	endloop
	call dispatch_ForGroupCallback_destroyForGroupCallback(cb)
	set u_1 = null
	set from = null
endfunction

function finishPreload takes nothing returns nothing
	local integer clVar
	local group temp
	call unit_remove(Preloader_dum)
	set temp = Preloader_dumg
	set clVar = alloc_ForGroupCallback_forEachFrom_Preloader()
	call group_forEachFrom(temp, clVar)
	call group_destr(Preloader_dumg)
	set Preloader_dumg = null
	set temp = null
endfunction

function call_nullTimer_Preloader takes integer this_1 returns nothing
	call finishPreload()
endfunction

function call_nullTimer_StartupSystem takes integer this_1 returns nothing
	local integer storage = unit_getStorage(u[this_1])
	if storage != 0 then
		call dispatch_Storage_StorageSystem_Storage_addWare(storage, 0, StartupSystem_START_WOOD_COUNT_PER_PEASANT)
	endif
endfunction

function dispatch_CallbackSingle_ClosureTimers_CallbackSingle_call takes integer this_1 returns nothing
	if CallbackSingle_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling CallbackSingle.call")
		else
			call error("Called CallbackSingle.call on invalid object.")
		endif
	endif
	if CallbackSingle_typeId[this_1] <= 670 then
		if CallbackSingle_typeId[this_1] <= 667 then
			if CallbackSingle_typeId[this_1] <= 666 then
				if CallbackSingle_typeId[this_1] <= 665 then
					call call_doAfter_BuildingSite_BuildingSystem(this_1)
				else
					call call_doAfter_BuildingSystem(this_1)
				endif
			else
				call call_doAfter_BuildingSystem_556(this_1)
			endif
		elseif CallbackSingle_typeId[this_1] <= 669 then
			if CallbackSingle_typeId[this_1] <= 668 then
				call call_doAfter_BuildingSystem_557(this_1)
			else
				call call_doAfter_ClosureTimers(this_1)
			endif
		else
			call call_doAfter_ClosureTimers_559(this_1)
		endif
	elseif CallbackSingle_typeId[this_1] <= 673 then
		if CallbackSingle_typeId[this_1] <= 672 then
			if CallbackSingle_typeId[this_1] <= 671 then
				call call_doAfter_ClosureTimers_560(this_1)
			else
				call call_doAfter_registerPlayerUnitEvent_AbilitySystem(this_1)
			endif
		else
			call call_doAfter_registerPlayerUnitEvent_BuildingSystem(this_1)
		endif
	elseif CallbackSingle_typeId[this_1] <= 675 then
		if CallbackSingle_typeId[this_1] <= 674 then
			call call_nullTimer_OnUnitEnterLeave(this_1)
		else
			call call_nullTimer_Preloader(this_1)
		endif
	else
		call call_nullTimer_StartupSystem(this_1)
	endif
endfunction

function CallbackSingle_onDestroy takes integer this_1 returns nothing
	call timer_release(CallbackSingle_t[this_1])
endfunction

function dealloc_CallbackSingle takes integer obj returns nothing
	if CallbackSingle_typeId[obj] == 0 then
		call error("Double free: object of type CallbackSingle")
	else
		set CallbackSingle_nextFree[CallbackSingle_firstFree] = obj
		set CallbackSingle_firstFree = CallbackSingle_firstFree + 1
		set CallbackSingle_typeId[obj] = 0
	endif
endfunction

function destroyCallbackSingle takes integer this_1 returns nothing
	call CallbackSingle_onDestroy(this_1)
	call dealloc_CallbackSingle(this_1)
endfunction

function dispatch_CallbackSingle_destroyCallbackSingle takes integer this_1 returns nothing
	if CallbackSingle_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling CallbackSingle.CallbackSingle")
		else
			call error("Called CallbackSingle.CallbackSingle on invalid object.")
		endif
	endif
	call destroyCallbackSingle(this_1)
endfunction

function CallbackSingle_staticCallback takes nothing returns nothing
	local timer t = GetExpiredTimer()
	local integer cb = timer_getData(t)
	call dispatch_CallbackSingle_ClosureTimers_CallbackSingle_call(cb)
	call dispatch_CallbackSingle_destroyCallbackSingle(cb)
	set t = null
endfunction

function code__start_CallbackSingle_ClosureTimers takes nothing returns nothing
	call CallbackSingle_staticCallback()
endfunction

function code__start_OrderAction_OrderSystem takes nothing returns nothing
	call OrderAction_finish()
endfunction

function group_enumUnitsSelected takes group this_1, player p, boolexpr filter returns nothing
	call GroupEnumUnitsSelected(this_1, p, filter)
endfunction

function executeCommand takes nothing returns nothing
	local unit u_1
	local group from
	local integer storage
	call group_enumUnitsSelected(Group_ENUM_GROUP, Command_GiveWares_USER_PLAYER, null)
	set from = Group_ENUM_GROUP
	loop
		exitwhen  not group_hasNext(from)
		set u_1 = group_next(from)
		set storage = unit_getStorage(u_1)
		if storage != 0 then
			call dispatch_Storage_StorageSystem_Storage_addWare(storage, 0, 4)
			call dispatch_Storage_StorageSystem_Storage_addWare(storage, 1, 3)
			call dispatch_Storage_StorageSystem_Storage_addWare(storage, 2, 2)
		endif
	endloop
	set u_1 = null
	set from = null
endfunction

function executeCommand_863 takes nothing returns nothing
	set bj_lastCreatedFogModifier = CreateFogModifierRect(Command_ShowAll_USER_PLAYER, FOG_OF_WAR_VISIBLE, bj_mapInitialPlayableArea, true, false)
	call FogModifierStart(bj_lastCreatedFogModifier)
endfunction

function getOrderSourceCount takes nothing returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_getValueCount(OrderSystem_ORDER_SOURCE_MAP)
endfunction

function getOrderTargetCount takes nothing returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_getValueCount(OrderSystem_ORDER_TARGET_MAP)
endfunction

function getResourceCount takes nothing returns integer
	return dispatch_UnitHashMap_UnitMap_UnitHashMap_getValueCount(ResourceSystem_RESOURCE_MAP)
endfunction

function executeCommand_864 takes nothing returns nothing
	local integer testCounter = 1
	call print("-------- Test " + int_toString(testCounter) + ":")
	call print("Current resources: " + int_toString(getResourceCount()))
	call print("Current order sources: " + int_toString(getOrderSourceCount()))
	call print("Current order targets: " + int_toString(getOrderTargetCount()))
	call print("Current building sites: " + int_toString(getBuildingSiteCount()))
	call print("Current workers: " + int_toString(getWorkerCount()))
endfunction

function alloc_CallbackSingle_doAfter_BuildingSystem takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 666
		else
			call error("Out of memory: Could not create CallbackSingle_doAfter_BuildingSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 666
	endif
	return this_1
endfunction

function alloc_CallbackSingle_doAfter_BuildingSystem_509 takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 667
		else
			call error("Out of memory: Could not create CallbackSingle_doAfter_BuildingSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 667
	endif
	return this_1
endfunction

function alloc_CallbackSingle_doAfter_BuildingSystem_510 takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 668
		else
			call error("Out of memory: Could not create CallbackSingle_doAfter_BuildingSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 668
	endif
	return this_1
endfunction

function setTestName takes string testName_1, boolean isInGameTest returns string
	if isInGameTest then
		return testName_1
	else
		return UnitTest_TEST_NAME_WURSTUNIT
	endif
endfunction

function unit_issuePointOrderById takes unit this_1, integer id, real target_x, real target_y returns boolean
	return IssuePointOrderById(this_1, id, target_x, target_y)
endfunction

function testBuildingSystem_Build takes nothing returns nothing
	local string testName_1 = setTestName("testBuildingSystem_Build", true)
	local unit unitA_1
	local integer storageA
	local integer workerCount_1
	local integer buildingSiteCount_1
	local integer clVar
	local integer clVar_1
	local integer clVar_2
	local real temp
	local real temp_1
	local real temp_2
	call ForGroup(GetUnitsInRectAll(Rect( - 128.,  - 128., 128., 128.)), ref_function_code__ForGroup_BuildingSystem)
	set unitA_1 = createUnit(Player(0), Melee_peasant, 0., 0., 0.)
	set storageA = unit_getStorage(unitA_1)
	call assertNotNull(testName_1, storageA)
	call dispatch_Storage_StorageSystem_Storage_addWare(storageA, 0, 5)
	set workerCount_1 = getWorkerCount()
	set buildingSiteCount_1 = getBuildingSiteCount()
	call unit_issuePointOrderById(unitA_1, Melee_farm, 0., 0.)
	set BuildingSystem_testBuildingSystem_Build_building = null
	set temp = UtilityFunctions_MIN_ACTION_SLEEP_TIME
	set clVar = alloc_CallbackSingle_doAfter_BuildingSystem()
	call construct_CallbackSingle(clVar)
	set workerCount[clVar] = workerCount_1
	set testName[clVar] = testName_1
	set buildingSiteCount[clVar] = buildingSiteCount_1
	set unitA[clVar] = unitA_1
	call doAfter(temp, clVar)
	set temp_1 = 2. * UtilityFunctions_MIN_ACTION_SLEEP_TIME
	set clVar_1 = alloc_CallbackSingle_doAfter_BuildingSystem_509()
	call construct_CallbackSingle(clVar_1)
	call doAfter(temp_1, clVar_1)
	set temp_2 = 3. * UtilityFunctions_MIN_ACTION_SLEEP_TIME
	set clVar_2 = alloc_CallbackSingle_doAfter_BuildingSystem_510()
	call construct_CallbackSingle(clVar_2)
	set unitA_738[clVar_2] = unitA_1
	call doAfter(temp_2, clVar_2)
	set unitA_1 = null
endfunction

function bool_assertFalse takes boolean this_1, string testName_1 returns nothing
	call bool_assertEquals(this_1, testName_1, false)
endfunction

function dealloc_Stock takes integer obj returns nothing
	if Stock_typeId[obj] == 0 then
		call error("Double free: object of type Stock")
	else
		set Stock_nextFree[Stock_firstFree] = obj
		set Stock_firstFree = Stock_firstFree + 1
		set Stock_typeId[obj] = 0
	endif
endfunction

function destroyStock takes integer this_1 returns nothing
	call Stock_onDestroy(this_1)
	call dealloc_Stock(this_1)
endfunction

function dispatch_Stock_destroyStock takes integer this_1 returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Stock.Stock")
		else
			call error("Called Stock.Stock on invalid object.")
		endif
	endif
	if Stock_typeId[this_1] <= 804 then
		call destroyStock(this_1)
	else
		call destroyWorkshop(this_1)
	endif
endfunction

function alloc_Stock takes nothing returns integer
	local integer this_1
	if Stock_firstFree == 0 then
		if Stock_maxIndex < 32768 then
			set Stock_maxIndex = Stock_maxIndex + 1
			set this_1 = Stock_maxIndex
			set Stock_typeId[this_1] = 801
		else
			call error("Out of memory: Could not create Stock.")
			set this_1 = 0
		endif
	else
		set Stock_firstFree = Stock_firstFree - 1
		set this_1 = Stock_nextFree[Stock_firstFree]
		set Stock_typeId[this_1] = 801
	endif
	return this_1
endfunction

function new_Stock takes integer wares returns integer
	local integer this_1 = alloc_Stock()
	call construct_Stock(this_1, wares)
	return this_1
endfunction

function testStockSystem_AddAndRemove takes boolean isInGameTest returns nothing
	local string testName_1 = setTestName("testStockSystem_AddAndRemove", isInGameTest)
	local integer a = new_Stock(new_LinkedList())
	local integer temp_tuple_wareType
	local integer temp_tuple_wareType_1
	local integer temp_tuple_wareType_2
	local integer b
	local integer waresA
	local integer waresB
	local integer tuple_temp
	local integer tuple_temp_1
	local integer tuple_temp_2
	call bool_assertTrue(dispatch_Stock_Stock_Stock_isEmpty(a), testName_1)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getAmountOfWareTypes(a), testName_1, 0)
	call dispatch_Stock_Stock_Stock_addWare(a, 3, 2)
	call dispatch_Stock_Stock_Stock_addWare(a, 1, 2)
	call dispatch_Stock_Stock_Stock_addWare(a, 8, 1)
	call dispatch_Stock_Stock_Stock_addWare(a, 3, 1)
	call bool_assertFalse(dispatch_Stock_Stock_Stock_isEmpty(a), testName_1)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getAmountOfWareTypes(a), testName_1, 3)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getWareCount(a, 3), testName_1, 3)
	set tuple_temp = dispatch_Stock_Stock_Stock_getLastWare(a)
	set temp_tuple_wareType = tuple_temp
	call bool_assertTrue(temp_tuple_wareType == 8, testName_1)
	set tuple_temp_1 = dispatch_Stock_Stock_Stock_getWare(a, 0)
	set temp_tuple_wareType_1 = tuple_temp_1
	call bool_assertTrue(temp_tuple_wareType_1 == 3, testName_1)
	set tuple_temp_2 = dispatch_Stock_Stock_Stock_getWare(a, 1)
	set temp_tuple_wareType_2 = tuple_temp_2
	call bool_assertTrue(temp_tuple_wareType_2 == 1, testName_1)
	call bool_assertFalse(dispatch_Stock_Stock_Stock_hasWare(a, 1, 3), testName_1)
	call bool_assertTrue(dispatch_Stock_Stock_Stock_hasWare(a, 1, 2), testName_1)
	call dispatch_Stock_Stock_Stock_removeWare(a, 3, 2)
	call dispatch_Stock_Stock_Stock_removeWare(a, 1, 2)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getAmountOfWareTypes(a), testName_1, 2)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getWareCount(a, 3), testName_1, 1)
	set b = new_Stock(new_LinkedList())
	call bool_assertTrue(dispatch_Stock_Stock_Stock_isEmpty(b), testName_1)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getAmountOfWareTypes(b), testName_1, 0)
	set waresA = new_LinkedList()
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresA, wareToIndex(3, 2))
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresA, wareToIndex(1, 3))
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresA, wareToIndex(8, 1))
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresA, wareToIndex(0, 6))
	call bool_assertFalse(dispatch_Stock_Stock_Stock_hasWaresAny(b, waresA), testName_1)
	call bool_assertFalse(dispatch_Stock_Stock_Stock_containsAny(b, a), testName_1)
	call dispatch_Stock_Stock_Stock_addWares(b, waresA)
	call bool_assertFalse(dispatch_Stock_Stock_Stock_isEmpty(b), testName_1)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getAmountOfWareTypes(b), testName_1, 4)
	call bool_assertTrue(dispatch_Stock_Stock_Stock_hasWares(b, waresA), testName_1)
	call bool_assertTrue(dispatch_Stock_Stock_Stock_containsAny(b, a), testName_1)
	set waresB = new_LinkedList()
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresB, wareToIndex(3, 3))
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresB, wareToIndex(0, 1))
	call dispatch_Stock_Stock_Stock_removeWares(b, waresB)
	call bool_assertFalse(dispatch_Stock_Stock_Stock_isEmpty(b), testName_1)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getAmountOfWareTypes(b), testName_1, 3)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getWareCount(b, 3), testName_1, 0)
	call int_assertEquals_1032(dispatch_Stock_Stock_Stock_getWareCount(b, 0), testName_1, 5)
	call bool_assertFalse(dispatch_Stock_Stock_Stock_hasWares(b, waresB), testName_1)
	call bool_assertTrue(dispatch_Stock_Stock_Stock_hasWaresAny(b, waresB), testName_1)
	call testSuccess_1138(testName_1)
	call dispatch_Stock_destroyStock(a)
	call dispatch_Stock_destroyStock(b)
	call dispatch_LinkedList_destroyLinkedList(waresA)
	call dispatch_LinkedList_destroyLinkedList(waresB)
endfunction

function dispatch_Storage_StorageSystem_Storage_addWares takes integer this_1, integer wares returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.addWares")
		else
			call error("Called Storage.addWares on invalid object.")
		endif
	endif
	call Storage_addWares(this_1, wares)
endfunction

function dispatch_Storage_StorageSystem_Storage_removeWares takes integer this_1, integer wares returns nothing
	if Stock_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Storage.removeWares")
		else
			call error("Called Storage.removeWares on invalid object.")
		endif
	endif
	call Storage_removeWares(this_1, wares)
endfunction

function testStorageSystem_AddAndRemove takes boolean isInGameTest returns nothing
	local string testName_1 = setTestName("testStorageSystem_AddAndRemove", isInGameTest)
	local unit unitA_1 = createUnit(Basics_DUMMY_PLAYER, Melee_peasant, 0., 0., 0.)
	local integer a = new_Storage(unitA_1, 8)
	local unit unitB
	local integer b
	local integer waresA
	local integer waresB
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(a), testName_1, 8)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(a), testName_1, 0)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getFreeCapacity(a), testName_1, 8)
	call dispatch_Storage_StorageSystem_Storage_addWare(a, 3, 3)
	call dispatch_Storage_StorageSystem_Storage_addWare(a, 1, 2)
	call dispatch_Storage_StorageSystem_Storage_addWare(a, 3, 1)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(a), testName_1, 8)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(a), testName_1, 6)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getFreeCapacity(a), testName_1, 2)
	call dispatch_Storage_StorageSystem_Storage_removeWare(a, 3, 2)
	call dispatch_Storage_StorageSystem_Storage_removeWare(a, 1, 2)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(a), testName_1, 8)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(a), testName_1, 2)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getFreeCapacity(a), testName_1, 6)
	set unitB = createUnit(Basics_DUMMY_PLAYER, Melee_peasant, 0., 0., 0.)
	set b = new_Storage(unitA_1, 13)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(b), testName_1, 13)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(b), testName_1, 0)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getFreeCapacity(b), testName_1, 13)
	set waresA = new_LinkedList()
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresA, wareToIndex(3, 2))
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresA, wareToIndex(1, 3))
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresA, wareToIndex(3, 1))
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresA, wareToIndex(0, 6))
	call dispatch_Storage_StorageSystem_Storage_addWares(b, waresA)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(b), testName_1, 13)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(b), testName_1, 12)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getFreeCapacity(b), testName_1, 1)
	set waresB = new_LinkedList()
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresB, wareToIndex(3, 3))
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(waresB, wareToIndex(0, 1))
	call dispatch_Storage_StorageSystem_Storage_removeWares(b, waresB)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(b), testName_1, 13)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(b), testName_1, 8)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getFreeCapacity(b), testName_1, 5)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_transferWares(b, a), testName_1, 2)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(a), testName_1, 8)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(a), testName_1, 8)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getFreeCapacity(a), testName_1, 0)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getMaxCapacity(b), testName_1, 13)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getUsedCapacity(b), testName_1, 2)
	call int_assertEquals_1032(dispatch_Storage_StorageSystem_Storage_getFreeCapacity(b), testName_1, 11)
	call testSuccess_1138(testName_1)
	if isInGameTest then
		call unit_remove(unitA_1)
		call unit_remove(unitB)
	endif
	call dispatch_Storage_destroyStorage(a)
	call dispatch_Storage_destroyStorage(b)
	call dispatch_LinkedList_destroyLinkedList(waresA)
	call dispatch_LinkedList_destroyLinkedList(waresB)
	set unitA_1 = null
	set unitB = null
endfunction

function hashtable_flushChild takes hashtable this_1, integer parentKey returns nothing
	call FlushChildHashtable(this_1, parentKey)
endfunction

function Table_flush takes integer this_1 returns nothing
	call hashtable_flushChild(Table_ht, this_1)
endfunction

function HashMap_flush takes integer this_1 returns nothing
	set HashMap_size[this_1] = 0
	call Table_flush(this_1)
endfunction

function HashList_clear takes integer this_1 returns nothing
	call hashtable_flushChild(HashList_ht, this_1)
	call hashtable_flushChild(HashList_occurences, this_1)
	set HashList_size[this_1] = 0
endfunction

function dispatch_HashList_HashList_HashList_clear takes integer this_1 returns nothing
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.clear")
		else
			call error("Called HashList.clear on invalid object.")
		endif
	endif
	call HashList_clear(this_1)
endfunction

function IterableMap_flush takes integer this_1 returns nothing
	if  not IterableMap__destroyed[this_1] then
		call dispatch_HashList_HashList_HashList_clear(IterableMap_keys[this_1])
	endif
	call HashMap_flush(this_1)
endfunction

function dispatch_Table_Table_Table_flush takes integer this_1 returns nothing
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling Table.flush")
		else
			call error("Called Table.flush on invalid object.")
		endif
	endif
	if Table_typeId[this_1] <= 821 then
		if Table_typeId[this_1] <= 820 then
			call Table_flush(this_1)
		else
			call HashMap_flush(this_1)
		endif
	else
		call IterableMap_flush(this_1)
	endif
endfunction

function Table_onDestroy takes integer this_1 returns nothing
	call dispatch_Table_Table_Table_flush(this_1)
endfunction

function HashMap_onDestroy takes integer this_1 returns nothing
	call Table_onDestroy(this_1)
endfunction

function dealloc_HashMap takes integer obj returns nothing
	if Table_typeId[obj] == 0 then
		call error("Double free: object of type HashMap")
	else
		set Table_nextFree[Table_firstFree] = obj
		set Table_firstFree = Table_firstFree + 1
		set Table_typeId[obj] = 0
	endif
endfunction

function destroyHashMap takes integer this_1 returns nothing
	call HashMap_onDestroy(this_1)
	call dealloc_HashMap(this_1)
endfunction

function HashList_onDestroy takes integer this_1 returns nothing
	call dispatch_HashList_HashList_HashList_clear(this_1)
endfunction

function dealloc_HashList takes integer obj returns nothing
	if HashList_typeId[obj] == 0 then
		call error("Double free: object of type HashList")
	else
		set HashList_nextFree[HashList_firstFree] = obj
		set HashList_firstFree = HashList_firstFree + 1
		set HashList_typeId[obj] = 0
	endif
endfunction

function destroyHashList takes integer this_1 returns nothing
	call HashList_onDestroy(this_1)
	call dealloc_HashList(this_1)
endfunction

function dispatch_HashList_destroyHashList takes integer this_1 returns nothing
	if HashList_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashList.HashList")
		else
			call error("Called HashList.HashList on invalid object.")
		endif
	endif
	call destroyHashList(this_1)
endfunction

function IterableMap_onDestroy takes integer this_1 returns nothing
	call dispatch_HashList_destroyHashList(IterableMap_keys[this_1])
	set IterableMap__destroyed[this_1] = true
	call HashMap_onDestroy(this_1)
endfunction

function dealloc_IterableMap takes integer obj returns nothing
	if Table_typeId[obj] == 0 then
		call error("Double free: object of type IterableMap")
	else
		set Table_nextFree[Table_firstFree] = obj
		set Table_firstFree = Table_firstFree + 1
		set Table_typeId[obj] = 0
	endif
endfunction

function destroyIterableMap takes integer this_1 returns nothing
	call IterableMap_onDestroy(this_1)
	call dealloc_IterableMap(this_1)
endfunction

function dispatch_HashMap_destroyHashMap takes integer this_1 returns nothing
	if Table_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling HashMap.HashMap")
		else
			call error("Called HashMap.HashMap on invalid object.")
		endif
	endif
	if Table_typeId[this_1] <= 821 then
		call destroyHashMap(this_1)
	else
		call destroyIterableMap(this_1)
	endif
endfunction

function UnitHashMap_onDestroy takes integer this_1 returns nothing
	call dispatch_HashMap_destroyHashMap(UnitHashMap_map[this_1])
endfunction

function IterableUnitHashMap_onDestroy takes integer this_1 returns nothing
	call dispatch_HashList_destroyHashList(IterableUnitHashMap_keys[this_1])
	call UnitHashMap_onDestroy(this_1)
endfunction

function dealloc_IterableUnitHashMap takes integer obj returns nothing
	if UnitMap_typeId[obj] == 0 then
		call error("Double free: object of type IterableUnitHashMap")
	else
		set UnitMap_nextFree[UnitMap_firstFree] = obj
		set UnitMap_firstFree = UnitMap_firstFree + 1
		set UnitMap_typeId[obj] = 0
	endif
endfunction

function destroyIterableUnitHashMap takes integer this_1 returns nothing
	call IterableUnitHashMap_onDestroy(this_1)
	call dealloc_IterableUnitHashMap(this_1)
endfunction

function dealloc_UnitHashMap takes integer obj returns nothing
	if UnitMap_typeId[obj] == 0 then
		call error("Double free: object of type UnitHashMap")
	else
		set UnitMap_nextFree[UnitMap_firstFree] = obj
		set UnitMap_firstFree = UnitMap_firstFree + 1
		set UnitMap_typeId[obj] = 0
	endif
endfunction

function destroyUnitHashMap takes integer this_1 returns nothing
	call UnitHashMap_onDestroy(this_1)
	call dealloc_UnitHashMap(this_1)
endfunction

function dispatch_UnitHashMap_destroyUnitHashMap takes integer this_1 returns nothing
	if UnitMap_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling UnitHashMap.UnitHashMap")
		else
			call error("Called UnitHashMap.UnitHashMap on invalid object.")
		endif
	endif
	if UnitMap_typeId[this_1] <= 849 then
		call destroyUnitHashMap(this_1)
	else
		call destroyIterableUnitHashMap(this_1)
	endif
endfunction

function alloc_UnitHashMap takes nothing returns integer
	local integer this_1
	if UnitMap_firstFree == 0 then
		if UnitMap_maxIndex < 32768 then
			set UnitMap_maxIndex = UnitMap_maxIndex + 1
			set this_1 = UnitMap_maxIndex
			set UnitMap_typeId[this_1] = 849
		else
			call error("Out of memory: Could not create UnitHashMap.")
			set this_1 = 0
		endif
	else
		set UnitMap_firstFree = UnitMap_firstFree - 1
		set this_1 = UnitMap_nextFree[UnitMap_firstFree]
		set UnitMap_typeId[this_1] = 849
	endif
	return this_1
endfunction

function alloc_HashMap takes nothing returns integer
	local integer this_1
	if Table_firstFree == 0 then
		if Table_maxIndex < 32768 then
			set Table_maxIndex = Table_maxIndex + 1
			set this_1 = Table_maxIndex
			set Table_typeId[this_1] = 821
		else
			call error("Out of memory: Could not create HashMap.")
			set this_1 = 0
		endif
	else
		set Table_firstFree = Table_firstFree - 1
		set this_1 = Table_nextFree[Table_firstFree]
		set Table_typeId[this_1] = 821
	endif
	return this_1
endfunction

function HashMap_init takes integer this_1 returns nothing
	set HashMap_size[this_1] = 0
endfunction

function Table_init takes integer this_1 returns nothing
endfunction

function construct_Table takes integer this_1 returns nothing
	call Table_init(this_1)
endfunction

function construct_HashMap takes integer this_1 returns nothing
	call construct_Table(this_1)
	call HashMap_init(this_1)
endfunction

function new_HashMap takes nothing returns integer
	local integer this_1 = alloc_HashMap()
	call construct_HashMap(this_1)
	return this_1
endfunction

function UnitHashMap_init takes integer this_1 returns nothing
	set UnitHashMap_map[this_1] = new_HashMap()
endfunction

function construct_UnitHashMap takes integer this_1, integer nullElem returns nothing
	call UnitHashMap_init(this_1)
	set UnitHashMap_nullElem[this_1] = nullElem
endfunction

function new_UnitHashMap takes integer nullElem returns integer
	local integer this_1 = alloc_UnitHashMap()
	call construct_UnitHashMap(this_1, nullElem)
	return this_1
endfunction

function stringFromIndex takes integer index returns string
	local string str = dispatch_Table_Table_Table_loadString(TypeCasting_typecastdata, index)
	return str
endfunction

function string_assertEquals takes string this_1, string testName_1, string expected returns nothing
	if this_1 != expected then
		call testFail_1134(testName_1, "Expected <" + expected + ">, Actual <" + this_1 + ">")
	endif
endfunction

function testUnitHashMap_AddAndRemove takes boolean isInGameTest returns nothing
	local string testName_1 = setTestName("testUnitHashMap_AddAndRemove", isInGameTest)
	local integer a = new_UnitHashMap(stringToIndex(null))
	local unit unitA_1 = createUnit(Basics_DUMMY_PLAYER, Melee_peasant, 0., 0., 0.)
	local unit unitB
	local unit unitC
	local integer b
	local unit unitD
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(a, unitA_1, stringToIndex("unitA"))
	call string_assertEquals(stringFromIndex(dispatch_UnitHashMap_UnitMap_UnitHashMap_get(a, unitA_1)), testName_1, "unitA")
	call bool_assertTrue(dispatch_UnitHashMap_UnitMap_UnitHashMap_has(a, unitA_1), testName_1)
	set unitB = createUnit(Basics_DUMMY_PLAYER, Melee_peasant, 0., 0., 0.)
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(a, unitB, stringToIndex("unitB"))
	call string_assertEquals(stringFromIndex(dispatch_UnitHashMap_UnitMap_UnitHashMap_get(a, unitB)), testName_1, "unitB")
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_remove(a, unitA_1)
	call bool_assertFalse(dispatch_UnitHashMap_UnitMap_UnitHashMap_has(a, unitA_1), testName_1)
	call string_assertEquals(stringFromIndex(dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(a, unitA_1)), testName_1, stringFromIndex(UnitHashMap_nullElem[a]))
	call string_assertEquals(stringFromIndex(dispatch_UnitHashMap_UnitMap_UnitHashMap_tryRemove(a, unitA_1)), testName_1, stringFromIndex(UnitHashMap_nullElem[a]))
	call string_assertEquals(stringFromIndex(dispatch_UnitHashMap_UnitMap_UnitHashMap_get(a, unitB)), testName_1, "unitB")
	call string_assertEquals(stringFromIndex(dispatch_UnitHashMap_UnitMap_UnitHashMap_tryGet(a, unitB)), testName_1, "unitB")
	set unitC = createUnit(Basics_DUMMY_PLAYER, Melee_peasant, 0., 0., 0.)
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(a, unitC, stringToIndex("unitC"))
	call string_assertEquals(stringFromIndex(dispatch_UnitHashMap_UnitMap_UnitHashMap_tryRemove(a, unitC)), testName_1, "unitC")
	set b = new_UnitHashMap(0)
	call bool_assertFalse(dispatch_UnitHashMap_UnitMap_UnitHashMap_has(b, unitB), testName_1)
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(b, unitA_1, 1)
	call int_assertEquals_1032(dispatch_UnitHashMap_UnitMap_UnitHashMap_get(b, unitA_1), testName_1, 1)
	call bool_assertFalse(dispatch_UnitHashMap_UnitMap_UnitHashMap_has(a, unitA_1), testName_1)
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(b, unitB, 2)
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_put(b, unitC, 3)
	call int_assertEquals_1032(dispatch_UnitHashMap_UnitMap_UnitHashMap_get(b, unitC), testName_1, 3)
	call dispatch_UnitHashMap_UnitMap_UnitHashMap_remove(b, unitB)
	set unitD = createUnit(Basics_DUMMY_PLAYER, Melee_peasant, 0., 0., 0.)
	call testSuccess_1138(testName_1)
	if isInGameTest then
		call unit_remove(unitA_1)
		call unit_remove(unitB)
		call unit_remove(unitC)
		call unit_remove(unitD)
	endif
	call dispatch_UnitHashMap_destroyUnitHashMap(a)
	call dispatch_UnitHashMap_destroyUnitHashMap(b)
	set unitA_1 = null
	set unitB = null
	set unitC = null
	set unitD = null
endfunction

function executeCommand_865 takes nothing returns nothing
	call testUnitHashMap_AddAndRemove(true)
	call testStockSystem_AddAndRemove(true)
	call testStorageSystem_AddAndRemove(true)
	call testBuildingSystem_Build()
endfunction

function init_Abilities takes nothing returns boolean
	return true
endfunction

function init_AbilityIds takes nothing returns boolean
	return true
endfunction

function init_AbilityObjEditing takes nothing returns boolean
	return true
endfunction

function init_AbilitySystem takes nothing returns boolean
	set AbilitySystem_INFO_MSG_TIME = 2.
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_SPELL_CAST, ref_function_code__registerPlayerUnitEvent_AbilitySystem)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_ISSUED_TARGET_ORDER, ref_function_code__registerPlayerUnitEvent_AbilitySystem_598)
	return true
endfunction

function init_Ability_Harvest takes nothing returns boolean
	set AbilityData_Harvest_cooldown = 0.8
	return true
endfunction

function init_Angle takes nothing returns boolean
	set Angle_DEGTORAD = 0.017453293
	set Angle_RADTODEG = 57.295779513
	return true
endfunction

function init_AttachmentPoints takes nothing returns boolean
	return true
endfunction

function init_Basics takes nothing returns boolean
	set Basics_ANIMATION_PERIOD = 0.030
	set Basics_HEIGHT_ENABLER = 1097691750
	set Basics_DUMMY_PLAYER = Player_players[PLAYER_NEUTRAL_PASSIVE]
	return true
endfunction

function int_bitOr takes integer this_1, integer other returns integer
	return BlzBitOr(this_1, other)
endfunction

function int_bitXor takes integer this_1, integer other returns integer
	return BlzBitXor(this_1, other)
endfunction

function initPows takes nothing returns nothing
	local integer allPows
	local integer i
	local integer temp
	local integer i_1
	local integer temp_1
	set BitSet_pows[0] = 1
	set allPows = 1
	set i = 1
	set temp = BitSet_BITSET_SIZE - 1
	loop
		exitwhen i > temp
		set BitSet_pows[i] = BitSet_pows[i - 1] * 2
		set allPows = int_bitOr(allPows, BitSet_pows[i])
		set i = i + 1
	endloop
	set i_1 = 0
	set temp_1 = BitSet_BITSET_SIZE - 1
	loop
		exitwhen i_1 > temp_1
		call int_bitXor(allPows, BitSet_pows[i_1])
		set i_1 = i_1 + 1
	endloop
endfunction

function init_BitSet takes nothing returns boolean
	set BitSet_BITSET_SIZE = 32
	call initPows()
	return true
endfunction

function alloc_CallbackPeriodic_doPeriodically_BuildingSystem takes nothing returns integer
	local integer this_1
	if CallbackPeriodic_firstFree == 0 then
		if CallbackPeriodic_maxIndex < 32768 then
			set CallbackPeriodic_maxIndex = CallbackPeriodic_maxIndex + 1
			set this_1 = CallbackPeriodic_maxIndex
			set CallbackPeriodic_typeId[this_1] = 647
		else
			call error("Out of memory: Could not create CallbackPeriodic_doPeriodically_BuildingSystem.")
			set this_1 = 0
		endif
	else
		set CallbackPeriodic_firstFree = CallbackPeriodic_firstFree - 1
		set this_1 = CallbackPeriodic_nextFree[CallbackPeriodic_firstFree]
		set CallbackPeriodic_typeId[this_1] = 647
	endif
	return this_1
endfunction

function CallbackPeriodic_init takes integer this_1 returns nothing
endfunction

function construct_CallbackPeriodic takes integer this_1 returns nothing
	call CallbackPeriodic_init(this_1)
endfunction

function CallbackPeriodic_start takes integer this_1, timer whichTimer, real time returns nothing
	local timer receiver = whichTimer
	local timer receiver_1
	call timer_setData(receiver, this_1)
	set receiver_1 = receiver
	call timer_startPeriodic(receiver_1, time, ref_function_CallbackPeriodic_staticCallback)
	set receiver = null
	set receiver_1 = null
endfunction

function dispatch_CallbackPeriodic_ClosureTimers_CallbackPeriodic_start takes integer this_1, timer whichTimer, real time returns nothing
	if CallbackPeriodic_typeId[this_1] == 0 then
		if this_1 == 0 then
			call error("Nullpointer exception when calling CallbackPeriodic.start")
		else
			call error("Called CallbackPeriodic.start on invalid object.")
		endif
	endif
	call CallbackPeriodic_start(this_1, whichTimer, time)
endfunction

function timer_doPeriodically takes timer this_1, real time, integer cb returns integer
	call dispatch_CallbackPeriodic_ClosureTimers_CallbackPeriodic_start(cb, this_1, time)
	return cb
endfunction

function doPeriodically takes real time, integer cb returns integer
	return timer_doPeriodically(getTimer(), time, cb)
endfunction

function alloc_IterableUnitHashMap takes nothing returns integer
	local integer this_1
	if UnitMap_firstFree == 0 then
		if UnitMap_maxIndex < 32768 then
			set UnitMap_maxIndex = UnitMap_maxIndex + 1
			set this_1 = UnitMap_maxIndex
			set UnitMap_typeId[this_1] = 850
		else
			call error("Out of memory: Could not create IterableUnitHashMap.")
			set this_1 = 0
		endif
	else
		set UnitMap_firstFree = UnitMap_firstFree - 1
		set this_1 = UnitMap_nextFree[UnitMap_firstFree]
		set UnitMap_typeId[this_1] = 850
	endif
	return this_1
endfunction

function alloc_HashList takes nothing returns integer
	local integer this_1
	if HashList_firstFree == 0 then
		if HashList_maxIndex < 32768 then
			set HashList_maxIndex = HashList_maxIndex + 1
			set this_1 = HashList_maxIndex
			set HashList_typeId[this_1] = 694
		else
			call error("Out of memory: Could not create HashList.")
			set this_1 = 0
		endif
	else
		set HashList_firstFree = HashList_firstFree - 1
		set this_1 = HashList_nextFree[HashList_firstFree]
		set HashList_typeId[this_1] = 694
	endif
	return this_1
endfunction

function HashList_init takes integer this_1 returns nothing
	set HashList_size[this_1] = 0
endfunction

function construct_HashList takes integer this_1 returns nothing
	call HashList_init(this_1)
endfunction

function new_HashList takes nothing returns integer
	local integer this_1 = alloc_HashList()
	call construct_HashList(this_1)
	return this_1
endfunction

function IterableUnitHashMap_init takes integer this_1 returns nothing
	set IterableUnitHashMap_keys[this_1] = new_HashList()
endfunction

function construct_UnitHashMap2 takes integer this_1 returns nothing
	call UnitHashMap_init(this_1)
endfunction

function construct_IterableUnitHashMap takes integer this_1, integer nullElem returns nothing
	call construct_UnitHashMap2(this_1)
	call IterableUnitHashMap_init(this_1)
	set UnitHashMap_nullElem[this_1] = nullElem
endfunction

function new_IterableUnitHashMap takes integer nullElem returns integer
	local integer this_1 = alloc_IterableUnitHashMap()
	call construct_IterableUnitHashMap(this_1, nullElem)
	return this_1
endfunction

function onUnitDeindex takes code func returns nothing
	call trigger_addCondition(UnitIndexer_onDeindexTrigger, Condition(func))
endfunction

function init_BuildingSystem takes nothing returns boolean
	local group finishedBuildings_1
	local integer clVar
	local real temp
	set BuildingSystem_BUILDING_ADJUSTMENT_RATE = 0.1
	set BuildingSystem_BUILDING_START_HP_PERCENTAGE = 0.1
	set BuildingSystem_MAX_AUTO_ORDER_RANGE = 1024.
	set BuildingSystem_MAX_NEAR_BY_RANGE = 256.
	set BuildingSystem_BUILDING_GROUND_UNIT_ID = Custom_buildingGround
	set BuildingSystem_BUILD_PROGRESS_ICON_PATH = Icons_bTNEngineeringUpgrade
	set BuildingSystem_BUILD_TIME_LEFT_ICON_PATH = Icons_bTNStatUp
	set BuildingSystem_WORKERS_ICON_PATH = Icons_bTNBash
	set BuildingSystem_BUILDING_SITE_MAP = new_IterableUnitHashMap(0)
	set BuildingSystem_WORKER_MAP = new_UnitHashMap(0)
	call onUnitDeindex(ref_function_code__onUnitDeindex_BuildingSystem)
	set finishedBuildings_1 = CreateGroup()
	set temp = BuildingSystem_BUILDING_ADJUSTMENT_RATE
	set clVar = alloc_CallbackPeriodic_doPeriodically_BuildingSystem()
	call construct_CallbackPeriodic(clVar)
	set finishedBuildings[clVar] = finishedBuildings_1
	call doPeriodically(temp, clVar)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_CONSTRUCT_START, ref_function_code__registerPlayerUnitEvent_BuildingSystem)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_UPGRADE_CANCEL, ref_function_code__registerPlayerUnitEvent_BuildingSystem_600)
	set BuildingSystem_testBuildingSystem_Build_building = null
	set finishedBuildings_1 = null
	return true
endfunction

function init_Buildings takes nothing returns boolean
	return true
endfunction

function init_ClosureForGroups takes nothing returns boolean
	local real tuple_temp
	local real tuple_temp_1
	call CreateGroup()
	set ClosureForGroups_tempCallbacksCount = 0
	set ClosureForGroups_maxCount = Integer_INT_MAX
	set ClosureForGroups_iterCount = 0
	call Filter(ref_function_code__Filter_ClosureForGroups)
	call Rect(0., 0., 0., 0.)
	set tuple_temp = Vectors_ZERO2_x
	set tuple_temp_1 = Vectors_ZERO2_y
	return true
endfunction

function init_ClosureTimers takes nothing returns boolean
	set ClosureTimers_x = 200
	return true
endfunction

function initializeTable takes nothing returns nothing
	local integer i = 0
	loop
		exitwhen i > 15
		call dispatch_Table_Table_Table_saveInt(Colors_decs, string_getHash(Colors_hexs[i]), i)
		set i = i + 1
	endloop
endfunction

function alloc_Table takes nothing returns integer
	local integer this_1
	if Table_firstFree == 0 then
		if Table_maxIndex < 32768 then
			set Table_maxIndex = Table_maxIndex + 1
			set this_1 = Table_maxIndex
			set Table_typeId[this_1] = 820
		else
			call error("Out of memory: Could not create Table.")
			set this_1 = 0
		endif
	else
		set Table_firstFree = Table_firstFree - 1
		set this_1 = Table_nextFree[Table_firstFree]
		set Table_typeId[this_1] = 820
	endif
	return this_1
endfunction

function new_Table takes nothing returns integer
	local integer this_1 = alloc_Table()
	call construct_Table(this_1)
	return this_1
endfunction

function init_Colors takes nothing returns boolean
	local integer tuple_temp = 255
	local integer tuple_temp_1 = 255
	local integer tuple_temp_2 = 255
	local integer tuple_temp_3 = 255
	local integer tuple_temp_4
	local integer tuple_temp_5
	local integer tuple_temp_6
	local integer tuple_temp_7
	local integer tuple_temp_8
	local integer tuple_temp_9
	local integer tuple_temp_10
	local integer tuple_temp_11
	local integer tuple_temp_12
	local integer tuple_temp_13
	local integer tuple_temp_14
	local integer tuple_temp_15
	local integer tuple_temp_16
	local integer tuple_temp_17
	local integer tuple_temp_18
	local integer tuple_temp_19
	local integer tuple_temp_20
	local integer tuple_temp_21
	local integer tuple_temp_22
	local integer tuple_temp_23
	local integer tuple_temp_24
	local integer tuple_temp_25
	local integer tuple_temp_26
	local integer tuple_temp_27
	local integer tuple_temp_28
	local integer tuple_temp_29
	local integer tuple_temp_30
	local integer tuple_temp_31
	local integer tuple_temp_32
	local integer tuple_temp_33
	local integer tuple_temp_34
	local integer tuple_temp_35
	local integer tuple_temp_36
	local integer tuple_temp_37
	local integer tuple_temp_38
	local integer tuple_temp_39
	local integer tuple_temp_40
	local integer tuple_temp_41
	local integer tuple_temp_42
	local integer tuple_temp_43
	local integer tuple_temp_44
	local integer tuple_temp_45
	local integer tuple_temp_46
	local integer tuple_temp_47
	local integer tuple_temp_48
	local integer tuple_temp_49
	local integer tuple_temp_50
	local integer tuple_temp_51
	local integer tuple_temp_52
	local integer tuple_temp_53
	local integer tuple_temp_54
	local integer tuple_temp_55
	local integer tuple_temp_56
	local integer tuple_temp_57
	local integer tuple_temp_58
	local integer tuple_temp_59
	local integer tuple_temp_60
	local integer tuple_temp_61
	local integer tuple_temp_62
	local integer tuple_temp_63
	local integer tuple_temp_64
	local integer tuple_temp_65
	local integer tuple_temp_66
	local integer tuple_temp_67
	local integer tuple_temp_68
	local integer tuple_temp_69
	local integer tuple_temp_70
	local integer tuple_temp_71
	local integer tuple_temp_72
	local integer tuple_temp_73
	local integer tuple_temp_74
	local integer tuple_temp_75
	set Colors_COLOR_WHITE_red = tuple_temp
	set Colors_COLOR_WHITE_green = tuple_temp_1
	set Colors_COLOR_WHITE_blue = tuple_temp_2
	set Colors_COLOR_WHITE_alpha = tuple_temp_3
	set tuple_temp_4 = 255
	set tuple_temp_5 = 2
	set tuple_temp_6 = 2
	set Colors_PLAYER_COLORS_red[0] = tuple_temp_4
	set Colors_PLAYER_COLORS_green[0] = tuple_temp_5
	set Colors_PLAYER_COLORS_blue[0] = tuple_temp_6
	set tuple_temp_7 = 0
	set tuple_temp_8 = 65
	set tuple_temp_9 = 255
	set Colors_PLAYER_COLORS_red[1] = tuple_temp_7
	set Colors_PLAYER_COLORS_green[1] = tuple_temp_8
	set Colors_PLAYER_COLORS_blue[1] = tuple_temp_9
	set tuple_temp_10 = 27
	set tuple_temp_11 = 229
	set tuple_temp_12 = 184
	set Colors_PLAYER_COLORS_red[2] = tuple_temp_10
	set Colors_PLAYER_COLORS_green[2] = tuple_temp_11
	set Colors_PLAYER_COLORS_blue[2] = tuple_temp_12
	set tuple_temp_13 = 83
	set tuple_temp_14 = 0
	set tuple_temp_15 = 128
	set Colors_PLAYER_COLORS_red[3] = tuple_temp_13
	set Colors_PLAYER_COLORS_green[3] = tuple_temp_14
	set Colors_PLAYER_COLORS_blue[3] = tuple_temp_15
	set tuple_temp_16 = 255
	set tuple_temp_17 = 252
	set tuple_temp_18 = 0
	set Colors_PLAYER_COLORS_red[4] = tuple_temp_16
	set Colors_PLAYER_COLORS_green[4] = tuple_temp_17
	set Colors_PLAYER_COLORS_blue[4] = tuple_temp_18
	set tuple_temp_19 = 254
	set tuple_temp_20 = 137
	set tuple_temp_21 = 13
	set Colors_PLAYER_COLORS_red[5] = tuple_temp_19
	set Colors_PLAYER_COLORS_green[5] = tuple_temp_20
	set Colors_PLAYER_COLORS_blue[5] = tuple_temp_21
	set tuple_temp_22 = 31
	set tuple_temp_23 = 191
	set tuple_temp_24 = 0
	set Colors_PLAYER_COLORS_red[6] = tuple_temp_22
	set Colors_PLAYER_COLORS_green[6] = tuple_temp_23
	set Colors_PLAYER_COLORS_blue[6] = tuple_temp_24
	set tuple_temp_25 = 228
	set tuple_temp_26 = 90
	set tuple_temp_27 = 175
	set Colors_PLAYER_COLORS_red[7] = tuple_temp_25
	set Colors_PLAYER_COLORS_green[7] = tuple_temp_26
	set Colors_PLAYER_COLORS_blue[7] = tuple_temp_27
	set tuple_temp_28 = 148
	set tuple_temp_29 = 149
	set tuple_temp_30 = 150
	set Colors_PLAYER_COLORS_red[8] = tuple_temp_28
	set Colors_PLAYER_COLORS_green[8] = tuple_temp_29
	set Colors_PLAYER_COLORS_blue[8] = tuple_temp_30
	set tuple_temp_31 = 125
	set tuple_temp_32 = 190
	set tuple_temp_33 = 241
	set Colors_PLAYER_COLORS_red[9] = tuple_temp_31
	set Colors_PLAYER_COLORS_green[9] = tuple_temp_32
	set Colors_PLAYER_COLORS_blue[9] = tuple_temp_33
	set tuple_temp_34 = 15
	set tuple_temp_35 = 97
	set tuple_temp_36 = 69
	set Colors_PLAYER_COLORS_red[10] = tuple_temp_34
	set Colors_PLAYER_COLORS_green[10] = tuple_temp_35
	set Colors_PLAYER_COLORS_blue[10] = tuple_temp_36
	set tuple_temp_37 = 77
	set tuple_temp_38 = 41
	set tuple_temp_39 = 3
	set Colors_PLAYER_COLORS_red[11] = tuple_temp_37
	set Colors_PLAYER_COLORS_green[11] = tuple_temp_38
	set Colors_PLAYER_COLORS_blue[11] = tuple_temp_39
	set tuple_temp_40 = 155
	set tuple_temp_41 = 0
	set tuple_temp_42 = 0
	set Colors_PLAYER_COLORS_red[12] = tuple_temp_40
	set Colors_PLAYER_COLORS_green[12] = tuple_temp_41
	set Colors_PLAYER_COLORS_blue[12] = tuple_temp_42
	set tuple_temp_43 = 0
	set tuple_temp_44 = 0
	set tuple_temp_45 = 195
	set Colors_PLAYER_COLORS_red[13] = tuple_temp_43
	set Colors_PLAYER_COLORS_green[13] = tuple_temp_44
	set Colors_PLAYER_COLORS_blue[13] = tuple_temp_45
	set tuple_temp_46 = 0
	set tuple_temp_47 = 234
	set tuple_temp_48 = 255
	set Colors_PLAYER_COLORS_red[14] = tuple_temp_46
	set Colors_PLAYER_COLORS_green[14] = tuple_temp_47
	set Colors_PLAYER_COLORS_blue[14] = tuple_temp_48
	set tuple_temp_49 = 190
	set tuple_temp_50 = 0
	set tuple_temp_51 = 254
	set Colors_PLAYER_COLORS_red[15] = tuple_temp_49
	set Colors_PLAYER_COLORS_green[15] = tuple_temp_50
	set Colors_PLAYER_COLORS_blue[15] = tuple_temp_51
	set tuple_temp_52 = 235
	set tuple_temp_53 = 205
	set tuple_temp_54 = 135
	set Colors_PLAYER_COLORS_red[16] = tuple_temp_52
	set Colors_PLAYER_COLORS_green[16] = tuple_temp_53
	set Colors_PLAYER_COLORS_blue[16] = tuple_temp_54
	set tuple_temp_55 = 248
	set tuple_temp_56 = 164
	set tuple_temp_57 = 139
	set Colors_PLAYER_COLORS_red[17] = tuple_temp_55
	set Colors_PLAYER_COLORS_green[17] = tuple_temp_56
	set Colors_PLAYER_COLORS_blue[17] = tuple_temp_57
	set tuple_temp_58 = 191
	set tuple_temp_59 = 255
	set tuple_temp_60 = 128
	set Colors_PLAYER_COLORS_red[18] = tuple_temp_58
	set Colors_PLAYER_COLORS_green[18] = tuple_temp_59
	set Colors_PLAYER_COLORS_blue[18] = tuple_temp_60
	set tuple_temp_61 = 220
	set tuple_temp_62 = 185
	set tuple_temp_63 = 235
	set Colors_PLAYER_COLORS_red[19] = tuple_temp_61
	set Colors_PLAYER_COLORS_green[19] = tuple_temp_62
	set Colors_PLAYER_COLORS_blue[19] = tuple_temp_63
	set tuple_temp_64 = 40
	set tuple_temp_65 = 40
	set tuple_temp_66 = 40
	set Colors_PLAYER_COLORS_red[20] = tuple_temp_64
	set Colors_PLAYER_COLORS_green[20] = tuple_temp_65
	set Colors_PLAYER_COLORS_blue[20] = tuple_temp_66
	set tuple_temp_67 = 235
	set tuple_temp_68 = 240
	set tuple_temp_69 = 255
	set Colors_PLAYER_COLORS_red[21] = tuple_temp_67
	set Colors_PLAYER_COLORS_green[21] = tuple_temp_68
	set Colors_PLAYER_COLORS_blue[21] = tuple_temp_69
	set tuple_temp_70 = 0
	set tuple_temp_71 = 120
	set tuple_temp_72 = 30
	set Colors_PLAYER_COLORS_red[22] = tuple_temp_70
	set Colors_PLAYER_COLORS_green[22] = tuple_temp_71
	set Colors_PLAYER_COLORS_blue[22] = tuple_temp_72
	set tuple_temp_73 = 164
	set tuple_temp_74 = 111
	set tuple_temp_75 = 51
	set Colors_PLAYER_COLORS_red[23] = tuple_temp_73
	set Colors_PLAYER_COLORS_green[23] = tuple_temp_74
	set Colors_PLAYER_COLORS_blue[23] = tuple_temp_75
	set Colors_hexs[0] = "0"
	set Colors_hexs[1] = "1"
	set Colors_hexs[2] = "2"
	set Colors_hexs[3] = "3"
	set Colors_hexs[4] = "4"
	set Colors_hexs[5] = "5"
	set Colors_hexs[6] = "6"
	set Colors_hexs[7] = "7"
	set Colors_hexs[8] = "8"
	set Colors_hexs[9] = "9"
	set Colors_hexs[10] = "A"
	set Colors_hexs[11] = "B"
	set Colors_hexs[12] = "C"
	set Colors_hexs[13] = "D"
	set Colors_hexs[14] = "E"
	set Colors_hexs[15] = "F"
	set Colors_decs = new_Table()
	call initializeTable()
	return true
endfunction

function trigger_registerPlayerChatEvent takes trigger this_1, player whichPlayer, string chatMessageToDetect, boolean exactMatchOnly returns event
	return TriggerRegisterPlayerChatEvent(this_1, whichPlayer, chatMessageToDetect, exactMatchOnly)
endfunction

function init_Command_GiveWares takes nothing returns boolean
	local trigger receiver
	local trigger receiver_1
	local trigger receiver_2
	set Command_GiveWares_USER_PLAYER = Player(0)
	set Command_GiveWares_COMMAND = "give wares"
	set Command_GiveWares_COMMAND_SHORT = "gw"
	set receiver = CreateTrigger()
	call trigger_addAction(receiver, ref_function_executeCommand)
	set receiver_1 = receiver
	call trigger_registerPlayerChatEvent(receiver_1, Command_GiveWares_USER_PLAYER, Command_GiveWares_COMMAND, true)
	set receiver_2 = receiver_1
	call trigger_registerPlayerChatEvent(receiver_2, Command_GiveWares_USER_PLAYER, Command_GiveWares_COMMAND_SHORT, true)
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
	return true
endfunction

function init_Command_ShowAll takes nothing returns boolean
	local trigger receiver
	local trigger receiver_1
	local trigger receiver_2
	set Command_ShowAll_USER_PLAYER = Player(0)
	set Command_ShowAll_COMMAND = "show all"
	set Command_ShowAll_COMMAND_SHORT = "sa"
	set receiver = CreateTrigger()
	call trigger_addAction(receiver, ref_function_executeCommand_619)
	set receiver_1 = receiver
	call trigger_registerPlayerChatEvent(receiver_1, Command_ShowAll_USER_PLAYER, Command_ShowAll_COMMAND, true)
	set receiver_2 = receiver_1
	call trigger_registerPlayerChatEvent(receiver_2, Command_ShowAll_USER_PLAYER, Command_ShowAll_COMMAND_SHORT, true)
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
	return true
endfunction

function init_Command_Test takes nothing returns boolean
	local trigger receiver
	local trigger receiver_1
	local trigger receiver_2
	set Command_Test_USER_PLAYER = Player(0)
	set Command_Test_COMMAND = "test"
	set Command_Test_COMMAND_SHORT = "t"
	set receiver = CreateTrigger()
	call trigger_addAction(receiver, ref_function_executeCommand_620)
	set receiver_1 = receiver
	call trigger_registerPlayerChatEvent(receiver_1, Command_Test_USER_PLAYER, Command_Test_COMMAND, true)
	set receiver_2 = receiver_1
	call trigger_registerPlayerChatEvent(receiver_2, Command_Test_USER_PLAYER, Command_Test_COMMAND_SHORT, true)
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
	return true
endfunction

function init_Command_UnitTests takes nothing returns boolean
	local trigger receiver
	local trigger receiver_1
	local trigger receiver_2
	set Command_UnitTests_USER_PLAYER = Player(0)
	set Command_UnitTests_COMMAND = "unit test"
	set Command_UnitTests_COMMAND_SHORT = "ut"
	set receiver = CreateTrigger()
	call trigger_addAction(receiver, ref_function_executeCommand_621)
	set receiver_1 = receiver
	call trigger_registerPlayerChatEvent(receiver_1, Command_UnitTests_USER_PLAYER, Command_UnitTests_COMMAND, true)
	set receiver_2 = receiver_1
	call trigger_registerPlayerChatEvent(receiver_2, Command_UnitTests_USER_PLAYER, Command_UnitTests_COMMAND_SHORT, true)
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
	return true
endfunction

function alloc_OffsetIdGenerator takes nothing returns integer
	local integer this_1
	if OffsetIdGenerator_firstFree == 0 then
		if OffsetIdGenerator_maxIndex < 32768 then
			set OffsetIdGenerator_maxIndex = OffsetIdGenerator_maxIndex + 1
			set this_1 = OffsetIdGenerator_maxIndex
		else
			call error("Out of memory: Could not create OffsetIdGenerator.")
			set this_1 = 0
		endif
	else
		set OffsetIdGenerator_firstFree = OffsetIdGenerator_firstFree - 1
		set this_1 = OffsetIdGenerator_nextFree[OffsetIdGenerator_firstFree]
	endif
	return this_1
endfunction

function OffsetIdGenerator_init takes integer this_1 returns nothing
	call new_HashMap()
endfunction

function construct_OffsetIdGenerator takes integer this_1, integer start returns nothing
	call OffsetIdGenerator_init(this_1)
endfunction

function new_OffsetIdGenerator takes integer start returns integer
	local integer this_1 = alloc_OffsetIdGenerator()
	call construct_OffsetIdGenerator(this_1, start)
	return this_1
endfunction

function init_ConstantDataSystem takes nothing returns boolean
	call new_OffsetIdGenerator(2021273648)
	call new_OffsetIdGenerator(1098526768)
	set Melee_townHall = 2021273701
	set Melee_keep = 2021273702
	set Melee_castle = 2021273703
	set Melee_farm = 2021273704
	set Melee_altarOfKings = 2021273705
	set Melee_barracks = 2021273706
	set Melee_lumberMill = 2021273707
	set Melee_blacksmith = 2021273708
	set Melee_workshop = 2021273709
	set Melee_arcaneSanctum = 2021273710
	set Melee_gryphonAviary = 2021273711
	set Melee_scoutTower = 2021273712
	set Melee_guardTower = 2021273713
	set Melee_cannonTower = 2021273714
	set Melee_arcaneTower = 2021273715
	set Melee_arcaneVault = 2021273716
	set Melee_peasant = 2021273648
	set Melee_footman = 2021273649
	set Custom_buildingGround = 2021273717
	set Trees_beech = 2021273909
	set Trees_beech_Var1 = 2021273910
	set Trees_beech_Var2 = 2021273911
	set Trees_beech_Var3 = 2021273912
	set Trees_beech_Var4 = 2021273913
	set Trees_birch = 2021273953
	set Trees_birch_Var1 = 2021273954
	set Trees_birch_Var2 = 2021273955
	set Trees_birch_Var3 = 2021273956
	set Trees_greyOak = 2021273957
	set Trees_greyOak_Var1 = 2021273958
	set Trees_greyOak_Var2 = 2021273959
	set Trees_greyOak_Var3 = 2021273960
	set Trees_greyOak_Var4 = 2021273961
	set Trees_chestnut = 2021273962
	set Trees_chestnut_Var1 = 2021273963
	set Trees_chestnut_Var2 = 2021273964
	set AbilityIdsCustom_showTargetInfo = 1098526768
	set AbilityIdsCustom_harvest = 1098526769
	set AbilityIdsCustom_build = 1098526770
	set AbilityIdsCustom_transferWares = 1098526771
	set AbilityIdsCustom_addBuildingBuff = 1098526772
	set AbilityIdsCustom_enterBuilding = 1098526775
	set AbilityIdsCustom_changeProduct = 1098526776
	set AbilityIdsCustom_removeWorker = 1098526777
	set BuffIdsCustom_building = 1098526774
	return true
endfunction

function init_Destructable takes nothing returns boolean
	return true
endfunction

function init_Doodads takes nothing returns boolean
	return true
endfunction

function createDummy takes real pos_x, real pos_y, player owner, real facing_radians returns unit
	local unit u_1 = createUnit(owner, DummyRecycler_DUMMY_UNIT_ID, pos_x, pos_y, facing_radians)
	local unit receiver = u_1
	local unit receiver_1
	local unit receiver_2
	local unit receiver_3
	local unit receiver_4
	local unit receiver_5
	call unit_addAbility(receiver, Basics_HEIGHT_ENABLER)
	set receiver_1 = receiver
	call unit_removeAbility(receiver_1, Basics_HEIGHT_ENABLER)
	set receiver_2 = receiver_1
	call unit_addAbility(receiver_2, DummyRecycler_ROOT_ENABLER)
	set receiver_3 = receiver_2
	call unit_removeAbility(receiver_3, DummyRecycler_ROOT_ENABLER)
	set receiver_4 = receiver_3
	call unit_setXY(receiver_4, pos_x, pos_y)
	set receiver_5 = receiver_4
	call unit_setFacing(receiver_5, facing_radians)
	set createDummytempReturn = u_1
	set u_1 = null
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
	set receiver_3 = null
	set receiver_4 = null
	set receiver_5 = null
	return createDummytempReturn
endfunction

function alloc_ArrayQueue takes nothing returns integer
	local integer this_1
	if ArrayQueue_firstFree == 0 then
		if ArrayQueue_maxIndex < 32768 then
			set ArrayQueue_maxIndex = ArrayQueue_maxIndex + 1
			set this_1 = ArrayQueue_maxIndex
			set ArrayQueue_typeId[this_1] = 633
		else
			call error("Out of memory: Could not create ArrayQueue.")
			set this_1 = 0
		endif
	else
		set ArrayQueue_firstFree = ArrayQueue_firstFree - 1
		set this_1 = ArrayQueue_nextFree[ArrayQueue_firstFree]
		set ArrayQueue_typeId[this_1] = 633
	endif
	return this_1
endfunction

function ArrayQueue_init takes integer this_1 returns nothing
	set ArrayQueue_rp[this_1] = 0
	set ArrayQueue_size[this_1] = 0
endfunction

function construct_ArrayQueue takes integer this_1 returns nothing
	call ArrayQueue_init(this_1)
endfunction

function new_ArrayQueue takes nothing returns integer
	local integer this_1 = alloc_ArrayQueue()
	call construct_ArrayQueue(this_1)
	return this_1
endfunction

function init_DummyRecycler takes nothing returns boolean
	local integer i
	local integer temp
	local real facing_radians
	local integer j
	local integer temp_1
	local unit dummy
	local real tuple_temp
	set DummyRecycler_DUMMY_UNIT_ID = 2019849581
	set DummyRecycler_ROOT_ENABLER = 2020765556
	set DummyRecycler_DIFFERENT_ANGLES = 8
	set DummyRecycler_ANGLE_DEGREE = 360 * 1. / DummyRecycler_DIFFERENT_ANGLES
	set DummyRecycler_SAVED_UNITS_PER_ANGLE = 6
	set DelayNode_t = CreateTimer()
	set DelayNode_first = 0
	set i = 0
	set temp = DummyRecycler_DIFFERENT_ANGLES - 1
	loop
		exitwhen i > temp
		set DummyRecycler_angleQueues[i] = new_ArrayQueue()
		set tuple_temp = i * DummyRecycler_ANGLE_DEGREE
		set facing_radians = tuple_temp
		set j = 0
		set temp_1 = DummyRecycler_SAVED_UNITS_PER_ANGLE - 1
		loop
			exitwhen j > temp_1
			set dummy = createDummy(vec2_op_minus(MapBounds_boundMax_x, MapBounds_boundMax_y, 16., 16.), vec2_op_minus_return_y, Basics_DUMMY_PLAYER, facing_radians)
			call dispatch_ArrayQueue_DummyRecycler_ArrayQueue_enqueue(DummyRecycler_angleQueues[i], dummy)
			set j = j + 1
		endloop
		set i = i + 1
	endloop
	set dummy = null
	return true
endfunction

function init_ErrorHandling takes nothing returns boolean
	set ErrorHandling_MUTE_ERROR_DURATION = 60
	set ErrorHandling_PRIMARY_ERROR_KEY = -1
	set ErrorHandling_HT = hashtable_compiletime
	set ErrorHandling_suppressErrorMessages = false
	return true
endfunction

function init_EventHelper takes nothing returns boolean
	call new_HashMap()
	call new_HashMap()
	call new_Table()
	return true
endfunction

function verifyFrameNameLength takes string name returns boolean
	if string_length(name) > Framehandle_BLZ_FRAMENAME_MAXLENGTH then
		call error("Trying to address frame with exceeding maximum frame name length (" + int_toString(Framehandle_BLZ_FRAMENAME_MAXLENGTH) + ") for: " + name)
		return false
	endif
	return true
endfunction

function createFrame takes string typeName, string name, framehandle owner, string inherits, integer createContext returns framehandle
	call verifyFrameNameLength(name)
	return BlzCreateFrameByType(typeName, name, owner, inherits, createContext)
endfunction

function framehandle_setSize takes framehandle this_1, real width, real height returns nothing
	call BlzFrameSetSize(this_1, width, height)
endfunction

function init_Framehandle takes nothing returns boolean
	local framehandle receiver
	set Framehandle_GAME_UI = BlzGetOriginFrame(ORIGIN_FRAME_GAME_UI, 0)
	set Framehandle_BLZ_FRAMENAME_MAXLENGTH = 560
	set receiver = createFrame("FRAME", "SetMousePositionCage", Framehandle_GAME_UI, null, 0)
	call framehandle_setSize(receiver, 0.0001, 0.0001)
	set receiver = null
	return true
endfunction

function init_GameTimer takes nothing returns boolean
	set GameTimer_gameTimer = CreateTimer()
	call timer_start(GameTimer_gameTimer, 100000., null)
	call timer_startPeriodic(CreateTimer(), Basics_ANIMATION_PERIOD, ref_function_code__startPeriodic_GameTimer)
	return true
endfunction

function init_Group takes nothing returns boolean
	set Group_ENUM_GROUP = CreateGroup()
	return true
endfunction

function init_HashList takes nothing returns boolean
	set HashList_ht = hashtable_compiletime_570
	set HashList_occurences = hashtable_compiletime_571
	return true
endfunction

function init_Icons takes nothing returns boolean
	set Icons_bTNBash = "ReplaceableTextures\\CommandButtons\\BTNBash.blp"
	set Icons_bTNBundleOfLumber = "ReplaceableTextures\\CommandButtons\\BTNBundleOfLumber.blp"
	set Icons_bTNEngineeringUpgrade = "ReplaceableTextures\\CommandButtons\\BTNEngineeringUpgrade.blp"
	set Icons_bTNFarm = "ReplaceableTextures\\CommandButtons\\BTNFarm.blp"
	set Icons_bTNHumanArmorUpOne = "ReplaceableTextures\\CommandButtons\\BTNHumanArmorUpOne.blp"
	set Icons_bTNHumanLumberUpgrade1 = "ReplaceableTextures\\CommandButtons\\BTNHumanLumberUpgrade1.blp"
	set Icons_bTNHumanLumberUpgrade2 = "ReplaceableTextures\\CommandButtons\\BTNHumanLumberUpgrade2.blp"
	set Icons_bTNMonsterLure = "ReplaceableTextures\\CommandButtons\\BTNMonsterLure.blp"
	set Icons_bTNSleep = "ReplaceableTextures\\CommandButtons\\BTNSleep.blp"
	set Icons_bTNSnazzyScroll = "ReplaceableTextures\\CommandButtons\\BTNSnazzyScroll.blp"
	set Icons_bTNStatUp = "ReplaceableTextures\\CommandButtons\\BTNStatUp.blp"
	set Icons_bTNWorkshop = "ReplaceableTextures\\CommandButtons\\BTNWorkshop.blp"
	return true
endfunction

function unit_setPathing takes unit this_1, boolean value returns nothing
	call SetUnitPathing(this_1, value)
endfunction

function init_InstantDummyCaster takes nothing returns boolean
	local unit receiver
	local unit receiver_1
	local unit receiver_2
	local unit receiver_3
	local unit receiver_4
	set InstantDummyCaster_DUMMY_CASTER_UNIT_ID = 2016423985
	set InstantDummyCaster_DUMMY_ROOT_ABIL_ID = 1095577650
	set receiver = createUnit(Basics_DUMMY_PLAYER, InstantDummyCaster_DUMMY_CASTER_UNIT_ID, MapBounds_boundMax_x, MapBounds_boundMax_y, 0.)
	call unit_setPathing(receiver, false)
	set receiver_1 = receiver
	call unit_addAbility(receiver_1, Basics_HEIGHT_ENABLER)
	set receiver_2 = receiver_1
	call unit_removeAbility(receiver_2, Basics_HEIGHT_ENABLER)
	set receiver_3 = receiver_2
	call unit_addAbility(receiver_3, InstantDummyCaster_DUMMY_ROOT_ABIL_ID)
	set receiver_4 = receiver_3
	call unit_removeAbility(receiver_4, InstantDummyCaster_DUMMY_ROOT_ABIL_ID)
	set InstantDummyCaster_caster = receiver_4
	set receiver = null
	set receiver_1 = null
	set receiver_2 = null
	set receiver_3 = null
	set receiver_4 = null
	return true
endfunction

function init_Integer takes nothing returns boolean
	set Integer_INT_MAX = 2147483647
	set Integer_INT_MIN = -2147483648
	return true
endfunction

function init_Lightning takes nothing returns boolean
	return true
endfunction

function alloc_Comparator_LinkedList takes nothing returns integer
	local integer this_1
	if Comparator_firstFree == 0 then
		if Comparator_maxIndex < 32768 then
			set Comparator_maxIndex = Comparator_maxIndex + 1
			set this_1 = Comparator_maxIndex
		else
			call error("Out of memory: Could not create Comparator_LinkedList.")
			set this_1 = 0
		endif
	else
		set Comparator_firstFree = Comparator_firstFree - 1
		set this_1 = Comparator_nextFree[Comparator_firstFree]
	endif
	return this_1
endfunction

function alloc_Comparator_LinkedList_517 takes nothing returns integer
	local integer this_1
	if Comparator_firstFree == 0 then
		if Comparator_maxIndex < 32768 then
			set Comparator_maxIndex = Comparator_maxIndex + 1
			set this_1 = Comparator_maxIndex
		else
			call error("Out of memory: Could not create Comparator_LinkedList.")
			set this_1 = 0
		endif
	else
		set Comparator_firstFree = Comparator_firstFree - 1
		set this_1 = Comparator_nextFree[Comparator_firstFree]
	endif
	return this_1
endfunction

function realToIndex takes real r returns integer
	return real_toInt(r * TypeCasting_R2I_PRECISION)
endfunction

function init_LinkedList takes nothing returns boolean
	call alloc_Comparator_LinkedList()
	call alloc_Comparator_LinkedList_517()
	call realToIndex(0.)
	return true
endfunction

function init_MagicFunctions takes nothing returns boolean
	set MagicFunctions_compiletime = false
	return true
endfunction

function rect_getMaxX takes rect this_1 returns real
	return GetRectMaxX(this_1)
endfunction

function rect_getMaxY takes rect this_1 returns real
	return GetRectMaxY(this_1)
endfunction

function rect_getMinX takes rect this_1 returns real
	return GetRectMinX(this_1)
endfunction

function rect_getMinY takes rect this_1 returns real
	return GetRectMinY(this_1)
endfunction

function region_addRect takes region this_1, rect rct returns nothing
	call RegionAddRect(this_1, rct)
endfunction

function vec2_op_mult takes real this_x, real this_y, real factor returns real
	set vec2_op_mult_return_x = this_x * factor
	set vec2_op_mult_return_y = this_y * factor
	return vec2_op_mult_return_x
endfunction

function vec2_op_plus takes real this_x, real this_y, real v_x, real v_y returns real
	set vec2_op_plus_return_x = this_x + v_x
	set vec2_op_plus_return_y = this_y + v_y
	return vec2_op_plus_return_x
endfunction

function initMapBounds takes nothing returns nothing
	local rect cond_result
	local region receiver
	local rect cond_result_1
	local region receiver_1
	local real tuple_temp
	local real tuple_temp_1
	local real tuple_temp_2
	local real tuple_temp_3
	local real tuple_temp_4
	local real tuple_temp_5
	local real tuple_temp_6
	local real tuple_temp_7
	if MagicFunctions_compiletime then
		set cond_result = Rect(-1024., -1024., 1024., 1024.)
	else
		set cond_result = GetPlayableMapRect()
	endif
	set MapBounds_playableMapRect = cond_result
	set receiver = CreateRegion()
	call region_addRect(receiver, MapBounds_playableMapRect)
	if MagicFunctions_compiletime then
		set cond_result_1 = Rect(-1536., -1536., 1536., 1536.)
	else
		set cond_result_1 = GetWorldBounds()
	endif
	set MapBounds_boundRect = cond_result_1
	set receiver_1 = CreateRegion()
	call region_addRect(receiver_1, MapBounds_boundRect)
	set MapBounds_boundRegion = receiver_1
	set tuple_temp = rect_getMinX(MapBounds_playableMapRect)
	set tuple_temp_1 = rect_getMinY(MapBounds_playableMapRect)
	set MapBounds_playableMin_x = tuple_temp
	set MapBounds_playableMin_y = tuple_temp_1
	set tuple_temp_2 = rect_getMaxX(MapBounds_playableMapRect)
	set tuple_temp_3 = rect_getMaxY(MapBounds_playableMapRect)
	set MapBounds_playableMax_x = tuple_temp_2
	set MapBounds_playableMax_y = tuple_temp_3
	set tuple_temp_4 = rect_getMinX(MapBounds_boundRect)
	set tuple_temp_5 = rect_getMinY(MapBounds_boundRect)
	set MapBounds_boundMin_x = tuple_temp_4
	set MapBounds_boundMin_y = tuple_temp_5
	set tuple_temp_6 = rect_getMaxX(MapBounds_boundRect)
	set tuple_temp_7 = rect_getMaxY(MapBounds_boundRect)
	set MapBounds_boundMax_x = tuple_temp_6
	set MapBounds_boundMax_y = tuple_temp_7
	call vec2_op_mult(vec2_op_plus(MapBounds_playableMin_x, MapBounds_playableMin_y, MapBounds_playableMax_x, MapBounds_playableMax_y), vec2_op_plus_return_y, .5)
	call vec2_op_mult(vec2_op_plus(MapBounds_boundMin_x, MapBounds_boundMin_y, MapBounds_boundMax_x, MapBounds_boundMax_y), vec2_op_plus_return_y, .5)
endfunction

function init_MapBounds takes nothing returns boolean
	call initMapBounds()
	return true
endfunction

function init_Maths takes nothing returns boolean
	return true
endfunction

function init_Matrices takes nothing returns boolean
	local real tuple_temp = 0.
	local real tuple_temp_1 = 0.
	local real tuple_temp_2 = 0.
	local real tuple_temp_3 = 0.
	local real tuple_temp_4 = 0.
	local real tuple_temp_5 = 0.
	local real tuple_temp_6 = 0.
	local real tuple_temp_7 = 0.
	local real tuple_temp_8 = 0.
	local real tuple_temp_9 = 0.
	local real tuple_temp_10 = 0.
	local real tuple_temp_11 = 0.
	local real tuple_temp_12 = 0.
	local real tuple_temp_13 = 0.
	local real tuple_temp_14 = 0.
	local real tuple_temp_15 = 0.
	set Matrices_ZERO44_m00 = tuple_temp
	set Matrices_ZERO44_m01 = tuple_temp_1
	set Matrices_ZERO44_m02 = tuple_temp_2
	set Matrices_ZERO44_m03 = tuple_temp_3
	set Matrices_ZERO44_m10 = tuple_temp_4
	set Matrices_ZERO44_m11 = tuple_temp_5
	set Matrices_ZERO44_m12 = tuple_temp_6
	set Matrices_ZERO44_m13 = tuple_temp_7
	set Matrices_ZERO44_m20 = tuple_temp_8
	set Matrices_ZERO44_m21 = tuple_temp_9
	set Matrices_ZERO44_m22 = tuple_temp_10
	set Matrices_ZERO44_m23 = tuple_temp_11
	set Matrices_ZERO44_m30 = tuple_temp_12
	set Matrices_ZERO44_m31 = tuple_temp_13
	set Matrices_ZERO44_m32 = tuple_temp_14
	set Matrices_ZERO44_m33 = tuple_temp_15
	return true
endfunction

function alloc_Board takes nothing returns integer
	local integer this_1
	if Board_firstFree == 0 then
		if Board_maxIndex < 32768 then
			set Board_maxIndex = Board_maxIndex + 1
			set this_1 = Board_maxIndex
		else
			call error("Out of memory: Could not create Board.")
			set this_1 = 0
		endif
	else
		set Board_firstFree = Board_firstFree - 1
		set this_1 = Board_nextFree[Board_firstFree]
	endif
	return this_1
endfunction

function Board_init takes integer this_1 returns nothing
endfunction

function construct_Board takes integer this_1 returns nothing
	call Board_init(this_1)
	set Board_name[this_1] = null
	set Board_priority[this_1] = 0
	set Board_disableFunc[this_1] = 0
endfunction

function new_Board takes nothing returns integer
	local integer this_1 = alloc_Board()
	call construct_Board(this_1)
	return this_1
endfunction

function init_MultiboardPrioritySystem takes nothing returns boolean
	local integer i
	local integer temp
	set MultiboardPrioritySystem_COUNT_PLAYERS = 12
	set MultiboardPrioritySystem_HEADLINE_ICON_PATH = "UI\\Minimap\\MinimapIconCreepLoc2.blp"
	set MultiboardPrioritySystem_SUB_HEADLINE_ICON_PATH = "UI\\Minimap\\MinimapIconCreepLoc2.blp"
	set i = 0
	set temp = MultiboardPrioritySystem_COUNT_PLAYERS - 1
	loop
		exitwhen i > temp
		set MultiboardPrioritySystem_currentBoards[i] = new_Board()
		if MultiboardPrioritySystem_currentBoards[i] == 0 then
			call Log_error("ERROR: MultiboardInfo struct cap exceeded")
		endif
		set i = i + 1
	endloop
	return true
endfunction

function alloc_IdGenerator takes nothing returns integer
	local integer this_1
	if IdGenerator_firstFree == 0 then
		if IdGenerator_maxIndex < 32768 then
			set IdGenerator_maxIndex = IdGenerator_maxIndex + 1
			set this_1 = IdGenerator_maxIndex
		else
			call error("Out of memory: Could not create IdGenerator.")
			set this_1 = 0
		endif
	else
		set IdGenerator_firstFree = IdGenerator_firstFree - 1
		set this_1 = IdGenerator_nextFree[IdGenerator_firstFree]
	endif
	return this_1
endfunction

function IdGenerator_init takes integer this_1 returns nothing
endfunction

function construct_IdGenerator takes integer this_1, integer start returns nothing
	call IdGenerator_init(this_1)
endfunction

function new_IdGenerator takes integer start returns integer
	local integer this_1 = alloc_IdGenerator()
	call construct_IdGenerator(this_1, start)
	return this_1
endfunction

function init_ObjectIdGenerator takes nothing returns boolean
	call new_IdGenerator(2016423984)
	call new_IdGenerator(1213018160)
	call new_IdGenerator(1095577648)
	call new_IdGenerator(1112354864)
	call new_IdGenerator(1229795376)
	call new_IdGenerator(1380790320)
	return true
endfunction

function init_ObjectIds takes nothing returns boolean
	set ObjectIds_CHARMAP = ".................................!.#$%&'()*+,-./0123456789:;<=>?@ABCDEFGHIJKLMNOPQRSTUVWXYZ[.]^_`abcdefghijklmnopqrstuvwxyz{|}~................................................................................................................................."
	return true
endfunction

function alloc_Dataset takes nothing returns integer
	local integer this_1
	if Dataset_firstFree == 0 then
		if Dataset_maxIndex < 32768 then
			set Dataset_maxIndex = Dataset_maxIndex + 1
			set this_1 = Dataset_maxIndex
			set Dataset_typeId[this_1] = 681
		else
			call error("Out of memory: Could not create Dataset.")
			set this_1 = 0
		endif
	else
		set Dataset_firstFree = Dataset_firstFree - 1
		set this_1 = Dataset_nextFree[Dataset_firstFree]
		set Dataset_typeId[this_1] = 681
	endif
	return this_1
endfunction

function Dataset_init takes integer this_1 returns nothing
endfunction

function construct_Dataset takes integer this_1, integer playerID returns nothing
	call Dataset_init(this_1)
	set Dataset_playerID[this_1] = playerID
	set Dataset_usedMultiboard[this_1] = null
	set Dataset_adjustingTimer[this_1] = getTimer()
	set Dataset_targetedUnit[this_1] = null
	set Dataset_targetedDestructable[this_1] = null
endfunction

function new_Dataset takes integer playerID returns integer
	local integer this_1 = alloc_Dataset()
	call construct_Dataset(this_1, playerID)
	return this_1
endfunction

function init_ObjectInfoSystem takes nothing returns boolean
	local integer i
	local integer temp
	set ObjectInfoSystem_COUNT_PLAYERS = 12
	set ObjectInfoSystem_MULTIBOARD_PRIORITY = 1
	set ObjectInfoSystem_ADJUSTING_TIME = 0.5
	set ObjectInfoSystem_MULTIBOARD_NAME = "ObjectInfoSystem"
	set i = 0
	set temp = ObjectInfoSystem_COUNT_PLAYERS - 1
	loop
		exitwhen i > temp
		set ObjectInfoSystem_datasets[i] = new_Dataset(i)
		if ObjectInfoSystem_datasets[i] == 0 then
			call Log_error("ERROR: InfoBoard struct cap exceeded")
		endif
		set i = i + 1
	endloop
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_SELECTED, ref_function_code__registerPlayerUnitEvent_ObjectInfoSystem)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_SPELL_CAST, ref_function_code__registerPlayerUnitEvent_ObjectInfoSystem_602)
	return true
endfunction

function init_Objects takes nothing returns boolean
	return true
endfunction

function alloc_CallbackSingle_nullTimer_OnUnitEnterLeave takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 674
		else
			call error("Out of memory: Could not create CallbackSingle_nullTimer_OnUnitEnterLeave.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 674
	endif
	return this_1
endfunction

function nullTimer takes integer cb returns integer
	return doAfter(0., cb)
endfunction

function player_setAbilityAvailable takes player this_1, integer abilityId, boolean avail returns nothing
	call SetPlayerAbilityAvailable(this_1, abilityId, avail)
endfunction

function init_OnUnitEnterLeave takes nothing returns boolean
	local integer i
	local integer temp
	local integer clVar
	set OnUnitEnterLeave_eventTrigger = CreateTrigger()
	set OnUnitEnterLeave_preplacedUnits = CreateGroup()
	set OnUnitEnterLeave_tempUnitsCount = 0
	set OnUnitEnterLeave_ABILITY_ID = 1095577649
	set i = 0
	set temp = bj_MAX_PLAYER_SLOTS - 1
	loop
		exitwhen i > temp
		call player_setAbilityAvailable(Player_players[i], OnUnitEnterLeave_ABILITY_ID, false)
		set i = i + 1
	endloop
	set clVar = alloc_CallbackSingle_nullTimer_OnUnitEnterLeave()
	call construct_CallbackSingle(clVar)
	call nullTimer(clVar)
	return true
endfunction

function onLeave takes code c returns nothing
	call trigger_addAction(OnUnitEnterLeave_eventTrigger, c)
endfunction

function init_OrderSystem takes nothing returns boolean
	set OrderSystem_ORDER_ICON_PATH = Icons_bTNSnazzyScroll
	set OrderSystem_POS_TOLERANCE_RANGE = 1.
	set OrderSystem_POS_CHECK_RATE = 1.
	set OrderSystem_ORDER_SOURCE_MAP = new_UnitHashMap(0)
	set OrderSystem_ORDER_TARGET_MAP = new_UnitHashMap(0)
	call onLeave(ref_function_code__onLeave_OrderSystem)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_DEATH, ref_function_code__registerPlayerUnitEvent_OrderSystem)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_UPGRADE_CANCEL, ref_function_code__registerPlayerUnitEvent_OrderSystem_604)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_UPGRADE_FINISH, ref_function_code__registerPlayerUnitEvent_OrderSystem_605)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_ISSUED_TARGET_ORDER, ref_function_code__registerPlayerUnitEvent_OrderSystem_606)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_ISSUED_ORDER, ref_function_code__registerPlayerUnitEvent_OrderSystem_607)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_ISSUED_POINT_ORDER, ref_function_code__registerPlayerUnitEvent_OrderSystem_608)
	return true
endfunction

function init_Orders takes nothing returns boolean
	set SpecialOrders_cancel = 851976
	set SpecialOrders_smart = 851971
	set SpecialOrders_stunned = 851973
	set OrderIds_attack = 851983
	set OrderIds_attackground = 851984
	set OrderIds_frostnova = 852226
	set OrderIds_holdposition = 851993
	set OrderIds_innerfire = 852066
	set OrderIds_move = 851986
	set OrderIds_patrol = 851990
	set OrderIds_repair = 852024
	set OrderIds_repairoff = 852026
	set OrderIds_repairon = 852025
	set OrderIds_shadowstrike = 852527
	set OrderIds_stop = 851972
	set OrderIds_thunderbolt = 852095
	set OrderIds_undefend = 852056
	return true
endfunction

function alloc_CallbackPeriodic_doPeriodically_PersonSystem takes nothing returns integer
	local integer this_1
	if CallbackPeriodic_firstFree == 0 then
		if CallbackPeriodic_maxIndex < 32768 then
			set CallbackPeriodic_maxIndex = CallbackPeriodic_maxIndex + 1
			set this_1 = CallbackPeriodic_maxIndex
			set CallbackPeriodic_typeId[this_1] = 648
		else
			call error("Out of memory: Could not create CallbackPeriodic_doPeriodically_PersonSystem.")
			set this_1 = 0
		endif
	else
		set CallbackPeriodic_firstFree = CallbackPeriodic_firstFree - 1
		set this_1 = CallbackPeriodic_nextFree[CallbackPeriodic_firstFree]
		set CallbackPeriodic_typeId[this_1] = 648
	endif
	return this_1
endfunction

function onEnter takes code c returns nothing
	call trigger_addCondition(OnUnitEnterLeave_eventTrigger, Filter(c))
endfunction

function init_PersonSystem takes nothing returns boolean
	local integer clVar
	local real temp
	set PersonSystem_FOOD_ICON_PATH = Icons_bTNMonsterLure
	set PersonSystem_SLEEP_ICON_PATH = Icons_bTNSleep
	set PersonSystem_HOUSE_ICON_PATH = Icons_bTNFarm
	set PersonSystem_WORKPLACE_ICON_PATH = Icons_bTNWorkshop
	set PersonSystem_MAX_FOOD = 100.
	set PersonSystem_MAX_SLEEP = 100.
	set PersonSystem_MAX_DAYS_NO_FOOD = 3
	set PersonSystem_MAX_DAYS_NO_SLEEP = 5
	set PersonSystem_STATS_ADJUSTMENT_RATE = UtilityFunctions_INGAME_DAY_SECONDS / 24.
	set PersonSystem_surnameCounter = 0
	set PersonSystem_PERSON_MAP = new_IterableUnitHashMap(0)
	call onEnter(ref_function_code__onEnter_PersonSystem)
	call onLeave(ref_function_code__onLeave_PersonSystem)
	set temp = PersonSystem_STATS_ADJUSTMENT_RATE
	set clVar = alloc_CallbackPeriodic_doPeriodically_PersonSystem()
	call construct_CallbackPeriodic(clVar)
	call doPeriodically(temp, clVar)
	return true
endfunction

function initPlayerArray takes nothing returns nothing
	local integer i = 0
	local integer temp = bj_MAX_PLAYER_SLOTS - 1
	loop
		exitwhen i > temp
		set Player_players[i] = Player(i)
		set i = i + 1
	endloop
endfunction

function init_Player takes nothing returns boolean
	set Player_localPlayer = GetLocalPlayer()
	call initPlayerArray()
	return true
endfunction

function init_Playercolor takes nothing returns boolean
	call ConvertPlayerColor(24)
	call ConvertPlayerColor(25)
	call ConvertPlayerColor(26)
	call ConvertPlayerColor(27)
	return true
endfunction

function alloc_CallbackSingle_nullTimer_Preloader takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 675
		else
			call error("Out of memory: Could not create CallbackSingle_nullTimer_Preloader.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 675
	endif
	return this_1
endfunction

function string_charAt takes string this_1, integer index returns string
	return SubString(this_1, index, index + 1)
endfunction

function toRawCode takes integer value returns string
	local string result_1 = ""
	local integer remainingValue = value
	local integer byteno = 0
	local integer charValue
	loop
		exitwhen byteno > 3
		set charValue = ModuloInteger(remainingValue, 256)
		set remainingValue = remainingValue / 256
		set result_1 = string_charAt(ObjectIds_CHARMAP, charValue) + result_1
		set byteno = byteno + 1
	endloop
	return result_1
endfunction

function int_toRawCode takes integer this_1 returns string
	return toRawCode(this_1)
endfunction

function init_Preloader takes nothing returns boolean
	local integer clVar
	set Preloader_autoFinish = true
	set Preloader_dumg = CreateGroup()
	set Preloader_dum = createUnit(Basics_DUMMY_PLAYER, DummyRecycler_DUMMY_UNIT_ID, 0., 0., 0.)
	if Preloader_dum == null then
		call error("DUMMY_UNITID (" + int_toRawCode(DummyRecycler_DUMMY_UNIT_ID) + ") not added correctly to the map.")
	endif
	if Preloader_autoFinish then
		set clVar = alloc_CallbackSingle_nullTimer_Preloader()
		call construct_CallbackSingle(clVar)
		call nullTimer(clVar)
	endif
	return true
endfunction

function init_Printing takes nothing returns boolean
	set Printing_DEBUG_LEVEL = 2
	set Printing_DEBUG_MSG_DURATION = 45.
	return true
endfunction

function init_Quaternion takes nothing returns boolean
	return true
endfunction

function init_Real takes nothing returns boolean
	set Real_REAL_MAX = 340282366920938000000000000000000000000.
	return true
endfunction

function init_RegisterEvents takes nothing returns boolean
	set RegisterEvents_onCastMap = new_HashMap()
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_SPELL_EFFECT, ref_function_code__registerPlayerUnitEvent_RegisterEvents)
	return true
endfunction

function init_ResourceSystem takes nothing returns boolean
	set ResourceSystem_MAX_AUTO_ORDER_RANGE = 1024.
	set ResourceSystem_WORKERS_ICON_PATH = Icons_bTNBash
	set ResourceSystem_RESOURCE_MAP = new_UnitHashMap(0)
	set ResourceSystem_findNextResource_ValidUnits = CreateGroup()
	call onEnter(ref_function_code__onEnter_ResourceSystem)
	call onUnitDeindex(ref_function_code__onUnitDeindex_ResourceSystem)
	return true
endfunction

function getSmartUsedAbilityIds takes nothing returns integer
	local integer abilityIds = new_LinkedList()
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(abilityIds, AbilityIdsCustom_harvest)
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(abilityIds, AbilityIdsCustom_build)
	call dispatch_LinkedList_LinkedList_LinkedList_add_1(abilityIds, AbilityIdsCustom_transferWares)
	return abilityIds
endfunction

function init_SmartOrderSystem takes nothing returns boolean
	set SmartOrderSystem_SMART_USED_ABILITY_IDS = getSmartUsedAbilityIds()
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_ISSUED_TARGET_ORDER, ref_function_code__registerPlayerUnitEvent_SmartOrderSystem)
	return true
endfunction

function init_Sounds takes nothing returns boolean
	return true
endfunction

function init_Soundsets takes nothing returns boolean
	return true
endfunction

function init_StartupSystem takes nothing returns boolean
	local trigger receiver
	local trigger receiver_1
	local real tuple_temp
	local real tuple_temp_1
	set StartupSystem_USER_PLAYER = Player(0)
	set tuple_temp = 0.
	set tuple_temp_1 = 0.
	set StartupSystem_START_VEC_x = tuple_temp
	set StartupSystem_START_VEC_y = tuple_temp_1
	set StartupSystem_START_PEASANT_COUNT = 5
	set StartupSystem_START_WOOD_COUNT_PER_PEASANT = 5
	set StartupSystem_currentInitStatus = null
	set receiver = CreateTrigger()
	call trigger_addAction(receiver, ref_function_runStartup)
	set receiver_1 = receiver
	call trigger_execute(receiver_1)
	set receiver = null
	set receiver_1 = null
	return true
endfunction

function init_Stock takes nothing returns boolean
	set Stock_MAX_WARE_COUNT = 99999
	set Stock_MAX_WARE_TYPES = 9999
	return true
endfunction

function init_StorageSystem takes nothing returns boolean
	set StorageSystem_CAPACITY_ICON_PATH = Icons_bTNSnazzyScroll
	set StorageSystem_STORAGE_MAP = new_UnitHashMap(0)
	call onEnter(ref_function_code__onEnter_StorageSystem)
	call onLeave(ref_function_code__onLeave_StorageSystem)
	return true
endfunction

function init_String takes nothing returns boolean
	set String_charset = "0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ"
	set String_numberset = "0123456789"
	call string_length(String_numberset)
	call string_length(String_charset)
	return true
endfunction

function init_Table takes nothing returns boolean
	set Table_ht = hashtable_compiletime_569
	return true
endfunction

function init_TargetsAllowed takes nothing returns boolean
	return true
endfunction

function createItem_657 takes integer itemId, real pos_x, real pos_y, real pos_z returns item
	return CreateItem(itemId, pos_x, pos_y)
endfunction

function createItem takes integer itemId, real pos_x, real pos_y returns item
	return createItem_657(itemId, vec2_toVec3(pos_x, pos_y), vec2_toVec3_return_y, vec2_toVec3_return_z)
endfunction

function item_setVisible takes item this_1, boolean flag returns nothing
	call SetItemVisible(this_1, flag)
endfunction

function init_TerrainUtils takes nothing returns boolean
	local item receiver
	call real_squared(10.)
	set TerrainUtils_DUMMY_ITEM_ID = 2003790951
	set receiver = createItem(TerrainUtils_DUMMY_ITEM_ID, Vectors_ZERO2_x, Vectors_ZERO2_y)
	call item_setVisible(receiver, false)
	call Rect(0., 0., 128., 128.)
	call real_toInt(MapBounds_boundMax_x - MapBounds_boundMin_x)
	call real_toInt(MapBounds_boundMax_y - MapBounds_boundMin_y)
	set receiver = null
	return true
endfunction

function init_Textures takes nothing returns boolean
	return true
endfunction

function init_TimerUtils takes nothing returns boolean
	set TimerUtils_freeTimersCount = 0
	set TimerUtils_timerData = new_Table()
	set TimerUtils_HELD = 679645218
	call new_HashMap()
	return true
endfunction

function initTypecastData takes nothing returns nothing
	call dispatch_Table_Table_Table_saveString(TypeCasting_typecastdata, 0, "")
endfunction

function init_TypeCasting takes nothing returns boolean
	set TypeCasting_typecastdata = new_Table()
	set TypeCasting_R2I_PRECISION = 1000.
	call initTypecastData()
	return true
endfunction

function init_UI takes nothing returns boolean
	return true
endfunction

function init_UnitIds takes nothing returns boolean
	return true
endfunction

function init_UnitIndexer takes nothing returns boolean
	set UnitIndexer_onIndexTrigger = CreateTrigger()
	set UnitIndexer_onDeindexTrigger = CreateTrigger()
	set UnitIndexer_tempUnitsCount = 0
	call onEnter(ref_function_code__onEnter_UnitIndexer)
	call onLeave(ref_function_code__onLeave_UnitIndexer)
	return true
endfunction

function init_UnitTest takes nothing returns boolean
	set UnitTest_SHOW_START_TEST_MESSAGE = true
	set UnitTest_TEST_NAME_WURSTUNIT = "UseWurstunit"
	set UnitTest_TEST_NAME_MAP = new_HashMap()
	return true
endfunction

function init_Unit_AltarOfKings takes nothing returns boolean
	set UnitData_AltarOfKings_scalingValue = 0.65
	return true
endfunction

function init_Unit_ArcaneSanctum takes nothing returns boolean
	set UnitData_ArcaneSanctum_scalingValue = 1.2
	return true
endfunction

function init_Unit_ArcaneTower takes nothing returns boolean
	set UnitData_ArcaneTower_scalingValue = 1.1
	return true
endfunction

function init_Unit_ArcaneVault takes nothing returns boolean
	set UnitData_ArcaneVault_scalingValue = 0.8
	return true
endfunction

function init_Unit_Barracks takes nothing returns boolean
	set UnitData_Barracks_scalingValue = 1.2
	return true
endfunction

function init_Unit_Blacksmith takes nothing returns boolean
	set UnitData_Blacksmith_scalingValue = 0.65
	return true
endfunction

function init_Unit_CannonTower takes nothing returns boolean
	set UnitData_CannonTower_scalingValue = 1.1
	return true
endfunction

function init_Unit_Castle takes nothing returns boolean
	set UnitData_Castle_scalingValue = 1.1
	return true
endfunction

function init_Unit_GuardTower takes nothing returns boolean
	set UnitData_GuardTower_scalingValue = 1.1
	return true
endfunction

function init_Unit_Keep takes nothing returns boolean
	set UnitData_Keep_scalingValue = 1.1
	return true
endfunction

function init_Unit_LumberMill takes nothing returns boolean
	set UnitData_LumberMill_scalingValue = 0.8
	return true
endfunction

function init_Unit_ScoutTower takes nothing returns boolean
	set UnitData_ScoutTower_scalingValue = 1.1
	return true
endfunction

function init_Unit_TownHall takes nothing returns boolean
	set UnitData_Townhall_scalingValue = 1.1
	return true
endfunction

function init_Units takes nothing returns boolean
	return true
endfunction

function init_UnitsPresetFunctions takes nothing returns boolean
	return true
endfunction

function initBaseUnitTypeIdMap takes nothing returns integer
	local integer map = new_HashMap()
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_beech_Var1, Trees_beech)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_beech_Var2, Trees_beech)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_beech_Var3, Trees_beech)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_beech_Var4, Trees_beech)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_birch_Var1, Trees_birch)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_birch_Var2, Trees_birch)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_birch_Var3, Trees_birch)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_greyOak_Var1, Trees_greyOak)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_greyOak_Var2, Trees_greyOak)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_greyOak_Var3, Trees_greyOak)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_greyOak_Var4, Trees_greyOak)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_chestnut_Var1, Trees_chestnut)
	call dispatch_HashMap_HashMap_HashMap_put(map, Trees_chestnut_Var2, Trees_chestnut)
	return map
endfunction

function init_UtilityFunctions takes nothing returns boolean
	set UtilityFunctions_MIN_TRIGGER_SLEEP_TIME = 0.01
	set UtilityFunctions_MIN_ACTION_SLEEP_TIME = 0.25
	set UtilityFunctions_INGAME_DAY_SECONDS = 480.
	set UtilityFunctions_BASE_UNIT_TYPE_ID_MAP = initBaseUnitTypeIdMap()
	return true
endfunction

function init_Vectors takes nothing returns boolean
	local real tuple_temp = 0.
	local real tuple_temp_1 = 0.
	set Vectors_ZERO2_x = tuple_temp
	set Vectors_ZERO2_y = tuple_temp_1
	call Location(0., 0.)
	return true
endfunction

function init_WeatherEffects takes nothing returns boolean
	return true
endfunction

function alloc_CallbackPeriodic_doPeriodically_WorkshopSystem takes nothing returns integer
	local integer this_1
	if CallbackPeriodic_firstFree == 0 then
		if CallbackPeriodic_maxIndex < 32768 then
			set CallbackPeriodic_maxIndex = CallbackPeriodic_maxIndex + 1
			set this_1 = CallbackPeriodic_maxIndex
			set CallbackPeriodic_typeId[this_1] = 649
		else
			call error("Out of memory: Could not create CallbackPeriodic_doPeriodically_WorkshopSystem.")
			set this_1 = 0
		endif
	else
		set CallbackPeriodic_firstFree = CallbackPeriodic_firstFree - 1
		set this_1 = CallbackPeriodic_nextFree[CallbackPeriodic_firstFree]
		set CallbackPeriodic_typeId[this_1] = 649
	endif
	return this_1
endfunction

function init_WorkshopSystem takes nothing returns boolean
	local integer clVar
	local real temp
	set WorkshopSystem_MAX_STORABLE_EDUCTS = 5
	set WorkshopSystem_MAX_STORABLE_PRODUCTS = 3
	set WorkshopSystem_PRODUCTION_ADJUSTMENT_RATE = 0.1
	set WorkshopSystem_PRODUCTION_PROGRESS_ICON_PATH = Icons_bTNEngineeringUpgrade
	set WorkshopSystem_PRODUCTION_TIME_LEFT_ICON_PATH = Icons_bTNStatUp
	set WorkshopSystem_WORKERS_ICON_PATH = Icons_bTNBash
	set WorkshopSystem_WORKSHOP_MAP = new_IterableUnitHashMap(0)
	call onEnter(ref_function_code__onEnter_WorkshopSystem)
	call onUnitDeindex(ref_function_code__onUnitDeindex_WorkshopSystem)
	call registerPlayerUnitEvent(EVENT_PLAYER_UNIT_UPGRADE_FINISH, ref_function_code__registerPlayerUnitEvent_WorkshopSystem)
	set temp = WorkshopSystem_PRODUCTION_ADJUSTMENT_RATE
	set clVar = alloc_CallbackPeriodic_doPeriodically_WorkshopSystem()
	call construct_CallbackPeriodic(clVar)
	call doPeriodically(temp, clVar)
	return true
endfunction

function init_WorldGenerationSystem takes nothing returns boolean
	call Player(PLAYER_NEUTRAL_PASSIVE)
	return true
endfunction

function alloc_CallbackSingle_nullTimer_StartupSystem takes nothing returns integer
	local integer this_1
	if CallbackSingle_firstFree == 0 then
		if CallbackSingle_maxIndex < 32768 then
			set CallbackSingle_maxIndex = CallbackSingle_maxIndex + 1
			set this_1 = CallbackSingle_maxIndex
			set CallbackSingle_typeId[this_1] = 676
		else
			call error("Out of memory: Could not create CallbackSingle_nullTimer_StartupSystem.")
			set this_1 = 0
		endif
	else
		set CallbackSingle_firstFree = CallbackSingle_firstFree - 1
		set this_1 = CallbackSingle_nextFree[CallbackSingle_firstFree]
		set CallbackSingle_typeId[this_1] = 676
	endif
	return this_1
endfunction

function newInitStatus takes string statusName returns nothing
	if StartupSystem_currentInitStatus != null then
		call print("Initialisation: Finished " + StartupSystem_currentInitStatus)
	endif
	set StartupSystem_currentInitStatus = statusName
	if StartupSystem_currentInitStatus != null then
		call print("Initialisation: Starting " + StartupSystem_currentInitStatus)
	endif
endfunction

function runStartup takes nothing returns nothing
	local integer i
	local integer temp
	local unit u_1
	local integer clVar
	call SetMusicVolume(0)
	call newInitStatus("player units creation")
	set i = 1
	set temp = StartupSystem_START_PEASANT_COUNT
	loop
		exitwhen i > temp
		set u_1 = createUnit(StartupSystem_USER_PLAYER, Melee_peasant, StartupSystem_START_VEC_x, StartupSystem_START_VEC_y, 0.)
		set clVar = alloc_CallbackSingle_nullTimer_StartupSystem()
		call construct_CallbackSingle(clVar)
		set u[clVar] = u_1
		call nullTimer(clVar)
		set i = i + 1
	endloop
	call createUnit(StartupSystem_USER_PLAYER, Melee_footman, StartupSystem_START_VEC_x, StartupSystem_START_VEC_y, 0.)
	call newInitStatus(null)
	call print("Finished initialisation")
	set u_1 = null
endfunction

function initGlobals takes nothing returns nothing
	set CallbackSimple_firstFree = 0
	set CallbackSimple_maxIndex = 0
	set CallbackSingle_firstFree = 0
	set CallbackSingle_maxIndex = 0
	set CallbackPeriodic_firstFree = 0
	set CallbackPeriodic_maxIndex = 0
	set Stock_firstFree = 0
	set Stock_maxIndex = 0
	set ForGroupCallback_firstFree = 0
	set ForGroupCallback_maxIndex = 0
	set OffsetIdGenerator_firstFree = 0
	set OffsetIdGenerator_maxIndex = 0
	set ArrayQueue_firstFree = 0
	set ArrayQueue_maxIndex = 0
	set DelayNode_firstFree = 0
	set HLIterator_firstFree = 0
	set HLIterator_maxIndex = 0
	set HashList_firstFree = 0
	set HashList_maxIndex = 0
	set Table_firstFree = 0
	set Table_maxIndex = 0
	set Comparator_firstFree = 0
	set Comparator_maxIndex = 0
	set LLBackIterator_firstFree = 0
	set LLEntry_firstFree = 0
	set LLEntry_maxIndex = 0
	set LLIterator_firstFree = 0
	set LLIterator_maxIndex = 0
	set LinkedList_firstFree = 0
	set LinkedList_maxIndex = 0
	set Board_firstFree = 0
	set Board_maxIndex = 0
	set PlayerIDClosure_firstFree = 0
	set PlayerIDClosure_maxIndex = 0
	set IdGenerator_firstFree = 0
	set IdGenerator_maxIndex = 0
	set Dataset_firstFree = 0
	set Dataset_maxIndex = 0
	set CallbackCondition_firstFree = 0
	set CallbackCondition_maxIndex = 0
	set OrderAction_firstFree = 0
	set OrderAction_maxIndex = 0
	set OrderSource_firstFree = 0
	set OrderSource_maxIndex = 0
	set OrderTarget_firstFree = 0
	set OrderTarget_maxIndex = 0
	set Person_firstFree = 0
	set Person_maxIndex = 0
	set UnitIndex_firstFree = 0
	set UnitIndex_maxIndex = 0
	set UnitMap_firstFree = 0
	set UnitMap_maxIndex = 0
	set ref_function_init_Abilities = function init_Abilities
	set ref_function_init_AbilityIds = function init_AbilityIds
	set ref_function_init_Real = function init_Real
	set ref_function_init_Integer = function init_Integer
	set ref_function_init_BitSet = function init_BitSet
	set ref_function_init_String = function init_String
	set ref_function_init_TargetsAllowed = function init_TargetsAllowed
	set ref_function_init_Angle = function init_Angle
	set ref_function_init_Vectors = function init_Vectors
	set ref_function_init_Player = function init_Player
	set ref_function_init_Destructable = function init_Destructable
	set ref_function_init_Maths = function init_Maths
	set ref_function_init_Printing = function init_Printing
	set ref_function_init_MagicFunctions = function init_MagicFunctions
	set ref_function_init_Basics = function init_Basics
	set ref_function_init_GameTimer = function init_GameTimer
	set ref_function_init_ErrorHandling = function init_ErrorHandling
	set ref_function_init_Matrices = function init_Matrices
	set ref_function_init_Quaternion = function init_Quaternion
	set ref_function_init_Table = function init_Table
	set ref_function_init_Playercolor = function init_Playercolor
	set ref_function_init_Colors = function init_Colors
	set ref_function_init_Framehandle = function init_Framehandle
	set ref_function_init_Group = function init_Group
	set ref_function_init_Lightning = function init_Lightning
	set ref_function_init_WeatherEffects = function init_WeatherEffects
	set ref_function_init_TypeCasting = function init_TypeCasting
	set ref_function_init_HashList = function init_HashList
	set ref_function_init_EventHelper = function init_EventHelper
	set ref_function_init_AbilityObjEditing = function init_AbilityObjEditing
	set ref_function_init_RegisterEvents = function init_RegisterEvents
	set ref_function_init_MapBounds = function init_MapBounds
	set ref_function_init_ClosureForGroups = function init_ClosureForGroups
	set ref_function_init_LinkedList = function init_LinkedList
	set ref_function_init_ObjectIds = function init_ObjectIds
	set ref_function_init_UnitIds = function init_UnitIds
	set ref_function_init_Icons = function init_Icons
	set ref_function_init_DummyRecycler = function init_DummyRecycler
	set ref_function_init_TimerUtils = function init_TimerUtils
	set ref_function_init_ClosureTimers = function init_ClosureTimers
	set ref_function_init_Preloader = function init_Preloader
	set ref_function_init_ConstantDataSystem = function init_ConstantDataSystem
	set ref_function_init_Orders = function init_Orders
	set ref_function_init_UtilityFunctions = function init_UtilityFunctions
	set ref_function_init_UnitTest = function init_UnitTest
	set ref_function_init_Stock = function init_Stock
	set ref_function_init_ObjectIdGenerator = function init_ObjectIdGenerator
	set ref_function_init_OnUnitEnterLeave = function init_OnUnitEnterLeave
	set ref_function_init_MultiboardPrioritySystem = function init_MultiboardPrioritySystem
	set ref_function_init_UnitIndexer = function init_UnitIndexer
	set ref_function_init_StorageSystem = function init_StorageSystem
	set ref_function_init_InstantDummyCaster = function init_InstantDummyCaster
	set ref_function_init_OrderSystem = function init_OrderSystem
	set ref_function_init_Buildings = function init_Buildings
	set ref_function_init_Doodads = function init_Doodads
	set ref_function_init_Objects = function init_Objects
	set ref_function_init_Sounds = function init_Sounds
	set ref_function_init_Soundsets = function init_Soundsets
	set ref_function_init_Textures = function init_Textures
	set ref_function_init_UI = function init_UI
	set ref_function_init_Units = function init_Units
	set ref_function_init_AttachmentPoints = function init_AttachmentPoints
	set ref_function_init_UnitsPresetFunctions = function init_UnitsPresetFunctions
	set ref_function_init_Unit_TownHall = function init_Unit_TownHall
	set ref_function_init_Unit_AltarOfKings = function init_Unit_AltarOfKings
	set ref_function_init_Unit_ArcaneSanctum = function init_Unit_ArcaneSanctum
	set ref_function_init_Unit_ArcaneTower = function init_Unit_ArcaneTower
	set ref_function_init_Unit_ArcaneVault = function init_Unit_ArcaneVault
	set ref_function_init_Unit_ScoutTower = function init_Unit_ScoutTower
	set ref_function_init_Unit_LumberMill = function init_Unit_LumberMill
	set ref_function_init_Unit_Keep = function init_Unit_Keep
	set ref_function_init_Unit_Barracks = function init_Unit_Barracks
	set ref_function_init_Unit_Blacksmith = function init_Unit_Blacksmith
	set ref_function_init_Unit_CannonTower = function init_Unit_CannonTower
	set ref_function_init_Unit_Castle = function init_Unit_Castle
	set ref_function_init_Unit_GuardTower = function init_Unit_GuardTower
	set ref_function_init_BuildingSystem = function init_BuildingSystem
	set ref_function_init_ResourceSystem = function init_ResourceSystem
	set ref_function_init_Ability_Harvest = function init_Ability_Harvest
	set ref_function_init_WorkshopSystem = function init_WorkshopSystem
	set ref_function_init_PersonSystem = function init_PersonSystem
	set ref_function_init_AbilitySystem = function init_AbilitySystem
	set ref_function_init_Command_GiveWares = function init_Command_GiveWares
	set ref_function_init_Command_ShowAll = function init_Command_ShowAll
	set ref_function_init_Command_Test = function init_Command_Test
	set ref_function_init_Command_UnitTests = function init_Command_UnitTests
	set ref_function_init_ObjectInfoSystem = function init_ObjectInfoSystem
	set ref_function_init_SmartOrderSystem = function init_SmartOrderSystem
	set ref_function_init_StartupSystem = function init_StartupSystem
	set ref_function_init_TerrainUtils = function init_TerrainUtils
	set ref_function_init_WorldGenerationSystem = function init_WorldGenerationSystem
	set ref_function_code__registerPlayerUnitEvent_AbilitySystem = function code__registerPlayerUnitEvent_AbilitySystem
	set ref_function_code__registerPlayerUnitEvent_AbilitySystem_598 = function code__registerPlayerUnitEvent_AbilitySystem_600
	set ref_function_code__onUnitDeindex_BuildingSystem = function code__onUnitDeindex_BuildingSystem
	set ref_function_code__registerPlayerUnitEvent_BuildingSystem = function code__registerPlayerUnitEvent_BuildingSystem
	set ref_function_code__registerPlayerUnitEvent_BuildingSystem_600 = function code__registerPlayerUnitEvent_BuildingSystem_602
	set ref_function_code__Filter_BuildingSystem = function code__Filter_BuildingSystem
	set ref_function_code__ForGroup_BuildingSystem = function code__ForGroup_BuildingSystem
	set ref_function_code__Filter_ClosureForGroups = function code__Filter_ClosureForGroups
	set ref_function_executeCommand = function executeCommand
	set ref_function_executeCommand_619 = function executeCommand_863
	set ref_function_executeCommand_620 = function executeCommand_864
	set ref_function_executeCommand_621 = function executeCommand_865
	set ref_function_DelayNode_recycle = function DelayNode_recycle
	set ref_function_code__startPeriodic_GameTimer = function code__startPeriodic_GameTimer
	set ref_function_code__ForGroup_Group = function code__ForGroup_Group
	set ref_function_code__registerPlayerUnitEvent_ObjectInfoSystem = function code__registerPlayerUnitEvent_ObjectInfoSystem
	set ref_function_code__registerPlayerUnitEvent_ObjectInfoSystem_602 = function code__registerPlayerUnitEvent_ObjectInfoSystem_604
	set ref_function_code__onLeave_OrderSystem = function code__onLeave_OrderSystem
	set ref_function_code__registerPlayerUnitEvent_OrderSystem = function code__registerPlayerUnitEvent_OrderSystem
	set ref_function_code__registerPlayerUnitEvent_OrderSystem_604 = function code__registerPlayerUnitEvent_OrderSystem_606
	set ref_function_code__registerPlayerUnitEvent_OrderSystem_605 = function code__registerPlayerUnitEvent_OrderSystem_607
	set ref_function_code__registerPlayerUnitEvent_OrderSystem_606 = function code__registerPlayerUnitEvent_OrderSystem_608
	set ref_function_code__registerPlayerUnitEvent_OrderSystem_607 = function code__registerPlayerUnitEvent_OrderSystem_609
	set ref_function_code__registerPlayerUnitEvent_OrderSystem_608 = function code__registerPlayerUnitEvent_OrderSystem_610
	set ref_function_code__onEnter_PersonSystem = function code__onEnter_PersonSystem
	set ref_function_code__onLeave_PersonSystem = function code__onLeave_PersonSystem
	set ref_function_code__registerPlayerUnitEvent_RegisterEvents = function code__registerPlayerUnitEvent_RegisterEvents
	set ref_function_code__onEnter_ResourceSystem = function code__onEnter_ResourceSystem
	set ref_function_code__onUnitDeindex_ResourceSystem = function code__onUnitDeindex_ResourceSystem
	set ref_function_code__Filter_ResourceSystem = function code__Filter_ResourceSystem
	set ref_function_code__registerPlayerUnitEvent_SmartOrderSystem = function code__registerPlayerUnitEvent_SmartOrderSystem
	set ref_function_runStartup = function runStartup
	set ref_function_code__onEnter_StorageSystem = function code__onEnter_StorageSystem
	set ref_function_code__onLeave_StorageSystem = function code__onLeave_StorageSystem
	set ref_function_code__onEnter_UnitIndexer = function code__onEnter_UnitIndexer
	set ref_function_code__onLeave_UnitIndexer = function code__onLeave_UnitIndexer
	set ref_function_code__onEnter_WorkshopSystem = function code__onEnter_WorkshopSystem
	set ref_function_code__onUnitDeindex_WorkshopSystem = function code__onUnitDeindex_WorkshopSystem
	set ref_function_code__registerPlayerUnitEvent_WorkshopSystem = function code__registerPlayerUnitEvent_WorkshopSystem
	set ref_function_CallbackPeriodic_staticCallback = function CallbackPeriodic_staticCallback
	set ref_function_code__start_CallbackSingle_ClosureTimers = function code__start_CallbackSingle_ClosureTimers
	set ref_function_code__startPeriodic_Dataset_ObjectInfoSystem = function code__startPeriodic_Dataset_ObjectInfoSystem
	set ref_function_code__Filter_registerEnterRegion_nullTimer_OnUnitEnterLeave = function code__Filter_registerEnterRegion_nullTimer_OnUnitEnterLeave
	set ref_function_code__registerPlayerUnitEvent_nullTimer_OnUnitEnterLeave = function code__registerPlayerUnitEvent_nullTimer_OnUnitEnterLeave
	set ref_function_code__ForGroup_nullTimer_OnUnitEnterLeave = function code__ForGroup_nullTimer_OnUnitEnterLeave
	set ref_function_code__start_OrderAction_OrderSystem = function code__start_OrderAction_OrderSystem
	set ref_function_code__startPeriodic_OrderAction_OrderSystem = function code__startPeriodic_OrderAction_OrderSystem
endfunction

function main takes nothing returns nothing
	local trigger initTrig
	call initGlobals()
	call initCompiletimeState()
	call SetCameraBounds(( - 6912.0) + GetCameraMargin(CAMERA_MARGIN_LEFT), ( - 8192.0) + GetCameraMargin(CAMERA_MARGIN_BOTTOM), 7936.0 - GetCameraMargin(CAMERA_MARGIN_RIGHT), 6656.0 - GetCameraMargin(CAMERA_MARGIN_TOP), ( - 6912.0) + GetCameraMargin(CAMERA_MARGIN_LEFT), 6656.0 - GetCameraMargin(CAMERA_MARGIN_TOP), 7936.0 - GetCameraMargin(CAMERA_MARGIN_RIGHT), ( - 8192.0) + GetCameraMargin(CAMERA_MARGIN_BOTTOM))
	call SetDayNightModels("Environment\\DNC\\DNCLordaeron\\DNCLordaeronTerrain\\DNCLordaeronTerrain.mdl", "Environment\\DNC\\DNCLordaeron\\DNCLordaeronUnit\\DNCLordaeronUnit.mdl")
	call SetTerrainFogEx(0, 3000.0, 5000.0, 0.500, 0.235, 0.376, 0.627)
	call NewSoundEnvironment("Default")
	call SetAmbientDaySound("LordaeronSummerDay")
	call SetAmbientNightSound("LordaeronSummerNight")
	call SetMapMusic("Music", true, 0)
	call InitBlizzard()
	call InitGlobals()
	set initTrig = CreateTrigger()
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Abilities))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Abilities.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_AbilityIds))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package AbilityIds.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Real))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Real.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Integer))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Integer.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_BitSet))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package BitSet.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_String))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package String.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_TargetsAllowed))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package TargetsAllowed.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Angle))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Angle.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Vectors))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Vectors.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Player))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Player.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Destructable))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Destructable.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Maths))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Maths.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Printing))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Printing.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_MagicFunctions))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package MagicFunctions.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Basics))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Basics.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_GameTimer))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package GameTimer.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_ErrorHandling))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package ErrorHandling.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Matrices))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Matrices.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Quaternion))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Quaternion.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Table))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Table.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Playercolor))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Playercolor.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Colors))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Colors.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Framehandle))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Framehandle.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Group))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Group.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Lightning))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Lightning.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_WeatherEffects))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package WeatherEffects.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_TypeCasting))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package TypeCasting.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_HashList))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package HashList.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_EventHelper))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package EventHelper.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_AbilityObjEditing))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package AbilityObjEditing.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_RegisterEvents))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package RegisterEvents.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_MapBounds))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package MapBounds.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_ClosureForGroups))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package ClosureForGroups.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_LinkedList))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package LinkedList.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_ObjectIds))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package ObjectIds.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_UnitIds))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package UnitIds.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Icons))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Icons.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_DummyRecycler))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package DummyRecycler.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_TimerUtils))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package TimerUtils.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_ClosureTimers))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package ClosureTimers.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Preloader))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Preloader.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_ConstantDataSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package ConstantDataSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Orders))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Orders.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_UtilityFunctions))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package UtilityFunctions.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_UnitTest))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package UnitTest.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Stock))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Stock.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_ObjectIdGenerator))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package ObjectIdGenerator.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_OnUnitEnterLeave))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package OnUnitEnterLeave.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_MultiboardPrioritySystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package MultiboardPrioritySystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_UnitIndexer))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package UnitIndexer.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_StorageSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package StorageSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_InstantDummyCaster))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package InstantDummyCaster.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_OrderSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package OrderSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Buildings))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Buildings.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Doodads))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Doodads.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Objects))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Objects.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Sounds))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Sounds.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Soundsets))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Soundsets.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Textures))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Textures.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_UI))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package UI.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Units))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Units.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_AttachmentPoints))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package AttachmentPoints.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_UnitsPresetFunctions))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package UnitsPresetFunctions.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_TownHall))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_TownHall.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_AltarOfKings))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_AltarOfKings.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_ArcaneSanctum))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_ArcaneSanctum.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_ArcaneTower))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_ArcaneTower.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_ArcaneVault))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_ArcaneVault.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_ScoutTower))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_ScoutTower.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_LumberMill))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_LumberMill.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_Keep))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_Keep.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_Barracks))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_Barracks.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_Blacksmith))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_Blacksmith.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_CannonTower))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_CannonTower.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_Castle))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_Castle.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Unit_GuardTower))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Unit_GuardTower.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_BuildingSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package BuildingSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_ResourceSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package ResourceSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Ability_Harvest))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Ability_Harvest.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_WorkshopSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package WorkshopSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_PersonSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package PersonSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_AbilitySystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package AbilitySystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Command_GiveWares))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Command_GiveWares.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Command_ShowAll))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Command_ShowAll.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Command_Test))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Command_Test.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_Command_UnitTests))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package Command_UnitTests.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_ObjectInfoSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package ObjectInfoSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_SmartOrderSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package SmartOrderSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_StartupSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package StartupSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_TerrainUtils))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package TerrainUtils.")
	endif
	call TriggerClearConditions(initTrig)
	call TriggerAddCondition(initTrig, Condition(ref_function_init_WorldGenerationSystem))
	if  not TriggerEvaluate(initTrig) then
		call error("Could not initialize package WorldGenerationSystem.")
	endif
	call TriggerClearConditions(initTrig)
	call DestroyTrigger(initTrig)
	set initTrig = null
endfunction

function InitAllyPriorities takes nothing returns nothing
	call SetStartLocPrioCount(0, 7)
	call SetStartLocPrio(0, 0, 6, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(0, 1, 8, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(0, 2, 10, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(0, 3, 11, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(0, 4, 12, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(0, 5, 14, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(0, 6, 17, MAP_LOC_PRIO_LOW)
	call SetStartLocPrioCount(1, 4)
	call SetStartLocPrio(1, 0, 2, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(1, 1, 5, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(1, 2, 11, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(1, 3, 16, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(2, 1)
	call SetStartLocPrio(2, 0, 16, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(3, 2)
	call SetStartLocPrio(3, 0, 5, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(3, 1, 13, MAP_LOC_PRIO_LOW)
	call SetStartLocPrioCount(4, 9)
	call SetStartLocPrio(4, 0, 0, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(4, 1, 6, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(4, 2, 9, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(4, 3, 10, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(4, 4, 11, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(4, 5, 12, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(4, 6, 14, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(4, 7, 15, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(4, 8, 17, MAP_LOC_PRIO_LOW)
	call SetStartLocPrioCount(5, 2)
	call SetStartLocPrio(5, 0, 3, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(5, 1, 13, MAP_LOC_PRIO_LOW)
	call SetStartLocPrioCount(6, 2)
	call SetStartLocPrio(6, 0, 12, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(6, 1, 14, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(7, 3)
	call SetStartLocPrio(7, 0, 2, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(7, 1, 8, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(7, 2, 16, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(8, 1)
	call SetStartLocPrio(8, 0, 17, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(9, 2)
	call SetStartLocPrio(9, 0, 10, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(9, 1, 15, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(10, 3)
	call SetStartLocPrio(10, 0, 9, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(10, 1, 12, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(10, 2, 14, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(11, 3)
	call SetStartLocPrio(11, 0, 1, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(11, 1, 9, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(11, 2, 10, MAP_LOC_PRIO_LOW)
	call SetStartLocPrioCount(12, 1)
	call SetStartLocPrio(12, 0, 14, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(13, 2)
	call SetStartLocPrio(13, 0, 3, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(13, 1, 5, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(14, 1)
	call SetStartLocPrio(14, 0, 12, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(15, 1)
	call SetStartLocPrio(15, 0, 9, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(16, 1)
	call SetStartLocPrio(16, 0, 2, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(17, 1)
	call SetStartLocPrio(17, 0, 8, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(18, 9)
	call SetStartLocPrio(18, 0, 4, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(18, 1, 5, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(18, 2, 6, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(18, 3, 9, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(18, 4, 11, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(18, 5, 13, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(18, 6, 16, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(18, 7, 17, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(18, 8, 20, MAP_LOC_PRIO_HIGH)
	call SetEnemyStartLocPrioCount(18, 8)
	call SetEnemyStartLocPrio(18, 0, 1, MAP_LOC_PRIO_LOW)
	call SetEnemyStartLocPrio(18, 1, 4, MAP_LOC_PRIO_LOW)
	call SetEnemyStartLocPrio(18, 2, 5, MAP_LOC_PRIO_LOW)
	call SetEnemyStartLocPrio(18, 3, 6, MAP_LOC_PRIO_HIGH)
	call SetEnemyStartLocPrio(18, 4, 8, MAP_LOC_PRIO_HIGH)
	call SetEnemyStartLocPrio(18, 5, 9, MAP_LOC_PRIO_LOW)
	call SetEnemyStartLocPrio(18, 6, 16, MAP_LOC_PRIO_HIGH)
	call SetEnemyStartLocPrio(18, 7, 20, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrioCount(19, 12)
	call SetStartLocPrio(19, 0, 1, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(19, 1, 4, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(19, 2, 5, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 3, 6, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 4, 8, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 5, 9, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 6, 10, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 7, 11, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 8, 14, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 9, 17, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 10, 18, MAP_LOC_PRIO_LOW)
	call SetStartLocPrio(19, 11, 20, MAP_LOC_PRIO_LOW)
	call SetStartLocPrioCount(20, 10)
	call SetStartLocPrio(20, 0, 4, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(20, 1, 5, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(20, 2, 8, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(20, 3, 11, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(20, 4, 13, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(20, 5, 14, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(20, 6, 15, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(20, 7, 16, MAP_LOC_PRIO_HIGH)
	call SetStartLocPrio(20, 8, 18, MAP_LOC_PRIO_HIGH)
	call SetEnemyStartLocPrioCount(20, 4)
	call SetEnemyStartLocPrio(20, 0, 0, MAP_LOC_PRIO_LOW)
	call SetEnemyStartLocPrio(20, 1, 4, MAP_LOC_PRIO_LOW)
	call SetEnemyStartLocPrio(20, 2, 5, MAP_LOC_PRIO_LOW)
	call SetEnemyStartLocPrio(20, 3, 9, MAP_LOC_PRIO_LOW)
endfunction

function InitCustomPlayerSlots takes nothing returns nothing
	call SetPlayerStartLocation(Player(0), 0)
	call ForcePlayerStartLocation(Player(0), 0)
	call SetPlayerColor(Player(0), ConvertPlayerColor(0))
	call SetPlayerRacePreference(Player(0), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(0), false)
	call SetPlayerController(Player(0), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(1), 1)
	call ForcePlayerStartLocation(Player(1), 1)
	call SetPlayerColor(Player(1), ConvertPlayerColor(1))
	call SetPlayerRacePreference(Player(1), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(1), false)
	call SetPlayerController(Player(1), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(2), 2)
	call ForcePlayerStartLocation(Player(2), 2)
	call SetPlayerColor(Player(2), ConvertPlayerColor(2))
	call SetPlayerRacePreference(Player(2), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(2), false)
	call SetPlayerController(Player(2), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(3), 3)
	call ForcePlayerStartLocation(Player(3), 3)
	call SetPlayerColor(Player(3), ConvertPlayerColor(3))
	call SetPlayerRacePreference(Player(3), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(3), false)
	call SetPlayerController(Player(3), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(4), 4)
	call ForcePlayerStartLocation(Player(4), 4)
	call SetPlayerColor(Player(4), ConvertPlayerColor(4))
	call SetPlayerRacePreference(Player(4), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(4), false)
	call SetPlayerController(Player(4), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(5), 5)
	call ForcePlayerStartLocation(Player(5), 5)
	call SetPlayerColor(Player(5), ConvertPlayerColor(5))
	call SetPlayerRacePreference(Player(5), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(5), false)
	call SetPlayerController(Player(5), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(6), 6)
	call ForcePlayerStartLocation(Player(6), 6)
	call SetPlayerColor(Player(6), ConvertPlayerColor(6))
	call SetPlayerRacePreference(Player(6), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(6), false)
	call SetPlayerController(Player(6), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(7), 7)
	call ForcePlayerStartLocation(Player(7), 7)
	call SetPlayerColor(Player(7), ConvertPlayerColor(7))
	call SetPlayerRacePreference(Player(7), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(7), false)
	call SetPlayerController(Player(7), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(8), 8)
	call ForcePlayerStartLocation(Player(8), 8)
	call SetPlayerColor(Player(8), ConvertPlayerColor(8))
	call SetPlayerRacePreference(Player(8), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(8), false)
	call SetPlayerController(Player(8), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(9), 9)
	call ForcePlayerStartLocation(Player(9), 9)
	call SetPlayerColor(Player(9), ConvertPlayerColor(9))
	call SetPlayerRacePreference(Player(9), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(9), false)
	call SetPlayerController(Player(9), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(10), 10)
	call ForcePlayerStartLocation(Player(10), 10)
	call SetPlayerColor(Player(10), ConvertPlayerColor(10))
	call SetPlayerRacePreference(Player(10), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(10), false)
	call SetPlayerController(Player(10), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(11), 11)
	call ForcePlayerStartLocation(Player(11), 11)
	call SetPlayerColor(Player(11), ConvertPlayerColor(11))
	call SetPlayerRacePreference(Player(11), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(11), false)
	call SetPlayerController(Player(11), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(12), 12)
	call ForcePlayerStartLocation(Player(12), 12)
	call SetPlayerColor(Player(12), ConvertPlayerColor(12))
	call SetPlayerRacePreference(Player(12), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(12), false)
	call SetPlayerController(Player(12), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(13), 13)
	call ForcePlayerStartLocation(Player(13), 13)
	call SetPlayerColor(Player(13), ConvertPlayerColor(13))
	call SetPlayerRacePreference(Player(13), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(13), false)
	call SetPlayerController(Player(13), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(14), 14)
	call ForcePlayerStartLocation(Player(14), 14)
	call SetPlayerColor(Player(14), ConvertPlayerColor(14))
	call SetPlayerRacePreference(Player(14), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(14), false)
	call SetPlayerController(Player(14), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(15), 15)
	call ForcePlayerStartLocation(Player(15), 15)
	call SetPlayerColor(Player(15), ConvertPlayerColor(15))
	call SetPlayerRacePreference(Player(15), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(15), false)
	call SetPlayerController(Player(15), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(16), 16)
	call ForcePlayerStartLocation(Player(16), 16)
	call SetPlayerColor(Player(16), ConvertPlayerColor(16))
	call SetPlayerRacePreference(Player(16), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(16), false)
	call SetPlayerController(Player(16), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(17), 17)
	call ForcePlayerStartLocation(Player(17), 17)
	call SetPlayerColor(Player(17), ConvertPlayerColor(17))
	call SetPlayerRacePreference(Player(17), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(17), false)
	call SetPlayerController(Player(17), MAP_CONTROL_USER)
	call SetPlayerStartLocation(Player(21), 18)
	call ForcePlayerStartLocation(Player(21), 18)
	call SetPlayerColor(Player(21), ConvertPlayerColor(21))
	call SetPlayerRacePreference(Player(21), RACE_PREF_HUMAN)
	call SetPlayerRaceSelectable(Player(21), false)
	call SetPlayerController(Player(21), MAP_CONTROL_COMPUTER)
	call SetPlayerStartLocation(Player(22), 19)
	call ForcePlayerStartLocation(Player(22), 19)
	call SetPlayerColor(Player(22), ConvertPlayerColor(22))
	call SetPlayerRacePreference(Player(22), RACE_PREF_ORC)
	call SetPlayerRaceSelectable(Player(22), false)
	call SetPlayerController(Player(22), MAP_CONTROL_COMPUTER)
	call SetPlayerStartLocation(Player(23), 20)
	call ForcePlayerStartLocation(Player(23), 20)
	call SetPlayerColor(Player(23), ConvertPlayerColor(23))
	call SetPlayerRacePreference(Player(23), RACE_PREF_UNDEAD)
	call SetPlayerRaceSelectable(Player(23), false)
	call SetPlayerController(Player(23), MAP_CONTROL_COMPUTER)
endfunction

function InitCustomTeams takes nothing returns nothing
	call SetPlayerTeam(Player(0), 0)
	call SetPlayerState(Player(0), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(1), 0)
	call SetPlayerState(Player(1), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(2), 0)
	call SetPlayerState(Player(2), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(3), 0)
	call SetPlayerState(Player(3), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerAllianceStateAllyBJ(Player(0), Player(1), true)
	call SetPlayerAllianceStateAllyBJ(Player(0), Player(2), true)
	call SetPlayerAllianceStateAllyBJ(Player(0), Player(3), true)
	call SetPlayerAllianceStateAllyBJ(Player(1), Player(0), true)
	call SetPlayerAllianceStateAllyBJ(Player(1), Player(2), true)
	call SetPlayerAllianceStateAllyBJ(Player(1), Player(3), true)
	call SetPlayerAllianceStateAllyBJ(Player(2), Player(0), true)
	call SetPlayerAllianceStateAllyBJ(Player(2), Player(1), true)
	call SetPlayerAllianceStateAllyBJ(Player(2), Player(3), true)
	call SetPlayerAllianceStateAllyBJ(Player(3), Player(0), true)
	call SetPlayerAllianceStateAllyBJ(Player(3), Player(1), true)
	call SetPlayerAllianceStateAllyBJ(Player(3), Player(2), true)
	call SetPlayerAllianceStateVisionBJ(Player(0), Player(1), true)
	call SetPlayerAllianceStateVisionBJ(Player(0), Player(2), true)
	call SetPlayerAllianceStateVisionBJ(Player(0), Player(3), true)
	call SetPlayerAllianceStateVisionBJ(Player(1), Player(0), true)
	call SetPlayerAllianceStateVisionBJ(Player(1), Player(2), true)
	call SetPlayerAllianceStateVisionBJ(Player(1), Player(3), true)
	call SetPlayerAllianceStateVisionBJ(Player(2), Player(0), true)
	call SetPlayerAllianceStateVisionBJ(Player(2), Player(1), true)
	call SetPlayerAllianceStateVisionBJ(Player(2), Player(3), true)
	call SetPlayerAllianceStateVisionBJ(Player(3), Player(0), true)
	call SetPlayerAllianceStateVisionBJ(Player(3), Player(1), true)
	call SetPlayerAllianceStateVisionBJ(Player(3), Player(2), true)
	call SetPlayerTeam(Player(4), 1)
	call SetPlayerState(Player(4), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(5), 1)
	call SetPlayerState(Player(5), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(6), 1)
	call SetPlayerState(Player(6), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(7), 1)
	call SetPlayerState(Player(7), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerAllianceStateAllyBJ(Player(4), Player(5), true)
	call SetPlayerAllianceStateAllyBJ(Player(4), Player(6), true)
	call SetPlayerAllianceStateAllyBJ(Player(4), Player(7), true)
	call SetPlayerAllianceStateAllyBJ(Player(5), Player(4), true)
	call SetPlayerAllianceStateAllyBJ(Player(5), Player(6), true)
	call SetPlayerAllianceStateAllyBJ(Player(5), Player(7), true)
	call SetPlayerAllianceStateAllyBJ(Player(6), Player(4), true)
	call SetPlayerAllianceStateAllyBJ(Player(6), Player(5), true)
	call SetPlayerAllianceStateAllyBJ(Player(6), Player(7), true)
	call SetPlayerAllianceStateAllyBJ(Player(7), Player(4), true)
	call SetPlayerAllianceStateAllyBJ(Player(7), Player(5), true)
	call SetPlayerAllianceStateAllyBJ(Player(7), Player(6), true)
	call SetPlayerAllianceStateVisionBJ(Player(4), Player(5), true)
	call SetPlayerAllianceStateVisionBJ(Player(4), Player(6), true)
	call SetPlayerAllianceStateVisionBJ(Player(4), Player(7), true)
	call SetPlayerAllianceStateVisionBJ(Player(5), Player(4), true)
	call SetPlayerAllianceStateVisionBJ(Player(5), Player(6), true)
	call SetPlayerAllianceStateVisionBJ(Player(5), Player(7), true)
	call SetPlayerAllianceStateVisionBJ(Player(6), Player(4), true)
	call SetPlayerAllianceStateVisionBJ(Player(6), Player(5), true)
	call SetPlayerAllianceStateVisionBJ(Player(6), Player(7), true)
	call SetPlayerAllianceStateVisionBJ(Player(7), Player(4), true)
	call SetPlayerAllianceStateVisionBJ(Player(7), Player(5), true)
	call SetPlayerAllianceStateVisionBJ(Player(7), Player(6), true)
	call SetPlayerTeam(Player(8), 2)
	call SetPlayerState(Player(8), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(9), 2)
	call SetPlayerState(Player(9), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(10), 2)
	call SetPlayerState(Player(10), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerTeam(Player(11), 2)
	call SetPlayerState(Player(11), PLAYER_STATE_ALLIED_VICTORY, 1)
	call SetPlayerAllianceStateAllyBJ(Player(8), Player(9), true)
	call SetPlayerAllianceStateAllyBJ(Player(8), Player(10), true)
	call SetPlayerAllianceStateAllyBJ(Player(8), Player(11), true)
	call SetPlayerAllianceStateAllyBJ(Player(9), Player(8), true)
	call SetPlayerAllianceStateAllyBJ(Player(9), Player(10), true)
	call SetPlayerAllianceStateAllyBJ(Player(9), Player(11), true)
	call SetPlayerAllianceStateAllyBJ(Player(10), Player(8), true)
	call SetPlayerAllianceStateAllyBJ(Player(10), Player(9), true)
	call SetPlayerAllianceStateAllyBJ(Player(10), Player(11), true)
	call SetPlayerAllianceStateAllyBJ(Player(11), Player(8), true)
	call SetPlayerAllianceStateAllyBJ(Player(11), Player(9), true)
	call SetPlayerAllianceStateAllyBJ(Player(11), Player(10), true)
	call SetPlayerAllianceStateVisionBJ(Player(8), Player(9), true)
	call SetPlayerAllianceStateVisionBJ(Player(8), Player(10), true)
	call SetPlayerAllianceStateVisionBJ(Player(8), Player(11), true)
	call SetPlayerAllianceStateVisionBJ(Player(9), Player(8), true)
	call SetPlayerAllianceStateVisionBJ(Player(9), Player(10), true)
	call SetPlayerAllianceStateVisionBJ(Player(9), Player(11), true)
	call SetPlayerAllianceStateVisionBJ(Player(10), Player(8), true)
	call SetPlayerAllianceStateVisionBJ(Player(10), Player(9), true)
	call SetPlayerAllianceStateVisionBJ(Player(10), Player(11), true)
	call SetPlayerAllianceStateVisionBJ(Player(11), Player(8), true)
	call SetPlayerAllianceStateVisionBJ(Player(11), Player(9), true)
	call SetPlayerAllianceStateVisionBJ(Player(11), Player(10), true)
	call SetPlayerTeam(Player(12), 3)
	call SetPlayerTeam(Player(13), 3)
	call SetPlayerTeam(Player(14), 3)
	call SetPlayerTeam(Player(15), 3)
	call SetPlayerTeam(Player(16), 3)
	call SetPlayerTeam(Player(17), 3)
	call SetPlayerTeam(Player(21), 4)
	call SetPlayerTeam(Player(22), 4)
	call SetPlayerTeam(Player(23), 4)
endfunction

function config takes nothing returns nothing
	call SetMapName("TRIGSTR_001")
	call SetMapDescription("TRIGSTR_003")
	call SetPlayers(21)
	call SetTeams(21)
	call SetGamePlacement(MAP_PLACEMENT_TEAMS_TOGETHER)
	call DefineStartLocation(0, 128.0, 0.0)
	call DefineStartLocation(1,  - 1152.0,  - 5888.0)
	call DefineStartLocation(2, 1472.0,  - 5824.0)
	call DefineStartLocation(3,  - 4352.0,  - 6528.0)
	call DefineStartLocation(4,  - 6272.0, 4864.0)
	call DefineStartLocation(5,  - 3136.0,  - 7168.0)
	call DefineStartLocation(6,  - 3008.0,  - 1216.0)
	call DefineStartLocation(7, 4736.0,  - 4032.0)
	call DefineStartLocation(8, 4800.0, 1152.0)
	call DefineStartLocation(9,  - 4352.0,  - 4032.0)
	call DefineStartLocation(10,  - 3840.0,  - 2688.0)
	call DefineStartLocation(11,  - 2112.0,  - 4352.0)
	call DefineStartLocation(12,  - 3520.0,  - 1408.0)
	call DefineStartLocation(13,  - 4480.0,  - 8448.0)
	call DefineStartLocation(14,  - 3392.0,  - 1664.0)
	call DefineStartLocation(15,  - 5440.0,  - 3776.0)
	call DefineStartLocation(16, 576.0,  - 5056.0)
	call DefineStartLocation(17, 3520.0, 3136.0)
	call DefineStartLocation(18,  - 6720.0, 1920.0)
	call DefineStartLocation(19, 6848.0,  - 3648.0)
	call DefineStartLocation(20, 4800.0,  - 896.0)
	call InitCustomPlayerSlots()
	call InitCustomTeams()
	call InitAllyPriorities()
endfunction

