# CDucks

![Poster by Benjamin Hall](img/Poster.png)

## How to Play:
Several options exist for play.
 - You may consult any of the official releases (four as of 11/05/2025) [here](https://github.com/KERUITSICEDARVILLE/CDucks).
 - You may open this project in Unity (version 6000.2.9f1 preferred)
 - There's a Build0.zip in the main repo for easy access to a (mostly standalone) executable

## Description: 
This is a continuation of the development of [CDucks](https://github.com/KERUITSICEDARVILLE/CDucks) as subjected to five graded assignments per the Computer Graphics (CS4710) curriculum at Cedarville Uni. Our team took inspiration from map management games such as Plague Inc. and Bloons Tower Defense. A full-featured (PC-only) game was presented at a game exhibition at Cedarville Uni.

## Controls and Features:
We present a feature-rich game having a HUD overlay and mouse-grid interaction controls. To access the grid, having hexagonal a lattice and hexagonal grid spaces, one must select a region of the map on which to focus, or zoom sufficiently such that the indicator on the top of the HUD is at capacity. Once a region is selected, further zoom permits the user to see up close or zoom out of the region by exhausting the indicator. Using mouse middle-click, one may pan the map. Alternatively the pan button (bottom far right) may be selected and augment the mouse control such that pressing mouse left click allows the user to pan.

The grid may be interacted with in a number of ways, all determined by what "item" currently resides in the players "hand". The user (with sufficient funds) may employ a duck on the board by simply selecting the desired (unlocked) duck and clicking the left mouse button. The scooper (net) allows for early-game currency collection.

Algae (see game code for: BasicBlight/BlightController) occupy grid spaces at a rate proportional to a hidden growth factor. Algae blooms once at a growth of 100% and spawns a new spore which continues growing from a base growth of 30%. Fortunately, you are equipped with "items" for combat. You may place ducks having a range of attack indicated by a radius of green tiles. Early game requires that, without ducks, you use a net to attack algae. The user may press and hold to attack.

In order to gain back some of the user's spent currency, the user may remove ducks via the skull box "item". Currency is refunded based on duck health.

The banking system also requires explanation. There are two "wallets". One wallet contains currency you have earned this round and will be able to spend next round. The other wallet contains currency that you may currently use. The only way to obtain currency to spend immediately is by removing ducks.

If you are looking to play, best of luck!
