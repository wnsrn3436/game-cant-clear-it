# Can't Clear It

[한국어](README.ko.md)

A game entered in a GameMaker community event. The concept was exactly what the title says: a game that can't be cleared. You have to push through a field packed with red walls and bouncing balls.

<p>
  <img src="docs/screenshots/screenshot-1.png" width="480" alt="Gameplay">
</p>


## How to play

Download it from Releases and run it.

Move with the arrow keys and fire the shotgun with space. You can't fire while running, and touching a ball kills you.

The shotgun has one rule: bullets that overlap cancel each other out. If you spam the trigger, your bullets hit each other and all vanish right in front of you. Fire one shot at a time with a gap between shots and they travel far.


## How it works

All it takes is a collision event on the bullet object against itself, with an action that destroys the instance. The event runs for both bullets in the collision, so both vanish. That one action gave the game a rule where you have to watch the timing of your shots, and the rule also fits the idea of a game that can't be cleared.


## Files

| Path | Contents |
|---|---|
| `source/cant-clear-it.gmk` | Original project file |
| `source/split/` | Text tree split out with GmkSplitter |
| `docs/screenshots/` | Screenshots |
| Releases | Files for distribution |


## License

CC BY-NC-ND 4.0. Unmodified copies may be shared for noncommercial purposes with attribution. Distributing modified versions and commercial use are not allowed. Bundled libraries, graphics, sounds, and maps made by other people keep their own rights. See [LICENSE](LICENSE).
