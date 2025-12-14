# Roll20 Never Stop Blowing Up (NSBU) Roller Desktop App

> [!IMPORTANT]
> This was copied from my [Roll-NSBU-Roller repo](https://github.com/CorgiDev/Roll20-NSBU-Roller/settings/pages).

This is a simple desktop app to make my Never Stop Blowing Up (NSBU) rolls easier for me to roll. This is all based on the NSBU game system. You can learn more about it from the following pages, or checking out the sections in this page under the [NSBU Game Details heading](#nsbu-game-details):

- [‘Never Stop Blowing Up’ Game System | DropOut Store](https://store.dropout.tv/products/never-stop-blowing-up-game-system) (It is free!)
- [Dimension 20: Never Stop Blowing Up | :DropOut](https://www.dropout.tv/dimension-20-never-stop-blowing-up)
  - 10 episodes
  - Requires a subscription to watch.

## Desktop App Details

### Compatibility

The app should be able to be built to run on Windows, Linux, and Mac. Though I have only ever tested it on Windows.
 
### Installation

1. Install Node.js (https://nodejs.org/) if you haven't already
2. Install dependencies:
   ```
   npm install
   ```

### Running the App

To run the application in development mode:

```
npm start
```

### Building the App

To build the application for your platform:

- Windows: `npm run build:win`
- macOS: `npm run build:mac`
- Linux: `npm run build:linux`

The built application will be in the `dist` folder.

> [!NOTE]
> You can copy the `<os>-unpacked` folder onto your pc and make a shortcut to it on your desktop to more easily launch the app.

### Features

- Character information tracking
- Skill rolling
- Injury tracking
- Abilities management
- Group suites
- Auto-save functionality (data persists between sessions)
- Import/Export character data as JSON files

### NSBU Game Details

#### Stat Types

The following stats are the ones tht would potentially need to roll for:

- Stunts
- Brawl
- Tough
- Tech
- Weapons
- Drive
- Sneak
- Wits
- Hot

#### Roll Values

The following are the die values you may need to roll:

- 1d4
- 1d6
- 1d8
- 1d10
- 1d12
- 1d20
- 1d00 - Only happens when you blow up a d20
 
#### Turbo Tokens

Turbo tokens are earned when you blow up roll twice, or fail a roll.

#### Injuries

Injuries have to be tracked. Injury types include:

- Superficial
- Severe
- Adrenlized

#### Group Suites and Individual Abilities

There are various additional individual and group abilities you can get if you play a game using them.

### NSBU Credits

NSBU was written by Brennan Lee Mulligan & Carlos Luna, design & layout by Ruby Lavin, and with special thanks to The Intrepid Heroes & Hunters Entertainment.

## Resources

The following resources are for me to reference as I work on building out this extension, and are not relevant to the NSBU game itself.

- https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world
- https://www.freecodecamp.org/news/building-chrome-extension/
- https://www.w3schools.com/css/css3_mediaqueries_ex.asp
- https://www.w3schools.com/css/css3_flexbox_container.asp
- Resources for adding a dark mode:
  - https://stackoverflow.com/questions/19844545/replacing-css-file-on-the-fly-and-apply-the-new-style-to-the-page
