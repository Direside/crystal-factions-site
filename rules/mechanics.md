# Mechanics

## Must
The following ability is a mandatory requirement of playing the card.

By default all abilities are required unless otherwise stated. This means the player who played the ability must activate and complete the action if possible. It is however allowable that a player might enter a situation in which they are unable to completely do the action, in which case they would fulfill the requirement as much as possible. E.g. "End of Turn: You must discard three cards from your hand", with a hand of only one card, would mean you discard down to 0.

## May
The following ability is optional.

This is to allow the player who played the ability to skip the activation of said ability. If you skip part of an ability, you must skip the whole ability. E.g. If you "may discard a card to gain 5 hp", you cannot skip the discard and still gain the hit points.

## Discard
Move specified card to your discard pile.

Cards can be discarded from the hand or playfield for a given player. Discarded cards always end up in the discard pile for the player that owns the card.

## Destroy
Target player moves selected card to their discard pile.

Similar to discard, but works on cards that are in play. Destroyed cards no longer trigger their End of Turn abilities. You cannot destroy a stealth or untargetable card.

## Gain Crystals
Increase your available crystals by the listed amount.

Crystals are available immediately for use in the stage the ability is triggered. Crystals gain on a When Played ability can be used to play future cards in the same turn. Gained crystals cannot be used to pay for the card that gave you those crystals, only subsequent cards. Crystal victory conditions are still calculated at the end of turn, even if you hit the required amount by gaining crystals earlier in the turn.

## Gain HP
Increase your hit points by the listed amount.

You may gain additional hit points above your maximum unless otherwise stated. Hit points are gained at the time the ability is triggered, gaining hit points after you have already reached 0 does not prevent a loss.

## Deal Damage
Reduce the targeted players hit points by the listed amount.

Damage is applied in the order the abilities are activated. Unlike crystal victory conditions you immediately lose if your hit points are reduced to 0. If there is an ability that causes damage to both players and reduces them both to below zero, the game is a draw.

## Prevent Damage
Reduce the amount of damage you take from all abilities up to the listed amount this turn.

Prevents damage from abilities as well as damage from combat, in the order it occurred. This cannot be used to prevent damage that occurred in an earlier stage of the turn or before the ability was activated. E.g. If your opponent played a “Deal 2 damage” ability, then you played a “Prevent 2 damage this turn” you would still take the 2 damage, but any future triggered abilities or combat damage would be prevented up to the 2.

## Disable
Specified cards power is 0 until end of turn.

This does not stop End of Turn abilities or other interactions with the card. Disabled cards are still considered as their type and being in a lane/in play for any calculations that consider that. Disabled tech cards still provide tech requirements for a players turn, but any abilities that consider your tech level, e.g. "gain crystals equal to your tech level", would be effected.

## Shift
Move a card from one lane to another.

This ability does not re-activate any abilities on played cards. If your card had a lane dependent End of Turn ability then it applies to the lane it was moved to, not the lane it was played in. Cards moved into or out of the tech lane do not alter the tech you have available for your current turn.

## Displace
Move an opponents card from one lane to another.

See Shift, but applies to another player's lanes instead.

## Draw
Add a card from your deck or the basic card pool to the specified players hand.

Some abilities may specify a location to draw from such as your discard pile, or a specific type of card, such as a basic card. Cards drawn may be played as normal any time after the draw action is completed.

## Return to Hand
Return a card from the playfield to the specified players hand.

Some abilities may specify a location or card type to return to your hand. Cards played this turn may return to your hand unless specified. It's not necessarily required that the card was in your hand at any point, cards put into play by other abilities may also be returned to your hand.

## Reduce Cost
Reduce the amount of crystals you must pay to play a card.

This may be on your current card, or applied to future cards you play on the turn. If the card cost depends on cards in play, you do not count the card currently being played in any cost reductions for itself.

## Reduce Tech Req.
Reduce the amount of tech pool consumed to play a card.

This may be on your current card, or applied to future cards you play on the turn. If the card tech requirement reduction depends on cards in play, you do not count the card currently being played in any tech reductions for itself.

## Shuffle into your Deck
Take specified card, place it on top of your deck and then shuffle the whole deck.

Shuffling should be sufficient that the cards location is no longer known. Your opponent may cut the deck after any shuffle.

## Put into Play
Take a card from specified location and put it into the specified lane.

If no location is specified the card goes from your hand into any lane. Cards put into the Mining and Attack lanes take effect immediately. Cards in the tech lane count when calculating the number of cards present in the lane, but do not allow for additional tech on the current turn.

