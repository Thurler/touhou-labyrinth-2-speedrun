# Sakuya Izayoi and Remilia Scarlet

![](img/remisaku.png)

This page explains the strategies employed against Sakuya and Remilia on their boss fight. This includes party composition, which spells to use offensively and defensively, and how the battle should flow, which attacks to watch out for, etc. Since strategies vary greatly from route to route, explanations will be separated accordingly.

[Back to index page](../index.md)

## Quick Summary

Sakuya and Remilia block your way to the 11F stairs, and are one of the only mandatory boss fights where you have more than one target. Naturally, the first question is who to kill first, but that is easily answered when you look at Sakuya's 92 DTH resistance. Reisen's Intense Vertigo drops that to 74, allowing some characters to proc DTH on her. With Sakuya gone, Remilia will do nothing but spam Spear the Gungnir, making the fight very easy and manageable.

## Quick Links
* [AI Script - Sakuya](#script-sakuya)
* [AI Script - Remilia](#script-remilia)
* [Attack List - Sakuya](#attacks-sakuya)
* [Attack List - Remilia](#attacks-remilia)
* [Strategies](#strats)
	* [Ame-no-Murakumo (NG)](#ng-murakumo)

## <a id="script-sakuya"></a>AI Script - Sakuya

* Once, if Remilia is alive and below 50% HP:
	* Private Square
	* Private Square
* If Remilia is alive:
	* 30% chance to Misdirection or Regular Attack
	* 20% chance to Daze
	* 15% chance to Razor Wind
	* 5% chance to Soul Sculpture
* If Remilia is dead, follow this order:
	* Soul Sculpture
	* Killing Doll
	* Lunar Clock
	* Soul Sculpture
	* Use one of the following spells:
		* 40% chance to Daze
		* 25% chance to Leg Sweep
		* 20% chance to Regular Attack
		* 15% chance to Storm of Blue Rain
	* Lunar Clock

## <a id="script-remilia"></a>AI Script - Remilia

* Once, if Sakuya is alive and below 50% HP:
	* Blood Drain
* If Sakuya is alive:
	* 40% chance to Regular Attack
	* 25% chance to Row Attack
	* 20% chance to Spear the Gungnir
	* 15% chance to Slash Dive
* If Sakuya is dead, follow this order:
	* Spear the Gungnir
	* Spear the Gungnir
	* Curse of Vlad Tepes

## <a id="attacks-sakuya"></a>Attack List - Sakuya

* **Regular Attack**
	* Basic PHY attack targetting DEF, has a 3/103 chance of targetting slot 4 and ruining your day
* **Misdirection**
	* AoE PHY attack targetting DEF, kinda low power but expect frail units to still get OHKO'd
* **Daze**
	* FIR spell targetting DEF, moderate damage and can inflict SHK
* **Leg Sweep**
	* Row NTR spell targetting DEF, moderate damage and can inflict SHK on everyone
* **Razor Wind**
	* AoE WND spell targetting DEF, high damage compared to Misdirection
* **Storm of Blue Rain**
	* AoE CLD spell targetting MND, deals good damage if weak to CLD
* **Soul Sculpture**
	* AoE WND spell targetting DEF, very high piercing damage
* **Killing Doll**
	* Single target PHY spell targetting DEF, very high DEF factor so it's easy to mitigate damage
* **Private Square**
	* AoE spell that simply inflicts unresistable PAR to everyone, completely broken
* **Lunar Clock**
	* Self SPD buff by 66%, can make her berserk phase a nightmare to deal with

## <a id="attacks-remilia"></a>Attack List - Remilia

* **Regular Attack**
	* Basic PHY attack targetting DEF, has a 3/103 chance of targetting slot 4 and ruining your day
* **Row Attack**
	* Row version of the regular attack, will hit rightmost slots for barely any damage
* **Slash Dive**
	* Basic WND attack targetting DEF, about as strong as regular attack
* **Spear the Gungnir**
	* Powerful single target PHY spell targetting DEF, expect very high damage
* **Curse of Vlad Tepes**
	* Self ATK/DEF/MAG/MND buff by 50%, very easy to dispel these thanks to her low DBF resistance
* **Blood Drain**
	* Self ATK/DEF/MAG/MND buff to her AND Sakuya, also halves Sakuya's current HP

## <a id="strats"></a>Strategies

#### <a id="ng-murakumo"></a>Ame-no-Murakumo (NG)

As mentioned in the summary, the strat is to proc DTH on Sakuya and then juggle Remilia's berserk phase. We use Komachi to do this, since she's the only one in this route that has access to high DTH skills. Ferriage in the Deep Fog at level 5 has a 64% chance to DTH, and stacked with 25% from The Shinigami's Work, that gives us a 15% chance to proc DTH on Sakuya. The alternative strat is to damage rush Sakuya and hope to keep her in permanent PAR stun (she only has 16 PAR resistance), hoping she never uses Private Square, and that is clearly slower and less reliable than a 15% proc rate.

In order to do all that reliably, we'll need Komachi and Reisen in front, and we'll add in Guardian Nitori to sponge Remilia's attacks, as well as Aya to use DGA on Komachi and get more Ferriage in the Deep Fog casts out there. After dispatching Sakuya, Remilia will be stuck on a Spear/Tepes loop, which is perfectly manageable since Nitori can tank those very easily, specially with buffs.

In order to defeat Remilia, we must first dispel her buffs and debuff her SPD so that her damage output becomes more manageable. We use Cirno to debuff SPD, and Reisen to debuff everything else, but mostly MND. Iku can then come in to deal high damage to a MND debuffed Remilia, and also debuff her DEF in the process. With such debuff in place, Nitori can snipe in a Super Scope after being buffed, and Chen can come in to Kimontonkou + PSW spam for really high FIR damage, which Remilia is weak to. For healing and support, we add in Sanae and Reimu, whose mission is to keep Nitori healthy and everyone else buffed for maximum damage. Aya plays the switcher support role.

**PHASE 1 - Sakuya DTH**

The goal here is to simply get the DTH proc on Sakuya, so we give Komachi as many turns as possible to cast Ferriage in the Deep Fog. You must reset the fight if Komachi fails thrice or if Reisen dies.

* Aya uses DGA on Komachi
* Komachi tries Ferriage in the Deep Fog #1
* Reisen uses Lunatic Red Eyes
* Nitori spams Portable Versatile Machine
* Aya uses Sarutahiko's Guidance on herself
* Komachi tries Ferriage in the Deep Fog #2
* Aya uses DGA on Komachi
* Komachi tries Ferriage in the Deep Fog #3

**PHASE 2 - Remilia**

After Sakuya dies, you should debuff Remilia to maximize your damage output and minimize hers. There is a lot of adapting here depending on how she targets her Spear the Gungnirs, and when you get the SPD debuff to delay her Curse of Vlad Tepes. Each character has a specific role in this fight, and they should focus on keeping the damage flow going, switching out as necessary:

* Nitori manages her own buffs and uses Super Scope when DEF debuff is at max
* Aya switches characters around and buffs SPD as needed
* Cirno spams Icicle Fall whenever Remilia's SPD debuff is too low
* Reisen spams Lunatic Red Eyes whenever Remilia rebuffs herself
* Iku spams Elekiter Dragon Palace whenever Reisen procs the MND debuff
* Chen uses Kimontonkou + PSW after Iku debuffs DEF
* Sanae comes in to heal Nitori and buff Iku/Chen as needed
* Reimu can provide emergency buffs, healing and damage in a pinch

[Back to index page](../index.md)
