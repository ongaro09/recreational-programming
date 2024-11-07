
# Building Fantansy Quest

I will be building a game, piece by piece, called "Fantasy Quest", which is a text-based adventure game.

## Game Principle

The game follows the premise of a combat system where players(or warriors) have to fight to live.
They are equipped with a sword, and as is often the convention, their health is paramount.

```health_after_attack = player_health - sword_damage```

Now, we may need to deal bonus damage when a sword is enchanted with a power spell (to be developed later).

The first dialogue happens between the game hero, called "Makmende" and an Owl. A talking Owl.
```
Okra : Aye aye!

Makmende: ...

Okra: Where are you off to this morning?...

Makmende : Where did an owl learn to speak?

```

When the hero walks through poison, their health should reduce by a given factor `n`.
