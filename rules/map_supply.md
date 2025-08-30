# Campaign Map & Supply

## The Campaign Map

The campaign map is divided into several named **Regions**. Each region is a collection of thematically-linked **Locations** that are connected by **Routes**.

*   **Regions**: Groups of locations that, when fully controlled, provide a strategic bonus to the controlling player.
*   **Locations**: These are the individual territories you fight to control, such as towns, strongholds, or mountain passes. Each has a Supply Value representing the army points it can support:
    *   **Village**: 250 Supply
    *   **Town**: 500 Supply
    *   **Fortress**: 800 Supply
    *   **Capital**: 1000 Supply
*   **Routes**: These are the paths that connect Locations, restricting army movement and creating natural chokepoints.

## Armies & Supply

In Tumult, armies are an abstract representation of a player's military might, not physical pieces on the map. A player's forces are represented by their **Army Roster**, which is a master list of all the units they command.

When a battle is fought, players muster an army for that specific engagement by choosing units from their Army Roster. The same units and heroes can be used in multiple battles during the same campaign turn.

## Calculating Battle Size

The maximum size of an army in any given battle is determined by the **Supply Value** of the Location where the battle is taking place. This is calculated using the **Decimal Contribution System**.

To calculate the maximum points for a battle at a specific Location (the "battleground"):

*   **Attacker's Maximum Army Size**:
    *   100% of the Supply Value of the battleground Location.
    *   10% of the Supply Value from each adjacent, friendly-controlled Location.
    *   1% of the Supply Value from each second-degree friendly-controlled Location.

*   **Defender's Maximum Army Size**:
    *   100% of the Supply Value of the battleground Location.
    *   10% of the Supply Value from each adjacent, friendly-controlled Location.
    *   1% of the Supply Value from each second-degree friendly-controlled Location.

Once both players have calculated their maximum army size, a 500-point floor is applied.

*   **Apply 500-Point Floor**: If a player’s calculated maximum army size is below 500, it is raised to 500. Otherwise, they use their full calculated value.

Players then muster an army for the battle, ensuring their army's total points value does not exceed their calculated maximum.

**Example Scenarios:**

*   **Scenario 1**: Player A attacks Player B at a Location. Player A's calculated maximum is 800 points, and Player B's is 650 points. Player A can field an army up to 800 points, and Player B can field an army up to 650 points.
*   **Scenario 2**: Player A attacks Player B. Player A's maximum is 700, and Player B's is 350. Player B's maximum is raised to 500 points.
*   **Scenario 3**: Player A attacks Player B. Player A's maximum is 400, and Player B's is 250. Both players' maximums are raised to 500 points.

## Region Control Bonuses

When a player controls all Locations within a single Region, they gain a persistent **Region Control Bonus**. This creates a strong mid-game objective and makes the choice of where to expand a key strategic decision.

The goal is for each bonus to be unique and rooted in the lore of the region itself.

### Region Bonus Design Toolbox

The following are examples of thematic bonuses that can be assigned to specific regions when the map is created.

**Economic Bonuses (The People are Prosperous)**

*   **Breadbasket:** The fertile farmlands of this region are pacified and organized. Gain an additional **100 Gold Crowns** during the Resolution Phase.
*   **Ancient Mines:** By securing these mountains, you have reopened ancient, treasure-laden mines. After any battle you win, you gain an additional **1D6x10 Gold Crowns**.

**Military Bonuses (The People are Martial)**

*   **The Musterfields:** This region is known for its hardy, militant populace. You may reduce the cost of replenishing or recruiting one **Core** unit by up to 50% during each Downtime Phase.
*   **Mountain Fastness:** The locals know every secret path and hidden watchtower. Any friendly army defending within this region's Locations adds a flat **+150 Supply** to its calculated army size.

**Heroism Bonuses (The People are Inspired)**

*   **Land of Legends:** Your leader's deeds have become local legend. Your primary Hero gains **+1 Renown** after any battle they participate in, win or lose.
*   **The Ancient Temple:** This region houses a sacred temple, and by protecting it, you have earned divine favour. Once per battle, a unit joined by your Hero may re-roll a single failed Break test.
