# Can't Clear It

Made for a GameMaker community event with the idea of building a game that, as the title says, cannot be cleared. You have to push through a field packed with red walls and bouncing balls.

<p>
  <img src="docs/screenshots/screenshot-1.png" width="480" alt="Gameplay">
</p>


## How to play

Download from Releases and run it.

Move with the arrow keys and fire the shotgun with space. You cannot fire while running. Touching a ball kills you.

The shotgun has one rule: bullets that overlap cancel each other out. Fire wildly and your bullets collide with each other and vanish right in front of you. Space your shots out and they travel far.


## How it works

The bullet object has a collision event with itself that destroys the instance, and that is all there is to it. The event runs on both bullets that touched, so both vanish. A single action creates a rule that makes firing rhythm matter, which fits the concept of a game that cannot be cleared.


## Files

| Path | Contents |
|---|---|
| `source/cant-clear-it.gmk` | Original project file |
| `source/split/` | Text tree produced by GmkSplitter |
| `docs/screenshots/` | Screenshots |
| Releases | Distributed build |


## License

CC BY-NC-ND 4.0. Unmodified copies may be shared for noncommercial purposes with attribution. Modified versions and commercial use are not allowed. Bundled libraries, graphics, sounds, and maps made by other people keep their own rights. See [LICENSE](LICENSE).
