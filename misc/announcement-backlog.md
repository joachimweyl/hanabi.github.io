# Introduction

As noted in the [convention changes document](convention-changes.md), sometimes a change to the conventions is made but is not yet announced due to there being a backlog of things to announce. This document contains the backlog.

<br />

## The Backlog (General Conventions)

@everyone New conventions:

**The Duplicitous Value Clue** (by pianoblook)

```text
- Normally, we do not give _Play Clues_ to duplicated cards, as that would violate _Good Touch Principle_.
- However, in some situations, it is possible to give a _Play Clue_ to Bob and trick him into playing a duplicated card. If while doing so, the clue also picked up one or more other valuable cards, then this would be a _Duplicitous Value Clue_.
- We agree that as long as this kind of clue meets _Minimum Clue Value Principle_ (not counting the duplicated card itself), no further _Prompts_ or blind-plays are called for - the point of the clue was to simply "lock in" a save on the valuable cards.
- For example, in a 3-player game:
  - Red 2 and blue 2 are played on the stacks.
  - Alice holds a globally-known red 3.
  - Alice clues number 3 to Bob as a _Play Clue_, touching 2 cards.
  - Bob plays the focused 3, assuming that it is the blue 3. However, it is actually red 3, and it successfully plays on the stacks.
  - Although this was unexpected, the team sees that this was a _Duplicitous Value Clue_, since there is sufficient value in "locking in" a save on Bob's other 3.
  - Bob marks his other 3 as **any** useful 3. It is not promised to be playable. (Thus, no-one will think that it is a _Prompt_ or a _Finesse_.)
- For _Duplicitous Value Clues_ that do **not** meet _Minimum Clue Value Principle_, see the _[Dupe Tempo Clue Principle](#dupe-tempo-clue-principle)_ section below.
```

**The Duplicitous Blind-Play** (by pianoblook)

```text
- In the _Duplicitous Value Clue_, a duplicated card is clued directly (in order to "get" some other cards). Similar to this, it is also possible to get a duplicated card to blind-play (in order to "get" some other cards). This is called a _Duplicitous Blind-Play_.
- _Duplicitous Blind-Plays_ function the same way as _Duplicitous Value Clues_ in that as long as the clue meets _Minimum Clue Value Principle_, no further _Prompts_ or blind-plays are called for.
- For example, in a 4-player game:
  - Red 2 and blue 2 are played on the stacks.
  - Alice holds a globally-known red 3.
  - Alice clues blue to Donald, touching a blue 4 as a _Play Clue_.
  - Bob blind-plays his _Finesse Position_, expecting it to be a blue 3 as a _Finesse_. Instead, it is a red 3, and successfully plays on the stacks.
  - Although this was unexpected, the team sees that this was a _Duplicitous Blind-Play_, since there is sufficient value in "locking in" a save on Donald's blue 4.
  - The team knows that blue 4 is not promised to be playable. (Thus, no-one will think that it is a _Prompt_ or a _Finesse_.)
- Note that _Duplicitous Blind-Plays_ can also be performed with certain _Ejections_, _Discharges_, and so on.
```

**The Duplicitous Tempo Clue** (by pianoblook)

```text
- First, see the section on the _[Duplicitous Value Clue](#duplicitous-value-clue)_ and the _[Duplicitous Blind-Play](#duplicitous-blind-play)_.
- In the _Duplicitous Value Clue_ and the _Duplicitous Blind-Play_, one or more "extra" valuable cards are touched for later. But what if this type of move is performed, but no additional valuable cards were touched?
- If a filled-in card is revealed as playable, the clue should retroactively be treated as a _Tempo Clue_. Thus, this type of clue is called a _Duplicitous Tempo Clue_.
- _Duplicitous Tempo Clues_ may or may not cause a _Tempo Clue Chop Move_. (The conditions for this are the same as a "normal" _Tempo Clue_.)
- For example, in a 3-player game:
  - Red 1 and blue 1 are played on the stacks.
  - Cathy holds a globally-known red 2.
  - Bob holds a previously-touched green 2, but its rank is not yet known.
  - Alice clues number 2 to Bob, touching one new card, and also "filling in" the green 2.
  - Bob knows that this is a _Play Clue_ on the blue 2. He plays it, but it is actually a red 2, and successfully plays on the stacks.
  - Bob's first thought was that this was a _Duplicitous Value Clue_, but no other new cards were touched as part of the clue. Thus, Bob knows that this is a _Duplicitous Tempo Clue_ instead.
  - Since Bob's green 2 was _Promptable_ and Alice was not in a valid stalling situation, Bob treats this as a _Tempo Clue Chop Move_.
```

**The Assisted Trash Chop Move** (by pianoblook)

