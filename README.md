## Elden Ring Character Planner
![logo](https://i.imgur.com/U1JLw57.png)
## Description
Elden Ring Character Planner is an application meant to help players experiment with builds. In Elden Ring, players can choose a starting class which determines their starting attributes and level. From there, they can add to their attributes when they level up. Each weapon in the game scales with attributes specific to that weapon. With the app, players can view their damage after scaling is applied, as well as if they are over-encumbered by equipping heavier items than they can manage.

## Installation

In order to run this application, expo-cli will need to be installed first.
- You can find instructions to [install expo here.](https://docs.expo.dev/get-started/installation/).
- You will also need to install yarn to download packages. [Instructions can be found here.](https://classic.yarnpkg.com/lang/en/docs/install).

After installing both of these, download and unpackage the repository, then browse to the directory it was unpackaged to.
In terminal run these commands to get a running version:
```sh
cd EldenRing-CharacterPlanner
yarn install
expo start
```

From here, you can scan the QR code provided in the terminal by expo. This will require the mobile expo app on a phone or tablet. 
- [Expo for Android](https://play.google.com/store/apps/details?id=host.exp.exponent)
- [Expo for iPhone](https://apps.apple.com/ca/app/expo-go/id982107779)

Alternatively, you can create a build by following instructions [here.](https://docs.expo.dev/classic/building-standalone-apps/) and  following the CLI prompts provided by Expo.

## Operation Instructions

The primary screen is divided into three main sections: Attributes, Equipment, and Status

![blank_screen](https://i.imgur.com/wYUaqTB.pngg)

From here, you can choose from one of the starting classes, which will update your attributes.

![drop_down](https://i.imgur.com/3OTm86H.png)

Any of the equipment slots near the center act as buttons and can be pressed. When pressed, you will be taken to the corresponding screen depending on what type of equipment you chose. After selecting weapon, you'll be taken to the weapons screen, to choose from. The weapon and chest slot screens are shown below:

![weapons](https://i.imgur.com/jsqdwux.png) ![chest](https://i.imgur.com/kTvktrp.png)
The armor and talisman screens have the same layouts, but weapons give you more options. Some weapons can only be 'Standard' and can't be infused with elements or Heavy, Keen or Quality. All grey buttons are physical-only enhancements, while fire lightning and magic are hybrid damage (at the cost of scaling). Once you select an armor piece, or a weapon enhancement, you will be taken back to the main screen and the slot will be filled.

This is what a fully filled out inventory looks like, wich some attribute additions:
![chest](https://i.imgur.com/Amlm4jG.png)
As equipment and attributes are changed, the bottom status menu is updated. The magic enhanced version of the claymore was selected, so there is physical and magic damage. Equip load remains green because this individual has enough endurance to not become overencumbered. The effects of the talismans are also displayed in the status.

## Potential Future Features
- There are only some of the weapons, armors, and talismans of the game added (enough to test variation). Most weapons have 7 enhance types, which means 7 objects, each with their own damage and scaling. Data files grow quickly for these game entities.
- Elden Ring has all kinds of tertiary things that affect damage, which could be added.
- Spells and ranged weapons.
- More status features, like armor secondary stats.

## Credits
- The idea comes from the original webapp for Dark Souls 1: [MugenMonkey](https://mugenmonkey.com/darksouls)
- All game image files and game data used come from [FextaLife](https://eldenring.wiki.fextralife.com/Elden+Ring+Wiki). I do not claim ownership over any of these, nor will this ever be commercialized.
