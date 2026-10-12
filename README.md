# Timeline

A historical side-scrolling exploration game. Walk left toward the past and right toward the future; learn from people and objects to discover paths through history.

## Prototype scope
First chapter: northwestern South Asia, from the transformation of Mature Harappan urban settlements after c. 1900 BCE toward early Vedic-era communities. This is a **gradual, regionally varied historical transition**, not a single invasion or abrupt replacement. Broader project eventually continues toward Chandragupta Maurya and Kautilya.

## Gameplay decisions
- Keyboard: A/D or left/right move; W/up jump; S/down duck/inspect/excavate. Numpad equivalents supported. Mouse/touch also usable in menus and dialogue.
- Phone: on-screen touch controls.
- Walking speed stays comfortable; **historical year progression must be much slower**, with a consistent, documented map scale.
- Interact only when the player character is over/adjacent to an object, allowing 1–2 native pixels of tolerance.
- Starting an interaction freezes movement **and** the date.
- Dialogue stays on-screen; ensure letters are sharp, not blurry.
- Inventory tabs: physical objects, knowledge, journal, timeline, privileges/awards.
- Knowledge can reveal information in locations previously visited.
- Historical NPCs use calendars and dating conventions appropriate to their own cultures; BCE/CE remains visible to the player.
- No player death required.
- Keep art simple 8-bit/pixel style; layered landscapes and monuments change with time.

## Historical integrity
- Clearly distinguish evidence-based claims, reconstructions, and unknowns.
- Harappan urban decline was not the disappearance of its population.
- Indo-Aryan-speaking migrations were complex and spread across time; avoid presenting newcomers as a single army from modern Iran responsible for destroying Harappan cities.
- Source historical claims when adding educational content.

## Development workflow
- Keep a small, playable, phone-friendly HTML/JavaScript prototype.
- Develop features incrementally and test keyboard/touch behavior.
- Add code on a branch and submit a pull request for review once the initial project is bootstrapped.
- Render deployment and Drive storage will be configured once destinations are shared.
