# passdrop

**Note: I am no longer actively developing PassDrop, as I no longer use iOS devices or Mac OS X.**

**Since the existing version of PassDrop uses an outdated DropBox API that will or has stopped working (depending on when you read this), I have removed it from the app store to prevent users buying an app that no longer functions.**

**If you want a more up to date version of PassDrop, check out [Chad Austin's fork](https://github.com/chadaustin/passdrop), which is available on the app store as [PassDrop 2](https://itunes.apple.com/us/app/passdrop-2/id1206056096).**

PassDrop is a fully-featured secure password management system, compatible with the free [KeePass 1.x (Classic)](http://keepass.info/) and multi-platform [KeePassX](http://www.keepassx.org/) desktop applications. PassDrop uses the free [DropBox](http://www.dropbox.com) storage service for hassle-free synchronization of your password databases between your iPhone, Windows, OS X, and Linux desktop computers.

## PassDrop FAQ

If you are experiencing issues or need help using PassDrop, please check out the [PassDrop FAQ](https://github.com/rudism/passdrop/blob/master/FAQ.md).

## Current Features (1.2)

- Strong emphasis on clean, simple, intuitive user interface
- Fully optimized for all devices including retina iPhones and iPads
- Built for iOS 7
- Load, create, and edit multiple KeePass 1.x databases in your DropBox account
- Open KeePass 1.x databases with any file extension
- Fully integrated two-way syncing to DropBox, with collision detection
- Lock file utilization when opening databases in edit mode
- Offline read access to databases when no network is available
- View, create, move, sort, and edit all groups and entries nested to any level
- Password generator to automatically create random strong passwords for entries
- Entry search capabilities at global and group-specific levels
- Copy logins, passwords, urls, or notes to your clipboard
- Automatically open urls in Safari while PassDrop remains open in the background
- Optionally clear clipboard whenever PassDrop is re-activated
- "Lock in background" option to auto-lock your database after a customizable amount of time
- Hide "Backup" group results when searching entries
- Encrypted HTTPS communication directly with the official DropBox API for maximum security

## Commonly Requested Missing Features

- File attachment viewing and sharing
- Option to visually mark or hide expired entries
- Add files from other apps via file sharing
- Ability to unlink DropBox and keep local databases
- Key file authentication
- Better UTF16/international character support
- KeePass 2.x database support
- KeePass 2.x is not an improved version of KeePass 1.x, but rather an entirely new product with completely unrelated file formats. Both KeePass 1.x and 2.x are actively developed and maintained and are viable password storage solutions. I chose to support KeePass 1.x with PassDrop due to the higher portability and multi-platform support for the KeePass 1.x file format.
- Twofish encryption
