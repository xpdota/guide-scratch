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

Due to it being AoE, it is also useful for dungeons, as well as situations such as P3S where it might be possible to hit
multiple targets.

#### "But My Pneuma Didn't Heal!"

Due to game engine limitations, Pneuma works in a very odd way. The "target" of the ability is the enemies that it
damages. The heal is actually implemented as a heal over time that applies instantly. However, sometimes the game client
won't correctly show the change in HP, hence why sometimes people think it didn't work. In addition, the heal applies
instantly as soon as the ability snapshot (0.5 seconds from the end of the cast, i.e. same as slidecasting), so it is
easy to waste the heal by healing too early.

### Toxicon

Toxicon is an instant cast GCD that is damage-neutral with Dosis on a single target, and Toxicon is similar to
Dyskrasia, but uses "Adderstring" charges and has slightly different scaling. It is damage-neutral with Dosis on a
single target, and beats Dyskrasia for AoE in all practical scenarios.

[//]: # (Everything below here is copied from the basic guide, need to touch up)

## Addersgall Heals

These require a stack of Addersgall to use. Since you get a charge every 20 seconds, and can store up to three, you can
use these very frequently. In fact, each of them restores 7% of your mana, so you should use them liberally even if not
necessarily needed.

- Kerachole: It provides a 10% mitigation and 100p regen for 15 seconds to nearby party members. Functionally very
  similar to Scholar's Sacred Soil, but does not need to be placed (for better or for worse). Its 30 second cooldown
  means it can be up half the time, and the 500p total healing is more than Ixochole. Generally, this should be your
  go-to ability for incoming AoE damage. Does not stack with Taurochole. Unlike Asylum, this does **not** have a free
  tick on application.
- Ixochole: A simple 400p AoE heal on a 30 second cooldown.
- Taurochole: A single target, 700 potency heal, plus 10% damage mitigation for 15 seconds. 45 second cooldown. Does not
  stack with Kerachole.
- Druochole: A single target, 600p heal. This does not have a cooldown.

Generally, Addersgall heals should be your first and foremost healing tool, as using them restores mana.

### Kerachole Usage

Being a 15 second mitigation on a 30 second cooldown, Kerachole has very good uptime. If you need to catch two instances
of damage with less than 15 seconds between them, you can do so with a single Kerachole. If the two instances are
between 15 and 30 seconds apart, you can catch both by casting the first one early so that it will come off cooldown
before the second.

## Other oGCD heals

Next up, your other oGCD heals. These do not cost anything other than the cooldown itself, so they should be your second
priority for healing, behind Addersgall heals.

- Kardia: See the [Kardia](#Kardia) section above.
- Physis: AoE regen plus heal boost on a 60 second cooldown. The regen is 650 potency total over 15 seconds (5 ticks of
  130p each). The healing up effect only last 10 seconds, but affects all healing, even your co-healer.
- Haima: A shield that repeatedly re-applies itself when absorbed (up to 5 times, not including the initial shield).
  Each shield is 300 potency, so the best case scenario is 1800p total absorbed.
- Panhaima: Like Haima, but AoE, with a lower potency to compensate.
- Holos: Similar effect to Taurochole, but AoE. However, it does stack with Kerachole or Taurochole. The 300p heal is
  minor, but still something, so ideally you want to make use of both the healing and damage reduction.

Again, these cost nothing - try to use them as much as possible!

### Haima and Panhaima Details

Haima (and Panhamia, hereafter just Haima) has several intricacies that are worth knowing.

Haima has two separate buffs that it applies. One of them has a stack number, the other does not. The one without the
stack number is the shield itself. The one with the number indicates how many more times the shield will automatically
re-apply. The initial application does not consume a stack, so 6 shields total can be applied.

The duration of each buff is 15 seconds. The 15 seconds for the shield buff is reapplied every time the shield is
consumed, thus while you will not get any more refreshes past the 15 seconds, the final shield buff linger for up to 15
seconds longer.

Panhaima and Haima do stack.

## GCD Heals

Excluding Pnuema as previous discussed, GCD heals should be your last resort. They cost damage, and Sage's GCD heals are
not particularly effective. You have Diagnosis as a single target, with Eukrasia adding a shield. Prognosis is an AoE
heal, with Eukrasia also adding a shield. Generally, the Eukrasian versions are preferred, but both versions should be
avoided if possible.

## Utility

- Icarus: Your gapcloser. You're the only healer with a gapcloser, so make good use of it. It can be used on an enemy or
  party member.
- Soteria: Temporarily boosts the healing from Kardia. Useful for when you need a little extra free single target
  healing, or general tank upkeep.
- Zoe: Increases the potency of the next GCD heal by 50%. The important part is the Pneuma counts as a GCD heal for this
  purpose, so you can make use of this without using a pure GCD heal.
- Pepsis: Converts shields from your GCD heals that are currently applied to raw healing. Like Scholar's Emergency
  Tactics, but in reverse (you use the heal first, then use Pepsis).
- Rhizomata: Gives you a charge of Addersgall. Since Addersgall heals give mana, this can help with MP management even
  if the healing is not needed.
- Krasis: Increases healing received by a target. You should cast this on the target that you want to heal, not
  yourself.

[//]: # (TODO: Kardia range)