## Typed Cards
A card of a type is specified the the text under the card name and effects all abilities for the named type.

Cards may have multiple types. If multiple types are on a card it counts as all the listed types when it comes to resolving abilities.

## Split Cost
Pay a cost to play this, but then and additional cost to leave it in play at End of Turn.

The End of Turn cost is only played once to keep the card in play. If an ability or effect returns the card to your hand, or otherwise removes it from play, re-playing the card will require the End of Turn cost to be paid again.

## Corrupt
Add a number of -1 corruption tokens to the specified location.

1. End of turn: Discard a card from your hand to remove a corruption token.
2. Start of turn: Pay 2 to remove a corruption token. This occurs before Tech is calculated, so removing from your tech lane works as you’d expect and gives you the tech allowance.

Corruption tokens are applied immediately to the location they are played. Values cannot drop below your base, so you will still be able to play cards and gain crystals. Tokens applied to tech take effect on your next turn, unless removed during your start.

It's possible to prevent yourself from being able to play any cards with corruption. Removing corruption happens during your End of Turn phase and in the order you choose.

## Boost
Add a number of +1 boost tokens to the specified location.

Boost tokens are applied immediately for mining and attack lanes, but boost tokens in the tech lane don't take effect until the next turn. Unlike corruption tokens, boost tokens cannot be removed unless you have an ability that does so.

## Take Priority
Move the priority token to your side of the field.

All future phases play out as if you had priority. You resolve your Mining and End of Turn phases first, including any win conditions triggered during them.

## Postpone Priority
Move the priority token to the next player. Take the rest of your turn after all players are done.

This lets you interrupt your play phase and allow the other players to take their play phases before you. This does not reset your tech limit for the turn, give you another draw phase, or re-activate any abilities. You may only do this once per turn, so if another player passes the priority back to you, you may not postpone again.

## Gambit
Add a number of gambit tokens to your Attack lane. During combat resolution the losing player takes +1 damage.

This does not effect your Attack power in the lane. It is additional damage added after the combat is resolved. Damage is taken as part of the Attack phase and before any End of Turn effects. Damage can be reduced or prevented by abilities.

## Stealth
Play a card face down in a lane. End of Turn: Reveal this card, then pay its costs and tech requirement and trigger it's abilities during the End of Turn phase instead, or return it to your hand.

Cards must have the stealth keyword on them to be played as such. You must reveal the card even if you are returning it to your hand. If a card revealed is not a stealth card that player forfiets the match. Stealth cards are untargettable until they are revealed.

## Solo
Solo cards can only be played if you have not played any other cards this turn.

Playing a solo card ends your turn and moves to the next player, or the Attack phase if you are the last player.

## Scuttle
Discard a card to gain hitpoints equal to its power.

Power is determined by the value in that lane it is in when the ability triggers. This does not include any Boost or Corrupt tokens on the lane, just the number on the card itself.

## Reallocate
Temporarily use the power from your Attack or Mining lane as Tech this turn.

If you reallocate your Mining lane to another, skip your Mining phase. If you reallocate your Attack lane, your attack power counts as 0 in the combat calculation. Corruption counts in the reallocation so a power of 5 with one -1 corruption token would count as 4. Like normal, tech from cards played this turn does not count. E.g. If you had 3 power in your Mining lane, played a basic card to increase it to 4, then reallocated, you would only have 3 additional tech. Skipping a phase means your power in that lane is 0, even if you played additional cards in that lane during the turn you reallocated.

## Redeploy
Return all cards from your lanes to your hand.

You must pay the tech and crystal costs like normal when playing these cards. Some abilities may specify a type, e.g. "Redeploy all your basic cards", or may apply to all played cards. Redeploying does not refund the tech or crystals used to play cards this turn.

## Untargettable
This card cannot be the target of any abilities this turn.

Effect lasts from the time the card is played until after the End of Turn phases are complete. Abilties that target all cards, e.g. "Redeploy", or effects that target a type, e.g. "all Drone cards", still effect this card.

## Piloted
When this card is discarded or returned to your deck or hand, place a basic trooper in it's place.

Piloted is a type of card that has a special effect. It will have a type icon similar to existing types in the game. Effect occurs from abilities played by yourself as well as other players. Basic trooper is from the deck, not from your hand, you do not need a basic trooper in your hand to activate this.

## Morph
Specified card takes on target cards types and power for this turn.

This does not include abilities, unless the ability is tied to a type, e.g. Piloted. The morphed card retains it's original costs and tech requirements if returned to your hand. After this turn it reverts to its original types and power levels.