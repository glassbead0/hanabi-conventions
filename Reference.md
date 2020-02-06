# Strategy Reference for the Hyphen-ated Group

Our group has come up with many different strategies. It is helpful to give specific names to each strategy to aid in both discussion and comprehension. If you know the general way we play but don't know about a specific kind of move, then you can look it up in this document.

If you are a new player, do not bother reading this document. It is much better to simply read the [introductory document](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md) and then start playing games with the group. This document can be used as a reference as you continue to naturally improve at the game.

Note that convention updates for the group are listed in the `#announcements` channel on the [Hanabi Discord server](https://discord.gg/FADvkJp). (You can also review the [commit history](https://github.com/Zamiell/hanabi-conventions/commits/master) of this repository.)

<br />

## Table of Contents

1. [First Principles](#first-principles)
2. [Examples](#examples)
3. [Level 1 - Beginner Strategies](#level-1---beginner-strategies)
4. [Level 2 - Intermediate Strategies](#level-2---intermediate-strategies)
5. [Level 2 - General Principles](#level-2---general-principles)
6. [Level 2 - Common Mistakes & Illegal Moves](#level-2---common-mistakes--illegal-moves)
7. [Level 3 - Advanced Strategies](#level-3---advanced-strategies)
8. [Level 4 - Expert Strategies](#level-4---expert-strategies)
9. [Level 5 - Rarely Used Strategies](#level-5---rarely-used-strategies)
    * [Save Clues & Non-Emergency Chop Moves](#level-5---rarely-used-strategies-save-clues--non-emergency-chop-moves)
    * [Finesses & Bluffs](#level-5---rarely-used-strategies-finesses--bluffs)
    * [Pushes & Pulls](#level-5---rarely-used-strategies-pushes--pulls)
    * [Emergency Moves](#level-5---rarely-used-strategies-emergency-moves)
    * [Ejection](#level-5---rarely-used-strategies-ejection)
    * [Discharge](#level-5---rarely-used-strategies-discharge)
    * [Miscellaneous](#level-5---rarely-used-strategies-miscellaneous)
10. [Variant-Specific Strategies](#variant-specific-strategies)
11. [Convention Attribution](#convention-attribution)

<br />

## First Principles

In general, we want all of our strategies to flow from some basic principles. That way, new players can just learn the first principles, and then use logic and reasoning to find out the resulting strategy that their teammate is intending. However, there are a few wrinkles with this:

1) Some of our strategies are arbitrary and do not flow from the first principles. So take the phrase "First Principles" with a grain of salt.
2) Since the principles are a little abstract, they are more useful as a reference than as an actual guide on how to play Hanabi with our group - this is what the [introductory document](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md) is for.

<br />

### 1. Chop Principle

* The "chop" is the right-most unclued card.
* When a player needs to discard and has no known safe discards, they should discard the chop card.

### 2. Minimum Clue Value Principle

* A given clue must either:
  * indicate sufficient information for **one or more previously unclued** cards to be played (as a *Play Clue*)
  * prevent the possible discard of a card that needs to be saved (as a *Save Clue*)

### 3. Save Principle

* Cards that meet the following criteria must not be discarded:
  * only one copy remains (e.g. 5's or unplayed cards in the discard pile)
  * it is a 2 and not visible elsewhere in players' hands
  * it is currently playable and not visible elsewhere in players' hands
* When a card that needs to be saved is at immediate risk of being discarded, it must be indicated with a *Save Clue*.
* A player receiving a clue that could be either a *Save Clue* or a *Play Clue* **must** consider both possibilities. Specifically, this means that the player must hold on to the card until they know for sure.

### 4. Good Touch Principle

* A safe discard is defined as:
  * a copy of a card that has already been played
  * a copy of a card that is in someone's hand and has been clued
* Safe discards should **not** be clued (unless there's an important reason to).
* Players should generally assume that any clued card in their hand will be eventually be played.

### 5. Play Order Principle

* When a *Play Clue* touches multiple cards, if it includes the chop, it's focused on the chop. (This is referred to as the *Chop-Focus* convention.)
* Otherwise, the clue is focused on the newest (e.g. left-most) of the freshly-introduced cards.
* The non-focused cards may or may not be playable.

### 6. Left-Most Playable Principle

* When a player is expected to play a card (or know a card is playable) in a situation not covered by the *Play Order Principle*, the card to be played is the left-most of the various cards that are most likely to be it.

### 7. Information Lock Principle

* What is indicated by a clue is determined by the known information at the time the clue is given. Subsequent clues may build upon that information, but do not override it unless a direct conflict is evident.

### 8. Good Lie Principle

* When a *Play Clue* is given, it's a message that says the card is playable. Sometimes this message can be a lie, in order to usefully manipulate other players.
* Valid lies must not allow for the possibility of any misinformed player to give a conflicting clue or misplay. In simpler terms, this means that good lies almost always reveal themselves on the very next turn.

### 9. High Value Principle

* The highest value clue is expected. If a clue is given, it should be interpreted to be the highest value move available to that player.
* In other words, you can draw many important conclusions from the fact that a player did not do some other (potentially higher-value) move.

<br />

## Level 1 - Beginner Strategies

* Level 1 strategies can be learned with no games of Hanabi played. You can either learn them before you play your first game or after you play a few games to learn the basic mechanics.

### Chop

* As outlined in the [beginner guide](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md), when players have to discard, they typically discard their right-most unclued card.
* A player's chop card is formally defined as **the next unclued card that they would discard if they had nothing to do**.
* If a player has a clued card that is known useless, then they will typically discard the useless card **instead** of discarding their chop. (But the useless card does **not** count as the chop - their chop remains the right-most unclued card.)

### The Prompt

* The *Prompt* is a move covered in the [beginner guide](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md). It is when you get a player to play a clued card that was previously unknown.

### The Finesse

* The *Finesse* is a move covered in the [beginner guide](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md). It is when you get a player to blind-play a card to fulfill a promise that a certain card is playable right now.
* *Finesses* must be on "matching" cards. (For example, the red 1 leads directly leads into the red 2, so they are considered to be a "matching" pair of cards.)

### Finesse Position

* As covered in the [beginner guide](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md), a player's *Finesse Position* refers to the slot that their left-most unclued card is in.

<br />

## Level 2 - Intermediate Strategies

* Level 2 strategies should only be learned if you have played with the group a few times and have got the basics down. (5-10 games of experience or more.)
* This level contains the moves that compose our "core" repertoire. While these moves may not be used in every single game, the complexity level of all of them is fairly low, so start to get familiar with them.

### 2 Saves

* As explained in the beginner's guide, *2 Saves* must be given with a number 2 clue.
  * The exception to this rule is when the other copy of the 2 is in the discard pile. Then you can do a "normal" *Save Clue* on the 2 with a color clue.
* Players are **not allowed** to perform a *2 Save* on a 2 if the other copy of the 2 is visible in someone else's hand.
  * The exception to this rule is when the same 2 is on two people's chops at the same time. In that situation, players are allowed to *2 Save* whichever one they want. And if it is the *Early Game*, then players **must** choose to save one of them before initiating the *Mid-Game*.

### Fix Clues

* Nearly every clue that is given is either a *Save Clue* or *Play Clue*. One small exception to this is a *Fix Clue*, which is an attempt to "fix" an impending misplay.
* *Fix Clues* are often needed when a duplicate card is touched. Cards are not normally duplicated (which follows from *Good Touch Principle*), but sometimes someone makes a mistake, or a sequence of particular cards makes duplicating necessary. Duplicate cards will lead to misplays, so it is the team's responsibility to fix the problem and intervene before this happens.

<img src="img/intermediate/fix_clue.png" height="300" />

* In the above screenshot:
  * Before the clue was given, Alice had an unknown purple card in her hand.
  * From *Good Touch Principle*, Alice concluded that her card must be purple 5, and had planned to play it as soon as possible.
  * Bob clues number 3 to Alice, which "fills in" the purple card and reveals that it is purple 3.
  * Since Alice was just about to play this card, Alice knows that this was a *Fix Clue* and that she can now safely discard the purple 3.

<img src="img/intermediate/fix_clue2.png" height="300" />

* **A clue cannot be a *Play Clue* and a *Fix Clue* at the same time.** If you receive a *Fix Clue* and it touches other ancillary cards, none of them are necessarily playable; the primary point of the clue is to fix the impending misplay.
* In the above screenshot:
  * Before the clue was given, Alice has an unknown 1 in her hand.
  * From *Good Touch Principle*, Alice concluded that her 1 must be green 1, and had planned to play it as soon as possible.
  * Bob clues blue to Alice, which "fills in" the 1 and reveals that it is blue 1. The blue clue also touches a blue card on slot 1.
  * In this situation, Alice might be tempted to think that this is a *Play Clue* on a blue 2 in slot 1, especially considering that the slot 1 card was the only brand new card introduced in the clue (and that the focus of a clue should always be on the brand new card introduced).
  * However, the fact that the blue clue "fixed" an impending misplay means that Bob may have had no choice but to clue blue, and he may not necessarily be trying to give a *Play Clue*.
  * Alice marks the blue card as either blue 2, blue 3, blue 4, or blue 5, and discards the blue 1.

### Fix Clues (That Give No Additional Information)

* Usually a *Fix Clue* will "fill in" the card to explicitly make it known that the card is unplayable or duplicated. However, it is also possible to perform a *Fix Clue* just by cluing the card again. For example:
  * Alice clues Bob number 1 and it touches three 1's.
  * Bob successfully plays two 1's.
  * Before Bob can play the 3rd 1, Alice clues Bob number 1 again, and all the clue does is re-touch the remaining 1.
  * Now it is Bob's turn. Since he was going to play the 1 already without Alice doing anything, the clue must have some other meaning. Thus, it is a *Fix Clue*: the remaining 1 is bad, and Bob can safely discard it.
* Note that in general, giving a *Fix Clue* should wait until the card is actually in danger of being misplayed (like in the previous example). If a duplicated card is not in danger of being misplayed anytime soon, then players should defer giving the *Fix Clue* until later. This way, it gives the player a chance to figure out the duplication on their own, which can happen from time to time.

### Playing Multiple 1's - Play Order Inversion in the Starting Hand (Part 1)

* If one or more 1's in your hand are clued, **you should assume that they are all playable**. (This only applies to 1's, and follows from *Good Touch Principle*.)
* We agree that playing 1's at the beginning of the game is a special case - you should always **play the 1's in your starting hand from oldest to newest**. (This is a special case because normally, *Play Clues* mean to play the left-most card.)

<img src="img/intermediate/playing_multiple_1s.png" height="150" />

* In the above screenshot, on the first turn of the game, Alice clues number 1 to Bob, which touches three 1s on slot 2, slot 3, and slot 4.
* From *Good Touch Principle*, Bob knows that he can now play all 3 of these cards.
* Bob should play the slot 4 card first, and then the slot 3 card, and then the slot 2 card.

### Playing Multiple 1's - The Fresh 1's Rule (Part 2)

* If two (or more) 1's are clued in someone's hand, and one of the 1's was in the starting hand, and one of the 1's was not, then the "fresh" card is probably more important. (Otherwise, the clue might have been given earlier.)
* Thus, freshly drawn 1's should always be played before any 1's that were present in the starting hand.
* Continuing on the example in the previous section, imagine that:
  * Bob plays the slot 4 card. (He then draws a card, and all of the other cards in his hand slide over.)
  * Alice clues 1's to Bob, which touches a brand new card on slot 1 and re-touches the ones on slot 3 and slot 4.

<img src="img/intermediate/playing_multiple_1s2.png" height="150" />

* Bob knows that fresh 1's have precedence, so he plays the slot 1 card next. After that, he should play the slot 4 card, and then the slot 3 card (e.g. resuming the play order from before).

### The Prompt + Finesse

* In general, remember that players will always assume *Prompts* over *Finesses*. Thus, is it possible to do a clue that *Prompts* a card from a player's hand **and then** gets them to blind-play their *Finesse Position* card on the next turn.
* For example, in a 3-player game:
  * Red 1 is played on the stacks.
  * Bob has a clued red card in his hand on slot 4.
  * Alice clues Cathy red, which touches a red 4.
  * Bob knows he must have both red 2 and red 3, but he only has one clued red card in his hand. So this must be both a *Prompt* on him and a *Finesse* on him at the same time.
  * Since *Prompts* take precedence over *Finesses*, he plays the clued red card first from slot 4 as red 2.
  * On his next turn, he blind-plays slot 2 as red 3. (His *Finesse Position* at the time of the clue was slot 1, but he drew a card, and now the red 3 slid down to slot 2.)

### The Reverse Finesse

* In a normal *Finesse*, you would give a clue to a player who comes after the player blind-playing a card. If you give a *Finesse* clue to someone who gets to have a turn **before** the blind-play occurs, it is called a *Reverse Finesse*. This is more complicated than a normal *Finesse* and is harder to see.
* Because *Reverse Finesses* exist as a strategy, before playing any cards, players should always check out everyone's *Finesse Position*. If a card in someone's *Finesse Position* is playable and "matches" the clue, then **they need to defer playing the clued card** for at least one go-around and wait to see what happens.
* If the player with the "matching" card blind-plays it, then it means that the clued card is the next card in the chain. For example, in a 3-player game:
  * It is the first turn and nothing is played on the stacks.
  * Alice clues Bob red, which touches his red 2.
  * Next, it is Bob's turn. Normally, Bob would think that he had the red 1, and play it immediately.
  * However, Bob also notices that on Cathy has a red 1 on her slot 1 position. Thus, he has to give a chance for Cathy to prove whether or not a *Reverse Finesse* is happening. If Cathy does not blind-play anything, then Bob should have the red 1, and he can play it on his next turn.
  * Bob discards.
  * Cathy blind-plays red 1. Bob now knows that he has the red 2.
* If the player with the "matching card" **does not** blind-play, then the clued card is probably the other copy, and can be played on the next turn. For example, in a 3-player game:
  * The setup is the same as the last example. Bob is clued red, so he suspects a *Reverse Finesse* is occurring and discards.
  * Cathy discards.
  * Now Bob knows that the red card in his hand is actually the red 1.

### The Self-Finesse

* It is also possible to perform a *Finesse* on a player by giving **them** a clue.
* For example, in a 3-player game:
  * All of the 1's are played on the stacks.
  * Alice clues number 3 to Cathy, touching one 3 on slot 2.
  * Bob discards.
  * Cathy knows that this was a *Play Clue* on the 3, but there are no 3's that are directly playable. Thus, someone must have the matching 2. Since Bob discarded, Cathy must be the one who has the matching 2.
  * Thus, Cathy plays her *Finesse Position* card as **any** 2. It is red 2 and successfully plays.
  * Cathy now knows that her 3 must match the 2, so she marks her 3 as red 3.
* Note that *Self-Finesses* can be difficult to perform because the player receiving the clue will **only** consider the possibility of a *Self-Finesse* **if there are no other possibilities** for the clue. For example:
  * If the clue looks like it *could* just be a normal/direct *Play Clue* on a card, then the clue receiver will not blind-play anything - they will just play the card that was clued.
  * If the clue looks like it *could* be a *Prompt*, then the clue receiver will not play anything and assume that it is a *Prompt*. (At least, until the other player has had a chance to play the *Prompted* card.)
  * If the clue looks like it *could* be a *Reverse Finesse*, then the clue receiver will not play anything and assume that it is a *Reverse Finesse*. (At least, until the other player has had a chance to blind-play the card.)

### Bluffs

* *Finesses* are quite efficient. So, when you see a playable card in someone's *Finesse Position* slot, you will often want to "get" the card with a *Finesse* (instead of cluing it directly). However, often times, the proper "connecting" card is not on the table.
* In this situation, you can perform an alternate strategy by lying to the next player. By cluing an unrelated, one-away from playable card, the next player will think that it is a *Finesse* and that they have the matching card, so they will blind-play their *Finesse Position* card. This is called a *Bluff*.
* After the card is blind-played, the player who received the clue will realize that something strange has happened - the type of clue **did not match** the card that was blind-played. Thus, the clued card is not currently playable and must be a one-away from playable card.
* For example, in a 3-player game:
  * All the 2's are played on the stacks.
  * Alice clues Cathy red, which touches a red 4 as a *Play Clue*.
  * Next, it is Bob's turn. Bob sees that, with this red clue, Cathy has just been signaled that she has the red 3.
  * From Bob's perspective, this looks like a *Finesse* - if Bob does not blind-play the red 3 right now, Cathy will go on to misplay the red 4 as the red 3.
  * Bob blind-plays his slot 1 card. However, it is not the red 3, it was the blue 3! Now Bob knows that he has been *Bluffed* by Alice.
  * Next, Cathy sees that Bob just blind-played a blue 3 immediately after this red clue, so she knows that she must have a one-away from playable red card - the red 4. Cathy holds on to the red 4 for later and discards.
* Except in rare circumstances, ***Bluffing* is only permissible when you are the person directly before the player who is blind-playing a card**. This is called being in *Bluff Seat*. Do not *Bluff* unless you are in *Bluff Seat*! (This follows from *Good Lie Principle*.)

### Choosing between 2 equal value play clues

* If there are 2 equaly value play clues available to give, for example, you can give a 1-for-1 play clue on a green 2 in Bob's hand on, or a 1-for-1 play clue on a blue 2 in Cathy's hand, there are a few factors to consider when deciding which clue to give.
* If one of the cards leads into another playbable card that is visible, but not yet clued, you should lean towards cluing that one, although other circuumstances might make you choose otherwise.
* All other things being equal, if there are 2 equal value 1-for-1 clues to give, you should give the clue on the card that is closer to chop, because that one is in more danger of moving it's way to chop and being discarded. For Example:
   * Blue 1 and Green 1 are played on the stacks.
   * Nobody has any clued cards
   * Bob has Blue 2 on slot 4, Cathy has Green 2 on slot 2
   * Alice clues blue to Bob, touching his Blue 2 on slot 4 as a play clue. This is better than cluing Cathy Green, since the team has more time to give that clue.
   
 * The exception to this rule is when 2 players each have a copy of the same playable card, and you can choose which player to give the clue to. In this case, you shoudl give the clue to the player who's card is *farthest* from chop. This allows the other trash copy of the card to be discarded sooner, rather than filling up someones hand for a long time

### The Early Game (Intermediate Section)

* The *Early Game* is introduced in the beginner's document. In short:
  * The *Early Game* is defined as the period of time before the first discard happens.
  * Players **must** "extinguish" all of the available *Play Clues* and *Save Clues* on the board before ending the *Early Game*.
* As an intermediate player, you should note that:
  * Misplaying a card **does not count** as ending the *Early Game*.
  * Discarding known trash **does not count** as ending the *Early Game*.
  * Doing special discards that "transfer" cards to other players **does not count** as ending the *Early Game*.

### 5 Stalls (Intermediate Section)

* As mentioned in the beginner document, *5 Stalls* are when a player clues an off-chop 5 purely because they want (or need) to give a stall clue.
* *5 Stalls* are usually done in the *Early Game*, but they can also be done in the *Mid-Game* if a player is in a special situation where they are not allowed to discard.
* *5 Stalls* **cannot** be given if there are any playable 5's. In this situation, a number 5 clue would just look like a *Play Clue* on the 5.
* *5 Stalls* **must** be given to the 5 that is closest to chop. For example, in a 3-player game:

### The Chop Move

* Normally, players discard their oldest (right-most) unclued card. However, sometimes a player can know that an unclued card is very important.
* A *Chop Move* is a special kind of move that indicates to a player that the unclued card that is currently on their chop is very important.
* After the *Chop Move*, the player considers the card on their chop to be touched with an "invisible" clue. Thus, their chop will "move" to the next right-most unclued card.
* A *Chop Move* is permanent, meaning that a *Chop Moved* card should not be discarded for the remainder of the game.
* Several kinds of *Chop Moves* are listed below.

### The Trash Chop Move

* See the *Chop Move* section above for an explanation on what a *Chop Move* is.
* In the middle of a game, if all of the 1's have been played already, and someone clues a 1, this is quite strange. (From *Good Touch Principle*, players are not supposed to touch cards that have already been played.) In this situation, the 1 is considered "trash".
* The clue must have some deeper meaning. We agree that it means that the cards to the right of the trash are important. The point of the clue was to give the player a safe discard.
* However, in addition to giving a safe discard, it should also *Chop Move* **all** of the cards to the right of the trash.
* For example, in a 3-player game:
  * All of the 1's are played.
  * Bob has a completely unclued hand.
  * Alice clues 1's to Bob, which touches a 1 in his slot 4.
  * Bob *Chop Moves* his slot 5.
  * Bob discards the 1.
  * Bob's chop is now his slot 4.
* Most of the time, the *Trash Chop Move* is done for a single card (meaning that the trash card that was clued was one-away from chop). However, you can also use the *Trash Chop Move* to *Chop Move* multiple cards. For example, in a 3-player game:
  * All of the 1's have been played on the stacks.
  * Bob has a completely unclued hand.
  * Alice clues 1's to Bob, which touches a 1 in his slot 1.
  * Bob *Chop Moves* his slot 2, his slot 3, his slot 4, and his slot 5 (a quadruple *Chop Move*).
  * Bob discards the 1.
  * Bob's chop is now his slot 1.
* This move is most commonly done with a number 1 clue because it is likely that in the middle of a game, all of the 1's will be already played. But it could also be done with a number two 2 clue if all the 2's are already played / accounted for. Or, it could be done with a red clue if all of the red cards are already played / accounted for. And so forth.
* Strategy wise, the *Trash Chop Move* is used for two main reasons:
  1) Sometimes there are multiple critical cards in a row on chop and it falls to one player to save all of them. In this situation, a multiple-card *Chop Move* could be the only way to do it.
  2) Some cards (e.g. a one-away from playable 3) are quite useful to the team, but "illegal" to touch directly (as touching them directly with a clue would imply that they are playable right now). If the game is going well, then it can be useful to "waste" a clue in order to have the card saved permanently.
* Note that you are **not** allowed to *Trash Chop Move* a card that you can just clue directly with a *Save Clue* (unless there are multiple critical cards in a row on chop and you have no other choice). This is because having some positive information is always better than having the card be a mystery.
* If a *Trash Chop Move* touches **multiple** trash cards, then it only *Chop Moves* the cards to the right of the right-most trash card. For example, in a 3-player game:
  * All the 1's are played on the stacks.
  * Bob has a completely unclued hand.
  * Alice clues 1's to Bob, which touches a 1 in slot 2 and a 1 in slot 4.
  * Bob **only** *Chop Moves* his slot 5 card.

### Chop Moves & New Clues

* See the *Chop Move* section above for an explanation on what a *Chop Move* is.
* Once a card has been *Chop Moved* and is no longer in danger of being discarded, it is treated as an already-clued card with regards to new clues given to that hand. For example, in a 3-player game:
  * All of the 1's have been played on the stacks.
  * Bob has a completely unclued hand.
  * Alice clues 1's to Bob, which touches a 1 in his slot 4.
  * Bob *Chop Moves* his slot 5.
  * Bob discards the 1.
  * Bob's chop is now his slot 4.
  * Cathy clues blue to Bob, which touches his slot 1 (the card he just drew) and his slot 5 (the card that was just *Chop Moved*).
  * Bob knows that the focus of the clue is always on the brand-new card introduced, so this is **not** chop-focus, and the focus of the clue is on slot 1.
  * Thus, Bob will play blue 2 from slot 1 on his next turn.

### Chop Moves & Prompts

* See the *Chop Move* section above for an explanation on what a *Chop Move* is.
* *Chop Moves* interact with *Prompts* & *Finesses* in a potentially confusing way. *Chop Moved* cards should **not** be played into *Prompts*, even though they are imagined to have an "invisible" clue on them. For example:
  * All the 1's are played on the stacks.
  * Bob has no cards clued in his hand, but he is *Chop Moved* for a mystery card on his slot 5.
  * Alice clues Cathy red, which touches a red 3.
  * Bob knows that he is promised the red 2. If this is a *Finesse*, then he has the red 2 on his *Finesse Position* (slot 1).
  * However, Bob is also *Chop Moved* for a card. Bob knows that *Chop Moved* cards have an "invisible" clue around them, and Bob also knows that *Prompts* are said to take precedence over *Finesses*.
  * So should he play his slot 1 as a *Finesse* or his slot 5 as a *Prompt*? In this situation, Bob knows that *Prompts* do not apply to *Chop Moved* cards, so Bob should play his slot 1.

### The 5's Chop Move

* See the *Chop Move* section above for an explanation on what a *Chop Move* is.
* Normally, we are only allowed to save 5's on chop (unless it is done with a *5 Stall* clue, which can happen in the *Early Game* and other "stalling" situations).
* So, if a number 5 clue is performed on a 5 that is not on chop, and it is **not** a stalling situation, then it will normally look like a *Play Clue* on that 5.
* However, if the 5 is **one-away** from chop (or, if two or more 5's are clued and the right-most 5 is one-away from chop), then we agree that it has a special meaning, and that the clue is **not** a *Play Clue* at all.
* Instead, it is understood that the clue is a *5's Chop Move*, and the player should *Chop Move* in a manner similar to the *Trash Chop Move*.
* Note that the *5's Chop Move* is different than the *Trash Chop Move* in that you can only chop move **one** card with it. Thus, if you clue a 5 and it is **two** (or more) slots away from the chop, then it is to be assumed to be a *Play Clue* on the 5.
* Similar to the *Trash Chop Move*, if a *5's Chop Move* touches **multiple** 5's, then it only *Chop Moves* the cards to the right of the right-most 5. For example, in a 3-player game:
  * All the 1's are played on the stacks.
  * Bob has a completely unclued hand.
  * Alice clues 5's to Bob, which touches a 5 in slot 2 and a 5 in slot 4.
  * Bob **only** *Chop Moves* his slot 5 card.

### The Scream Discard Chop Move (Deliberately Discarding Instead of Playing)

* See the *Chop Move* section above for an explanation on what a *Chop Move* is.
* The *Chop Move* outlined above is a tool to save multiple cards with one clue. However, sometimes you may not have a clue at all. One way to solve this situation is with a special kind of discard.
* Typically, discarding is a last resort. So, if you have a known playable card in your hand, you can send a powerful message to your teammate by discarding instead. This is called a *Scream Discard*. Since your teammate expected you to play the card, it is like screaming at them to let them know that things are very bad.
* The player being "screamed at" should permanently move their chop by one position.
* Furthermore, the player being "screamed at" is not allowed to discard on this turn. Instead, they must give a clue. If there are no normal *Play Clues* or *Save Clues* to give, then they are allowed to give "stall" clues, like a *5 Stall*. If there are no *5 Stalls* to give, they can even just "fill-in" some information on an already-clued card (and doing this should not cause a *Finesse*).
* Players are only allowed to *Scream Discard* for **cards that are playable or critical** (or a needed 2 that isn't seen anywhere else). (This follows from *Save Principle*.)
* Players are **not** allowed to *Scream Discard* for cards that are one-away from being playable.
* Sometimes, a player will discard with a known-playable card in their hand, but they are **not** intending a *Scream Discard* - it is some other special situation:
  1) It is not a *Scream Discard* if the next player **has** to generate a clue for cluing the next player after that. This is called a *Generation Discard*; see below.
  2) It is not a *Scream Discard* when the card that the player did not play was a "blind" card from a *Finesse* **and** the blind card could also be in the next player's *Finesse Position*. When this happens, the next player will usually want to blind-play their *Finesse Position* card, since this sequence of events indicates either an *Ambiguous Finesse* or a *Pass Bluff* (which are both covered later on).

### The Generation Discard

* Usually, if someone has a known playable card and they discard instead of playing that card, this would indicate a *Scream Discard Chop Move*.
* However, if playing the card (player 1) would cause the next player to discard (player 2) and the next player after that (player 3) to have a critical and/or playable card "ride" on chop, it is a very bad situation. Thus, the discard is **just** for the purposes of generating a clue so that player 2 can clue player 3.
* The *Generation Discard* is **only** to be used as a last resort. If player 3 has something else to do (like play a card or give some obvious clue), then player 1 should just play their card and let the card "ride" on chop.

### A Scream Discard Flowchart

[Here is a handy flowchart](https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/flowcharts/scream_discard_flowchart.png) for determining whether something is a *Scream Discard Chop Move* or a *Generation Discard*. (It also mentions a more advanced move called an *Echo Scream Discard Chop Move*, but you can safely ignore that for now.)

### The Tempo Clue (Re-cluing a Card to Play)

* *Tempo Clues* are defined as clues that "get" no new cards. Their purpose is to get 1 or more cards played that **already** had a clue on them.
* Note that *Tempo Clues* do **not** meet *Minimum Clue Value Principle*, so we do not generally perform them. However, in the following special circumstances, *Tempo Clues* have enough value to justify giving them:
  1. When it gets 2 or more clued cards to play
  2. When the clued card is "out of order" (meaning that it is impossible for a *Prompt* to get the card played)
  3. When the clued card was *Chop Moved* and it is now playable
  4. When playing the clued card would "unlock" someone's hand (see the section on *Locked Hands* later on)
  5. When the clue giver is in a situation that requires them to stall (e.g. the player is *Locked*, etc.)
* When a *Tempo Clue* touches multiple cards, the focus is on the left-most card.
  * The exception is if one of the cards was previously *Chop Moved*. In that case, the focus is on the left-most *Chop Moved* card.
* If a *Tempo Clue* touches multiple cards, it typically means that all the touched cards are playable. See the *Double Tempo Clue* section below.
* Since they are so inefficient, *Tempo Clues* done outside of the special circumstances listed above are assigned a special meaning. See the *Tempo Clue Chop Moves* section below.

### The Double Tempo Clue (Re-cluing 2+ Cards to Play)

* Typically, when a *Tempo Clue* is given that touches two or more cards, it means that **all** of the cards touched are playable in focus order.
* For example, in a 3-player game:
  * It is the first turn and nothing is played on the stacks.
  * Alice clues red to Bob, which touches slot 1, slot 2, and slot 3.
  * Bob plays red 1 from slot 1. The other two red cards in his hand could be nearly anything.
  * Cathy clues red to Bob, which does not introduce any new cards, but it does re-touch slot 2 and slot 3.
  * Bob knows that this is a *Double Tempo* clue. Both must be playable in order, so he must have red 2 in slot 2, and red 3 in slot 3.
* Note that the normal "play all the cards" interpretation does not apply in some special situations:
  * when the clue unlocks a player's hand
  * when the clue got 2+ cards played in total (using cards in someone else's hand)
  * when the clue touched a *Chop Moved* card; in this situation, **only** the *Chop Moved* card is playable


### Double Discard Situations

* Often times in Hanabi, two players will discard in a row. However, in rare cases, this can cause a perfect score to be lost.
* For example, in a 3-player game:
  * Alice has nothing to do. Alice discards her chop and it is a red 4.
  * Bob has nothing to do. Bob also has a completely unclued hand. Bob discards his chop and it is the other copy of the red 4.
  * Since both copies of the red 4 are discarded, it is no longer possible to get a perfect score. (The maximum score now is 23 instead of 25.)
  * Normally, someone on the team would give a *Save Clue* to Bob's red 4 before it could get discarded. But since Bob's turn was immediately after Alice's turn, no-one on the team had time to save it.
* In the above example, on Bob's turn, since Bob *could* have the red 4 on his chop, we would say that Bob is in a *Double Discard Situation* for the red 4.
* More formally, a *Double Discard Situation* is defined as when the previous player discards or misplays an unplayed card **and** the current player could be discarding the other copy of that card.
* Players agree to **never** discard in a *Double Discard Situation* if it has the potential to lower the maximum score. Instead, they must give some clue. If there are no normal *Play Clues* or *Save Clues* to give, then they are allowed to give "stall" clues, like a *5 Stall*. If there are no *5 Stalls* to give, they can even just "fill-in" some information on an already-clued card (and doing this should not cause a *Finesse*).
* Let's revisit the above example to show what Bob should have done:
  * Alice has nothing to do. Alice discards her chop and it is a red 4.
  * Bob has nothing to do (meaning that there are no normal *Play Clues* or *Save Clues* to give). Bob also has a completely unclued hand.
  * Bob's chop is his slot 5 card. Since Bob does not see the red 4 in anyone else's hand and Bob's slot 5 card has no positive or negative clues on it, it is possible that Bob's slot 5 card could be the red 4. Thus, Bob knows that he is currently in a *Double Discard Situation* for the red 4.
  * Since there are no normal *Play Clues* or *Save Clues* available, Bob looks around to see if he can give a *5 Stall*. Bob sees that Cathy has a red 5 on her slot 1, so he clues number 5 to Cathy as a *5 Stall*.
  * Cathy knows that since Bob was in a *Double Discard Situation* for the red 4, she should not read too closely into his clues. This number 5 clue must just be a *5 Stall* (as opposed to a *Play Clue* on the 5).

<br />

## Level 2 - General Principles

While the other sections in this document contain lists of special "moves", this section only contains general principles. We refer to them in post-game reviews and when thinking about the game.


### Efficiency

* A big part of Hanabi is of trying to be as efficient as possible. This means that players will generally try to "get" as many cards with one clue as possible.
* If you use one clue to get one card, we refer to that as a 1-for-1 clue. For example:
  * On the first turn of the game, Alice clues Bob number 1, touching one 1 as a 1-for-1.
* If you use one clue to get two cards, we refer to that as a 2-for-1 clue. For example:
  * On the first turn of the game, Alice clues Bob number 1, touching two 1's as a 2-for-1. (Bob will play both.)
* 3-for-1 clues are even better than 2-for-1 clues, and so forth. It is even possible to perform a 9-for-1 clue with advanced techniques.
* If a clue touches two cards but only one of them will play right now, it **still counts** as a 2-for-1. This is because we assume that all touched cards will eventually play from *Good Touch Principle*. For example:
  * On the first turn of the game, Alice clues Bob red, touching a red 1 on slot 1 and a red 5 on slot 2 as a 2-for-1. (Bob will only play the red 1 and save the other red card for later.)
* On Hanabi Live, the current efficiency is shown on the right side of the screen. Efficiency is calculated by the following formula:
  * `number of clues given / (number of cards played + number of unplayed cards with one or more clues "on" them)`
* **If efficiency is low, players should probably not perform 1-for-1 clues!** Instead, it is better to discard and try to let someone perform a *Finesse*.

### Tempo

* *Tempo* is a term used to describe the speed at which cards are played. (This is similar to how it is used in other games such as chess.)
* Hanabi can be thought of a race to get all the cards played before the time runs out. This means that even if the team is being extremely efficient, they can still lose the game if they are not playing their cards fast enough. Thus, players have to **strike a balance between efficiency and tempo**.
* At the beginning of the game, there is a lot of time left, so players will generally prefer clues that get a lot of efficiency over clues that get a lot of tempo.
* At the end of the game, there is almost no time left, so players stop caring about efficiency and start caring only about tempo.
* On Hanabi Live, "Pace" is shown at the right side of the screen, which is a measure of how many more discards can occur. Starting pace is calculated by the following formula:
  * `current score + cards in deck + number of players - maximum score`
* Even at the beginning of the game, players might prefer a clue that gets tempo over a more efficient clue if it will prevent the discard of some other useful card. It all depends on the context of the game!

### Misplay Cost Principle

* On a turn where a player misplays and accumulates a strike for the team, they could have discarded instead and generated a clue.
* So, if you can spend one clue to stop one misplay, the value comes out even.
* Thus, since there are only 2 strikes allowed and accumulating strikes limits flexibility, it is almost always worth it to spend one clue to stop one strike.
* If it would require two clues to stop an impending misplay, then as long as the strike would not lose the game, it is usually best to let the player misplay the card and get a strike.

### Stomping on a Finesse

* This is when a player clues a card directly that was going to be blind-played from a *Finesse*. Typically, this is a mistake, and it means that the player who gave the clue was not paying attention and failed to see that a *Finesse* happened at all.

### Lines

* During your turn, part of figuring out the best move involves looking into the future to see what the next player will do. If they discard, will it be okay? Is there some obvious clue that they will do? And so on.
* As you get better at Hanabi, you will need to do this prediction not just for the next player, but for an entire go-around of the table. And as you really get good at Hanabi, you will need to do this for as far in the future as you can reasonable predict. (Sometimes, this means 15 moves or more in the future.)
* Similar to chess, initiating a move in which you can predict the next sequence of moves is called initiating a "line".
* In post-game reviews, we will often compare and hypothetically "play through" two different lines to see which one is better.

### Discard Modulation

* Often times, either you or the player who comes after you can perform a clue. And the clue would have the same result if done by either player. So who should do it?
* One way to decide is to look at the next player's chop. Is their chop high-value, low-value, or useless? If it is high-value, then you should discard and let them give the clue. If it is low-value or useless, then you should give the clue and let them discard.
* "Stealing" clues in this way is called *Discard Modulation*. If other players are discarding to let you give all of the clues, you probably have a high-value chop.

### One-Away From Playable

* In general, 3's are pretty high value, and 4's are pretty low value.
* But combined with this, cards that are one-away from playable are pretty high value, and cards that are two-away (or more) are pretty low value.
* Thus, in some situations, a one-away 4 may be more valuable than a two-away 3.
* According to our conventions, it is illegal to clue a one-away from playable card as the focus of the clue without it being some kind of special move like a *Finesse* or *Bluff*. However, sometimes we still want to "save" these cards. Thus, they are prime targets for indirect saves like the *Trash Chop Move* or the *5's Chop Move*.
* However, in most cases, *Chop Moving* the valuable card just won't be possible. So in general, you should try to construct lines that protect high-value cards from being discarded for as long as possible.

### The All 4's Test

* According to *Save Principle*, the team must not let any critical and/or playable cards be discarded. So part of constructing a line is figuring out whether this might happen.
* When considering a line, it is not safe to assume that a player will clue anything in your hand. You should perform the *All 4's Test*: what would everyone do if I have all useless 4's in my hand? If a critical and/or playable card would get discarded, then the line has failed the test, and it is probably a bad idea.

### Schrödinger's Cat Principle

* Often times when you are given a clue, the card could be two or more things. For example:
  * In a no-variant game, a red *Play Clue* might indicate a red 2 or a red 3 depending on whether or not red 2 will blind-play from someone else's hand.
  * In a rainbow-game, a red clue might indicate either a *Play Clue* on a red 1 or a *Delayed Play Clue* on a rainbow 2 through another player's yet-to-be-played rainbow 1.
* After getting a clue, you should immediately mark all of the possibilities down on the card as a note.
* For all of your subsequent turns, you have to treat that card like it is **all of the possibilities** at the same time. This is a lot like the *Schrödinger's Cat* quantum physics analogy, which states a cat is both alive and dead at the same time, and you won't know until you actually open the box and look. Similarly, treat the unknown card as all the possibilities, and you won't actually know until the card is played.
* The implications of *Schrödinger's Cat Principle* is that players must be very careful - before playing a card, they will often have to wait for everyone else to have a turn to allow for the possibility of a *Prompt*, *Reverse Finesse*, and so forth.


### Team Distribution Principle

* In general, it is better for useful cards to be distributed **evenly** throughout the team. This is especially important in 5-player games.
* Thus, if one of your teammates has 3 out of 4 cards clued, it may be better for **them** to be the one giving the clues, and you to be the one discarding - even if their chop is known trash.
* There are multiple reasons for this. First, you don't want them to get a *Locked Hand*, which is generally bad. Second, if they continue to draw playable cards, the game may end before they get a chance to play them all.

### Bluff Seat and the Pang of Guilt

* As mentioned in the section on *Bluffs*, you are in *Bluff Seat* for a certain player if you are immediately before them.
* Before cluing a card directly, you should first consider if it is on *Finesse Position*. If it is, and you clue it directly, you may be "stealing" someone's *Finesse* or *Bluff*.
* Thus, in this situation, it may be better to discard and let the player in *Bluff Seat* get the card. If you do decide to clue the card directly, you should always feel a *Pang of Guilt*.

### End-Game Threshold (End Game)

* Towards the end of the game, the strategy of the team will change. In most games, you stop becoming concerned with efficiency and become more concerned with tempo - every card needs to play **right now** before the game ends!
* Thus, since clues can mean different things depending on whether you are in the *Mid-Game* or the *End-Game*, you need to be able to keep track of when the *End-Game* has arrived.
* A value called *Pace* is used to determine *End-Game* status. *Pace* is calculated by the following formula: `current score + cards in deck + number of players - maximum score`
  * On [Hanabi Live](https://hanabi.live), the user interface will calculate this for you on the right side of the screen.
* Pace is essentially the maximum amount of discards that can happen while still having a chance to get the maximum score.
* If pace is **less than the number of players**, the *End-Game* has arrived.
  * On [Hanabi Live](https://hanabi.live), pace will turn yellow when this occurs.
* If pace is **less than the number of players / 2**, you should be very careful with discarding. It might still be the best thing to do, but if there are enough clues in the bank, it is usually better to *Burn* a clue (meaning to deliberately waste a clue).
* If pace is 0, no more discards can happen in order to get the maximum score.
* If pace is below 0, it is impossible to get the maximum score.

### The Pace +1 Rule

* Players can use *Pace* to determine if it is safe to discard. In general, a group can discard down to pace 0 and still get a perfect score.
* However, as a rule, if pace is +1 and one of the players on your team **does not** have any playable cards, then you cannot discard - **you must let them perform the final discard**.
* If both you and another player do not have any playable cards, then you can do the final discard - the team won't be able to get a perfect score anyway. But if you you **could** have an unknown useful/playable card in your hand, then you should be very careful about discarding, because it could ruin a perfect score.

### Burning (End-Game Stalling) & Same-Suit Principle

* In the *End-Game*, often times there are still a lot of cards yet to be played. Thus, you need to be very careful when discarding, since by drawing a card you can make the game end before everyone has a chance to play all of the cards.
* If there are enough of clues available, you can choose to stall, by giving a low-value (or even a completely useless) clue. This is referred to as *Burning* a clue.
* The best way to give a useless clue is to re-clue cards which are already known to be playable.
* Give a *Burn Clue* if:
  * There is a possibility that the game can be completed without anyone discarding from now on.
  * You have two or more useful cards in your hand, and you want to follow *Team Distribution Principle*.
* Do not give a *Burn Clue* if:
  * The end-game has not started yet (see the *End-Game Threshold*).
  * You know that someone else will have to discard in the future.
  * There is only one more useful card in the deck and all of the useful cards in your hand are of the same suit as that card. This is known as *Same-Suit Principle*. For example:
    * You have two cards clued in your hand that you know to be red 3 and red 5.
    * The only useful cards left in the deck are two red 2's.
    * Here, there is no reason for you to stall, since the red 3 will **not** be played sooner if you stall.

### Recognizing *Finesses* on Other Players (Part 1)

* Sometimes, a player will give a clue that looks like it could be either a *Finesse* or a *Bluff*. Between these two moves, which should have precedence?
* For example, in a 4-player game:
  * All of the 1's are played on the stacks.
  * Cathy has a blue 2 on her *Finesse Position*.
  * Alice clues blues to Donald, highlighting a blue 3 as a *Play Clue*.
  * Now, it is Bob's turn.
* What to think **depends** on whether you are Bob or whether you are someone else on the team.
* First, let's consider the case of Bob, the very next player. Bob should **always assume a *Finesse* over a *Bluff***. From his perspective:
  * Bob knows that if this is a *Finesse*, then Cathy will blind-play the blue 2, and then Donald will know that he has the blue 3. If this is the case, Bob should not do anything special.
  * Bob also knows that if this is a *Bluff*, then Bob should blind-play his *Finesse Position* card immediately.
  * Bob knows that if there is any way that this could be a *Finesse* (the truth), he should **assume that the truth is being told**. Thus, Bob knows that it must be a *Finesse* on Cathy and should not blind-play anything.

### Telling the Difference Between a Finesse and a Bluff (Part 2)

* With the previous section in mind, let's switch examples and assume that Alice did a clue and then Bob blind-played a card.
* So secondly, we can consider the case of Bob **after** he has blind-played a card, which also extends to the rest of the team. How does everyone know whether Alice did a *Finesse* or a *Bluff* on Bob?
* The way to find out is to look at **whether the card that blind-played "matches" the clue that was given**. If the clue matches, then it is a *Finesse*. If the clue did not match, then it is a *Bluff*.
* If it is ambiguous whether or not the card matches, then the team should **always assume a *Bluff* over a *Finesse***. (Note that this is the opposite of the precedence in part 1!)
* Example 1:
  * Blue 1 is played on the stacks.
  * Alice clues Cathy about a blue card.
  * Bob blind-plays a blue 2.
  * This must be a *Finesse*, because **blue matches blue**. So Cathy should think that she has the blue 3.
* Example 2:
  * Blue 1 is played on the stacks.
  * Alice clues Cathy about a blue card.
  * Bob blind-plays a red 1.
  * This must be a *Bluff*, because **red does not match blue**. So Cathy should think that she has the one-away from playable blue card, blue 3.
* Example 3:
  * Rainbow 1 is played on the stacks.
  * Alice clues Cathy about a blue card.
  * Bob blind-plays a rainbow 2.
  * This must be a *Finesse*, because **blue matches blue**. So Cathy should think that she has the rainbow 3.
* Example 4:
  * Blue 2 is played on the stacks.
  * Alice clues Cathy about a 4.
  * Bob blind-plays the blue 3.
  * This must be a *Finesse*, because **3 matches 4**. So Cathy should think that she has the blue 4.
* Example 5:
  * Blue 2 is played on the stacks.
  * Alice clues Cathy about a 4.
  * Bob blind-plays the red 1.
  * This must be a *Bluff*, because **1 does not match 4**. So Cathy should think that she has the one-away from playable 4, the blue 4. (This is an example of a *Hard Bluff*, which is covered in more detail later.)
* Example 6:
  * Nothing is played on the stacks.
  * Alice clues Cathy about a 4.
  * Bob blind-plays the red 1.
  * This **cannot** be a *Bluff*, because there are no one-away from playable 4's. So even though 1 does not match 4, this must be a *Finesse*, because Alice is not allowed to perform a *Bluff* with any card that she wants.
  * Cathy does not see any other red cards in Bob's hand. So Cathy should think that she has the red 4, because that would match the blind-play of a red 1. Subsequently, Cathy must have red 2 on her *Finesse Position* and red 3 on her *Second Finesse Position*.

### Urgency Principle (How to Tell If Someone Is Finessed)

* Normally, when a *Finesse* or *Bluff* occurs, someone blind-plays right away. This is extremely important, because it resynchronizes the information amongst the team. So, as a group, we always agree to blind-play our cards are soon as reasonably possible. This is called *The Urgency Principle*.
* Thus, if you see that a player does **not** blind-play into the *Finesse* or *Bluff*, then you know that the *Finesse* must be **on you**.
* However, there are some important exceptions:
  1) Players are allowed to **defer** playing into a *Finesse* or *Bluff* if they are doing a *Finesse* or *Bluff* of their own (and no-one else on the team could have done it).
  2) Players are allowed to **defer** playing into a *Finesse* or *Bluff* if they are doing something really important, like saving a 5 on chop, giving a *Play Clue* to a card that is about to be discarded, or something along those lines.
* So, if any of the above two conditions apply, then you have to **wait** and give the player yet another turn to demonstrate whether or not they will blind-play.

### Guide Principle

* Part of Hanabi involves making sure that if you perform an action, someone else on the team won't discard anything important (*Save Principle*). Additionally, part of Hanabi involves accounting for all the possibilities (*Schrödinger's Cat Principle*).
* Combined, these two principles usually result in players taking the most conservative possible approach, even if a certain action would have a very low risk of losing the game.
* One exception to the above rules is when Bob does not know whether or not a *Finesse* or *Bluff* is occurring. For example, in a 3-player game:
  * No cards are played on the stacks.
  * Alice clues red to Cathy, touching a red 2 as a *Play Clue*.
  * Bob does not see any red 1's in anyone else's hand. Thus, Bob knows that Alice intends for him to blind-play a card.
  * From Bob's perspective, it can be either a *Finesse* (on exactly red 1) or a *Bluff* (on the 1 of any of the other suits).
  * Cathy also has a critical 5 in chop.
  * If this is a *Finesse*, then Bob will blind-play the red 1, and Cathy will play the red 2. If this is the case, Cathy will never be at risk of discarding the 5 and losing the game.
  * If this is a *Bluff*, then Bob will blind-play some other 1, and Cathy will have nothing to do. If this is the case, then Cathy could discard and the team could lose the game.
  * Should Bob risk blind-playing or should he save the 5?
* In this example, it follows from *Save Principle* that Bob should "play it safe" and give a *5 Save* to the 5 and *then* try to blind-play the red 1 on the next turn.
* However, Bob also knows from *Good Lie Principle*, lies have to resolve immediately. If Bob saved the 5, and then blind-played on the next turn, and it turned out to be a *Bluff*, then the lie would not have resolved immediately. Thus, from *Good Lie Principle*, Bob can assume that this is a *Finesse*.
* Stated in a different way, Bob has to trust that Alice is successfully "guiding" the rest of the team with the line that she has chosen. This means that Bob is going to play exactly red 1 into the red 2. Alternatively, it could also be the case that it is a *Bluff*, but Cathy will not discard, and will clue some card in Bob's hand. Either way, the 5 will be safe. This is called *Guide Principle*.

<br />

## Level 2 - Common Mistakes & Illegal Moves

### The Wrong Prompt (Mistake)

* A common mistake in Hanabi is to attempt to perform a *Finesse* when there is a "matching" card in that player's hand. Since *Prompts* take precedence over *Finesses*, the player will always play their matching clued cards first.
* When a card is *Prompted* and it misplays, everyone can read into this mistake - it was almost certainly a *Wrong Prompt*, meaning that the player who gave the clue probably intended for the *Finesse Position* card to play instead.
* Thus, if there is nothing else special about the situation, the player who misplayed should go on to play their *Finesse Position* card on the next turn.

### Critical Discards after a Chop Move (Mistake)

* If a player *Chop Moves* a card, and then the next time they discard, they discard a critical card, then obviously some kind of mistake occurred.
* The best explanation is that the *Chop Move* was never intended in the first place.
* Thus, when this happens, the player should "undo" the *Chop Move*.

### Undoing a Chop Move (Mistake)

* Often times a player can misinterpret a clue as a *Chop Move* when it really had some other meaning. If this happens, after they discard their new *Chop*, everyone else on the team will know that an accidental *Chop Move* has occurred.
* Later on in the game, sometimes a player in this situation can retroactively realize that they have made a mistake by *Chop Moving* earlier on. They might be tempted to shift their chop back to where it is supposed to be.
* However, unless they discard a critical card (see the above section), players should generally **not ever undo a *Chop Move***, because they could be discarding a now-critical card that was not critical at the time of the original mistake. Everyone else on the team did not bother to clue the now-critical card, because they thought it was safely *Chop Moved*.

### Bluff Prompts / Prompt Bluffs (Illegal)

* It is illegal to trick players into thinking that they are *Prompted*. *Prompts* **must** be the truth.
* For example, in a 4-player game:
  * Red 1 and blue 1 are played on the stacks.
  * Bob has a clued 2 in his hand and does not know its true identity.
  * Alice clues red to Donald, touching a red 3 as a *Play Clue*.
  * Bob knows that this must be a *Prompt*, so his 2 must be red 2. He plays it, and it is instead the blue 2.
  * Cathy is slightly surprised that Bob played the blue 2, but he must have been able to figure it out somehow.
  * Furthermore, Cathy knows that Alice's clue to Donald must be a *Finesse*, so Cathy must have the red 2 on her *Finesse Position*. She plays it, and it is instead the blue 5 and misplays.
  * This was Alice's fault, because *Bluffs* are only allowed if they can be revealed immediately from a blind-play.

### Self-Bluffs with Color Clues (Illegal)

* It is possible (and fairly common) to perform a *Self-Bluff* on a player with a rank clue.
* For example, in a 3-player game:
  * Red 2 is played on the stacks.
  * Alice clues number 4 to Bob, which touches one brand new 4 as a *Play Clue*.
  * Bob knows that this is probably red 4, but he does not see any red 3's. Thus, Bob knows he must have the red 3, and blind-plays his *Finesse Position* card. It is blue 1.
  * Bob now knows that he was *Bluffed* and that the 4 in his hand is exactly red 4.
* *Self-Bluffs* on players with color clues are nonsensical, so players should not have to entertain that possibility. 
* For example, in a 3-player game:
  * Red 2 is played on the stacks.
  * Alice clues red to Bob, touching one brand new red card  as a *Play Clue*.
  * Bob has a negative 3 clue on his red card, so he knows it cannot be red 3.
  * Bob does not see any red cards in other player's hands.
  * Bob cannot have the red 3 in his *Finesse Position*, because that card has negative red.
  * Bob now needs to figure out what the clue means. When going through all of the possibilities, he can safely put aside the possibility of a *Self-Bluff with Color* / a *Known Self-Bluff*, because we agree that they are illegal. The clue must have some other meaning and Bob will defer to whatever the next-most-likely thing is.

<br />

## Level 3 - Advanced Strategies

* Level 3 strategies should only be learned if you have played with the group for a week or longer. (25+ games of experience or more.)
* This level covers specific kinds of moves that are pretty useful and happen fairly often, but are a little bit more complicated. 

### Allowable Stall Clues

* In certain special situations, everyone understands that a player might be giving a "stall" clue. However, there are limits - they are not allowed to just clue anything they want. These are the specific clues that they are allowed to give along with the priority of each clue:

| Priority | Type of Clue | Early Game (Severity 1) | Double Discard (Severity 2) | Locked Hand (Severity 3) | 8 Clues (Severity 4)
| -------- | ------------ | ----------------------- | --------------------------- | ------------------------ | --------------------
| 1        | Normal *Play Clues* or *Save Clues*                                                   | ✔ | ✔ | ✔ | ✔
| 2        | *5 Stall* (cluing off-chop 5's)                                                       | ✔ | ✔ | ✔ | ✔
| 3        | *Tempo Clue* (re-cluing a card to make it play)                                       | ❌ | ✔ | ✔ | ✔
| 4        | *Locked Hand Save* (saving any card on chop)                                          | ❌ | ❌ | ✔ | ✔
| 5        | *8 Clue Save* (saving any non-fresh card)                                             | ❌ | ❌ | ❌ | ✔
| 6        | Filling in extra info on clued cards                                                  | ❌ | ✔ | ✔ | ✔
| 7        | *Hard Burn* (re-cluing an unplayable card that gives no new information, usually a 5) | ❌ | ✔ | ✔ | ✔

* For example, if a player could perform a *5 Stall* (priority 2), then they are not allowed to perform a *Tempo Clue* (priority 3). Or, if a player could perform a *Tempo Clue* (priority 3), they are not allowed to *Hard Burn* (priority 7), and so forth.
  * However, remember that the *Finesse Position Exception* applies to *5 Stalls*. (This is covered in the "5 Stall" section above.)
* What is the point of having a complicated table with defined priorities? Well, normally, players in stalling situations are not able to give tricky-looking *Finesses*, because everyone else on the team will think that they are giving a stall clue. However, if it can be seen that there is a better clue available for them to give, then everyone can know that they are **not** giving a stall clue. Thus, because of this priority table, players in stalling situations are still often able to make *Finesses* happen.
* Obviously, stall clues are not allowed when the player has a known playable card in their hand.

### Locked Hands & The Locked Hand Save (L.H.S. / LHS) (Severity 3 Stalling)

* Generally speaking, it is a bad situation when someone's hand gets fully clued. This is also known as being *Locked*, and it should be avoided if possible. However, sometimes it cannot be helped, like when a player draws three 5's in a row.
* A player with a *Locked Hand* may give a low-value clue because they are not sure that they can play anything (and they can't discard because their hand is fully clued). Similar to a *Double Discard* situation, players should not read too closely into any clues given during this state.
* If the team is out of clues and someone's hand is fully clued, then you **have** to discard to generate a clue for them. Similarly, if there is only 1 clue left, you cannot steal it from them.
* Players with a *Locked Hand* gain the special ability to save any card on chop. This is called a *Locked Hand Save* if it saves a card that would otherwise not be legal to save (like some one-away from playable card that is not in the discard pile yet). However, players can only do *Locked Hand Saves* if there are no higher priority clues available. See the "Allowable Stall Clues" section above.

### The Anxiety Play (Forcing a Locked Player to Play)

* Sometimes, someone with a *Locked Hand* has a playable card, but they do not know that they can play it yet. Re-cluing the card would signal this, but that would waste a clue and not be very efficient.
* A better way to signal this information is to deliberately leave them at 0 clues. By convention, this means that one of their cards is actually playable. The player should play the card in their hand that is most likely to be playable. If there is more than one option, then they should know that the left-most is playable. (This follows from *Left-Most Playable Principle*.)
* This is called an *Anxiety Play* because you are putting the *Locked* player in a "do or die" situation.

### Clues Given While at 8 Clues & The 8 Clue Save (Severity 4 Stalling)

* At the beginning of the game, you start with 8 clues. This section only applies to situations where you climb to 8 clues in the middle of the game.
* A player who has a turn with 8 clues in the bank may give a low-value clue because they are not sure that they can play anything (and they can't discard because the game does not allow you to discard while at 8 clues). Similar to a *Double Discard* or a *Locked Hand* situation, players should not read too closely into any clues given during this state.
* Players at 8 clues gain the special ability to save any card that they want, on **or** off chop, as long as the card is not freshly drawn. This is called an *8 Clue Save*. However, similar to a *Locked Hand Save*, they can only do this if there are no higher priority clues available. See the "Allowable Stall Clues" section above.

### The Priority Prompt & The Priority Finesse

* Typically, players will only have one card to play at a time. In this case, unless there is some really good clue to give, there are no decisions to be made - they just play their one playable card.
* What if a player has two or more playable cards to play? Which card should they play first?
* If one of the cards is not completely known yet (e.g. a playable 2 of unknown color), then the player might want to play that card first in order to find out exactly what it is. In general, **nothing special is triggered by players playing an unknown card.**
* On the other hand, something special **can** be triggered if a player plays a fully-known card, because they knew exactly what they were doing. Our group agrees that **playable cards should be played in a specific order**. We refer to this as *Priority*. The agreed *Priority* is as follows:

| Priority | Category of card                                                   | Reason
| -------- | ------------------------------------------------------------------ | ------
| 1        | Blind-plays                                                        | Demonstrating that a *Finesse* or *Bluff* occurred is very important.
| 2        | Cards that lead into clued cards in someone else's hand            | Otherwise, the team would lose *Tempo*.
| 3        | Cards that lead into the player's own hand                         | It is bad for a suit to be "held up" on one player.
| 4        | 5's                                                                | Playing a 5 gets the team a free clue.
| 5        | The lower rank card                                                | The smaller stacks are more important to fill up.
| 6        | The left-most card                                                 | The left-most card is more likely to be good.

* If someone plays a fully-known card and the card does **not** have *Priority*, then the player must be trying to send a special message.
* Based on what card they did play, if you have any clued cards in your hand that match the next "connecting" card, it is a message that you can play it right now as a *Priority Prompt*. (This is similar to a normal *Prompt*, except instead of initiating the *Prompt* with a clue, they initiated it with the order that they played cards.)
* Alternatively, if you do not have any clued cards in your hand that matches the card that they played, then you you should play your *Finesse Position* card as a *Priority Finesse*.
* For example, in a 3-player game:
  * Alice has a known playable red 1 and a known playable blue 2 in her hand.
  * Alice plays blue 2.
  * Bob comes next. Bob does not see any red 2's. He does not see any blue 3's either. Thus, Alice was supposed to play the red 1 first, since red 1 is a lower rank than blue 2. Alice **did not** play the card with *Priority*.
  * This means that Bob must have blue 3. Bob does not have any clued cards in his hand, so he blind-plays his *Finesse Position* card.
* Similar to a normal *Prompt*, if a *Priority Prompt* could apply to two or more clued cards, then you should play the left-most one.
* Similar to a normal *Prompt*, if a *Priority Prompt* made you play the left-most card and it was not the matching card, then you should continuing playing clued cards until you find the matching card.

### The Priority Bluff 

* Similar to a normal *Bluff*, it is also possible for players to perform a *Priority Bluff*.
* For example, in a 3-player game:
  * Alice has a known playable red 1 and a known playable blue 2 in her hand.
  * Alice plays blue 2.
  * Bob comes next. Bob does not see any red 2's. He does not see any blue 3's either. Thus, Alice was supposed to play the red 1 first, since red 1 is a lower rank than blue 2. Alice **did not** play the card with *Priority*.
  * This means that Bob must have blue 3. Bob does not have any clued cards in his hand, so he blind-plays his *Finesse Position* card. It is **not** the blue 3 and is instead the green 1. Bob now knows that he was *Bluffed* and that no-one has the blue 3.

### A Priority Flowchart (For Choosing Between 2+ Playable Cards)

*Priority* can be confusing. [Here is a flowchart](https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/flowcharts/priority_flowchart.png) that shows, in general, which card should be played when there is a choice between two cards.

[Here is another flowchart](https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/flowcharts/priority_unknown_flowchart.png) that shows how *Priority* works when one or more of the cards is unknown.

### Priority Exceptions

Priority does not always apply. Some common exceptions are listed below.

1) *Priority* is generally "turned off" in the *End-Game*. (But *Priority* can still work if a player plays a card that would be terrible for the team otherwise.)

2) Normally, blind-playing cards has *Priority* over everything else. However, in some advanced cases, the blind-play does not need to be demonstrated to the team - everyone already has full knowledge of what is going on. In this case, players are supposed to treat the cards as clued for the purposes of finding the *Priority*. (The *Gentleman's Discards* is the main move that this applies to, which is a special move that is covered later.)

3) Normally, cards that are the same rank should be played from left-to-right. However, in certain situations, players can know that some **other** card is **more important** than the left-most card. If a player plays a "more important" card, it should never trigger a "right-to-left" style *Priority Finesse*. For example, in a 3-player game:

* In the *Early Game*, Alice clues number 2 to Bob, touching three 2's on slot 3, slot 4, and slot 5 (his chop). (This is the *2 Save* convention.)
* Later on in the game, all of the 1's are now played on the stacks.
* Bob has not received any other clues since then - all of his 2's are known playable, but he has no idea what color they are.
* Normally, Bob knows that he is supposed to play his 2's from left-to-right. However, he also knows that his 2 on slot 5 is the most important card out of all of them - it was the focus of the original *2 Save* by Alice.
* Thus, Bob plays his 2 on slot 5 first. After that, he plays the 2's from left-to-right like normal.

### The Double Prompt / Triple Prompt / etc.

* Sometimes, someone can give a *Prompt* that is prompting **two** (or more) cards with one clue, which is pretty efficient.
* For example, in a 3-player game:
  * A red 1 is played on the stacks.
  * Alice clues Cathy red, which touches a red 4.
  * Bob has two clued red cards in his hand. Since the red 4 is playable right now, he knows that his two red cards must be a red 2 and a red 3 (in order from left-to-right).
  * Bob plays the left-most card as red 2. On Bob's next turn, he plays the other red card as the red 3.

### The Double Finesse / Triple Finesse / etc.

* Typically, *Finesses* are performed by cluing a one-away from playable card. However, it is possible to get two different people to blind-play their cards in a row if you give a clue to a card that is two-away from being playable. This is very efficient, as it is a 3-for-1 clue.
* For example, in a 4-player game:
  * A red 1 is played on the stacks.
  * Alice clues Donald red, which touches a red 4.
  * Bob plays red 2 from his *Finesse Position*.
  * Cathy plays red 3 from her *Finesse Position*.
  * Donald plays red 4.
* Similarly, it is possible to get a single player to blind-play 2 cards in a row. In this situation, since they see that the blind cards are not in anyone else's hands, they will blind-play two turns in a row, playing from left to right.
* For example, in a 3-player game:
  * It is the first turn and nothing is played on the stacks.
  * Alice clues red to Cathy, touching a red 3.
  * Bob blind-plays red 1 from slot 1.
  * Cathy would normally think that she has red 2, which would match the red 1 that was just played. However, she sees that when the clue happened, there was a red 2 next to the red 1.
  * Thus, Cathy discards, giving Bob the chance to blind the play the red 2. If he does not blind-play it, then it was a normal *Finesse* and she has red 2. If he does blind-play it, then it was a *Double Finesse* and she has red 3.
  * On his next turn, Bob blind-plays red 2 from slot 2. Cathy now knows that she has the red 3.

### Prompts in Multi-Color Variants

* In multi-color variants, *Prompts* apply to the card with the most positive information.
* For example, in a 3-player rainbow game:
  * Red 2 is played on the stacks.
  * Alice clues red to Cathy, touching a red 4 as a *Play Clue*. This is a *Prompt* on Bob for a red 3.
  * In slot 1, Bob has a card with only a red clue on it. (Thus, it can be any red card or any rainbow card.)
  * In slot 2, Bob has a card with a red clue and a 3 clue on it. (Thus, it can be red 3 or rainbow 3.)
  * Since slot 2 has more positive information, Bob should choose to play slot 2 as red 3 (instead of slot 1, the left-most card).
* Players are **not** supposed to use information from negative clues.
* For example, in a 3-player rainbow game:
  * Red 2 is played on the stacks.
  * Alice clues red to Cathy, touching a red 4 as a *Play Clue*. This is a *Prompt* on Bob for a red 3.
  * In slot 1, Bob has a card with a positive red clue on it. (Thus, it can be any red card or any rainbow card.)
  * In slot 2, Bob has a card with a positive red clue on it and a negative green clue on it. (Thus, it can be any red card.)
  * Even though slot 2 is technically more likely to be the red 3, Bob knows that players are not supposed to use negative ifnormation for determining which card to play into a *Prompt*. Thus, Bob plays the red 3 from slot 1.

### Bluffs Through Already-Clued Cards

* It is also permissible to *Bluff* "through" cards that are already clued. This is better than a normal *Bluff* because in addition to getting the blind-play, it also gives information to the player with the in-between card.
* For example, in a 4-player game:
  * All the 1's are played on the stacks.
  * Bob has nothing clued in his hand.
  * Cathy has a red 3 clued in her hand with just a number 3 (she does not know what color it is).
  * Alice clues Donald red, which touches one red 4.
  * Bob knows that he must have the red 2. If he plays the red 2, then Cathy will play the red 3, and Donald will play the red 4.
  * Bob plays his *Finesse Position* card and it is instead the blue 2.
  * From Donald's perspective, since blue does not match red, he knows that this is a *Bluff*. Normally, he would think he has the one-away from playable red card, but that would be red 3, and Cathy already has that clued. If he had red 3, then the clue would be violating *Good Touch Principle*. Thus, he must have the red 4 instead.
  * From Cathy's perspective, she knows that the red 4 is two-away instead of one-away. *Bluffs* on two-away cards are normally illegal, so her mystery 3 must be exactly red 3, making the red 4 one-away after all.
* Sometimes, the player who has the in-between card might have more than one "matching" clued card. In this situation, the player is promised that they have the in-between card, but they are not promised the position - it can be any of the matching clued cards.

### The Ambiguous Finesse

* Sometimes, the player that is supposed to blind-play a card into a *Finesse* is ambiguous. For example, in a 4-player game:
  * Nothing is played on the stacks.
  * Alice clues Donald about a red 2 as a *Play Clue*.
  * Both Bob **and** Cathy have red 1 on their *Finesse Position*.
  * Bob will think that it is a *Reverse Finesse* directed at Cathy, and he will discard.
  * Next, Cathy thinks that Bob made a mistake and "missed" the *Finesse*. Cathy discards.
* Here, Cathy is actually the one making the mistake. It follows from *High-Value Principle* that you should never assume that your teammates are making a mistake. If Bob is discarding, then it means that Cathy also has the exact same copy of the card, and Cathy should immediately blind-play.
* From Cathy's perspective, it is also possible that Bob is performing a special move called a *Pass Bluff* (which is covered later on in the document).

### The Ambiguous Finesse Pass-Back

* When an *Ambiguous Finesse* occurs, one person will hesitate, not playing into the *Finesse*. Once that happens, it is usually clear that someone else on the team also has the matching card. Next, the other person should **immediately blind-play**, resolving the *Ambiguous Finesse* as fast as possible.
* However, in some specific situations, the next person **cannot** blind-play the card, or else a misplay would occur. In these situations, the second person has to **also** hesitate, "passing" the blind-play back to the first person again.
* For example, in a 4-player game:
  * Blue 1 is played on the stacks.
  * Alice clues blue to Donald, touching a blue 4 as a *Play Clue*.
  * Bob sees that Cathy has the blue 2 on her *Finesse Position*. From his position, this must be a *Double Finesse*, with Cathy blind-playing the blue 2, and Bob blind-playing the blue 3 from his own *Finesse Position*. Bob discards.
  * Cathy sees that Bob has the blue 2 on his *Finesse Position* and the blue 3 on his *Second Finesse Position*.
  * Cathy also knows that the only reason that Bob would discard is if Cathy **also** had the blue 2 on her *Finesse Position*. Thus, Bob expects her to blind-play on this turn, and this is an *Ambiguous Finesse*.
  * Normally, Cathy would blind-play the blue 2 herself. However, in this situation, if she blind-plays the blue 2, then Bob would go on to misplay the other blue 2, thinking that it is blue 3.
  * Thus, Cathy must pretend like the *Finesse* is not on her all, and force Bob to be the one to blind-play first. Cathy discards her chop card, passing the *Finesse* back to Bob.
  * Donald and Alice discard.
  * Bob knows that Cathy was supposed to blind-play the blue 2, but she didn't. He must also have the blue 2. Furthermore, he must also have the blue 3, as that would be an excellent reason for Cathy to pass the *Finesse* back to him. Bob will now blind-play blue 2 and blue 3.

### The Positional Discard (Indicating a Play with a Discard)

* Near the end of the game, if you have no clues left and no cards to play, you can transmit information based on which card you discard.
* Thus, you can discard the slot in your hand that matches the slot in someone else's hand that they are supposed to play.
* Usually, players will only do this if they can see all of the remaining useful cards. Since they see everything, they know that they cannot be discarding anything important.

### The Positional Misplay (Indicating a Play with a Misplay)

* On the final round of the game, if a player has no cards in their hand to play, a *Positional Discard* from **any** slot will work, because it is globally known that every card is visible.
* However, sometimes *Positional Discards* are done before the final round while there are still some cards left in the deck. In this situation, if a player discarded their chop card as a *Positional Discard*, this would not work, because discarding chop is the normal action that the rest of the team is expecting.
* Thus, in order to more strongly communicate the "play this slot" message, they can instead misplay their chop card. Since the rest of the team can see that the card misplayed for "no reason", they can deduce that it was a *Positional Misplay*.

### The Double Positional Misplay (Indicating Two Plays with a Misplay)

* Normally, the *Positional Misplay* is only used as a last-resort when a *Positional Discard* would not work. But what if a player does a *Positional Misplay* when a normal *Positional Discard* would have gotten the job done?
* *Positional Discards* and *Positional Misplays* promise that only one card in the specified slot is playable. So, if there are **two** people with a play on the same slot, then it will be ambiguous, because each of them will think that the other person is supposed to play.
* Thus, a *Positional Misplay* that is unnecessary transforms into a *Double Positional Misplay*, indicating to the team that **two** cards on that exact slot are playable.

### The Hidden Finesse

* Sometimes, you want to *Finesse* someone with a clued card already in their hand. However, if you try to *Finesse* them, they will assume it is a *Prompt* and will misplay their clued card, so it doesn't work out.
* However, what if the clued card actually is playable? That means you can still do the *Finesse* - they will play the *Prompted* card, see that it wasn't the card you had intended, and then blind-play their 2nd newest card on the next turn. This is called a *Hidden Finesse* because the *Finesse* was temporarily hidden by the presence of clued card.
* For example, in a 3-player game:
    * Red 1 and rainbow 2 are played on the stacks.
    * Alice clues red to Cathy, which touches her red 3.
    * Bob has a rainbow 3 clued as red in his hand and he has no idea what it is.
    * Bob sees that Alice's clue must be a *Prompt*, so he plays his red card as red 2. He is surprised to see that it is actually rainbow 3.
    * Bob knows that he really must have the red 2, and it must have been on *Finesse Position* when Alice originally gave the clue. Since he just drew a card after he played the rainbow 3, he now knows that the red 2 is on his slot 2 (the second-newest card).
    * On Bob's next turn, he blind-plays his the red 2 from slot 2.
    * In this example, the red 2 was "hidden" by the rainbow 3.

### The Layered Finesse

* Normally, if a red card is clued and someone blind-plays a blue card, it would be some kind of *Bluff*. However, we only allow players to perform a *Bluff* on the very next player. (This is referred to as sitting in *Bluff Seat*.)
* It follows from this that if an unrelated card is blind-played, and it cannot be a *Bluff*, then it must be a special kind of *Finesse*.
* Normally, a *Finesse* promises the exact copy of the card on *Finesse Position*. However, as long as all of the cards leading to the card are playable, you can still promise the exact copy of the card. We do **not** consider this to be a "lie", since the blind-playing player does indeed have the true copy of the card.
* We call this a *Layered Finesse* because the intended *Finesse* blind-play target is "layered" behind other playable cards.

<img src="https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/layered_finesse.png" alt="Layered Finesse Example" width="400">

* For example, in the above screenshot:
  * It is the first turn of the game and nothing is played on the stacks.
  * Alice clues green to Bob, touching a green 2 as a *Play Clue*.
  * Normally, Bob would think that he has the green 1. However, he also sees that this could be a *Reverse Layered Finesse* on Cathy. Thus, Bob cannot play anything right now - he must wait and see what Cathy does.
  * Bob clues yellow to Alice, touching a yellow 1 as a *Play Clue*.
  * Cathy knows that this is a *Reverse Finesse* and that she has the green 1. Cathy blind-plays her *Finesse Position* card and it is a blue 1.
  * Alice plays the yellow 1.
  * Bob knows that Alice must have been trying to blind-play a green 1. Thus, he must have the green 2, and Alice did indeed perfrom a *Layered Finesse*. Bob clues number 5 to Cathy as a *5 Save*.
  * Cathy was surprised that she played the blue 1. Could this be a *Bluff*? No, because Alice is not in *Bluff Seat* for Cathy, meaning that Alice is **not** allowed to bluff Cathy. Thus, this must be a *Layered Finesse* and Cathy must really have the green 1. Cathy plays her *Second Finesse Position* and it is the green 1.

### The Load Clue

* Players will generally play cards without *Priority* if they see the next card in someone else's *Finesse Position*, because this will get the card for "free" as a *Priority Finesse*.
* Less commonly, players will see the next card in someone else's hand, but it will not be in *Finesse Position*. In these cases, it might still be good to play the card without *Priority*, just so that the player with the next card will have something to do on their turn.
* However, if they do play the card without *Priority*, it will cause an impending misplay because the target player will think the card is actually on their *Finesse Position*. Thus, doing this **forces** someone to give a clue to the card directly in order to stop the misplay.
* This clue is similar to a *Fix Clue*, since it fixes an impending misplay. But we specifically call this kind of clue a *Load Clue* to differentiate it from a *Fix Clue* that fixes a lie or mistake. It is a *Load Clue* because it is loading the player up with something to do on their turn.
* If you receive a *Load Clue*, you should suspect that you might have something valuable on your chop, as this would be an excellent reason to commit the team to giving the *Load Clue* in the first place.
* If a player has a choice between playing one card that leads nowhere and playing one card that commits the team to giving a *Load Clue*, then they are not obligated to choose one or the other - they can choose whichever one is best for the situation.
* When a player receives a *Load Clue*, they are to interpret it as a normal *Play Clue* instead of a *Fix Clue*. For example, in a 3-player game:
  * Blue 1 and red 1 are played on the stacks.
  * Alice has a choice between playing a known blue 2 and a known red 2. The blue 2 has *Priority* because it is the left-most card.
  * Alice plays the red 2.
  * Bob sees that Cathy has the red 3, but it is on her chop instead of on her *Finesse Position*. Thus, Bob must now give a *Load Clue* to stop the impending misplay.
  * Cathy's hand is, from newest to oldest: yellow 4, yellow 3, yellow 4, blue 1, red 3.
  * Bob clues number 3 to Cathy.
  * Cathy is surprised - she was about to play her *Finesse Position* card as red 3, but she now knows that it can't be a red 3.
  * If this was a *Fix Clue*, Cathy might be inclined to play the card that was closest to her slot 1 (which would be the 3 on slot 2).
  * However, Cathy knows that *Load Clues* are to be interpreted as normal *Play Clues* instead of *Fix Clues*, so she interprets this as a normal *Chop-Focus Play Clue* and plays red 3 from slot 5.

### The Priority Finesse (Special Case)

* To review, if a player has two playable cards, and both of them are fully-known, then they always have the ability to trigger a *Priority Finesse*.
* If a player has two playable cards, and only one of them is fully-known, a *Priority Finesse* will never be triggered if they play the unknown card.
* But what if a player plays a fully-known card over an unknown card? They **can still** trigger a *Priority Finesse*, but **only** if every single possibility for the unknown card would have *Priority* over the card that was played.
* For example, in a 3-player game:
  * Red 2 is played on the stacks. The 1's are played on all of the other stacks.
  * Alice has a globally-known red 3. (She was given a *Play Clue* on it earlier.)
  * Alice has a 2 of unknown color. (She was given a *Save Clue* on it earlier, but it is now playable since all of the 1's are down.)
  * Alice's 2 could be either blue 2, green 2, yellow 2, or purple 2.
  * The rest of the team does not have any clued cards in their hands.
  * Alice knows that **all** of the possibilities for the 2 would have *Priority* over the red 3, since all of them are lower rank.
  * Alice plays the red 3 anyway, which triggers a *Priority Finesse* on the red 4.

### The Trust Finesse (A Situational Priority Finesse)

* According to the *Priority* rules, if an unknown card is played, no *Priority Finesse* can be triggered.
* However, even if this is the case, if playing one of the cards over the other would be really dumb, it should still trigger a *Finesse*.
* This type of move is called a *Trust Finesse* to distinguish it from the case where the card is globally known.
* It is also possible to perform a *Trust Prompt*, a *Trust Bluff*, and so forth.
* For example, in a 3-player game:
  * All the 1's are played on the stacks.
  * Alice has two playable cards in her hand:
    * One of the cards has a red clue on it. Since it was originally clued as a *Play Clue*, it is globally known that Alice knows that this is exactly red 2.
    * One of the cards has a number 2 clue on it. Since it was originally clued with a *Save Clue*, it can be any non-red 2. But it is playable because all of the 1's are already played.
  * Bob has a clued and globally known red 3 in his hand.
  * Alice knows that she is expected to play her red 2 into Bob's red 3, because that would be good teamwork.
  * Unknown from the rest of the team, Alice knows from the context of the game that her 2 must be exactly blue 2.
  * Bob has blue 3 on his *Finesse Position*.
  * Alice plays the globally unknown 2 to cause a *Trust Finesse*.

### The Paused Priority Finesse

* For the purposes of *Priority*, blind-playing a card is the most important thing to do. When players are supposed to be blind-playing a card, they are usually **not** allowed to perform a *Priority Finesse* - they must stick to playing the blind card.
* One exception to this is if a player is in the middle of unraveling the layer of a *Layered Finesse*. Since they have already blind-played their first card in the layer, they have demonstrated that the *Finesse* was on them, and now everyone on the team knows that the rest of the cards inside of the layer are "gotten" for sure.
* Thus, in this situation, a player can "pause" finishing up the *Layered Finesse* and play some other clued card to perform a *Paused Priority Finesse*.

### The Sarcastic Discard

* Occasionally, through a mistake (or complicated situation), the same card will be clued in two different people's hands. Generally, this is to be avoided, but sometimes it happens. Handling this can be tricky.
* Generally, the **first** player who fully realizes that they have the duplicate card should discard it (as opposed to playing it or holding on to it). This is called a *Sarcastic Discard*, and it communicates to the other player that they 100% have the discarded card.
* For example, in a 3-player game:
  * On the stacks, red 2 is played.
  * Alice has one red 3 clued in his hand with just number 3.
  * Alice clues number 3 to Bob, which touches one 3. (This is a mistake, because it might be violating *Good Touch Principle*.)
  * Bob knows that the only playable 3 is red 3. He also knows that Alice has a clued red 3 already in her hand. Thus, he knows that he has the red 3 and that Alice made a mistake.
  * Bob performs a *Sarcastic Discard* to pass the red 3 back to Alice.
* The *Sarcastic Discard* is similar to the *Prompt*, except that it is initiated by a discard instead of a clue.
* However, unlike a *Prompt*, if there are multiple cards that a *Sarcastic Discard* could apply to, then it does **not** promise that it is the left-most card. It only promises that they have the card somewhere. For example:
  * Alice *Sarcastic Discards* a red 3.
  * Bob has two cards clued with number 3 in his hand. He doesn't have any color information on either 3.
  * Bob can be certain that one of the two 3's is red 3, but he does not know which one it is yet.

### The Sarcastic Finesse

* Imagine that in a 3-player game:
  * Nothing is played on the stacks.
  * Alice has an already-clued 2 in her hand. She has no idea what color 2 it is.
  * Alice performs a *Finesse* by giving a red color *Play Clue* to a red 2 in Cathy's hand.
  * Bob blind-plays red 1 from his *Finesse Position*.
  * Normally, Cathy would think that she has the next red card, which is red 2, and play it.
  * However, what if Alice actually has the red 2? In this situation, Cathy is expected to perform a *Sarcastic Discard*.
* Doing a *Finesse* that potentially duplicates a card in this way is called a *Sarcastic Finesse*. Normally, potentially duplicating a card is bad - it violates *Good Touch Principle* and could lead to a clue being wasted. However, potentially duplicating a card with the *Sarcastic Finesse* is not bad because:
  * In the best case, you get a "true" *Finesse* (a 2-for-1 or better).
  * In the worst case, you get a 1-for-1 and full knowledge on a clued card in your own hand that was previously a mystery.

### The Gentleman's Discard

* The *Sarcastic Discard* is very similar to the *Prompt*, because it gets someone to play a card that already had a clue on it. It is also possible to intentionally discard a known card in order to get someone to blind-play a card, similar to a *Finesse*. 
* When this occurs, it is called a *Gentleman's Discard* to signify that the card played was completely blind as opposed to having a clue on it already.
* For example, in a 3-player game:
  * It is the first turn and nothing is played on the stacks.
  * Alice clues number 1 to Cathy, touching one 1.
  * Bob clues red to Cathy, filling in the already-touched 1 as red 1, as well as touching a new card, which must be red 2.
  * Cathy discards the known red 1 as a *Gentleman's Discard*.
  * Alice blind-plays her *Finesse Position* card as red 1.
* The *Gentleman's Discard* essentially transfers a card to another player on the team. However, often times, doing this will delay things and cost the team *Tempo*. Thus, a *Gentleman's Discard* that slows things down is only good if there is some other side benefit to offset the lost *Tempo* (such as delaying the discard of a valuable card, for example).
* For the purposes of *Priority*, *Gentleman's Discards* do not count as a blind-play. This means that if there is a playable clued card that leads into someone else's hand, then it should have priority over the blind-play from the *Gentleman's Discard*. (This is because the *Gentleman's Discard* is an information-symmetric move and nothing needs to be "proven" to other members of the team.)

### The Double Gentleman's Discard (Illegal)

* Normally, when a player performs a *Gentleman's Discard*, they know the **exact** identity of the card that they are discarding.
* However, sometimes a *Gentleman's Discard* can occur where, from your perspective, the card could have been two different things. Does this mean that the *Gentleman's Discard* "gets" **both** of the cards?
* No, it does not. By convention, even if it looks like the player could not have known the true identity of the card, the *Gentleman's Discard* only gets the specific other matching card. (The reason for this is that it allows players to act upon asymmetric information.)
* In extremely rare circumstances, *Double Gentleman's Discard* can be legal. This is covered in the expect section of the document, but can be safely ignored for non-experts.

### The Baton Discard

* Usually, when a *Gentleman's Discard* happens, it is for a playable card. But it is also possible to do a *Gentleman's Discard* to transfer a card to another player that is just completely unplayable at the current time.
* In order to disambiguate this from the more ordinary type of *Gentleman's Discard*, we call this a *Baton Discard*.
* For example, this would be a *Gentleman's Discard* in a 3-player game:
  * Red 2 is played on the stacks.
  * Alice discards a red 3.
  * Bob does not have any clued cards in his hand.
  * Bob looks at Cathy's hand and does not see the red 3. Thus, he knows that he has it.
  * Bob blind-plays his *Finesse Position* card and it is the red 3 and successfully plays.
* For example, this would be a *Baton Discard* in a 3-player game:
  * Red 1 is played on the stacks.
  * Alice discards a red 3.
  * Bob does not have any clued cards in his hand.
  * Bob looks at Cathy's hand and does not see the red 3. Thus, he knows that he has it.
  * Bob marks his *Finesse Position* card as red 3. For now, Bob does not have anything else to do, so he discards his chop card.
* *Baton Discards* are mostly useful for two main reasons:
  1) To better satisfy *Team Distribution Principle*. It makes sense to transfer a card out of a locked / almost locked hand to a player with an "empty" hand or a hand that only has one card clued in it.
  2) You want to protect your own chop. If you discard your chop, the team could be losing some high-value one-away from playable card. But if you transfer a card to someone else, it gives you something "safe" to do.

### The Certain Finesse / The Certain Discard

* Imagine that in a 3-player game:
  * Red 2 is played on the stacks.
  * Alice has an already-clued red card in her hand. It has a negative 4 clue on it, so from *Good Touch Principle* Alice knows that it is either red 3 or red 5.
  * Alice performs a *Reverse Finesse* by giving a red color *Play Clue* to a red 4 in Bob's hand.
  * Bob discards.
  * Cathy knows that she is promised the red 3 in her *Finesse Position*.
* This is an example of a *Certain Finesse* - it is similar to the *Sarcastic Finesse* above, but the "blind" card was potentially duplicated instead of the clued card.
* In this situation, if Alice really has the red 3, Cathy is allowed to blind-discard their *Finesse Position* card. This is called a *Certain Discard*, because Cathy can be certain that it is exactly red 3.
* A separate way to explain this convention is that everyone agrees that performing a *Layered Finesse* on a card that could potentially be clued in your own hand is illegal. So, everyone can be certain that they can safely blind discard a card to pass it back to someone who potentially duplicated. (*Layered Finesses* are an advanced type of *Finesse* that was explained above.)
* Note that players are **only allowed** to do a *Certain Discard* if they know they have not been *Bluffed*. This means that *Certain Finesses* **cannot be performed** from *Bluff Seat*.
* For example, in a 3-player game:
  * Red 2 and blue 3 are played on the stacks. Blue 4 is in the discard pile.
  * Alice has an unknown 3 in her hand that happens to be the red 3.
  * Alice clues number 4 to Cathy, touching a red 4 as a *Play Clue*.
  * Bob knows that Alice could be trying to perform a *Finesse* on a red 3. Normally, he would blind-discard his *Finesse Position* card as a *Certain Discard* in order to pass this card back to Alice.
  * However, Bob **also** knows that you are not allowed to perform a *Certain Discard* from *Bluff Seat*. In other words, there are other possibilities for this move - it could also be a *Bluff* on the blue 4. If he blind-discarded, that could "kill" the blue stack, since the other copy of blue 4 is already discarded.
  * Bob blind-plays his *Finesse Position* card and it is the blue 4. Good thing he did not discard the card!

### The Composition Finesse

* Sometimes, a move can be both a *Sarcastic Finesse* and a *Certain Finesse* at the same time. When this occurs, it is called a *Composition Finesse*.
* For example, in a 3-player game:
  * All of the 2's are played on the stacks.
  * Alice has a card in her hand with a red clue on it. It could be either red 3, red 4, or red 5.
  * Alice clues red to Bob, touching a red 4 as a *Play Clue*.
  * Bob discards.
  * Cathy knows that she has the red 3 on her *Finesse Position* (as a *Certain Finesse*). She can *Certain Discard* it if Alice has the red 3. But Alice does not have the red 3, so Cathy blind-plays the red 3.
  * Alice discards.
  * Bob knows that his red card is a red 4 (as a *Sarcastic Finesse*). He can *Sarcastic Discard* it if Alice has the red 4. But Alice does not have the red 4, so Bob plays the red 4.

### The Order Chop Move & The Skipped Order Chop Move

* Normally, at the beginning of the game, players are expected to play their 1's from right to left.
* If a player skips over their right-most 1, and there is nothing else special going on, it means that the next player should *Chop Move* one card.
* If a player skips over **two** of their right-most 1's, the message skips over the next player, and the player after that should *Chop Move* one card. (And a skip of three 1's means that the player three seats away should *Chop Move*.)
* For example, in a 3-player game:
  * It is the first turn and nothing is played on the stacks.
  * Alice clues Bob number 1, which touches three 1's. They are in slots 1, 2, and 3.
  * Bob is expected to play slot 3 (which is the oldest 1). If he plays slot 3, nothing special happens.
  * If Bob plays slot 2, he is performing an *Order Chop Move*, and Cathy should chop move one card (her slot 5).
  * If Bob plays slot 1, he is performing a *Skipped Order Chop Move*, and Alice should chop move one card (her slot 5).
* There are some common special situations that do **not** imply an *Order Chop Move*:
  * The 1 had priority from the *Fresh 1's Rule*.
  * The 1 that was played was originally *Finessed* from a clue that happened **before** the number 1 clue.
  * The 1 that was played was not **exactly** the same as the other 1's. Any positive or negative information that can be used to distinguish the 1s from each other "turns off" *Order Chop Moves*.
  * The 1 that was skipped over is known to be bad from contextual information. (See *The Stale 1's Clue* section.)

### Double Order Chop Move (for 3-Player Games)

* This convention only applies to 3-player games.
* In the *Order Chop Move* and the *Skipped Order Chop Move*, players can play 1's in a certain order to *Chop Move* a specific player of their choosing.
* In a 4 or 5-player game, skipping over three 1's would *Chop Move* the player three seats away. However, in a 3-player game, this would be nonsensical, since there are only 3 players in total.
* Thus, in a 3-player game, skipping over three 1's should *Double Chop Move* the very next player.
* In the rare case where four things are skipped over, it should skip over the next player and *Double Chop Move* the player after that.

### Trash Order Chop Move

* Sometimes, a player will have two known trash cards in their hand (and these cards are explicitly known trash, meaning that everyone on the team can equally see that they are known trash).
* In this situation, the player is expected to discard the newest (left-most) trash card.
* Thus, if a player skips over their newest trash card and instead discards the second newest trash card, they must be trying to communicate something extra.
* This means that the next player should *Chop Move* (in a manner similar to a *Order Chop Move*).
* Note that a player is not necessarily trying to perform a *Trash Order Chop Move* if the two trash cards have different kinds of clues on them. For example, by discarding specific trash cards, it can communicate that the player "sees" all of the non-trash possibilities of that card.

### The Misplay Chop Move

* Sometimes, a desirable card is on the next player's chop and it is not directly cluable. In this situation, players can cleverly use the various kinds of chop moves in order to save the card (e.g. *Trash Chop Move*, *5's Chop Move*, *Tempo Clue Chop Move*, and so forth).
* However, none of these chop moves may be available to perform. In such a situation, players can *Chop Move* a player by making them intentionally misplay a card. This works in exactly the same way as a *Trash Chop Move*, except that it the trash is not known to the player receiving the clue (and it costs the team a strike).
* For example, in a 3-player game:
  * All of the 2's are played on the stacks.
  * Bob's hand is completely unclued.
  * Alice clues Bob about one red card on slot 1 as a *Play Clue*.
  * Bob assumes that it is red 3 and immediately plays the card. However, it is actually red 1 and misplays.
  * Bob knows that Alice is trying to communicate something special to Bob. Similar to a *Trash Chop Move*, Bob now knows that multiple cards in his hand are important. He marks slot 2, slot 3, slot 4, and slot 5 as being *Chop Moved*.
* The *Misplay Chop Move* is the most costly type of chop move, so it should only be performed in a situation where no other kind of *Chop Move* would work.

### The 3 Bluff

* Typically, the player who receives a clue that causes a *Bluff* blind-play knows that the card that was clued is one-away from being playable.
* Our group plays with an artificial *3 Bluffs* convention. This means that in addition to being one-away from being playable, we agree that the touched card can also be any 3 that will be useful in the future.
* Here are some examples that cover the four most common *3 Bluff* situations:
    * **Color mismatch (valid):**
      * On the first turn of the game, Alice clues Cathy red, which touches a red 3.
      * Bob blind-plays blue 1.
      * Cathy knows that it is either a red 2 (if it was a normal *Bluff*) or a red 3 (if it was a *3 Bluff*). She marks down both of the possibilities for later.
    * **Number 3 with suit mismatch (valid):**
      * On the first turn of the game, Alice clues Cathy number 3, which touches a red 3.
      * Bob blind-plays blue 1.
      * Cathy knows that it was a *3 Bluff*, because a played 1 does not "match" number 3.
      * Beyond that, Cathy knows nothing about the card, besides that it is a 3 (since it has a number 3 clue on it).
    * **Color match (NOT valid; looks like a Double Finesse):**
      * On the first turn of the game, Alice clues Cathy red, which touches a red 3.
      * Bob blind-plays red 1.
      * Cathy sees that Bob does not have red 2. Since red matches red, Cathy assumes that she has the red 2.
      * Cathy misplays red 3 as red 2.
      * Alternatively, if Cathy saw that Bob had both red 1 and red 2 on *Finesse Position* at the time the clue was given, she would know that she has the red 2 **or** the red 3. Subsequently, Bob is promised a red 2, since if he does not blind-play a card, Cathy will go on to misplay the red 3 as red 2.
    * **Number 3 with suit match (valid):**
      * On the first turn of the game, Alice clues Cathy number 3, which touches a red 3.
      * Bob blind-plays red 1.
      * Cathy knows that it was a *3 Bluff*, because a played 1 does not "match" number 3.
      * Beyond that, Cathy knows nothing about the card, besides that it is a 3 (since it has a number 3 clue on it).
      * Even though red 1 and red 3 are the same suit, Bob is not promised a red 2, because if he does nothing, Cathy will not go on to misplay the red 3.
* The priority of *3 Bluffs* can be confusing. If you don't want to memorize the four examples above, you can simply ask the following questions:
  1) Does the clue "match" the blind-play? If it matches, then it is a *Finesse*. If it doesn't match, then it is a *Bluff*. Red matches red, but red does **not** match blue. 2 matches 3, but 1 does **not** match 3.
  2) Will the player who received the clue go on to misplay if nothing else is blind-played? If yes, then it is a *Finesse*. If no, then it is a *Bluff*.

### Discard Elimination & The Elimination Blind-Play

* Normally, your teammates would never let you discard anything important. So when you discard some playable card (or a needed 2) **and** that card is not in anyone else's hand, you might think that the team make a mistake.
* From *High Value Principle*, you should never assume your teammates are making a mistake. One excellent reason that they would let you discard an important card is that you have the other copy in your hand. (In order to satisfy *Good Touch Principle*, they had to wait for you to discard it so that they would not duplicate the card.)
* Thus, when you get a follow-up clue, you will know exactly what card it is.
* For example, in a 4-player game:
  * Red 3 is played on the stacks.
  * Alice has a completely unclued hand.
  * Alice discards her chop (slot 5). It is a (playable) red 4.
  * Alice knows that the team was not busy, so she must have the other copy of red 4.
  * Alice writes *Elimination Notes* on slots 2, 3, 4, and 5. (It can't be on slot 1, since that is the card she just drew.)
  * Bob clues Alice red, which touches a card on slot 1 and slot 2.
  * Normally, Alice would play the left-most card (slot 1) as red 4. However, because of the *Elimination Notes*, she knows that the red 4 must be on slot 2.
  * However, the focus of the clue is on slot 1, so slot 1 must also be playable.
  * Alice plays red 4 first from slot 2. Since the red 5 is the only good red card left, Alice can assume that her other red card is red 5, and can play it on the next turn.
* In other situations, your teammates will choose to **not** to clue the card directly. But once the *Elimination Notes* are whittled down, you should be able to blind-play it.
* For example, in a 4-player game:
  * Red 3 is played on the stacks.
  * Alice has a completely unclued hand.
  * Alice discards her chop (slot 5). It is a (playable) red 4.
  * Alice knows that the team was not busy, so she must have the other copy of red 4.
  * Alice writes *Elimination Notes* on slots 2, 3, 4, and 5. (It can't be on slot 1, since that is the card she just drew.)
  * Bob clues Alice blue, which touches slots 1, 2, 3, and 4. (This is a *Play Clue* on slot 1.)
  * Alice erases her *Elimination Notes* from slots 2, 3, and 4.
  * The only card left with an *Elimination Note* is slot 5.
  * Alice blind-plays red 4 from slot 5 on her next turn.
* One last thing to note is that players should not always make *Elimination Notes* when they discard a playable card. In rare cases, games can be extremely busy, leaving no reasonable way to get the playable card, so you always have to keep that in mind.

### The Elimination Play Clue

* A clue that touches multiple cards only has one focus. As you probably know by now, if the chop card was not touched, then the focus is the left-most card.
* However, this rule does not apply if a clue singles out a playable card from *Elimination*. In this case, the card is only focused on the *Elimination* card, and any other cards touched are not necessarily playable right now.
* For example, in a 3-player game:
  * Red 1 and blue 1 are played on the stacks.
  * Alice has both red 2's in her hand on slot 3 and slot 5. (Alice's chop is her slot 5.)
  * Alice discards her chop, and it is revealed to be the red 2.
  * Alice is surprised, and writes *Discard Elimination Notes* for red 2 on slots 2, 3, 4, and 5.
  * Bob gives a number 2 clue to Alice that touches a card in slot 1 and slot 4.
  * Normally, Alice would treat this as a *Play Clue* on the 2 in her slot 1. However, she now knows that her slot 4 card is exactly red 2 (and that she can play it right now).
  * Thus, Alice knows that the point of the clue was only to get the red 2. The 2 in her slot 1 can be any 2 in the game and is not necessarily playable right now.

### The Elimination Riding Deduction

* If there are only two cards left in your hand with *Elimination Notes* on them **and** the players before you let your chop card ride **and** the players before you were not busy, then the playable card cannot be on your chop.
* This means you can "jump ahead" and immediately blind-play the newest of the two cards with the note.
* For example, in a 3-player game:
  * Red 1 has been played on the red stack.
  * Alice has a completely unclued hand.
  * Alice discards her chop (slot 5). It is a (playable) red 2.
  * Alice knows that the team was not busy, so she must have the other copy of red 2.
  * Alice writes *Elimination Notes* on slots 2, 3, 4, and 5.
  * Alice receives no clues on the next go-around of the table. She discards, and now has *Elimination Notes* on slots 3, 4, and 5.
  * Alice receives no clues on the next go-around of the table. She discards, and now has *Elimination Notes* on slots 4 and 5.
  * Alice receives no clues on the next go-around of the table. Her teammates would not let the other copy of red 2 be discarded, so it must be on slot 4. Alice blind-plays red 2 from slot 4.

### The Elimination Riding Deduction Bluff

* Typically, when a player has two cards with *Elimination Notes* and the "true" copy of the card is on chop, you must clue it to let them know.
* However, if the other card is also playable, you can "lie" to them and not clue anything.
* Next, the player should perform an *Elimination Riding Deduction*, and play the unrelated card.
* After that, there will be only one card left with an *Elimination Note*, so they will go on to play the "true" card on their next turn.

### The Elimination Self-Chop Move

* Sometimes, you will have narrowed down your *Elimination Notes* to one specific card. Thus, even though the card has no positive clues on it, you know the exact identity of the card.
* If the card in question is on your chop **and** the card is not yet playable **and** you need to discard, you should obviously not discard the important elimination card. You should instead self-chop move and discard the next thing.

### The Elimination Finesse

* Normally, if a player is *Finessed*, they are supposed to play their *Finesse Position* card. However, if the player has two or more *Elimination Notes* in their hand for the specific *Finessed* card, then they know that it cannot be on *Finesse Position*.
* In this situation, the player is expected to play the **oldest** of the cards with the *Elimination Notes* on them (not counting *Chop Moved* cards, if any).
* For example, in a 3-player game:
  * Blue 2 is played on the stacks.
  * Alice has a completely unclued hand.
  * Alice discards a blue 3. Blue 3 was playable, and nothing urgent is currently happening, so she writes *Elimination Notes* on her hand for the other blue 3 on slots 2, 3, 4, and 5.
  * Bob clues Cathy blue, which touches a blue 4 as a *Play Clue*.
  * Cathy discards.
  * Alice knows that this is some sort of *Reverse Finesse*, as it is calling for the blue 3. However, the blue 3 cannot be in her *Finesse Position* (slot 1), as she knows from the *Elimination Notes* that it must be either on slot 2, 3, 4, or 5. So it must instead be a *Reverse Elimination Finesse*.
  * The *Elimination Finesse* promises that it is her oldest card, so she plays slot 5 as blue 3.
* As mentioned above, *Chop Moved* cards should be skipped over when finding the *Elimination Finesse* target. If there are two or more cards with *Elimination Notes* on them and they are all *Chop Moved*, then the oldest *Chop Moved* card should be played.
* *Elimination Finesses* apply to **all** types of situations with *Elimination Notes* (including *Discard Elimination Notes*, *Play Elimination Notes*, and *Double Discard Elimination Notes*). Subsequently, you can more specifically describe an *Elimination Finesse* as a *Discard Elimination Finesse*, a *Play Elimination Finesse*, or a *Double Discard Elimination Finesse*.
* Note that normal *Finesses* take priority over *Self-Elimination Finesses*. For example:
  * On the stacks, blue 2 and green 2 are played.
  * Alice has *Elimination Notes* on slot 3 and slot 4 for red 3.
  * Someone clues a number 4 in Alice's slot 1 as a *Self-Finesse*.
  * Alice must assume that it is a normal *Self-Finesse* and play blue 3 from slot 2. (If it was an *Elimination Self-Finesse*, she would play red 3 from slot 4.)

### Play Elimination

* When you discard something important, that triggers the writing of *Elimination Notes* on your own hand. This is *Discard Elimination* and is described above. But there are other ways that *Elimination Notes* are triggered.
* When another player plays a clued card in their hand that they should not have known was playable yet, it implies that they saw the other possibilities in someone else's hand. Thus, this should trigger you to write *Elimination Notes* on your hand. (Specifically, *Play Elimination* notes, as opposed to *Discard Elimination Notes*.)

### Double Discard Elimination

* When a player who is in a *Double Discard* situation discards anyway with an obvious clue to give (such as an off-chop 5), it implies that they **see** the other copy of the card, and were not *Double Discarding* at all.
* Thus, when this occurs, you should write *Elimination Notes* on your entire hand for that card.

### The Early 5's Chop Move

* In the *Early Game*, players are only allowed to clue an off-chop 5 if there is nothing left to do. (Or, as a special exception, if there is only one *Play Clue* to give to a card that happens to be on *Finesse Position*.)
* Thus, if someone clues a 5 and there **is** something else to do, they are performing a special move.
* If the 5 is one-away from chop, then they are performing an *Early 5's Chop Move*. This functions in the exact same way a normal *5's Chop Move* does (except it was done in the *Early Game*, which is not normally possible).

### The 5 Pull

* In the *Early Game*, players are only allowed to clue an off-chop 5 if there is nothing left to do. (Or, as a special exception, if there is only one *Play Clue* to give to a card that happens to be on *Finesse Position*.)
* Thus, if someone clues a 5 and there **is** something else to do, they are performing a special move.
* If the 5 is two or more away from chop, then they are performing a *5 Pull*. A *5 Pull* causes the player to blind-play the card to the right of the 5. For the player receiving the clue, it is understood that the 5 is not actually related to the blind-play. This is why it is called a *Pull* instead of a *Finesse* or a *Bluff*.
* *5 Pulls* are typically done to 5's that are in slot 1. But, for example, you can also clue a 5 in slot 2 in order to get a blind-play on slot 3.
* Even though they involve playing a blind card, a *5 Pull* should be treated as a *Delayed Play Clue*. This means that the blind card could play through any existing touched cards.
* *5 Pulls* also take precedence over *Finesses* and *Bluffs*. For example:
  * It is the *Early Game*.
  * Red 3 is played on the stacks.
  * Alice clues Cathy number 5, touching a red 5 on slot 1. (There are other *Play Clues* for Alice to give, so this is **not** a *5 Stall*.)
  * Normally, Bob would think that this is a *Finesse* and that he should blind-play his *Finesse Position* card as the red 4.
  * However, *5 Pulls* take precedence over *Finesses*. Bob can see that there is a playable blue 1 to the right of the 5, so no-one is promised the red 4.
* Since *5 Pulls* take precedence over *Finesses*, it is even possible to *5 Pull* a 4 without promising that the 5 is the matching suit.
* Normal *Play Clues* and *Delayed Play Clues* take priority over *Early 5's Chop Moves* and *5 Pulls* (as long as they don't cause any blind cards to play). For example:
  * It is the *Early Game*.
  * On the stacks, red 4 is played.
  * A blue 1 is available to clue in Bob's hand.
  * Instead, Alice clues an off-chop 5 in Cathy's hand (as number 5).
  * This is to be interpreted as a *Play Clue* on the red 5 (as opposed to a *5 Pull* on some other card).
* When a player is *Finessed* or *Bluffed*, they are allowed to defer playing the blind card in order to do a *Finesse* or *Bluff* of their own. However, if they could be *Bluffed*, they are **not** allowed to initiate a *5 Pull*. (Players are still allowed to defer playing into a *Finesse* in order to initiate a *5 Pull*.)
* In the rare case where a *5 Pull* is performed in a 3-player game by touching two 5's in slot 1 and slot 3, then the *5 Pulled* card is slot 2.
* For expert players, we define a specific [interaction between *5's Chop Moves* / *5 Pulls* and *2 Saves*](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#2-saves-advanced-section-interaction-with-5s-chop-moves--5-pulls).

### A Flowchart for Cluing 5's in the Early Game

* Differentiating between a *5 Stall* and a *5 Pull* can sometimes be confusing. [Here is a handy flowchart](https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/flowcharts/early_game_5_flowchart.png) that steps you through how you can tell the difference.

### The 5 Pull Prompt & The 5 Pull Finesse

* *5 Pulls* are also allowed to initiate a *Prompt* or *Finesse*.
* However, *5 Pulls* are **not** allowed to initiate a *Reverse Finesse*.
* With that said, players **do** have to respect that forward *5 Pull Finesses* could be *Layered*/*Clandestine*. ("Clandestine" is terminology is covered later on.)

### The 5 Pull Promise (A Follow-up Play Clue After a 5 Pull)

* Normally, *5 Pulls* have to be treated as *Delayed Play Clues*. This means that sometimes, it can take a long time for the pulled card to blind-play.
* From the perspective of the player who is *5 Pulled*, if a follow up *Play Clue* is given to a currently unplayable card, then they can disregard the *Delayed Play Clue* interpretation - the *5 Pulled* player is **promised** the card that makes the unplayable card playable.
* For example, in a 4-player game:
  * Alice has two clued 1's in her hand - red 1 and blue 1.
  * Bob does a *5 Pull* on Donald. Donald knows that the *5 Pulled* card could be either red 2 or blue 2 (if it is a *Delayed Play Clue*).
  * Cathy clues Alice about a red 3. Now, Donald knows that he is **promised** the red 2 as his *5 Pulled* card (and he no longer has to wait for the blue 1 to come down before blind-playing).

### Finesses While 5 Pulled

* Sometimes, a *5 Pulled* player may not play their pulled card right away. Maybe they have to wait for existing cards to play first, or maybe they want to capitalize on a *Finesse* while it is still available.
* Any *Finesse* that a *5 Pulled* player performs is to be treated as a *Certain Finesse*.
* Any *Certain Discard* that is performed in response to a *Finesse* that a *5 Pulled* player did applies to the *5 Pulled* card.

### The 5 Pull Skip

* If a player is already *Finessed*, it is possible to *Finesse* them again and get them to play their *Second Finesse Position* card.
* Similarly, if a *5 Pull* is performed, and the card immediately to the right of a 5 is already clued or already "gotten", then the *5 Pull* skips over that card and gets the next card after that.

### Duplication Responsibility

* Usually, if a 2 needs to be saved, it is not the responsibility of a player with already-clued 2's in his hand, because they could potentially violate *Good Touch Principle* by cluing it, so they should defer and let someone else on the team do it. (The same general concept also applies to cluing playable cards on chop, for example.)
* However, if all players have a clued 2 in their hand, then someone has to take a risk of violating *Good Touch Principle* in order to satisfy *Save Principle*. Who should do it?
* In this situation, the player who has the least number of matching clued cards should take responsibility. If 2+ players are tied, then the player with the more specific type of clue on their card(s) should take responsibility.
* If 2+ players have the exact same number of clued cards and type of clued cards, then either player should save the card.
* Example 1:
  * In a 3 player game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown 2's.
  * Cathy has 1 unknown 2.
  * Bob should let Cathy perform the save, since 1 matching card is less than 2 matching cards.
* Example 2:
  * In a 3 player game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown 2's.
  * Cathy has 2 unknown 2's.
  * The responsibility is shared, so Bob should perform the clue if Cathy has a good discard, or he can discard and let Cathy do it.
* Example 3:
  * In a 3 player game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown blue cards.
  * Cathy has 1 unknown 2's.
  * Bob should let Cathy perform the save, since 1 matching card is less than 2 matching cards.
* Example 4:
  * In a 3 player game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown blue cards. No blue cards have been played yet, so from Bob's perspective, each blue card has a 1/5 chance of being the blue 2.
  * Cathy has 2 unknown 2's. No 2's have been played yet, so from Cathy's perspective, each 2 has a 1/5 chance of being the blue 2.
  * The responsibility is shared, so Bob should perform the clue if Cathy has a good discard, or he can discard and let Cathy do it.
* Example 5:
  * In a 3 player game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown blue cards. No blue cards have been played yet, so from Bob's perspective, each blue card has a 1/5 chance of being the blue 2.
  * Cathy has 2 unknown 2's. One 2 has been played already, so from Cathy's perspective, each 2 has a 1/4 chance of being the blue 2.
  * Thus, it is Bob's responsibility to save the blue 2.

### Context Clues & The Stale 1's Clue

* Based on the *First Principles*, we have conventions that define what a clue means. But combined with this, we are always expected to look at the context of the game.
* For example, sometimes players will receive a clue that just feels strange. If this good clue could have been given a bunch of turns ago, why is it only being given now? Were the other players not paying close enough attention, and are only getting around to cluing this card now?
* In these types of situations, from *High Value Principle*, you can assume that the team is not making any mistakes, which means that the meaning of the clue should be altered from the "textbook" definition. We call these types of clues *Context Clues* because they rely on contextual reading of the game state.
* The most common *Context Clue* is given to "stale" 1's towards the beginning of the game. For example, in a 3-player game:
  * After a few ordinary clues happen, Alice discards, which ends the *Early Game* and initiates the *Mid-Game*. By doing this, she implies that there is nothing to do (because players are mandated to "extinguish" all of the available *Play Clues* and *Save Clues* in the *Early Game*).
  * Bob then immediately clues Cathy about two 1's.
  * Normally, from *Good Touch Principle*, Cathy would assume that both of the 1's were "good" and play both.
  * However, Cathy also knows that if both of these 1's were good, then Alice was required to clue them before discarding.
  * Thus, Cathy can reason that one of the 1's are bad. Furthermore, by convention, she knows that the oldest (right-most) 1 is bad, because that would be the one that she would ordinarily play first.
  * So, Cathy should skip over the oldest (right-most) 1, and play the other 1. Cathy should also treat the other 1 as known-trash.
* The *Stale 1's Clue* is specific example of a more general concept called *Focus Inversion*, which is covered later.

### Focus Inversion

* Sometimes, a *Play Clue* is given that both touches the chop card and one or more other card. The normal interpretation of this is to treat it as a chop-focus *Play Clue*, and play the chop. However, sometimes a player can know that the chop is not actually playable. This can be determined through:
  * explicit information - negative clues present on the card
  * implicit information - historical / contextual information about the card derived from moves that teammates performed earlier on in the game
* When this occurs, the clue is meant to be a *Play Clue* on the left-most card **instead** of the chop card.
* Just like a "normal" *Play Clue* that touches multiple new cards, the chop card (and other other new cards introduced) are not necessarily playable right now.
* For example, in a 3-player game:
  * Alice clues 1's to Bob, which introduces one card on slot 1.
  * Bob plays the 1 and it is red 1.
  * Cathy clues blue to Bob, which introduces two cards on slot 1 and slot 5.
  * Normally, Bob would think that this is a *Chop-Focus* clue, and play the blue 1 from slot 5.
  * However, his slot 5 card has a negative 1 clue on it (from Alice's number 1 clue), so it explicitly cannot be the blue 1.
  * Thus, this must be *Focus Inversion* and blue 1 must be on slot 1. The blue card on slot 5 can be either blue 2, blue 3, blue 4, or blue 5.
* Note that ***Self-Finesses* always take precedence over *Focus Inversion***.

### The Distribution Clue

* In the *End-Game*, when a player has many playable cards, there is the risk that they will not be able to play all cards before the end of the game.
* Thus, it might make sense to spend a clue to duplicate one of their playable cards in someone else's hand. This would violate *Good Touch Principle*, but it would relieve the player with the loaded hand from some of the card-playing burden.
* Since it distributes plays more evenly throughout the team, this is called a *Distribution Clue*. *Distribution Clues* better satisfy *Team Distribution Principle*.

<br />

## Level 4 - Expert Strategies

* Level 4 strategies should only be learned if you have played with the group for two to three weeks or longer. (100+ games of experience or more.)
* This level covers moves that are complicated, difficult to see, or require a deeper understanding of how Hanabi works in order to work properly.

### The Occupied Play Clue & The Occupied Finesse (O.P.C. / OPC)

* If a clue could be given by multiple players, who should give the clue? Usually, it makes the most sense for the players with playable cards to play those cards, and the players with nothing to do to give the clue.
* If someone gives a clue with a playable card in their hand and this forces the next player to have nothing to do, this is bad teamwork - unless there was a reason!
* When this occurs, even if the clue looks like an ordinary *Save Clue*, it **must** be a *Play Clue*, since the player who was doing it was occupied.
* Furthermore, if an *Occupied Play Clue* is given to a card that is not directly playable right now, it must be an *Occupied Finesse*!
* The concept of an *Occupied Finesse* generalizes to lots of different kind of moves. For example, when an occupied player clues an off-chop 5, it is certainly not a *5 Stall* - it must be an *Occupied 5 Pull*!

### The Clandestine Finesse

* To the player who receives a clue that initiates a *Layered Finesse*, it is usually obvious what is going on. For example, in a 4-player game:
  * Alice clues Donald about one blue card.
  * Bob discards.
  * Cathy blind-plays a green 1.
  * Donald clearly knows that this is a *Layered Finesse* on Cathy, and she will continue to play cards until she finds the blue card that matches the one in his hand.
* In other words, most *Layered Finesses* cause unrelated cards to blind-play that do not match the type of clue given.
* With that said, it is also possible to perform a *Layered Finesse* for unrelated cards that **do** match the type of the clue given. When this happens, it is hidden from the receiver of the clue, so we call it a *Clandestine Finesse* to disambiguate it from a (more obvious) *Layered Finesse*.

![Clandestine Finesse](img/clandestine_finesse.png)

* For example, in the above screenshot:
  * Alice clues number 3 to Cathy, which touches the purple 3 on slot 1 and the green 3 on slot 4. Thus, the purple 3 is the focus of the clue. This must be a *Play Clue* on the purple 3.
  * Bob knows that the purple 3 is currently unplayable, so it must be a *Finesse*. He blind-plays his *Finesse Position* as purple 2, but it is a red 2 instead and successfully plays.
  * Normally, Cathy would think that she has the red 3 on her slot 1, because the card that was blind-played matches the clue. (Number 2 matches number 3.)
  * However, Cathy also sees that Bob had a purple 2 on his *Second Finesse Position* at the time of the clue. So there is a possibility that this was a *Clandestine Finesse* instead of a normal *Finesse*. Thus, Cathy has to give Bob a chance to blind-play the purple 2. If he does not, then Cathy does indeed have the red 3. Cathy discards.
  * Alice also discards.
  * Bob was surprised that he played the red 2, but now knows that it was a *Clandestine Finesse* instead of a normal *Finesse*. He blind-plays his slot 2 and it is the purple 2 and successfully plays. (Bob knows that if he did not do this, then Zealousy would go on to misplay purple 3 as red 3.)
  * Cathy plays purple 3.
* Since we are allowed to lie in *Bluff Seat*, doing a *Layered Finesse* in *Bluff Seat* typically won't work. Instead of getting a big layered chain of cards, it will be interpreted as a *Bluff*, and only one card will be played. However, note that a *Clandestine Finesses* can get around this restriction, because it induces a potential misplay. The blind-playing player **must** continue to blind-play cards, or else the player receiving the clue will assume that the *Finesse* is "over" and will play the clued card.

### The Stacked Finesse

* If a player has been *Finessed*, then their *Finesse Position* moves right one slot, exactly like if the blind card was clued. (This is a similar concept to how the chop moves left one slot when a player is *Chop Moved*.)
* If **another** *Finesse* is performed on the player who has already been *Finessed*, it is stacking a 2nd *Finesse* on top of the first, and they are expected to blind-play the new *Finesse Position* card.
* However, because of the possibility of *Layered Finesses*, players should always blind-play their cards in order from left to right (and not jump ahead).
* In rare cases, players can determine that a *Layered Finesse* was impossible (due to negative clues or some other piece of context). In this situation, if the play order of the cards does not matter, players should always "jump ahead" and play the second card to demonstrate to the team that they "got" both *Finesses*.

### The Layered Gentleman's Discard

* One great reason to want to do a *Gentleman's Discard* is if the card you are discarding is also behind playable cards. This is similar to a *Layered Finesse*, only it was initiated by a discard instead of a clue.
* For example, in a 3-player game:
  * It is the first turn and nothing is played on the stacks.
  * Alice clues number 1 to Cathy, touching one 1.
  * Bob clues red to Cathy, filling in the already-touched 1 as red 1, as well as touching a new card, which must be red 2.
  * Cathy discards the known red 1 as a *Gentleman's Discard*.
  * Alice blind-plays her *Finesse Position* card as red 1, but it is green 1.
  * Alice knows that she is promised the red 1, so she will blind-play her slot 2 on her next turn.

### The Trash Push

* Normally, when a useless card is clued, it signifies a *Trash Chop Move*. However, what if the useless card is actually the card on chop? Then it wouldn't be *Chop Moving* anything.
* From *Good Touch Principle*, we know that it is pointless to spend a clue to touch a useless card on someone's chop, because if we just do nothing, the useless card will get automatically discarded.
* Subsequently, if this is done deliberately, it must have a meaning. By doing this, it means that we want to "push" the card that is next to the useless card onto the table.
* For example, in a 3-player game:
  * All of the 1's are played on the stacks.
  * Bob has no clued cards in his hand. His chop is his slot 5.
  * Alice clues Bob number 1, which only touches his slot 5 card.
  * Bob blind-plays his slot 4 card, and it is a playable red 2.
* Sometimes, a *Trash Push* is the only way to get a card played that is sitting between two other annoying cards.
* Similar to a *Bluff*, *Trash Pushes* must be immediately playable and should generally be demonstrated immediately. (This is unlike other similar moves like the *5 Pull*, which may have to wait a while.)

### The Trash Bluff

* Normally, when a useless card is clued, it signifies a *Trash Chop Move* or a *Trash Push*. However, for both of these strategies to work, it is assumed that the recipient of the clue will know that the card that was touched is useless.
* What if the recipient of the clue does **not** know that the card that was clued is useless? They will go on to misplay that card, mistaking it for a "normal" *Play Clue*.
* When you see this occur, it works like a *Bluff*; you must blind-play your *Finesse Position* card, or the player who received the clue will go on to misplay.
* *Trash Bluffs* are a good tool to get a card played that is sitting behind other annoying cards.
* For example, in a 3-player game:
  * On the stacks, all of the 1's are played **except** for red 1.
  * Cathy has no clued cards in her hand.
  * Alice clues Cathy number 1, which only touches her newest (slot 1) card. This card is a blue 1, but Cathy will assume that it is a red 1.
  * Bob blind-plays his *Finesse Position* card, and it is a playable blue 2.
  * Cathy now knows that her 1 must not be red 1, or else Bob would not have blind-played anything. The 1 must be some other trash card.
* Just like normal *Bluffs*, *Trash Bluffs* can only be done while in *Bluff Seat*.
* An important stipulation of the *Trash Bluff* is that by convention, *Trash Bluffs* **must only touch one card**, if at all possible.
  * If a player breaks this rule and intentionally touches multiple cards when they could have touched exactly one card, then they are trying to communicate something extra - an *Unneccessay Trash Chop Move* or a *Trash Double Bluff*. (These moves are covered in more detail later on.)
* In the case where multiple cards are clued as part of a *Trash Bluff*, **all** of the touched cards are considered to be trash. However, the focus of the clue should be the first thing discarded, which allows for the possibility of your teammates to give a follow-up *Fix Clue*.

### The Trash Finesse (Strong Form)

* In a *Finesse*, we would say that the clue "matches" the blind-play. For example, a blue clue on a blue 2 matches a blind-play of blue 1. Or, a number 2 clue on blue 2 matches a blind-play of blue 1.
* In a *Bluff*, we would say that the clue does not "match" the blind-play. For example, a blue clue on a blue 2 does not match a blind-play of a red 1. Or, a number 2 clue on a blue 2 does not match the blind-play of a red 2.
* In the *Trash Bluff* example above, a blue 1 is used to *Trash Bluff* a blue 2. Similar to a *Bluff*, we would say this number 1 clue does not match the blind-play of a blue 2.
* What if the *Trash Bluff* instead got a red 1 to blind-play? In this context, the red 1 would actually "match" the number 1 clue. Another way of saying this is that by cluing the trash 1 with a number 1 clue, the clue giver is saying that they **see** a matching 1 that is good.
* Thus, it is possible to perform a a *Trash Bluff* outside of *Bluff Seat* if the "matching" card is on someone's *Finesse Position*. When this is done, it promises that someone has that specific card, so we call it a *Trash Finesse* rather than a *Trash Bluff*.
* For example, in a 4-player game:
  * All the 1's are played on the stacks except for red 1.
  * Alice clues number 1 to Donald, which touches a blue 1. To Donald, this will look like it is a red 1.
  * At first glance, Bob might think this is a *Trash Bluff*, causing him to blind-play his *Finesse Position* card as either red 1 or some other currently-playable card.
  * However, Bob also sees that Cathy has a red 1 on her *Finesse Position*. Thus, Alice's clue was a *Trash Finesse* instead of a *Trash Bluff*, since it is promises a playable 1.
  * Thus, Bob discards.
  * Cathy blind-plays her *Finesse Position* card and it is red 1.
  * Donald discards his known-trash 1.
* *Double Trash Finesses* are explicitly disallowed. Thus, it is possible to perform a *Trash Finesse* in a situation like this:
  * All the 1's are played on the stacks except for red 1 and blue 1.
  * Alice clues number 1 to Donald, which touches two green 1's on slot 1 and 2. To Donald, this will look like it is both the red 1 and the blue 1.
  * Like in the previous example, Bob sees that Cathy has a red 1 on her *Finesse Position*.
  * At first glance, Bob might think that Alice is promising both red 1 and blue 1, which would mean that he would need to blind-play the blue 1.
  * However, a *Trash Finesse* only promises at least one matching card, and since he sees that Cathy has a matching card, then that is good enough. Thus, Bob discards.
  * Cathy blind-plays her *Finesse Position* card and it is red 1.
  * Donald knows that the focus of the clue (slot 1) is certainly trash, since that caused Cathy to blind-play.
  * Furthermore, Donald knows that his slot 2 card is also trash, because all the cards touched in a *Trash Bluff* or *Trash Finesse* are guaranteed to be trash.

### A Trash Flowchart

There are a lot of different moves that involve cluing trash. [Here is a handy flowchart](https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/flowcharts/cluing_trash_flowchart.png) for determining the difference between the different types of special moves that touch trash. (The flowchart contains some strategies that have not been covered yet, but the three most important moves to understand are the *Trash Chop Move*, the *Trash Finesse/Bluff*, and the *Trash Push*.)

### The Out-of-Order Finesse (Triple O / OOO / O.O.O.)

* Sometimes, a *Finesse* is initiated by giving a color clue to two or more cards where the next card in the sequence is clued, but it is **not** the focus of the clue.
* When this happens, the *Finesse* will still work: a player will blind-play a matching card. However, a *Fix Clue* must then be given to the player who originally received the clue, or they will go on to misplay.
* Normally, after receiving a *Fix Clue*, a player would normally "stop" and not assume anything else about his hand. However, this is a special situation: when the original *Finesse* was given, it was a message that the focus of the clue was playable. *Information Lock Principle* applies, and it means that the original focus of the clue is also playable.
* For example, in a 3-player game:
  * At the beginning of the game, Alice goes first.
  * Bob has a red 3 and a red 2 (on slots 1 and 2 respectively).
  * Cathy has a red 1 on slot 1 (in *Finesse Position*).
  * Alice clues Bob red (as an *Out-of-Order Reverse Finesse*). The focus of the clue is the red 3 on slot 1.
  * Bob sees the red 1 on Cathy's *Finesse Position*, so he has to respect that it could be *Reverse Finesse*. Bob discards.
  * Cathy blind-plays red 1.
  * Alice must now give a *Fix Clue* to Bob, or else red 3 will be misplayed as red 2.
  * Alice clues number 2 to Bob.
  * Bob plays red 2.
  * Bob knows that his other red card **must** be red 3, since it was originally clued as playable and it caused a *Reverse Finesse*.

### Finesses with a Lie Component

* *Good Lie Principle* states all that lies must resolve immediately. However, some players will occasionally perform *Finesses* that violate this principle. We would say that such *Finesses* have a *Lie Component*.
* Typically, when players lie out of *Bluff Seat*, the game quickly falls apart; subsequent clues will have different meanings to different players and everyone will become "desynchronized". This typically leads to a loss.
* With that said, it is sometimes possible to construct **safe** lines that contain a *Lie Component*. There is usually deep levels of nuance involved in these lines, so this kind of thing is only recommended for advanced and expert players.
* The previously mentioned *Out-of-Order Finesse* is an specific example of a *Finesse* with a *Lie Component*. One key attribute of the *Out-of-Order Finesse* is that the player who receives the *Fix Clue* knows that **all** of the related cards are playable, or it would not have been worth the risk (and the confusion) to perform a line with a *Lie Component* in the first place.
* This concept can be generalized to all *Finesses* that have a *Lie Component*. After a player receives a *Fix Clue* in such a situation, they should assume that the *Finesse* is "still on". So, depending on the situation, they should either know that the initial card that was clued is playable (like in an *Out-of-Order Finesse*) or continue to blind-play cards to the right of the card that got the *Fix Clue* (if more blind cards need to be played to fulfill the initial *Finesse*).

<br />


### The Trash Finesse (Weak Form)

* First, see the section on *Trash Touch Elimination*.
* When players deliberately touch ancillary trash and there is only one card "missing", then it should trigger *Trash Touch Elimination Notes*. But what if there are two or more cards that are missing?
* In this situation, the clue giver is promising that someone has one of the missing cards on their *Finesse Position*. Once the card is blind-played, the recipient of the clue will know that one of their ancillary cards are trash.
* This is more subtle than the strong *Trash Finesse*. In the strong form, the focus of the clue causes a blind-play. In the weak form, the non-focused cards are what causes the blind-play
* For example, in a 3-player game:
  * Red 2 is played on the stacks. All of the other suits have the 1 played on the stacks. 
  * Bob's hand is as follows, from newest to oldest: red 3, red 1, blue 1, green 1, yellow 1.
  * Alice wants to give a play clue to the red 3. Everyone on the team can see that she can give either 3s or red.
    * If she clues number 3, then it will uniquely touch the red 3 (and not violate *Good Touch Principle*).
    * If she clues red, then it will touch the red 3 and the red 1 (which **will** violate *Good Touch Principle*).
  * Alice clues red to Bob. Since nothing was stopping her from cluing number 3, this is very strange.
  * Bob plays the red 3.
  * There are two "missing" red cards - the red 4 and the red 5. Thus, Cathy knows that Alice must be intending a weak form *Trash Finesse*.
  * Cathy immediately blind-plays her *Finesse Position* card and it is the red 4.
  * Bob sees Cathy blind-play the next red card for seemingly no reason, so he is able to deduce that his slot 2 card is trash.

### The Pass Bluff

* First, see the section on the *Hesitation Blind-Play*.
* It is possible for a *Hesitation Blind-Play* to occur without anyone intending it to happen. However, if a player intentionally tries to make a *Hesitation Blind-Play* occur, it is called a *Pass Bluff*.
* In other words, after a *Finesse* occurs that is directed at you, you will know that your *Finesse Position* card is playable. If the next immediate player also has an unrelated playable card on their *Finesse Position*, you can pretend like the *Finesse* wasn't directed at you. This will cause them to think that the *Finesse* was directed at them, and you will get the unrelated card played for free.
* After the unrelated card is played, the next player should **not** continue to blind-play cards (as a *Layered Finesse*) because:
  * The "passing" player fulfills the real *Finesse* on their next turn.
  * The "passing" player was in *Bluff Seat*.
* *Pass Bluffs* rely on contextual information in order to work, so the circumstances in which you can do them are narrow.
* It is illegal for a player to perform a *Pass Bluff* if they could be *Bluffed*. (This is because the first *Bluff* would not resolve immediately and would violate *Good Lie Principle*.)
  * Subsequently, it is also illegal for a player to pass an *Ejection* to the next player.


#### The Suboptimal Save Prompt & The Suboptimal Save Finesse

* If the other copy of a card is in the trash already, then the remaining copy needs to be saved. These cards are allowed to be saved with either a color clue or a number clue.
* If both types of clues will **only** introduce one new card, then it is said that that there is a *Free Choice* between the two clue types.
* In this situation, the clue type will be chosen that "fills in" the other ancillary cards in the hand or gives important negative information.
* If a clue type is chosen that is clearly worse than the other one, then the clue giver must be trying to communicate something extra.
* The means that this innocent-looking *Save Clue* is really a *Play Clue*, and all of the in-between cards are called for.



- Rarely Used Strategies (Miscellaneous)

### The Hesitation Blind-Play

* Sometimes, a player will receive a *Play Clue* on a card. And then, instead of playing it, they will discard their chop instead. This would normally indicate some sort of emergency. However, sometimes it can be seen that there is nothing special going on and that everybody has safe chop cards.
* In such a situation, if the player is not making a mistake, the only reason that they would discard is that they are allowing for the possibility of a *Prompt* or a *Reverse Finesse* - someone else on the team has a playable card (either clued or on *Finesse Position*) that "matches" the card that they got the *Play Clue* on.
* Depending on the game state, clever players may be able to blind-play their *Finesse Position* card in reponse to this hesitation, getting a card for "free". This kind of move is called a *Hesitation Blind-Play*.
* For example, in a 3-player game:
  * Red 1 and all of the other 2's are played on the stacks.
  * The team has 5 clues. Nobody on the team has any cards clued in their hand.
  * Alice clues number 3 to Bob, touching a blue 3 on slot 1 as a *Play Clue*. (The team is now at 4 clues.)
  * Bob discards. (The team is now at 5 clues.)
  * From Cathy's perspective, Bob was supposed to play the blue 3 immediately instead of discarding.
  * Cathy knows that since the team has so many clues available, this cannot be a *Scream Discard* from Bob. (*Scream Discards* are only typically done when the team is at 0 or 1 clues.)
  * Thus, Cathy knows that Bob must be hesitating because is he allowing for the possibility of a *Reverse Finesse*. In this situation, the only possible card that could Bob could be hesitating for is red 2.
  * Cathy blind-plays her *Finesse Position* card. It is red 2 and it successfully plays.
  * Alice discards.
  * Bob knows that since Cathy blind-played the red 2, Alice did a *Reverse Finesse* and that he has the red 3.
  * Bob plays the 3, but it is revealed to be blue 3 instead of red 3.
  * Bob now knows that nobody has the red 3 and that Cathy blind-played the red 2 from Bob's hesitation.
* *Hesitation Blind Plays* are **not always safe** to do:
  * If a player could be hesitating for a clued card in your hand **or** your *Finesse Position* card, then you cannot cannot act on the hesitation. (If you guess wrong, you could misplay a critical card.)
  * If a player could be hesitating for a card that is identical to the card that was clued, then you cannot cannot act on the hesitation. (If you blind-play the same copy of the card, then they will go on to misplay the clued card.)
  * If blind-playing a particular card would cause the original clue to look like a *Double Finesse* with a "self" component, then you cannot cannot act on the hesitation. (For example, if a number 4 clue causes a *Hesitation Blind-Play* of a red 2, the clue receiver would go on to misplay their *Finesse Position* card as the red 3.)

### The Hesitation Chop Move (From a Misplay)

* Remember that as a special exception, *Scream Discards* do **not** apply when a player has a "blind" card to play in their hand **and** the blind card can exist in your hand.
* Thus, when this occurs, you will usually want to blind-play your *Finesse Position* card, since this sequence of events indicates either an *Ambiguous Finesse* or a *Pass Bluff*.
* When you blind-play a card in this situation and it misplays, it means that the unusual discard really was a *Scream Discard* after all, so you should treat it like a normal *Scream Discard* and permanently *Chop Move*.
* This is called a *Hesitation Chop Move* for short, since it was triggered by a (failed) *Hesitation Blind-Play*.

### Double Prompts in Multi-Color Variants

* Normally, when a multi-color card is *Prompted* from someone's hand, they should play the card that has the most positive information.
* However, what if they are *Prompted* for two cards of the same multi-color suit? They should play the card with the most positive information first, even if it is not the left-most card.
* For example, in a 3-player rainbow game:
  * Rainbow 1 is played on the stacks.
  * Bob has a slot 1 card that has a blue clue on it. (Thus, it is either a blue card or a rainbow card.)
  * Bob also has a slot 3 card that has a blue clue and a red clue on it. (Thus, it is a known rainbow card.)
  * Alice clues Cathy about a rainbow 4.
  * Bob is promised the rainbow 2 and the rainbow 3, so he knows that these cards must be on slots 1 and slot 3.
  * However, Bob also knows that you should always play the card with the most information on it first, so he plays his slot 3 card as rainbow 2 (instead of slot 1, the left-most card).

### The Fresh Play Clue (for Locked Players)

* If a player's chop is their slot 1, *Locked* players are **not** allowed to *Locked Hand Save* it. This follows from basic logic: it would be unlikely for a player with a *Locked Hand* to want to lock another player on the team with a non-critical card.
* Therefore, when a slot 1 chop card is clued by a *Locked* player, a *Play Clue* interpretation always takes priority over a *Locked Hand Save* interpretation.
* This type of *Play Clue* is called a *Fresh Play Clue* in order to disambiguate it from a *Locked Hand Save*.


### The Just-In-Time Fix Clue (To Fix a Layered Finesse with a Lie Component) (JIT / J.I.T.)

* When performing a *Layered Finesse* with a *Lie Component*, if the plan is to give a *Fix Clue* to the *Finesse Target* card (the "final" card that is to be blind-played), then it is important to wait until the **last** moment to give the *Fix Clue*. This is because after receiving the *Fix Clue*, the player will not play any more blind cards.
* Thus, you should first wait for all of the "good" blind cards to play, and **then** give the *Fix Clue* to the *Finesse Target*, so that it comes "just in time" before the misplay.
* Alternatively, if the plan is to give a *Fix Clue* to some **other** card than the *Finesse Target* (e.g. a number 5 clue to a 5 in the middle of the hand), then the *Fix Clue* does not necessarily have to be just in time. It can be done early, and the player will know that they have to continue blind-playing cards until they find the *Finesse Target*.
