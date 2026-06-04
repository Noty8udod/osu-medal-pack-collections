# All Medal Beatmap Pack Collections v1.0

A complete collection metadata set for every osu! beatmap pack that can grant medals, covering **Video Game Vol.1** through **Project Loved: Best of 2024**.
> ✅ Verified as of **June 3, 2026**  
> 📦 This is **not** a beatmap mirror and does **not** include `.osz` beatmap files.

<table>
<tr>
<td><img src="https://github.com/Noty8udod/osu-medal-pack-collections/blob/main/screenshots/showcase.png?raw=true" width="500" alt="Collection list overview"></td>
<td><img src="https://github.com/Noty8udod/osu-medal-pack-collections/blob/main/screenshots/showcase2.png?raw=true"></td>
</tr>
</table>

## Table of Contents

- [What this is](#what-this-is)
- [Quick start](#quick-start)
- [Download missing maps](#download-missing-maps)
- [Lazer import](#lazer-import)
- [Collection ordering](#collection-ordering)
- [Reporting issues and updates](#reporting-issues-and-updates)
- [License](#license)

---

## What this is

This resource is for medal hunters who want clean, organized collections for every medal-giving beatmap pack without manually building each one from scratch.

**Included files:**

| File | Purpose |
|---|---|
| `All_Medal_Beatmap_Packs_v1.0.osdb` | Recommended import file for Collection Manager |
| `All_Medal_Beatmap_Packs_v1.0_collections.db` | Backup collection database |
| `CHANGELOG.txt` | Version history |
| `screenshots/` | Preview images of the collection list |

**Includes:**

- One all-in-one collection covering every medal-giving beatmap pack
- Individual collections sorted by pack and category
- Featured Artist, Mappers' Guild, and Project Loved medal packs

> ⚠️ **This repository only contains collection metadata.** It does not redistribute `.osz` beatmap files, songs, backgrounds, beatmap assets, or any other copyrighted content.

---

## Quick start

Use the `.osdb` file with **[Collection Manager](https://github.com/Piotrekol/CollectionManager/releases)**.

The `.osdb` format is recommended because it handles missing maps better and is easier to share than a raw `.db` file. The `.db` backup is mainly for users who already have all required maps downloaded and only need the collection organization.

**Before importing anything, back up your current `collections.db`.**

1. Close osu!.
2. Back up your current `collections.db`.
3. Download `All_Medal_Beatmap_Packs_v1.0.osdb`.
4. Open **Collection Manager**.
5. Drop the `.osdb` file into Collection Manager.
6. Import and save the collections.
7. Open osu! (stable) and confirm the collections appear correctly.
8. *(osu!lazer users)* Run the setup wizard in lazer's settings and import your collections from stable.

> Only use `All_Medal_Beatmap_Packs_v1.0_collections.db` if you know what you are doing. Directly replacing `collections.db` can overwrite your existing personal collections if you did not back them up first.

---

## Download missing maps

These sources are listed in recommended order.

**1. [Collection Manager](https://github.com/Piotrekol/CollectionManager/releases)** *(recommended)*

1. Open **Collection Manager**.
2. Drop `All_Medal_Beatmap_Packs_v1.0.osdb` into Collection Manager.
3. Click **Online**.
4. Select **Download All Missing Maps**.
5. Save and import the collections.
6. Open osu! (stable) and confirm the collections appear correctly.
7. If using lazer, run the setup wizard and import the collections from stable.

> Collection Manager requires osu! cookies for online lookup and download features.

**2. [osekai](https://inex.osekai.net/medals/)**

osekai indexes medals and their unlock requirements. Clicking a medal that requires a beatmap pack may show a download button or redirect to the official page.

**3. osu!Collector**

```
<osu!Collector link — to be added>
```

Use this if you have an osu!Collector subscription ($1.99/month) and want a fast way to add the collection and download missing maps.

**4. [Official beatmap packs](https://osu.ppy.sh/beatmaps/packs)**

Download packs directly from osu!. This may require manually locating each pack.

---

## Lazer import

There is currently no direct `.osdb` or `collections.db` import flow inside osu!lazer. The cleanest approach is to import into osu! (stable) first, then import your stable data into lazer.

**Steps:**

1. Install osu! (stable) if you do not already have it.
2. Launch osu! (stable) once, you do not need to sign in.
3. Create at least one test collection in stable so the collection database exists.
4. Close stable.
5. Import these collections into stable using one of the following:
   - **Recommended:** Import the `.osdb` through Collection Manager.
   - **Backup/advanced:** Use the provided `collections.db` only after backing up your current one.
6. Launch stable and confirm the collections appear correctly.
   > Note: Empty spacer collections may not appear because they contain zero maps (although the spacers will appear on lazer's dropdown)
7. Open osu!lazer.
8. Go to **Settings → Run setup wizard**.
9. Skip to the import section.
10. Import your beatmaps and collections from osu! (stable).
11. After the import finishes, the collections will be available in lazer.

---

## Collection ordering

osu! and osu!lazer sort collections alphabetically with no manual ordering override. This collection set uses a numbering prefix so packs stay in a predictable order:

```
0001 Video Game Vol.1
...
0115 Project Loved: Best of 2024
```

**To keep your personal collections above these, prefix them with a period:**

```
.My Favorites
.Farming Maps
.Tournament Pools
```

The period sorts those collections toward the top alphabetically.

> Rename personal collections **inside osu!**, not inside Collection Manager. Manually reordering within Collection Manager may cause it to reorganize or renumber entries using its own scheme, which may not carry over cleanly to stable or lazer.

---

## Reporting issues and updates

Report missing or incorrect maps via GitHub issues.

**Helpful issue details:**

- Pack name
- Missing or incorrect beatmap
- osu! beatmap link, if available
- Screenshot, if helpful

**Version naming format:**

```
All_Medal_Beatmap_Packs_v1.0
All_Medal_Beatmap_Packs_v1.1
All_Medal_Beatmap_Packs_v1.2
```

**Example changelog entry:**

```
v1.1
- Added [new pack name]
- Updated checklist
- Re-exported .osdb
```

---

## Final note

This project mainly exists so other medal hunters don't have to organize everything from scratch like I did (which took me two days). It should also help newer players get up and running faster downloading packs and keeping track of them in a big library isn't the most straightforward thing, especially if you have a preferred sort order set up. By importing the collection metadata into osu! using a tool like collection manager, newer players get a progression path that isn't just climbing the leaderboard or farming pp.

Native collection import/export in osu! would make all of this way smoother one day, but hopefully this does the job in the meantime.

---

## License

This repository is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

See the root-level [`LICENSE`](LICENSE) file for the full license text.

You may copy, share, modify, mirror, and redistribute this collection metadata, provided attribution is given.

**Suggested attribution:**

```text
All Medal Beatmap Pack Collections by [Noty8udod](https://osu.ppy.sh/users/15181421)
Original repository: [osu-medal-pack-collections](https://github.com/Noty8udod/osu-medal-pack-collections)
```
>This license applies only to the files in this repository. It does not apply to osu!, beatmaps, beatmap assets, songs, backgrounds, or any third-party content.
