# Yuyuko Saigyouji (Boss)

![](img/yuyuko.png)

This page explains the strategies employed against Yuyuko on her boss fight. This includes party composition, which spells to use offensively and defensively, and how the battle should flow, which attacks to watch out for, etc. Since strategies vary greatly from route to route, explanations will be separated accordingly.

[Back to index page](../index.md)

## Quick Summary

Yuyuko is a mandatory boss on 14F that unlocks a rock seal guarding the way to Yukari on 15F. Using a variety of DTH inducing moves, this fight can be very unreliable when it comes to speedrunning, but thankfully she's weak to TRR, and by this point we can stack TRR with Yuuka/Satori, which is way more reliable when doing this fight underleveled.

## Quick Links
* [AI Script](#script)
* [Attack List](#attacks)
* [Strategies](#strats)
	* [Ame-no-Murakumo (NG)](#ng-murakumo)

## <a id="script"></a>AI Script

* Threshold Moves:
	* Deadly Swallowtail Lance at 70%
	* Ghastly Dream at 50%
	* Concentrate -> Saigyouji Flawless Nirvana at 30%
* On turn 1:
	* Saigyouji Flawless Nirvana
* Phase 1: Over 50% HP
	* 34% chance to Ghostly Dream's Butterfly
	* 11% chance to cast any of these:
		* Dark Arrow
		* Storm of Dark Flow
		* Red Curse
		* Purple Curse
		* Allure of Death
		* Destroy Magic
* Phase 2: Below 50% HP
	* 16% chance to Ghostly Dream's Butterfly
	* 12% chance to either:
		* Storm of Dark Flow
		* Red Curse
		* Purple Curse
		* Destroy Magic
		* Deadly Swallowtail Lance
		* Ghastly Dream
		* Flux of Yomotsu Hirasaka

## <a id="attacks"></a>Attack List

* **Dark Arrow**
	* DRK Spell targetting MND, deals good damage if weak to DRK
* **Storm of Dark Flow**
	* AoE DRK spell targetting MND, deals good damage if weak to DRK
* **Red Curse**
	* AoE FIR spell targetting MND, low damage but can ATK-debuff entire party
* **Purple Curse**
	* AoE MYS spell targetting MND, low damage but can MAG-debuff entire party
* **Allure of Death**
	* DRK spell targetting MND, low damage but very high DTH chance
* **Destroy Magic**
	* MYS spell targetting MND, very low damage but drains all MP
* **Flux of Yomotsu Hirasaka**
	* AoE DRK spell targetting MND, very low damage but very high DTH chance
* **Ghostly Dream's Butterfly**
	* SPI spell targetting MND, moderate damage, medium DTH chance, lowers target ATB
* **Deadly Swallowtail Lance**
	* Row DRK spell targetting MND, low damage and low DTH chance
* **Ghastly Dream**
	* AoE SPI spell targetting MND, moderate damage, high DTH chance
* **Saigyouji Flawless Nirvana**
	* AoE DRK spell targetting MND, very high damage, insanely high DTH chance

## <a id="strats"></a>Strategies

#### <a id="ng-murakumo"></a>Ame-no-Murakumo (NG)

Yuyuko is the first boss fight we will be TRR stacking on. The goal is to inflict TRR on her, then spam Beauty of Nature with Yuuka and Satori to scale up TRR duration, then kill her in one hit of Jealousy of the Kind. Since Yuyuko has 0 TRR resist, it's trivial to proc it on her and scale it up, but her 300 DRK affinity means we'll have to spend a considerable amount of time scaling it up. In order to make this process faster, we minmax every multiplier we can on Parsee and dump all money on her ATK, so that we only really need to stack TRR to around 1.2 million duration, ideally. Some details on how we got to that number:

* Jealousy of the Kind Formula = 2.5 \* (2.5 \* ATK - 0.5 \* DEF) \* (1.0 + (0.01 \* (TRR / 2500)))
* Spell level 5 multiplier = 1.2
* Final Blow multiplier = 1.32
* Flames of Jealousy multiplier = 1.3
* High Stakes multiplier = 1.24
* Herb of Awakening multiplier = 1.36
* Affinity multiplier = 0.3333
* Yuyuko's HP = 394400
* Yuyuko's DEF = 4000
* Parsee's approximate ATK = 6600

Final formula = 2.8938624 \* (16500 - 2000) \* (1.0 + (0.01 \* (TRR / 2500)))

* Isolating for TRR, assuming Parsee has a 50% ATK buff:
	* 394400 = 2.8938624 \* 22750 \* (1.0 + (0.01 \* (TRR / 2500)))
	* 5.990734411787043 = 1.0 + (0.01 \* (TRR / 2500))
	* 4.990734411787043 = 0.01 \* (TRR / 2500)
	* 499.0734411787043 = TRR / 2500
	* TRR = 1247683

* Isolating for TRR, assuming Parsee has no buffs:
	* 394400 = 2.8938624 \* 14500 \* (1.0 + (0.01 \* (TRR / 2500)))
	* 9.399202947590044 = 1.0 + (0.01 \* (TRR / 2500))
	* 8.399202947590044 = 0.01 \* (TRR / 2500)
	* 839.9202947590044 = TRR / 2500
	* TRR = 2099800

Realistically, Parsee will always have some buffs on her from the beginning of the fight, so 2 million is a more realistic figure to aim at if Sanae can't buff Parsee at the very end. It might seem like it would take forever to stack TRR that high, but remember Beauty of Nature applies a multiplier to the current value, so it grows exponentially. The difference between 1.2M and 2M should be 2-3 casts, hardly any time loss.

In order to keep everyone alive and well while we stup the TRR stack, Komachi is left on slot 1 to tank most hits and Sanae on slot 2 to share some buffs and heals. It's very important to keep Yuuka and Satori alive and near max HP, since Yuyuko is perfectly capable of 2 shotting each of them. Buffs can also help Satori and Yuuka move faster, speeding up the fight a bit. Chen is also essential in this fight to apply Herb of Awakening and IA pivot Yuuka and Satori right after they cast Beauty of Nature. Satori gets pretty much infinite MP thanks to Small MP recovery, so you'll never really be hard pressed for BoN casts.

The only other point that needs attention is the opener, Saigyouji Flawless Nirvana. The strat for that is to just sack 3 characters, and similarly to the Memorized Knowledge setup, we'll go with Reimu, Cirno and Kasen. This allows Final Prayer to fully heal Komachi, and Blizzard Blowout to fully debuff Yuyuko's SPD, giving you plenty of time to setup TRR stacking before her next move. Also important is to give Satori some DTH resistance, so she doesn't get sniped. It wouldn't be the end of the world, but TRR stacking is much, much slower with just Yuuka.

**PHASE 1 - TRR Proc**

The goal is to survive Saigyouji Flawless Nirvana, swap in the setup frontline and proc TRR. Should be pretty easy, considering Yuyuko has no TRR resistance:

* Swap in Chen -> Sanae -> Parsee
* Sanae uses Miracle Fruit on Parsee
* Swap Sanae for Yuuka
* Parsee uses Midnight Anathema Ritual
* Swap Parsee with Satori

**PHASE 2 - Beauty of Nature**

Here we simply stackc TRR as high as we can, stopping around 1.2 million for the optimal setup. IA pivoting and careful healing/buffing is essential here:

* Yuuka and Satori spam Beauty of Nature
* Swap Chen with Sanae
* Komachi IA pivots Yuuka and Satori
* Sanae juggles healing and IA pivoting

**PHASE 3 - Jealousy of the Kind**

Make sure you have everything ready before firing off Jealousy of the Kind - if Yuyuko survives you lose everything as she sweeps you with her strong spells:

* TRR reaches 1.2-2.0 million (6600+ ATK)
	* 1.22 million with Sanae buff
	* 2.06 million without Sanae buff
* Swap in Chen -> Parsee on slots 3 and 4
* Sanae uses Miracle Fruit on Parsee once
* Chen uses Herb of Awakening on Parsee
* Parsee delays her turn if needed then Jealousy of the Kind

[Back to index page](../index.md)
