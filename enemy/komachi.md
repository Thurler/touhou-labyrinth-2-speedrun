# Komachi Onozuka (Boss)

![](img/komachi.png)

This page explains the strategies employed against Komachi on her boss fight. This includes party composition, which spells to use offensively and defensively, and how the battle should flow, which attacks to watch out for, etc. Since strategies vary greatly from route to route, explanations will be separated accordingly.

[Back to index page](../index.md)

## Quick Summary

Komachi acts as the first stratum boss, and as such packs quite a punch on an unprepared party. She has access to DTH skills so protecting your main tank against that is pretty much required. She is very weak to NTR, making Nitori your best choice for attacking here. She also has weaknesses to FIR and WND, and is very weak to PSN and SHK, opening up several options for NG+.

## Quick Links
* [AI Script](#script)
* [Attack List](#attacks)
* [Strategies](#strats)
	* [Ame-no-Murakumo (NG)](#ng-murakumo)

## <a id="script"></a>AI Script

* Threshold Moves:
	* Narrow Confines of Avici at 40%
	* Scythe that Chooses the Dead at 25% (A)
* Phase 1: Over 76% HP
	* 40% chance to Short Life Expectancy (D)
	* 20% chance to either:
		* Phantom Coldness
		* Row Attack
		* Regular Attack (A)
* Phase 2: Between 34% and 76% HP
	* 45% chance to Short Life Expectancy (D)
	* 25% chance to Ferriage in the Deep Fog
	* 10% chance to either:
		* Phantom Coldness
		* Row Attack
		* Regular Attack (A)
* Phase 3: Between 16% and 34% HP
	* 45% chance to Short Life Expectancy (D)
	* 15% chance to Ferriage in the Deep Fog
	* 10% chance to either:
		* Recover
		* Phantom Coldness
		* Row Attack
		* Regular Attack (A)
* Phase 4: Below 16% HP
	* 40% chance to Short Life Expectancy (D)
	* 20% chance to either:
		* Scythe that Chooses the Dead (A)
		* Ferriage in the Deep Fog
		* Recover

## <a id="attacks"></a>Attack List

* **Regular Attack**
	* Basic PHY attack targetting DEF
* **Row Attack**
	* Row version of the regular attack
* **Phantom Coldness**
	* AoE CLD spell targetting DEF, deals good damage if weak to CLD
* **Short Life Expectancy**
	* PHY spell targetting DEF, always targets leftmost spot, can inflict DTH
* **Ferriage in the Deep Fog**
	* Row CLD spell targetting DEF, stronger than Phantom Coldness and can inflict DTH
* **Recover**
	* Heals Komachi for a small amount of HP
* **Narrow Confines of Avici**
	* AoE SPI spell targetting MND, deals lots of damage and can TRR, PAR, DTH and debuff. Make sure you only have tanky characters out when she uses this.
* **Scythe that Chooses the Dead**
	* SPI spell targetting DEF, this is her big nuke that will kill anything it hits. Can also inflict DTH.

## <a id="strats"></a>Strategies

#### <a id="ng-murakumo"></a>Ame-no-Murakumo (NG)

There is a lot of setup for this fight. Since Komachi has a lot going for her and we barely have access to good skills, we have to squeeze every advantage we can get from the characters we have available. Below are the vital characters in this fight and their major role:

* Nitori deals massive damage with Extending Arm
	* Maintenance + Wash Basin Set = OP
	* Can also buff herself early in the fight
* Momiji takes the main tank role thanks to her high HP and DEF
	* Ability to See Far Distances increases party ACC, improving consistency
	* Courtesan's Sorrow boosts her low DTH so Short Life Expectancy doesn't proc DTH
* Kasen deals good damage with Diving Waltz of the Raijuu
	* Can also PAR and MND-debuff
* Minoriko heals and rebuffs Momiji as needed
	* Can deal good damage after Kasen debuffs
* Keine boosts the attackers' ATK/MAG, has exactly 4 casts
* Reimu boosts everyone's DEF/MND at the start and provides AoE heal
	* Armored Yin-Yang Orb softens the Narrow Confines of Avici blow
* Youmu sticks around to activate Netherworld Dweller
	* Her high SPI affinity also helps her survive Narrow Confines of Avici
	* She can nuke Komachi once with Slash Clearing the Six Senses
* Kourin provides support by switching with Efficient Formation Switch
	* Can make Nitori spam for a damage rush
* Cirno can try to proc a SPD-debuff with Icicle Fall
* Marisa can Master Spark if something goes wrong
* Rumia can chip damage if everything goes wrong

The party composition is thus all 11 available characters, with the frontline being Momiji / Keine / Reimu / Nitori. The fight strategy can be divided into 4 phases, explained in detail below:

**PHASE 1 - Buffing**

The main goal here is to buff the frontline, specially Nitori and Momiji. Komachi will be using basic moves at the start so there is nothing to fear here. This phase ends when Kasen switches in. The actions should go like this:

* Nitori spams her self buff until she's switched out
* Reimu uses Great Hakurei Border once
* Keine uses Three Treasures - Sword once
* Momiji uses Attack, then switches Nitori for Kasen

**PHASE 2 - Kasen/Minoriko damage**

The second phase uses Kasen and Minoriko for damage, and lasts until Keine no longer has MP to buff Kasen. This should deal about 30-40% of Komachi's HP in damage, and Minoriko is responsible for keeping Momiji/Kasen alive and well. Reimu fires off a heal as well while Minoriko isn't swapped in.

* Keine spams Three Treasures - Sword
* Reimu uses Exorcising Border
* Kasen spams Diving Waltz of the Raijuu
* Momiji swaps Keine with Kasen
	* This keeps Keine safe so she can keep buffing
* Momiji swaps Reimu with Minoriko
* Minoriko juggles buff/heal/damage

**PHASE 3 - Kourin/Nitori damage**

Once Keine is out of MP, we switch in Cirno to hope for a lucky SPD debuff. The odds are 50%, so we can try at most twice while Kasen uses the remainder of her MP. Minoriko gets replaced with Kourin, who will replace Cirno with Nitori, so she can quickly damage Komachi and get switched back into safety by Momiji or Youmu (who swaps into Kasen's slot when she runs out of MP). The swapping keeps going until Komachi's ATB goes over 7500 and is below 40% HP.

* Momiji swaps no MP Keine with Cirno
* Cirno spams Icicle Fall
* Minoriko swaps self with Kourin
* Momiji swaps no MP Kasen with Youmu
	* Youmu provides a 20% damage boost to Nitori thanks to Netherworld Dweller
* Kourin swaps Cirno with Nitori
* Nitori spams Extending Arm
* Momiji/Kourin combo swap Nitori to renew her ATB

**PHASE 4 - Narrow Confines of Avici**

When the Narrow Confines are approaching, simply swap Nitori for Reimu and wait for it. If Reimu gets a turn, either heal everyone or buff everyone, whatever will help most. Reimu's Armored Yin-Yang Orb reduces incoming damage by 15% so that's a great help to tank it. After that, simply go back to swapping Nitori in and out to kill Komachi as fast as possible.

* Swap Nitori for Reimu when Komachi below 40%
* Reimu uses Great Hakurei Barrier (if there's time)
* Tank the Confines of Avici
* Resume combo swap with Nitori

This fight should be VERY consistent from what I've tested, so long as you predict Narrow Confines correctly and Nitori doesn't die, victory is guaranteed. Some accidents can happen with slot 4 targetting but that's very unlikely.

[Back to index page](../index.md)
