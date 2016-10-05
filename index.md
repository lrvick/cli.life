# CLI.life

A curated directory of tools for a CLI driven lifestyle.

## Password Management

### password-store

<https://password-store.org>

#### Example:

```bash
# Init with git
pass init 0xABCDEFG
pass git init
pass git remote add origin git@github.com:you/passdb.git

# Generate/sync 50 char random password for "somesite"
pass generate Personal/somesite 50

# Retrieve password on another system
git clone git@github.com:you/passdb.git $HOME/.password-store
pass Personal/somesite
```

#### Highlights:

  * Single script, easy to audit
  * Uses GPG under the hood with simplified syntax
  * Transparent support for GPG hardware tokens like Yubikey
  * Minimal exposure: decrypts one item at a time
  * Sync via remote git repos
  * Keyboard emulation to auto-type anywhere
  * Mobile companions available
  * Just a wrapper: you can always manage with GPG/git directly
  * Easy Sharing: Edit a text file in shared folder with others keys

#### Further Reading:

  * [TickOfTheTrades Guide to pass](http://www.tricksofthetrades.net/2015/07/04/notes-pass-unix-password-manager/)
  * [Android Password Store](https://github.com/zeapo/Android-Password-Store)

## Calendar

## Task Management

## Backup

## E-Mail

## Chat

## Browsing

## File Sharing

## Stocks

## Spreadsheet

## Documentation

## Programming

## News

## Version Control
