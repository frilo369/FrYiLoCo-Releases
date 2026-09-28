<div align="center">
  <h1>FrYiLoCo</h1>
  <p><strong>Every League of Legends skin, applied automatically. Alone or with your friends.</strong></p>
  <p>
    <a href="https://github.com/frilo369/FrYiLoCo-Releases/releases/latest/download/FrYiLoCo-Setup.exe"><strong>Download for Windows</strong></a>
    ·
    <a href="https://github.com/frilo369/FrYiLoCo-Releases/releases">All releases</a>
  </p>
</div>

FrYiLoCo is a skin catalogue and automatic patcher for League of Legends on Windows. Pick
any skin or chroma for any champion, and FrYiLoCo puts it in your game when champion select
ends. There is nothing to press. Play with friends in Party Mode and everyone sees each
other's skins.

The skins only show on your own computer, and for party members running FrYiLoCo. Other
players see the default skin.

## Contents

- [Install](#install)
- [Your first game](#your-first-game)
- [The skin catalogue](#the-skin-catalogue)
- [Automatic patching](#automatic-patching)
- [Party Mode](#party-mode)
- [The skin database](#the-skin-database)
- [Custom skins](#custom-skins)
- [Themes](#themes)
- [MetaSRC builds](#metasrc-builds)
- [Settings](#settings)
- [Updates](#updates)
- [Privacy](#privacy)
- [Good to know](#good-to-know)

## Install

1. Download **[FrYiLoCo-Setup.exe](https://github.com/frilo369/FrYiLoCo-Releases/releases/latest/download/FrYiLoCo-Setup.exe)**.
2. Run it. Windows may warn that the publisher is unknown, because FrYiLoCo is not
   code-signed. Choose **More info → Run anyway**.
3. Setup installs everything FrYiLoCo needs, including the League Toolkit patcher. It
   downloads the patcher from League Toolkit's official releases and verifies it before
   installing, so you need an internet connection.

FrYiLoCo runs on Windows 10 and 11 (64-bit). It starts with Windows and waits in the system
tray, so it is ready before your first champion select.

## Your first game

1. Open FrYiLoCo. If the catalogue is empty, or the top bar reads **UPDATE DATABASE**, press
   it to download the skins.
2. Queue up in League as usual.
3. When you lock in your champion, FrYiLoCo opens that champion's skins. Pick one.
4. That's it. As champion select ends, FrYiLoCo counts down and patches your game, and your
   skin is there when the game loads.

When the match ends, your skins are switched off, so every game starts from a clean
selection.

## The skin catalogue

- **Every champion, every skin.** Browse champions in a grid, search by name, filter by role
  (Top, Jungle, Mid, Bottom, Support), and sort A–Z, Z–A, most skins or fewest skins.
- **Chromas.** Chromas sit under their base skin. Open the skin to pick a colour.
- **Forms and editions.** Skins with forms or tiers carry their own art and a **FORM**,
  **TIER** or **EDITION** badge: Elementalist Lux, Gun Goddess Miss Fortune, Arcane
  Fractured Jinx, DJ Sona's genres, Revenant Reign Viego's swords, the Hall of Legends
  editions and more.
- **Skins.** Every skin from every champion in one gallery.
- **Enabled Skins.** Show only the champions you have a skin turned on for.
- **Your picked champion, bottom left.** The button in the bottom-left corner shows the
  champion you picked for the current match. Click it to open that champion's skins.
- **It remembers where you were.** Search, selection and scroll position are kept while the
  app is open.

In champion select, the catalogue opens by itself as you lock in, and comes to the front over
League. Clicking anywhere outside it closes it. You can turn both off in Settings.

## Automatic patching

You never have to press anything to apply your skins.

- The **match status** panel shows where you are: lobby, champion select, in game, match
  ended.
- As champion select ends, the status bar counts down with a short countdown sound, then
  patches the game with the skins you enabled. You can still change skins during the
  countdown, and your latest choice is used.
- It works in Summoner's Rift, ARAM, ARAM: Mayhem and Arena.
- **Force Patch.** If your game closes while the match is still running, because of a crash
  or because you quit to change a skin, the status bar turns into **Force Patch**. Press it
  and your skins are applied before you reconnect.
- When the match ends, the patcher stops and your skins are turned off for the next game.

## Party Mode

Play with friends and see each other's skins.

1. Press **PARTY** on the top bar.
2. One person presses **Create Party** and gets a four-character code, like `K7QX`.
3. Everyone else enters that code and presses **Join Party**.

Once you're in a party:

- Everyone's skin picks are synchronized, so you see your friends' skins in game and they
  see yours.
- Pick your own name and party icon.
- The bottom bar shows who is in the party and who is ready.
- Nobody has to press Ready. Each player is readied automatically near the end of champion
  select, and the whole party patches together.
- **Version check.** If your FrYiLoCo or skin database is older than someone else's in the
  party, you get a warning with one button that updates you. Everyone needs the same
  database to see the same skins.

Party Mode only sends small skin identifiers through the FrYiLoCo relay, never the skin files
themselves.

## The skin database

The skins come from the community
[LeagueSkins](https://github.com/Alban1911/LeagueSkins) database and are kept in
`Documents\FrYiLo Skins Database`:

- **Riot Skins** holds the official skins. Updating the database replaces this folder.
- **Custom Skins** is yours. No update ever touches it.

The top bar shows the date of your database, like `DATABASE SEP 27`. When a newer one is out,
the button turns green and reads **UPDATE DATABASE**. Press it and only the skins that changed
are downloaded. If anything goes wrong, your previous database is put back. The database
can't be updated during a match.

## Custom skins

Put any `.fantome` skin in `Documents\FrYiLo Skins Database\Custom Skins`, then open
**Custom Skins** in the left rail. Custom skins are turned on and patched just like official
ones.

## Themes

Open **Themes** in the left rail to change the look of the whole app. Each theme has its own
artwork and a colour palette that matches it:

Event Horizon (the default), Spirit Blossom, Somewhere Again, Neon Rick and Morty, Unlimited
Void, Gold Filament, Astral Peaks, Blue Dream, Crimson Cyberpunk, Cyan Cosmos, Itachi
Amaterasu and Monochrome Streetwear.

Themes work offline. An enabled skin is always green, whatever the theme.

## MetaSRC builds

Press **MetaSRC** in the left rail to open the MetaSRC build page for your champion in its own
window, with the ads hidden. When a game starts, it opens by itself for the champion you took
into the game, so you can read your build during the loading screen. It closes when the game
ends.

## Settings

Open Settings with the gear on the top bar.

| Setting                   | What it does                                                           |
| ------------------------- | ---------------------------------------------------------------------- |
| **Library**               | Opens your Riot Skins and Custom Skins folders.                        |
| **Start with Windows**    | Starts FrYiLoCo in the system tray when Windows starts. On by default. |
| **Live status**           | Shows the live session panel at the top right.                         |
| **Champion select**       | Opens your champion's skins when you lock in.                          |
| **Champion select focus** | Brings FrYiLoCo in front of League when you lock in.                   |
| **MetaSRC**               | Opens MetaSRC by itself when a game starts.                            |
| **Patch sounds**          | Plays the countdown sound before a patch.                              |
| **Theme updates**         | Keeps your own theme when an update changes the default one.           |
| **Updates**               | Shows your version and checks for a new one.                           |

## Updates

FrYiLoCo checks for updates when it starts. When a new version is out, the version button on
the top bar says so. Press it to update. Every update is signed, so FrYiLoCo only installs
updates that really come from FrYiLoCo.

The download link at the top of this page always gives you the newest version.

## Privacy

- No telemetry is sent unless you turn it on.
- Party Mode sends your party name, a random member ID and your skin identifiers, nothing
  else.
- Setup and database updates download from GitHub. Skin artwork may load from Riot's own
  image servers, with bundled champion icons as a fallback when you're offline.

## Good to know

- **Keep FrYiLoCo running before champion select.** It watches the League client to know when
  to patch, so it has to be open before champion select ends. Starting with Windows takes
  care of this.
- **League patches.** A League or Vanguard update can occasionally stop skins from working
  until FrYiLoCo or League Toolkit is updated.
- **Party members need the same database.** A skin missing from your database can't be shown
  to you. Update your database when the party warns you.
- **Chroma colours** are worked out from their names, so a few may not match Riot's exact
  colour.

## License

FrYiLoCo is built on [League Toolkit](https://github.com/LeagueToolkit)'s
[LTK Manager](https://github.com/LeagueToolkit/ltk-manager) and is licensed under the
GNU General Public License v3.0 or later. The patcher components are covered by
the LTK Patcher License.

FrYiLoCo is not an official League Toolkit or Riot Games product, and is not endorsed by
Riot Games.