```text
- _Trash Chop Moves_ can be very useful, but sometimes they can be "blocked" when there is no way to cleanly clue the known trash.
- In this situation, the problem can be solved by using a _Trash Bluff_ or an _Unknown Trash Discharge_ to get a duplicated card to blind-play. This is called an _Assisted Trash Chop Move_.
- Since no "extra" cards are touched as part of the move (like in an e.g. _Duplicitous Value Clue_), the point of the clue should be clear to the team: a _Trash Chop Move_ on all cards to the right of the clued card(s).
- For example, this is an _Assisted Chop Move_ from a _Trash Finesse_ in a 3-player game:
  - Blue 1 is played on the stacks.
  - Alice holds a globally-known yellow 1.
  - Cathy's hand is, from newest to oldest: `red 5, green 3, blue 1, yellow 4, green 4`
  - Alice clues number 1 to Cathy, touching the blue 1 as a _Play Clue_.
  - Bob knows that since the blue 1 was represented as a good 1, this must be a _Trash Finesse_, and Bob must have a red 1, a green 1, a yellow 1, or a purple 1 on his _Finesse Position_.
  - Bob blind-plays his _Finesse Position_. To his surprise, it is a yellow 1 and it successfully plays on the stacks.
  - Since yellow 1 was duplicated, the rest of the team knows that something unusual has happened. However, since no additional cards were touched as part of the clue, everyone knows that it was an _Assisted Chop Move_ on Cathy. (In this case, Cathy should _Chop Move_ slot 4 and slot 5.)
- For example, this is an _Assisted Chop Move_ from an _Unknown Trash Discharge_ in a 3-player game:
  - Blue 1 is played on the stacks.
  - Alice holds a globally-known yellow 1.
  - Cathy's hand is, from newest to oldest: `red 5, green 3, blue 1, yellow 4, green 4`
  - Alice clues blue to Cathy, touching the blue 1 as a _Play Clue_.
  - Bob knows that since blue 1 was represented as blue 2, this must be an _Unknown Trash Discharge_.
  - Bob blind-plays his _Third Finesse Position_. To his surprise, it is a yellow 1 and it successfully plays on the stacks.
  - Since yellow 1 was duplicated, the rest of the team knows that something unusual has happened. However, since no additional cards were touched as part of the clue, everyone knows that it was an _Assisted Chop Move_ on Cathy. (In this case, Cathy should _Chop Move_ slot 4 and slot 5.)
```

**The Time Travel Chop Move (Direct Form)** (by pianoblook)

```text
- Normally, a _Duplicitous Clue_ "gets" an extra card or "fills in" another card as a _Tempo Clue_. However, if a _Duplicitous Clue_ is performed that does not accomplish either of these things, it must have been done for some other reason.
- In this situation, after the duplication reveals itself, the clued player should interpret the clue as a _Trash Chop Move_ on their own hand. (In other words, they should pretend like the duplicated card was clued directly as a _Trash Chop Move_.)
- For example, in a 3-player game:
  - All of the 2s are played on the stacks.
  - Cathy holds a globally-known red 3.
  - Alice clues number 3 to Bob, touching a new 3 as a _Play Clue_.
  - Bob plays his 3, expecting it to be any 3 other than red. However, it is actually red 3, and successfully plays on the stacks.
  - Since this move was a 0-for-1 and did not provide tempo on any cards, everyone knows that this was a _Time Travel Chop Move_. Bob _Chop Moves_ all the cards that were behind his red 3.
```

**The Time Travel Chop Move (Blind-Play Form)** (by pianoblook)

```text
- Normally, a _Time Travel Chop Move_ involves cluing the duplicated card directly. But what if the duplicated card is "blocked" with no way to cleanly clue it?
- In this situation, players can cause the duplicated card to blind-play instead of cluing it directly, which should accomplish the same thing (i.e. the cards to the right of the duplicated card being _Chop Moved_). However, care has to be taken to ensure that the end result is truly "bad" enough to not be misinterpreted as another kind of clue.
- Specifically:
  - The clue must not satisfy _Minimum Clue Value Principle_ (similar to a _Duplicitous Clue_).
  - The clue must not look like an _[Assisted Trash Chop Move](#the-assisted-trash-chop-move)_ on the clue receiver.
- For example, in a 4-player game:
  - All of the 1s are played on the stacks. Donald has a known blue 2.
  - Bob has a previously-clued red card in his hand, but does not know the rank of the card.
  - Alice clues number 3 to Bob, "filling in" the red card as the red 3. (The clue touches no other cards.)
  - Bob knows that this is a _Finesse_ on the red 2 into the red 3. Bob blind-plays his _Finesse Position_, but it is a blue 2 instead of a red 2, which successfully plays on the stacks.
  - Since the move was a 0-for-1, Bob understands that he should _Chop Move_ everything that was behind the blue 2 as a _Time Travel Chop Move_.
```

<br />

## The Backlog (Variant-Specific Conventions)

n/a

<br />
