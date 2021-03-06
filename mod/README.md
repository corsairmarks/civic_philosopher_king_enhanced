# Overview

Like the idea of enlightened authoritarian rulers with Civic: Philosopher King but feel a bit underwhelmed at its actual affects?  Then this mod is for you!  It lightly enhances Civic: Philosopher King to have effects similar to those added to Civic: Distinguished Admiralty in Stellaris version 3.3 "Libra:" Rulers and Governors begin with +2 levels.

# Changes

Adds two events that grant bonus levels to Rulers and Governors for empires with Civic: Philosopher King.  Overwrites the built-in localisation for Civic: Philosopher King to describe this added effect.

## Compatibility

Any mod that does not remove Civic: Philosopher King.

Built for Stellaris version 3.4 "Cepheus."  Not compatible with achievements.

### When to Install

This mod can be safely added or removed from your savegame after the game has started.  It is implemented entirely through custom events.  If you remove it, your game will work normally.  Any rulers or governors will keep their bonus levels.

## Localisation

The text describing the effects for Civic: Philosopher King has been edited to describe its new effect for eight officially-supported Stellaris languages.  I'm reasonably confident in my splicing for most languages, although I may have used the wrong word for "and" in Chinese.  It is not translated for Korean or Japanese.

## Changelog

* 1.0.0 Initial version
* 1.0.1 Remove mod flag - as a small rules change, having a detection flag seems extraneous
* 1.0.2 Fix localisation for Chinese and Spanish - the files accidentally claimed to be English!
* 1.1.0 Flagged as compatible with Stellaris 3.4 "Cepheus" - no actual changes

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/civic_philosopher_king_enhanced)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.