# PF2e Statblocks for Obsidian

Use Markdown syntax to create great-looking Pathfinder Second Edition statblocks inside of Obsidian!

## Usage

To start an item block, create a codeblock with the language tag `pf2e-stats`, as shown:

    ```pf2e-stats
    [YOUR CONTENT HERE]
    ```

Additionally, you can use `sf2e-stats` instead to switch over to Starfinder 2e theming!

### Name

The name of the item/creature/etc is indicated with heading 1, prefixed with a single hash `#`.

### Level

The type of statblock and the item/creature/etc level is indicated with heading 2, prefixed with a double hash `##`.

### Traits

In a standard statblock, traits are signified by wrapping them in double-equals `==`, as below:

```
==Unique== ==Medium== ==Humanoid==
```

Certain specific traits, such as for size and rarity, are automatically colored according to convention.

For abbreviated statblocks, such as the ones for brief NPC blurbs, instead use heading 3, prefixed with a triple hash `###`

### Line Breaks

To reset indentation, do two line breaks after a line.

### Dividers

Horizontal lines (three hyphens `---`) can be added to break up the sections of a statblock. Always insert an extra line break before and after a divider.

### Action Icons

You can add action icons as follows:

- One action: `` `[one-action]` ``
- Two-action activity: `` `[two-actions]` ``
- Three-action activity: `` `[three-actions]` ``
- Free action: `` `[free-action]` ``
- Reaction: `` `[reaction]` ``

### Abilities

Abilities must be written on a single line: the ability name, any traits or action icons, and the rules text all go on the same line (e.g. **Harming Hands** Her harm spells deal d10s instead of d8s.). Do **not** insert a line break between the bolded ability name and its description. Line breaks inside an ability entry are only used for outcome blocks (e.g. new lines starting with **Critical Success**, **Success**, etc.).

Multiple abilities are separated by two line breaks, to reset indentation.

### Bullets
Do no use bulleted or numbered lists. If you wish to list items within an ability, place the item on its own line separated from the previous by a single line break, indent with a single tab, and bold the item name.


## Example

```pf2e-stats
# Awesome Belt of Various Actions
## Item 25
---

==Unique== ==Invested== ==Magical==

**Price** 9,001 gp

**Usage** worn belt; **Bulk** L

---

This belt enables the wearer to do all kinds of different things.

**Activate-Buckle Spin** `[one-action]` (manipulate, visual) **Effect** You spin the belt's fabulous buckle.  Select an enemy creature within 30 feet.  It must make a DC 30 Will save.
	**Critical Success** The target is unaffected.
	**Success** The target is dazzled until the beginning of your next turn.
	**Failure** The target is blinded until the beginning of your next turn.
	**Critical Failure** The target is blinded for 1 minute.

**Activate-Belt Lash** `[two-actions]` (attack, concentrate) **Effect** The belt whips out toward an adjacent foe.  Make an attack roll with a modifier of +35 against the target's AC.  This attack ignores your multiple attack penalty and does not increase your multiple attack penalty.  The target takes 6d6 bludgeoning damage.
	**Critical Success** The target takes double damage.
	**Success** The target takes full damage.
	**Failure** The target takes no damage.
	**Critical Failure** The belt comes free of your pants, causing them to fall down.  You are clumsy 2 until the end of your next turn.

**Activate-Leather Storm** `[three-actions]` (concentrate) **Effect** The belt whirls around, buffetting anyone nearby.  Creatures within a 15-foot emanation of you take 4d8 bludgeoning damage with a DC 30 basic Reflex save.

**Activate-Safety Strap** `[reaction]` (concentrate) **Trigger** You are falling and a ledge is within 15 feet; **Effect** The belt latches onto the ledge, stopping your fall.

**Activate-Holster Throw** `[free-action]` (concentrate) **Trigger** You roll initiative; **Effect** The belt launches a weapon from its holster.  You Interact to draw a weapon.
```
### Templates
