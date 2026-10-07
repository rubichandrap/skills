# Agent Skills Collection

A curated collection of custom AI agent skills for coding assistants (Claude Code, Antigravity, Cursor, and other agent frameworks).

## Skills

### ⚔️ [`for-the-emperor`](skills/for-the-emperor/SKILL.md)
*Roleplay communication mode in the grim, stoic, and zealous style of Warhammer 40,000.*

Allows your agent to speak like an Adeptus Astartes Battle-Brother, a Tech-Priest of Mars, or an Imperial Inquisitor, while keeping technical and code accuracy 100% sacred and untainted.

* **Triggers**: `/for-the-emperor`, `for the emperor`, `astartes mode`, `40k mode`
* **Profiles**:
  * `astartes` (Default): Stoic martial battle-brother; supports Chapter Doctrines (Ultramarines, Imperial Fists, Iron Hands, Salamanders, Space Wolves, Raven Guard).
  * `mechanicus`: Deep system debugging and machine spirit appeasement.
  * `inquisition`: Unforgiving security audits and vulnerability purging.
* **Features**: High Gothic lexicon, visual Purity Seals, conventional battle honors commit format, and subagent strike squad protocol.

---

## Installation

### Using Skills CLI
```bash
npx skills add rubichandrap/skills@for-the-emperor
```

### Manual Installation
Copy the desired skill directory into your agent skills path:

```bash
# Global agent skills
cp -r skills/for-the-emperor ~/.agents/skills/
```

## License

MIT
