# MisterZine Arcade BETA

MisterZine Arcade BETA is the members' Beta of
[MisterZine](https://github.com/matijaerceg/misterzine-on-device), for
supporters at [patreon.com/MisterZine](https://www.patreon.com/MisterZine).
Members get each new version of MisterZine in Beta before it reaches Stable,
the public release, and the members' extras marked ★ in Options, such as
themes.

This repository holds the ready-made downloads only. Beta takes Stable's
place on your card: favorites and settings come along, and Update All keeps
it current. You can go back to Stable at any time.

## Install

Your MiSTer needs its network connection and Downloader, which Update All
installs.

1. Download **MisterZine-Install-Beta.sh**, linked from the members' post on
   Patreon and attached to the newest release here.
2. Copy it to the `Scripts` folder on your SD card.
3. On the MiSTer, open Scripts and run **MisterZine-Install-Beta**.
4. Return to the main menu, choose **MisterZine Arcade BETA** and enter the
   code from the members' post.

The installer works whether or not MisterZine is already on the card, and
running it again is safe. It changes one line of your Downloader settings: the
address of the `misterzine` entry, which now leads here. Your other
Downloader settings stay as they are. The main-menu entry becomes
**MisterZine Arcade BETA**; on a card that never had MisterZine the installer
adds it, as **MisterZine-Setup** does. Keep the script in Scripts: it is how
you come back later.

## The code

MisterZine Arcade BETA asks for the six-digit code from the current members'
post and remembers it. A new batch of features comes with a new code: after
that update the app asks again, and the newest post has it. Please keep the
code to yourself.

## Updates

New versions arrive with your normal Update All runs. When one is out, the
bar at the bottom of the list shows **App update**, and **Update MisterZine
only** in Options fetches just the new version in a few seconds.

Every Stable release comes here too, with the members' extras, so Beta is
never behind Stable.

## Back to Stable

Run **MisterZine-Switch-To-Stable** from Scripts. It points the `misterzine`
entry back at Stable's releases and installs Stable in Beta's place. The
main-menu entry goes back to **MisterZine Arcade**. Favorites and settings
stay; the extras' settings wait on the card for when you come back.

## If Update All put Stable back

MiSTer Companion's Install Center, and copying Stable's
`downloader_misterzine.ini` to the card again, point the `misterzine` entry
back at Stable's releases. MisterZine Arcade BETA notices when it starts and
sets the entry back, saying **Update All keeps Beta now**. If Update All ran
first and Stable is back, MisterZine asks once whether to go back to
MisterZine Arcade BETA: hold A, and it runs your MisterZine-Install-Beta.

## If something goes wrong

- *Downloader is not on this card*: run Update All once, then run the script
  again.
- *An updater is running*: let Update All or Downloader finish, then try again.
- *Downloader did not finish*: check the network connection and run the
  script again. Update All also finishes the move, since the `misterzine`
  entry already names the version you chose.
- *An NFC tag or `bootcore` line stopped opening MisterZine*: Beta's entry is
  `/media/fat/MisterZine Arcade BETA.mgl`, Stable's
  `/media/fat/MisterZine Arcade.mgl`. Point it at the one on the card.

**MisterZine-Uninstall** removes MisterZine Arcade BETA the same way it
removes Stable. For anything else, see the
[user guide](https://github.com/matijaerceg/misterzine-on-device/blob/main/docs/USER_GUIDE.md)
and [troubleshooting](https://github.com/matijaerceg/misterzine-on-device/blob/main/docs/TROUBLESHOOTING.md).

## Licence

The members' extras are proprietary; the rest is MisterZine's own MIT code.
Each download carries MEMBERS-LICENSE.txt, which says which is which.
