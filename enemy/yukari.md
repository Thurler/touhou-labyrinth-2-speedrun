# Yukari Yakumo (Boss)

![](img/yukari.png)

This page explains the strategies employed against Yukari on her boss fight. This includes party composition, which spells to use offensively and defensively, and how the battle should flow, which attacks to watch out for, etc. Since strategies vary greatly from route to route, explanations will be separated accordingly.

[Back to index page](../index.md)

## Quick Summary

Yukari is a mandatory boss blocking the stairs to 16F. She has access to many spells that have annoying side effects to them, on top of having great damage potential with her big spells, particularly after her buffs when she goes berserk. Doing this fight at low levels is easier with TRR stacking, like with Yuyuko, but thanks to her 32 TRR resistance this requires a very particular setup.

## Quick Links
* [AI Script](#script)
* [Attack List](#attacks)
* [Strategies](#strats)
	* [Ame-no-Murakumo (NG)](#ng-murakumo)

## <a id="script"></a>AI Script

* Threshold Moves:
	* Mesh of Light and Darkness at 77%
	* Hyperactive Flying Object at 55%
	* World Devouring Calamity -> IN Quadruple Barrier at 25%
* If Yukari has any debuff, and turn is a multiple of 3:
	* Yukari's Spiriting Away
* Phase 1: Over 77% HP
	* 40% chance to Black Universe
	* 25% chance to Gravity Manipulation
	* 20% chance to Piercing Light
	* 15% chance to Magic Arrow
* Phase 2: Between 55% and 77% HP
	* 32% chance to Black Universe
	* 20% chance to Mesh of Light and Darkness
	* 20% chance to Gravity Manipulation
	* 16% chance to Piercing Light
	* 12% chance to Magic Arrow
* Phase 3: Between 25% and 55% HP
	* 25.6% chance to Black Universe
	* 20% chance to Hyperactive Flying Object
	* 16% chance to Mesh of Light and Darkness
	* 16% chance to Gravity Manipulation
	* 12.8% chance to Piercing Light
	* 9.6% chance to Magic Arrow
* Phase 4: Below 25% HP
	* 20.48% chance to Black Universe
	* 20% chance to IN Quadruple Barrier
	* 16% chance to Hyperactive Flying Object
	* 12.8% chance to Mesh of Light and Darkness
	* 12.8% chance to Gravity Manipulation
	* 10.24% chance to Piercing Light
	* 7.68% chance to Magic Arrow

## <a id="attacks"></a>Attack List

* **Magic Arrow**
	* MYS Spell targetting MND, deals good damage if weak to MYS
* **Piercing Light**
	* Row MYS Spell targetting MND, deals high piercing damage
* **Gravity Manipulation**
	* AoE DRK Spell targetting DEF, very low damage but very high chance to HVY and debuff SPD by 100%
* **Black Universe**
	* Reduces target's HP to 1, high chance to PAR, TRR and debuff SPD by 100%
* **World Devouring Calamity**
	* Fully depletes the entire party of 12's MP
* **Mesh of Light and Darkness**
	* AoE SPI Spell targetting MND, deals moderate damage, moderate chance to PAR and debuff SPD by 25%
* **Hyperactive Flying Object**
	* Row WND Spell targetting MND, deals high damage
* **IN Quadruple Barrier**
	* Buffs Yukari's ATK/DEF/MAG/MND/SPD by 33%
* **Yukari's Spiriting Away**
	* Removes all debuffs from Yukari, has very low delay

## <a id="strats"></a>Strategies

#### <a id="ng-murakumo"></a>Ame-no-Murakumo (NG)

* Jealousy of the Kind Formula = 2.5 \* (2.5 \* ATK - 0.5 \* DEF) \* (1.0 + (0.01 \* (TRR / 2500)))
* Spell level 5 multiplier = 1.2
* Final Blow multiplier = 1.32
* Flames of Jealousy multiplier = 1.3
* Herb of Awakening multiplier = 1.36
* Youkai Buster multiplier = 1.2
* Affinity multiplier = 1.0
* Yukari's HP = 480000
* Yukari's DEF = 6400

Final formula:
* TRR = (HP \* 250000 / (ATKF - DEFF)) - 250000
* TRR = (120000000000 / (ATK \* 17.5032 - 22405)) - 250000 (no YB)
* TRR = (120000000000 / (ATK \* 21.00384 - 26885)) - 250000 (YB)

Where:
* MULT = Product of all multipliers = 7.00128 (no YB) / 8.401536 (YB)
* ATKF = Parsee's approximate ATK \* 2.5 \* MULT = ATK \* 17.5032 (no YB) / 21.00384 (YB)
* DEFF = Target's DEF \* 0.5 \* MULT = 22405 (no YB) / 26885 (YB)

* Parsee's approximate ATK (0 gems):
	* No buffs = 5000 / 5300 -> 1.593M / 1.456M (No YB)
	                            1.286M / 1.172M (YB)
	* 30% buff = 6500 / 6890 -> 1.064M / 973K (No YB)
	                            845K / 769K (YB)
* Parsee's approximate ATK (5 gems):
	* No buffs = 5400 / 5700 -> 1.415M / 1.302M (No YB)
	                            1.137M / 1.043M (YB)
	* 30% buff = 7020 / 7410 -> 945K / 869K (No YB)
	                            746K / 683K (YB)
* Parsee's approximate ATK (10 gems):
	* No buffs = 5800 / 6100 -> 1.267M / 1.173M (No YB)
	                            1.014M / 936K (YB)
	* 30% buff = 7540 / 7930 -> 846K / 781K (No YB)
	                            663K / 610K (YB)

[Back to index page](../index.md)