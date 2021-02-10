# Gilded Rose Refactoring Kata

# Specs of the Gilded Rose

- Each item is initialised with a name (string), a sell-in (integer), and a quality value (integer)

- Gilded Rose is then initialised with items taken as an argument.

- the method update_quality is then called on items, which is then interated through and put through a series of conditional statements in order to decide how to alter the current quality value.

# Conditions

## General Item Conditions:
- After Sell In reaches 0, items degrade 2x as fast
- Quality can never be < 0 && never be > 50

## Special Items Conditions:
- "Sulfuras" (legendary item) never decreases in quality
- "Backstage passes", increase in quality as SellIn V approaches
	- (quality increases by 2 when they are 10 days out, and 3 when they are 5, but quality drops to 0 after the sell by date)
- "Conjured Items" degrade twice as fast as normal items
