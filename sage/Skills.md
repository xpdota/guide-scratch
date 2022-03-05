## Before you Start: Eukrasia

First, a note about skills with "Eukrasian" in the name - these are upgraded versions of other skills that you would
access by using the "Eukrasia" skill first. For example, to cast Eukrasian Dosis, first cast Eukrasia, then cast Dosis.
Eukrasia itself is a 1-second instant-cast GCD, and the buffed ability will become a 1.5-second instant-cast GCD.
Neither of these cast times are affected by spell speed, so any Eukrasian GCD will always be 2.5 seconds. In addition,
unlike a real 2.5 second instant GCD, you will only be able to weave one oGCD without clipping.

## Offensive Skills

While Sage does not offer a raid buff, it makes up for it by having the highest personal DPS of all the healers. The
general formula is similar, but Sage is the only healer to have a burst GCD (Phlegma). In addition, every offensive GCD
provides free healing to your Kardion target. Let's take a look at how Sage's offensive skills mesh with each other:

### Dosis

This is your main filler offensive GCD. When you have nothing higher priority to cast, use this. At 330 potency, it is
the most powerful of all the healer single target filler GCDs.

### Eukrasian Dosis

Eukrasian Dosis is your damage over time skill. Like the other healers, it lasts 30 seconds. DoT (and HoT) effects in
FFXIV operate on "server ticks", once every 3 seconds. On each of these ticks, DoTs and HoTs will apply their listed
potency. Thus, the total potency of Eukrasian Dosis is 700 (10 ticks of 70 potency). Typically, it should be re-applied
as closely as possibly to when it would expire. To keep 100% uptime, you need to factor in the 1 second needed to cast
Eukrasia, but the debuff application itself is instant.

### Dyskrasia

Your spammable AoE cooldown. With 170 potency per target, compared to 330 on Dosis, It becomes a gain on just two
targets. In addition, it is an instant cast, so it can be used while moving. Ideally, it would never be used on a single
target, but it *can* function as a last resort movement skill.

### Phlegma

Phlegma is unique as it is the only healer offensive GCD that operates on a charge system while still being a DPS gain.
It deals 510 damage to the main target, and 255 on other targets within a 5 yalm radius of the primary target. The range
is only 6 yards, so you will need to be somewhat close to the target. It is your most powerful single-target *and* AoE
ability.

Due to having two charges, it does not have a strict alignment need like you'd get out of other GCDs with a cooldown.
The general priority for when to use Phlegma charges is:

1. AoE, when needed. Hitting even just one additional target puts it at +50% potency. 
2. 2-minute burst windows. On a full-uptime fight, you will be able to use two charges in the opener, and then again at
   2, 6, 8, and 12 minute marks.
3. With a Ninja, dump remaining charges on 1-minute burst windows.
4. Movement. Phlegma is an instant GCD, so it allows free movement for its entire recast time.
5. Dump any remaining charges to avoid overcapping, or before a boss goes untargetable for a long enough period of time
   to make you overcap.

For dungeons, the priority would be to use them on packs, once the tank has finished pulling all the mobs together. Make
sure that you're targeting a mob that is within range of all the others, otherwise it may not hit everything if the mobs
are a bit more spread out.

### Pneuma

Pneuma is a combination damage and healing ability. It is damage-neutral compared to Dosis, with the same 330 potency on
the main target. For multiple targets, it is 198p on each target, making it fall behind only Phlegma for AoE. The 600p
heal is already decent, but it is best used with Zoe for a 900p damage-neutral AoE heal.

Due to it being AoE

#### "But My Pneuma Didn't Heal!"

Due to game engine limitations, Pneuma works in a very odd way. The "target" of the ability is the enemies that it his.
The heal is actually implemented as a heal over time that applies instantly. However, sometimes the game client won't
correctly show the change in HP, hence why sometimes people think it didn't work. In addition, the heal applies
instantly as soon as the ability snapshot (0.5 seconds from the end of the cast, i.e. same as slidecasting), so it is
easy to waste the heal by healing too early. 

### Toxicon

Toxicon is an instant cast GCD that is damage-neutral with Dosis on a single target, and 
Toxicon is similar to Dyskrasia, but uses "Adderstring" charges and has slightly different scaling. It is damage-neutral
with Dosis on a single target, and beats Dyskrasia for AoE in all practical scenarios. 

[//]: # (TODO: haima duration notes, kera does not give free tick)