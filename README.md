# Zomboid
Burning cherry Project Zomboid Server Settings

The settings are found in 2 files, Burningcherry.ini and Burningcherry_SandboxVars.lua



Below is the Default settings of these two files along with info about what the settings mean if needed:

    Zombies = 4, (How many zombies when the server starts, 1 is insane amount, 5 is none)
    Distribution = 1, (Where the zombies gravitate to, 1 is urban (in cities), 2 is uniform (everywhere))
    DayLength = 3, (1 is 15 minutes, 2 is 30 minutes, 3 is 1 hour, 4 is 2 hours, 5 is 3 hours, 6 is 4 hours, 7 is 5 hours, 8 is 12 hours, 9 is real-time)
    StartYear = 1, (1 is the 1st year etc)
    StartMonth = 4, (1 is Jan, 12 is Dec)
    StartDay = 1, (1 is the 1st of the month etc)
    StartTime = 2, (1 is 7AM, 2 is 9AM, 3 is 12PM, 4 is 2PM, 5 is 5PM, 6 is 9PM, 7 is 12AM, 8 is 2AM, 9 is 5AM)
    WaterShut = 7, (1=instant, 2=0-30days, 3=0-2month, 4=0-6month, 5=0-1years, 6=0-5years, 7=2-6month, 7=6-12month)
    ElecShut = 7, (1=instant, 2=0-30days, 3=0-2month, 4=0-6month, 5=0-1years, 6=0-5years, 7=2-6month, 7=6-12month)
    WaterShutModifier = 500, (the number of days before water is shut off -1 mean instant)
    ElecShutModifier = 480, (the number of days before electricity is shut off -1 mean instant)
    FoodLoot = 4, (1 is extremely rare, 5 is abundant)
    WeaponLoot = 2, (1 is extremely rare, 5 is abundant)
    OtherLoot = 3, (1 is extremely rare, 5 is abundant)
    Temperature = 3, (1 is very cold, 5 is very hot)
    Rain = 3, (How often it rains, 1 is very dry, 5 is is very rainy)
    ErosionSpeed = 5, (How fast erosion occurs, 1 is very fast (20 days), 5 is very slow (500 days))
    XpMultiplier = 15.0, (Obvious)
    Farming = 1, (How fast crops grow, 1 is very fast, 5 is very slow)

    CompostTime = 1 Determines how long it will take for food to decay in a composter. (1Week=1 2Weeks=2 3Weeks=3 4Weeks=4 6Weeks=5 8Weeks=6 10Weeks=7 12Weeks=8)
    StatsDecrease = 4, (How fast Stats Decrease when not being used, 1 is very fast, 5 is very slow)
    NatureAbundance = 3, (1 is very poor, 5 is very abundant)
    Alarm = 6, (How often houses are alarmed, 1 is never, 6 is very often)
    LockedHouses = 6, (How often houses are locked, 1 is never, 6 is very often)
    StarterKit = false, (To start with some basic essentials)
    Nutrition = false, (To enable the Nutrition system, calorie intake etc)
    FoodRotSpeed = 5, (How fast food rots, 1 is very fast, 5 is very slow)
    FridgeFactor = 5, (How effective refrigeration is, 1 is very low, 5 is very high)
    LootRespawn = 3, (How often loot respawns, 1 is none, 2 is every day, 3 is every week, 4 is every month, 5 is every two months)

    SeenHoursPreventLootRespawn = 0 This value is an integer defining the number of hours. When >0, loot will not respawn in zones that have been visited within this number of hours. [Default=0]
    TimeSinceApo = 1, (How many days since the start of the Apocalypse)
    PlantResilience = 3, (Plants resilience against disease/weather. 1 is very low, 5 is very high)
    PlantAbundance = 3, (How much farm plants produce. 1 is very poor, 5 is very abundant)
    EndRegen = 3, (Endurance regeneration (how fast you regain endurance). 1 is very fast, 5 is very slow)
    Helicopter = 3, (how regularly helicopters pass over the event zone. 1=never, 2 =once, 3=sometimes, 4=often)

    MetaEvent = 2, (how often zombie attacking meta-game events like distant gunshots will occur. 1=never, 2=sometimes, 3=often)

    SleepingEvent = 2, (governs night-time meta-game events during the player's sleep. 1=never, 2=sometimes, 3=often)

    GeneratorSpawning = 3, (increase/decrease the chance of electrical generators spawning on the map. 1=very low, 2=low, 3=normal, 4=high, 5=very high)
    GeneratorFuelConsumption = 1.0, (impacts how much fuel is consumed by generators. No fuel required= 0 . Minimum = 0, Maximum=100)
    SurvivorHouseChance = 3, (increase/decrease probability of discovering randomized safe houses on the map: either burnt out, containing loot stashes, dead survivor bodies etc. 1=never, 2=extremly rare, 3=rare, 4=sometimes, 5=often, 6=very often) 
    AnnotatedMapChance = 4, (impacts on how often a looted map will have annotations marked on it by deceased survivors. 1=never, 2=extremely rare, 3=rare, 4=sometimes, 5=often, 6=very often)
    CharacterFreePoints = 10, (adds free traits points during character creation)
    ConstructionBonusPoints = 3, (Player-built construction strength. 1=very low, 2=low, 3=normal, 4=high, 5=very high)
    NightDarkness = 2, (Darkness during night. 1=pitch black, 2=dark, 3=normal, 4=bright)
    InjurySeverity = 2, (increases and decreases the impact injuries on your body, and their healing time. 1=low, 2=normal, 3=high)
    BoneFracture = true, (False=no fractures, true=bones can break)
    HoursForCorpseRemoval = 72, (number of in-game hours before zombies corpses are automatically removed from the map)
    DecayingCorpseHealthImpact = 3, (governs impact that nearby decaying bodies has on the player's health and emotions. 1=none 2=low, 3=normal, 4=high)
    BloodLevel = 4, (how much blood spatter when getting injured or killing zombies. will 1=none 2=low, 3=normal, 4=high, 5=ultra gore)
    ClothingDegradation = 2, (governs how quickly clothing degrades, becomes dirty and bloodied. 1=disabled, 2=slow, 3=normal, 4=fast)
    FireSpread = false, (fire can spread or not. false=off, true=on)
    DaysForRottenFoodRemoval = 4, (number of in game days before rotten food is removed from the map. -1 means that rotten food is never removed.)

    AllowExteriorGenerator = true This allows generators to power exterior tiles, and for example can get gas pumps working after the electricity has turned off. (True or False)

    ZombieAttractionMultiplier = 1 Use this to multiply or reduce engine general loudness. [Minimum=0] [Maximum=100] [Default=1]

    CarSpawnRate = 2 (Low=1 Normal=2 High=3)

    ChanceHasGas = 1 Governs the chances of finding vehicles with gas in the tank. (Low=1 Normal=2 High=3)

    InitialGas = 2 Governs how full gas tanks will be in discovered cars. (VeryLow=1 Low=2 Normal=3 High=4 VeryHigh=5 Full=6)

    CarGasConsumption = 1.0 The rate in which vehicles will consume fuel. [Minimum=0.0] [Maximum=100] [Default=1.0].

    LockedCar = 4 How frequent the doors of a vehicle will be locked. (Never=1 ExtremelyRare=2 Rare=3 Sometimes=4 Often=5 VeryOften=6)

    CarGeneralCondition = 2 In what condition new cars will spawn. (VeryLow=1 Low=2 Normal=3 High=4 VeryHigh=5)

    CarDamageOnImpact = 3 Governs how much damage a vehicle will take after collisions. (VeryLow=1 Low=2 Normal=3 High=4 VeryHigh=5)

    TrafficJam = true Enable or disable traffic jams that spawn on the main roads of the map. (True or False)

    CarAlarm =  4 The frequency in which a car alarm will be triggered when opening a door. This will attract zombies to the vehicle's position. (Never=1 ExtremelyRare=2 Rare=3 Sometimes=4 Often=5 VeryOften=6)

    PlayerDamageFromCrash = true Enable or disable player getting damage from being in a car accident. (True or False)

    SirenShutoffHours = 1 Number of hours before the siren sound of a car alarm will stop playing. 0.0 means it will play until the car battery is dead. [Minimum=0] [Maximum=168] [Default=0] 

    RecentlySurvivorVehicles = 1 Governs whether the player can discover a car that has been maintained and cared for after the infection struck, i.e. is still in working order. (Low=1 Normal=2 High=3)

    EnableVehicles = true Enable or disable vehicles from spawning into the game. (True or False)

    VehicleEasyUse = false If true, cars will all be unlocked with a full gas tank and low engine loudness. (True or False)

    ZombieLore = {
        Speed = 3, (1 is sprinters (fastest), 2 is fast shamblers, 3 is shamblers (slowest))
        Strength = 3, (1 is superhuman, 2 is normal, 3 is weak)
        Toughness = 3, (1 is tough, 2 is normal, 3 is fragile)
        Transmission = 1, (1 is blood/saliva, 2 is everyone is infected, 3 is no transmission)
        Mortality = 6, (This governs how deadly infection is. 1 is instant, 6 is 1 to 2 weeks)
        Reanimate = 1, (How fast zombies come back to life...again. 1 is instant, 6 is 1 to 2 weeks)
        Cognition = 3, (How smart zombies are. 1 is Navigate/Use Doors, 3 is basic navigation only)
        Memory = 2, (How much zombies will remember. 1 is long, 4 is none)
        Decomp = 1, (1 is slows/weakens them, 4 is no effect)
        Sight = 2, (How well zombies can see. 1 is eagle-eyed, 3 is poor)
        Hearing = 2, (How well zombies can hear. 1 is pinpoint, 3 is poor)
        Smell = 2, (How well zombies can smell. 1 is bloodhound, 3 is poor)
        ThumpNoChasing = false, (environmental attacks. zombies that have not seen/heard a player can attack doors and constructions while roaming. true=on, false=off)
        ThumpOnConstruction = true, (damage construction. governs whether or not zombies can destroy player constructions and defences. true=on, false=off)
        ActiveOnly = 1, (governs whether zombies are more active during the day, or whether they act more nocturnally. Inactive zombies will be slower and tend not to give a chase. 1=both, 2=night, 3=day)

        TriggerHouseAlarm = true Allows zombies to trigger house alarms when breaking through windows and doors. Enabling this option will cause zombies to constantly be movie around populated areas, making the early game much more difficult. (True or False)
    },
    ZombieConfig = {
        PopulationMultiplier = 0.5, (Depends on "Zombies" in the SandboxVars. population multiplier: (old var. "zombie intensity") set how many zombies you want to begin with) Minimum=0,Maximum=4,Default=1)
        PopulationStartMultiplier = 1.0, (Adjusts the desired population at the start of the game. it's a start multiplier: how much of the "population multiplier" you want at game start (it will slowly increase) Minimum=0,Maximum=4,Default=1)
        PopulationPeakMultiplier = 2.0, (Adjusts the desired population on the peak day. Set how many zombies you want at X days (and forever after) Minimum=0,Maximum=4,Default=1)
        PopulationPeakDay = 100, (The day when the population reaches it's peak. Minimum=1, Maximum=365, Default=28)
        RespawnHours = 96, (The number of in-game hours that must pass before zombies may respawn in a cell. If zero spawning is disabled. Minimum=0, Maximum=8760, Default=72)
        RespawnUnseenHours = 10, (The number of in-game hours that a chunk must be unseen before zombies may re-spawn in it. Minimum=0, Maximum=8760, Default=16)
        RespawnMultiplier = 0.1, (The fraction of a cells desired population that may re-spawn every RespawnHours. Minimum=0, Maximum=1, Default=0.1)
        RedistributeHours = 12.0, (The number of in-game hours that must pass before zombies migrate to empty parts of the same cell. If zero, migration is disabled. Minimum=0, Maximum=8760, Default=12)
        FollowSoundDistance = 200, (The distance a virtual zombie will try to walk towards the last sound it heard. Minimum=10, Maximum=1000, Default=100)
        RallyGroupSize = 20, (The size of groups real zombies form when idle. Zero means zombies don't form groups. Groups don't form inside buildings or forest zones. Minimum=5, Maximum=1000, Default=20)
        RallyTravelDistance = 30, (The distance real zombies travel to from groups when idle. Minimum=5, Maximum=50, Default=20)
        RallyGroupSeparation = 15, (The distance between zombie groups. Minimum=5, Maximum=25, Default=15)
        RallyGroupRadius = 4, (How close members of a group stay to the group's leader. Minimum=1, Maximum=10, Default=3) 


Burningcherry.ini file:

    nightlengthmodifier=1.0 (controls how dark nightime is. 1.0=normal darkness, 0.0=bright)
    PVP=true (Enable PVP. tue=on, false=off)
    PauseEmpty=false (true=the server won't update if no players are on it (farming won't progress, etc., false=server time will run all time on)
    GlobalChat=true (enable the Global Chat (/all command in chat). tue=chat on, false=chat off)
    Open=true (server is open to all (no whitelist), tue=server open to all, false=players have to bee added to the whitelist)
    ServerWelcomeMessage= <RGB:1,0,0> Welcome to Project Zomboid MP ! to chat locally press 't', to global chat press 'y' or add '/all' before chatting <LINE> Type '/help' to have a list of available commands <LINE> <RGB:1,1,1> (Message that is displayed when joining the server)
    LogLocalChat=false (display local chat in the chat panel(only players nearby can see it), tue=on, false=off )
    AutoCreateUserInWhiteList=false (If your server is open, this option will allow the server to create the user in whitelist if they entered the server with a password, so his username will be protected)
    DisplayUserName=true (False = you won't see another players username on top of their head + their name won't be logged inside the local chat)
    SpawnPoint=0,0,0 (Use this to define a custom spawn point instead of the random one from character creation)
    SafetySystem=true (Allow the user to change their safety (if false and if PVP=true, then the safety will always be off)
    ShowSafety=true (Allow the players to see if someone have his safety off with the skull icon)
    SafetyToggleTimer=100 (When the player disable safety it take some times before HE enable it (tho the other players see it instantly), define it here)
    SafetyCooldownTimer=120 (Every time you hit someone in safety off, add this timer to the cool down before you can actually toggle safety off)
    SpawnItems=Add spawning items to new player, ex : Base.Axe,Base.WaterBottleFull... (every item need to be separated by a ",")
    DefaultPort=16261 (Default port used by the server)
    ResetID=123456789 (determines if the server has undergone a soft-reset. If this number does match the client, the client must create a new character. Used in conjunction with PlayerServerID. Please, backup these IDs somewhere) [*changed]
    Mods=CraftableAxes;Katana;MREMeal;NecroForge (Used to add mods to your server, like maps or other things, player will NEED to have this mods installed)
    Map=MD Cortman Medical;MD Kate & Baldspot;MD Large Warehouse;MD Sunstar Hotel;The Farm;The Mall;WP Apartments;WP Food & Hardware Store;WP Giga Mart;WP Police Station;WP School;WP Storage Lots;WP Town Hall;WP Twiggy's;Muldraugh, KY
    DoLuaChecksum=true (Do the lua checksum. Players with modified Lua files that differ from the server files will not be able to connect. true=Lua check, false=no lua check)
    Public=false (If true send the info of the server to pz.com to be visible in the public server list)
    PublicName=Your PZ Server (Required for public server)
    PublicDescription= server with high loot (Optionnal, for public server)
    MaxPlayers=64 (Max players who can connect on the server (admin can by pass this))
    PingFrequency=10 (Time between each client ping, in second)
    PingLimit=400 (Ping limit before being kicked, need to be 5 time over, in millisecond, 0 disbaled it. Using a value of 250 is good to avoid connections from china)
    HoursForLootRespawn=0 (Enable loot respawn if > 0, then the cell need to be unseen for X (this parameter) in-game hours before respawn loot in it)
    MaxItemsForLootRespawn=4 (For the loot respawn, if a container have more items than this number, it won't respawn loot (use it to limit respawn in safe house for example..)
    ConstructionPreventsLootRespawn=true (items will not respawn in buildings that players have built structures in (baricading counts). true=on, false=off; depends on 2 things: the amount of loot needed in a container to respawn and the amount of time a cell has to be unseen to respawn. Usually it doesn't happen because players fill their containers and visit frequently. Even if it did. Loot respawn will only ever ADD to a container. It won't delete or randomize a container)
    DropOffWhiteListAfterDeath=false (remove player accounts from the whitelist after death. Prevents creating a new character after death on)
    NoFire=false (all forms of fire are disabled. except campfires)
    AnnounceDeath=false (if true, every time a player dies a message will be displayed in the chat)
    MinutesPerPage=1.0 (the number of game-world minutes it takes to read one page of a book)
    SaveWorldEveryMinutes=0 (loaded pats of the map are saved after this many real-world minutes have passed. The map is usually saved only after clients leave a loaded area)
    PlayerSafehouse=false (admins and players may claim safehouses)
    AdminSafehouse=false (only admins may claim safehouses)
    SafehouseAllowTrepass=true (allow non-members to enter a safehouse without being invited)
    SafehouseAllowFire=true (allow fire to damage safehouses)
    SafehouseAllowLoot=true (allow non-members to take items from safehouses)
    SafehouseAllowRespawn=false (players spawn in a safehouse they were a member of before they died)
    SafehouseDaySurvivedToClaim=0 (players must have survived this many game-world days before they may claim a safehouse)
    SafeHouseRemovalTime=144 (players are automatically removed from a safehouse they have not visited for this many real-time hours)
    AllowDestructionBySledgehammer=true (allow players to destroy world objects with the sledgehammer)
    KickFastPlayers=false (kick players that appear to be moving faster than is possible. May be buggy -- use with cation)
    ServerPlayerID=1234567899 (Determines if the character is from another server or singeplayer. This value may be changed by soft-resets. If this number does match the client, the client must create a new character. Used in conjunction with ResetID. Please, backup these IDs somewhere) [*changed]
    RCONPort=12345 (Port for RCON) [*example]
    RCONPassword= YOURPASSWORD (Password for RCON) [*example]
    Password= SERVERLOGINPASSWORD (clients must know this password to join the server. Ignored when hosting a server via the Hosts button) [*example]
    MaxAccountsPerUser=0 (limits the number of different accounts a single Steam unser may create on this server. Ignored when using the hosts button)
    SleepAllowed=false (Enable sleep)
    SleepNeeded=false (If true you will need to sleep when exhausted)
    WorkshopItems=624489512;972954692;670807387 (MOD + MAP IDs - folder can be found at: %\Steam\SteamApps\workshop\content\)
    SteamScoreboard=true (show steam usernames and avatars in the player list. true=visible to everyone, false=visible to no one, admin=visible to admins)
    CoopServerLaunchTimeout=20
    CoopMasterPingTimeout=60
    VoiceEnable=true (In game Voip)
    VoiceComplexity=5
    VoicePeriod=20
    VoiceSampleRate=24000
    VoiceBuffering=8000
    VoiceMinDistance=1.0
    VoiceMaxDistance=50.0
    Voice3D=true
    server_browser_announced_ip=
    UseTCPForMapDownloads=false
    PlayerRespawnWithSelf=false
    PlayerRespawnWithOther=false
    FastForwardMultiplier=40.0
    PlayerSaveOnDamage=true
    SaveTransactionID=false
    DisableSafehouseWhenPlayerConnected=false

    Faction=true (enable Factions)
    FactionDaySurvivedToCreate=0 (How many days you must survive to create a Faction)
    FactionPlayersRequiredForTag=1
    AllowTradeUI=true (Allows you to trade among players)
    HoursForWorldItemRemoval=0.0 (How many in-game hrs before corpses dissappear)
    WorldItemRemovalList=Base.Vest,Base.Shirt,Base.Blouse,Base.Skirt,Base.Shoes
    ItemRemovalListBlacklistToggle=false
    DisableRadioStaff=false
    DisableRadioAdmin=true
    DisableRadioGM=true
    DisableRadioOverseer=false
    DisableRadioModerator=false
    DisableRadioInvisible=true