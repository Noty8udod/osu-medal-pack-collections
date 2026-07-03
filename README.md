# All Medal Beatmap Pack Collections v1.1

Collection files for osu! medal hunters who want every medal-giving beatmap pack organized without building all the collections by hand.

📦 Covers **Video Game Vol.1** through **Project Loved: Best of 2025**.

✅ Verified/updated as of **June 17, 2026**.

>  This is **not** a beatmap mirror. No `.osz` beatmap files, songs, backgrounds, or beatmap assets are included.

> **Medal tip:** This repo organizes the pack collections, but some medals have extra unlock conditions. Use **[osekai medals](https://inex.osekai.net/medals/)** to check requirements, solutions, mod restrictions, and game mode requirements. Some maps only show under their own game mode, so they may not appear in osu!standard.

<table>
<tr>
<td><img src="https://github.com/Noty8udod/osu-medal-pack-collections/blob/main/screenshots/showcase.png?raw=true" width="500" alt="Collection list overview"></td>
<td><img src="https://github.com/Noty8udod/osu-medal-pack-collections/blob/main/screenshots/showcase2.2.png?raw=true" width="500" alt="Collection list ending"></td>
</tr>
</table>

## Table of contents

* [What this is](#what-this-is)
* [Quick start](#quick-start)
* [Downloading missing maps](#downloading-missing-maps)
* [Optional bonus collection](#optional-bonus-collection)
* [osu!lazer import](#osulazer-import)
* [Collection ordering](#collection-ordering)
* [Reporting issues](#reporting-issues)
* [Project note](#project-note)
* [License](#license)

---

## What this is

This is a collection metadata set for every osu! beatmap pack that can grant medals. It is mainly meant for medal hunters who want the packs sorted cleanly in-game instead of manually creating every collection from scratch.

It also gives pack clearing a little more structure. Instead of only chasing leaderboards, pp, or random map downloads, you can work through the medal packs like a progression list.

## Included files

| File                                              | Purpose                                        |
| ------------------------------------------------- | ---------------------------------------------- |
| `All_Medal_Beatmap_Packs_v1.1.osdb`               | Recommended import file for Collection Manager |
| `All_Medal_Beatmap_Packs_v1.1.db`                 | Backup collection database                     |
| `Iconic_and_Notable_osu_Maps_v1.0.osdb`           | Optional iconic/notable maps collection        |
| `Iconic_and_Notable_osu_Maps_v1.0_collections.db` | Backup database for the optional collection    |
| `CHANGELOG.txt`                                   | Version history                                |
| `screenshots/`                                    | Preview images of the collection list          |

## Includes

* One all-in-one `.osdb` file for medal-giving beatmap packs
* Individual collections sorted by pack/category
* Featured Artist medal packs
* Mappers' Guild medal packs
* Project Loved medal packs
* Optional iconic/notable osu! maps collection

> This repository only contains collection metadata. It does not redistribute `.osz` files, songs, backgrounds, beatmap assets, or any other copyrighted content.

---

## Quick start

Use the `.osdb` file with **[Collection Manager](https://github.com/Piotrekol/CollectionManager/releases)**.

The `.osdb` file is recommended because it handles missing maps better and is easier to share than a raw `collections.db` file. The `.db` backup is mostly there for people who already know what they are doing and have the required maps downloaded.

**Back up your current `collections.db` before importing anything.**

1. Close osu!.
2. Back up your current `collections.db`.
3. Download `All_Medal_Beatmap_Packs_v1.1.osdb`.
4. Open **Collection Manager**.
5. Drop the `.osdb` file into Collection Manager.
6. Import and save the collections.
7. Open osu!stable and confirm the collections show up correctly.
8. If you use osu!lazer, run the setup wizard in lazer and import your collections from stable.

> Only use `All_Medal_Beatmap_Packs_v1.1.db` if you know what you are doing. Replacing `collections.db` directly can overwrite your personal collections if you did not back them up first.

---

## Downloading missing maps

These are listed in the order I would try them.

### 1. Collection Manager

**[Collection Manager](https://github.com/Piotrekol/CollectionManager/releases)** is the easiest option if you want to import the `.osdb` and download missing maps from one place.

1. Open **Collection Manager**.
2. Drop `All_Medal_Beatmap_Packs_v1.1.osdb` into Collection Manager.
3. Click **Online**.
4. Select **Download All Missing Maps**.
5. Save/import the collections.
6. Open osu!stable and confirm the collections show up correctly.
7. If you use lazer, run the setup wizard and import from stable.

> Collection Manager may require osu! cookies for online lookup/download features.

### 2. osekai medals

Use **[osekai medals](https://inex.osekai.net/medals/)** to check medal requirements and solutions.

Some medal pages may include a download button or link you back to the official osu! pack page.

### 3. osu!Collector

Use the **[osu!Collector collection](https://osucollector.com/collections/22116/All-Medal-Giving-packs)** if you have osu!Collector access and want a fast way to add the mass collection and grab missing maps.

### 4. Official beatmap packs

You can also download packs directly from the **[official osu! beatmap packs page](https://osu.ppy.sh/beatmaps/packs)**.

This is the most manual option, since you may need to find each pack yourself.

---

## Optional bonus collection

This release also includes a separate optional collection:

```text
Iconic_and_Notable_osu_Maps_v1.0.osdb
```

This is not part of the medal pack set and is **not required for medal hunting**. It is just a curated set of iconic, recognizable, older, or historically notable osu! maps.

The idea is to give newer, returning, or curious players a cleaner way to explore some well-known osu! map history without digging through years of community references.

It includes themed collections for things like:

* older legends
* leaderboard-history maps
* stamina culture
* jump training
* tech mapping
* Loved chaos
* other recognizable parts of osu! history

Important notes:

* This is optional.
* This is not required for medal hunting.
* This slots in at the bottom after the normal medal pack collections.
* This is not an official osu! beatmap pack.
* This is subjective and curated.
* This is not a complete historical archive.
* This does not include `.osz` files.
* This is collection metadata only.

Recommended file:

```text
Iconic_and_Notable_osu_Maps_v1.0.osdb
```

Backup file:

```text
Iconic_and_Notable_osu_Maps_v1.0_collections.db
```

---

## osu!lazer import

osu!lazer does not currently have a direct `.osdb` or `collections.db` import flow. The cleanest method is to import the collections into osu!stable first, then import your stable data into lazer.

1. Install osu!stable if you do not already have it.
2. Launch osu!stable once. You do not need to sign in.
3. Create at least one test collection in stable so the collection database exists.
4. Close stable.
5. Import these collections into stable:

   * Recommended: import the `.osdb` through Collection Manager.
   * Advanced: use the provided `collections.db` only after backing up your current one.
6. Launch stable and confirm the collections show up correctly.
7. Open osu!lazer.
8. Go to **Settings → Run setup wizard**.
9. Skip to the import section.
10. Import your beatmaps and collections from osu!stable.
11. After the import finishes, the collections should be available in lazer.

---

## Collection ordering

osu! and osu!lazer sort collections alphabetically and do not have a manual ordering override. This collection set uses number prefixes so the packs stay in a predictable order.

Example:

```text
0001 Video Game Vol.1
...
0121 Project Loved: Best of 2025
```

To keep your personal collections above these, prefix them with a period:

```text
.My Favorites
.Farming Maps
.Tournament Pools
```

The period sorts those collections toward the top alphabetically.

> Rename personal collections inside osu!, not inside Collection Manager. Manually reordering inside Collection Manager may cause it to reorganize or renumber entries using its own scheme, which may not carry over cleanly to stable or lazer.

---

## Reporting issues

If a map is missing or wrong, please open a GitHub issue.

Helpful details:

* Pack name
* Missing or incorrect beatmap
* osu! beatmap link, if available
* Screenshot, if useful

Version names use this format:

```text
All_Medal_Beatmap_Packs_v1.0
All_Medal_Beatmap_Packs_v1.1
All_Medal_Beatmap_Packs_v1.2
```

Example changelog entry:

```text
v1.1
- Added [new pack name]
- Updated checklist
- Re-exported .osdb
```

---

## Project note

This project mainly exists so other medal hunters do not have to organize everything from scratch like I did, which took me about two days.

It should also make the whole process less annoying for players who want a clear route through the medal packs. Downloading packs, checking requirements, and keeping everything sorted in a large osu! library is not exactly smooth, especially if you already have your own collection order set up.

Native collection import/export in osu! would make this a lot easier one day. Until then, this should hopefully save people some time.

---

## License

This repository is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

See the root-level [`LICENSE`](LICENSE) file for the full license text.

You may copy, share, modify, mirror, and redistribute this collection metadata, provided attribution is given.

Suggested attribution:

```text
All Medal Beatmap Pack Collections by Noty8udod
osu! profile: https://osu.ppy.sh/users/15181421
Original repository: https://github.com/Noty8udod/osu-medal-pack-collections
```

> This license only applies to the files in this repository. It does not apply to osu!, beatmaps, beatmap assets, songs, backgrounds, or any third-party content.
