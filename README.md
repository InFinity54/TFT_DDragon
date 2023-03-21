# _Teamfight Tactics_ - Data Dragon

Do you want to use DDragon for an another game from _Riot Games_? Check the [_Data Dragon_ repository for _League of Legends_](https://github.com/InFinity54/LoL_DDragon), [for _Legends of Runeterra_](https://github.com/InFinity54/LoR_DDragon) or the [_Valorant_ one](https://github.com/InFinity54/Valorant_DDragon).

## Introduction
_Data Dragon_ is a package of files you can use for your projects about [_Teamfight Tactics_](https://teamfighttactics.leagueoflegends.com), distributed by Riot Games. A new version of Data Dragon is released some days after each new set release. This repository allows you to update automatically all files more easily.

Don't forget that new patchs will be added right after their release on Riot Games' Developers website, but it takes often many days to come.

## Important note about repository folder tree
Starting with set 8 update (also called mid-set patch), released with patch 13.6 of _League of Legends_, the repository folders will also changed, and will be using a new folder tree, partially based on the one included in _League of Legends_ _Data Dragon_.

## Additional contents in this repository
This repository contains some additional files, not included in Data Dragon :

- Icons of all turbo badges (used for _Hyper Roll_ game mode)
- Icons of all _Double Up_ badges (used for _Double Up_ game mode)

## Unused contents in this repository
Because of the presence of all previous sets (which can still be downloaded from Riot Games servers), some contents which became unused in _Teamfight Tactics_ are available in this repository. This content can be some deleted elements, or old versions of actual stuff. In the repository, you will find :

- All previous sets of the game, since set 2.
- All previous mid-sets of the game (called "sets update" in this repository) for sets 3 to 5 included.

## Sets added to this repository
The date in front of each set represents the date when the set was pushed to this repository, not the date when it was released by Riot Games. Here's a list of all sets included in this repository :

- (March 21st, 2023) Set 8 (update) : Monsters Attack - Glitched Out [from [_League of Legends_ _Data Dragon_'s repository](https://github.com/InFinity54/LoL_DDragon)]
- (January 11th, 2023) Set 8 : Monsters Attack [from [_League of Legends_ _Data Dragon_'s repository](https://github.com/InFinity54/LoL_DDragon)]
- (July 17th, 2022) Set 7 : Dragonlands [from [CDragon](https://raw.communitydragon.org/latest/cdragon/tft/) and official game files - not yet released by _Riot Games_]
- (February 10th, 2022) Set 6 : Gizmos & Gadgets [partially, from [CDragon](https://raw.communitydragon.org/latest/cdragon/tft/) and [Set 6 Promo Assets Page](https://spark.adobe.com/page/ficXgtBZ0f3xd/) - not yet released by _Riot Games_]
- (August 1st, 2021) Set 5 (update) : Reckoning - Dawn of Heroes
- (May 1th, 2021) Set 5 : Reckoning
- (January 21th, 2021) Set 4 (update) : Fates - Festival of Beasts
- (December 9th, 2020) Set 4 : Fates
- (December 9th, 2020) Set 3 (update) : Galaxies - Return to the Stars
- (December 9th, 2020) Set 3 : Galaxies
- (December 9th, 2020) Set 2 : Rise of the Elements

## Note about Sets 6 and 7
Set 6 has been added with some assets available on the [Set 6 Promo Assets Page](https://express.adobe.com/page/ficXgtBZ0f3xd/) (published by _Riot Games_) or/and on [_CommunityDragon_](https://raw.communitydragon.org/latest/cdragon/tft/). Set 7 used the same process, but only with _CommunityDragon_.

This was needed because _Riot Games_ didn't release at all an official version of _Data Dragon_ for these sets of _Teamfight Tactics_. Keep in mind that they are partially complete, and it can contains some mistakes. Feel free to help me to improve these sets if you can (issues are open if you want to)!

Due to what I said just above, keep in mind that `items.json`, `champions.json` and `traits.json` files can contains some elements from previous sets, which are not used anymore. Some items pictures can be missing or incorrect too.

There is also some differences between official _Data Dragon_ files and the temporary reconstructed folder:
- In `traits.json`, `type` doesn't exist.
- In `traits.json`, `style` (in `sets` array) is a number (like 1), and not a string (like `silver`).
- In `traits.json`, the `description` contains some variables strings (like `@Duration@`), which are not included.
- In `items.json`, the `description` contains some variables strings (like `@Duration@`), which are not included.
- In `items.json`, `isElusive` and `isRadiant` doesn't exists.

Sets 6 and 7 have been recreated, but their corresponding mid-sets will not be available in this repository. Data about these two sets will be replaced by the official _Data Dragon_ data, if _Riot Games_ finally release it one day.

## Note about repository's updates for set 8
Since patch 13.1 of _League of Legends_, files of _Teamfight Tactics_ seems to be added to the [_Data Dragon_'s files of _League of Legends_](https://github.com/InFinity54/LoL_DDragon). Due to this change, all JSON files of this repository will have a different structure, starting with set 8.