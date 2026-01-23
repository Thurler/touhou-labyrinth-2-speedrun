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
	* 40% chance to Black Universe (B)
	* 25% chance to Gravity Manipulation
	* 20% chance to Piercing Light
	* 15% chance to Magic Arrow (B)
* Phase 2: Between 55% and 77% HP
	* 32% chance to Black Universe (B)
	* 20% chance to Mesh of Light and Darkness
	* 20% chance to Gravity Manipulation
	* 16% chance to Piercing Light
	* 12% chance to Magic Arrow (B)
* Phase 3: Between 25% and 55% HP
	* 25.6% chance to Black Universe (B)
	* 20% chance to Hyperactive Flying Object
	* 16% chance to Mesh of Light and Darkness
	* 16% chance to Gravity Manipulation
	* 12.8% chance to Piercing Light
	* 9.6% chance to Magic Arrow (B)
* Phase 4: Below 25% HP
	* 20.48% chance to Black Universe (B)
	* 20% chance to IN Quadruple Barrier
	* 16% chance to Hyperactive Flying Object
	* 12.8% chance to Mesh of Light and Darkness
	* 12.8% chance to Gravity Manipulation
	* 10.24% chance to Piercing Light
	* 7.68% chance to Magic Arrow (B)

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

Yukari is another boss we deal with by abusing TRR stacking. While she has 32 TRR resist, it's still a coin flip to inflict it with Parsee, making it consistent enough where it's a viable strategy. The real problem is preventing it from decaying too fast thanks to quicker recovery times with 32 resist. In order to do that, we manipulate the initiative so that Yuuka and Satori will immediately cast Beauty of Nature after Parsee, making sure the initial TRR duration is at least 70k before the ATB even starts to move.

Thanks to her being neutral to DRK, we don't need to scale TRR that high, which is a godsend given that every turn she has a 40% chance to cast Black Universe on a random spot. That means 1 in 5 turns will be spent reducing Yuuka or Satori to 1 HP, forcing you to scramble to heal them before her next turn, since any AoE attack will KO them. The TRR duration must be around x~y thousand. Some details on how to get to that number:

```
* Jealousy of the Kind Formula = 2.5 * (ATKF - DEFF) * (1.0 + (0.01 * (TRR / 2500)))
* Spell level 5 multiplier = 1.2
* Final Blow multiplier = 1.32
* Flames of Jealousy multiplier = 1.3
* Herb of Awakening multiplier = 1.36
* Youkai Buster multiplier = 1.2
* Affinity multiplier = 1.0
* Yukari's HP = 480000
* Yukari's DEF = 6400

Final formula:
TRR = (HP * 250000 / (ATKF - DEFF)) - 250000
TRR = (120000000000 / (ATK * 17.5032 - 22405)) - 250000
	* (Without Youkai Buster active)
TRR = (120000000000 / (ATK * 21.00384 - 26885)) - 250000
	* (With Youkai Buster active)

Where (without Youkai Buster):
* MULT = Product of all multipliers = 7.00128
* ATKF = Parsee's approximate ATK * 2.5 * MULT = ATK * 17.5032
* DEFF = Target's DEF * 0.5 * MULT = 22405

Where (with Youkai Buster):
* MULT = Product of all multipliers = 8.401536
* ATKF = Parsee's approximate ATK * 2.5 * MULT = ATK * 21.00384
* DEFF = Target's DEF * 0.5 * MULT = 26885

ATK formula:

* BASE = floor((Level + 4) * (Base + Subclass + Gem + Skill + Equip-G) + 4)
* ATK = BASE * (1 + Equip + (LevelBonus * 0.03) + (Library * 0.02))

Where:
* Level = At least 46, usually is 47
* Base = 11.4
* Subclass = 0 (Monk)
* Gem = At least 7, could be 10 = 1.4~2
* Skill = At least 0, could be 5 = 0~1
* Equip-G = 0
* Equip = At least 2.28, could be 2.72 (Cinderforge + Glaive x2)
* LevelBonus = At least 45, usually is 46
* Library = At least 170, could be 200

Best case: floor(51 * 14.4 + 4) * (9.1) = 738 * 9.1 = 6715
Worst case: floor(50 * 12.8 + 4) * (8.03) = 644 * 7.57 = 5171
With a 20% buff: 8058 ~ 6205
With a 50% buff: 10072 ~ 7756

Solving for ATK values (no Youkai Buster || with Youkai Buster):
* 5100 -> 1545k / 1167k / 827k || 1246k / 931k
* 5300 -> 1456k / 1100k / 778k || 1172k / 875k
* 5500 -> 1375k / 1039k / 734k || 1104k / 824k
* 5700 -> 1302k / 984k / 694k || 1043k / 778k
* 5900 -> 1234k / 933k / 656k || 987k / 736k
* 6100 -> 1173k / 886k / 622k || 936k / 696k
* 6300 -> 1116k / 842k / 590k || 889k / 660k
* 6500 -> 1064k / 802k / 560k || 845k / 627k
* 6700 -> 1015k / 765k / 532k || 805k / 596k
```

Note how different the thresholds become depending on what investment Parsee managed to get throughout the run, specifically if the Cinderforge Sword is available and how many Gems and Training Manuals were acquired. The values for with Youkai Buster omit the 50% buff as going that high up requires two buffs, which poses a great risk of Sanae dying and making the previous threshold goel unreachable. The five different outcomes can be interpreted as such:

- Sanae died early and there are no more ways to buff Parsee
- Sanae died early and Kourin / Keine + Satori got a 20% buff on Parsee
- Sanae died while Parsee was out, triggering Last Wish's buff
- Sanae stayed alive and is in front, but hasn't buffed Parsee yet
- Sanae stayed alive and is in front, and has buffed Parsee

As you may notice, the main line is to get Yukari to the Youkai Buster + 20% buff threshold, and setup the appropriate frontline for the final blow. If Sanae dies while this is ongoing, the Last Wish buff makes it so Parsee can still one shot Yukari immediately, since the no Youkai Buster + 50% buff line has a lower threshold.

A faster side line is to go for 1 extra Beauty of Nature after hitting the threshold, so that Parsee can immediately go for the kill after receiving Herb of Awakening and having Sanae in front. And finally, the line where Sanae dies early ahs a riskier component that relies on alternative buff methods, and a safer one that just has a higher threshold.

[Back to index page](../index.md)