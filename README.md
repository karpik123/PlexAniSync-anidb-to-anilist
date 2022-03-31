# PlexAniSync - anidb-to-anilist for x-jat anime titles

This is a list of my custom mappings for [PlexAniSync](https://github.com/RickDB/PlexAniSync). This list will be helpful for you if you meet all of the following criteria:
- your Plex is configured to use HAMA + ASS, where HAMA has `T-EM 'title'` set to AniDB
- your Plex has library language priority set as `x-jat, en`
- you use AniDB naming conventions for your folders

If you use PlexAniSync 1.3.17 or higher, you can use this list as remote custom mapping. Add below fragment to your custom_mappings.yaml:

```
remote-urls:
  - https://raw.githubusercontent.com/karpik123/PlexAniSync-anidb-to-anilist/main/anidb-to-anilist-x-jat.yaml
```

I'd gladly accept help for historical anime titles. I'll do my best to keep file up to date from Spring 2022 season onwards.

Below are some examples that my mappings fix.



### Boku No Hero Acadamia
| AniDB Name                   | Anilist Name            |
| ---------------------------- | ----------------------- |
| Boku no Hero Academia (2016) | Boku no Hero Academia   | 
| Boku no Hero Academia (2017) | Boku no Hero Academia 2 |
| Boku no Hero Academia (2018) | Boku no Hero Academia 3 |
| Boku no Hero Academia (2019) | Boku no Hero Academia 4 |
| Boku no Hero Academia (2021) | Boku no Hero Academia 5 |
| Boku no Hero Academia (2022) | Boku no Hero Academia 6 |

### Other assorted examples
| AniDB Name                            | Anilist Name                           |
| ------------------------------------- | -------------------------------------- |
| Sono Bisque Doll wa Koi o Suru        | Sono Bisque Doll wa Koi wo Suru        |
| SK8                                   | SK∞                                    |
| Kono Subarashii Sekai ni Shukufuku o! | Kono Subarashii Sekai ni Shukufuku wo! |
| Gekijouban Blood-C: The Last Dark     | BLOOD-C: The Last Dark                 |
| Fate/Zero (2012)                      | Fate/Zero 2nd Season                   |
| Gintama. (2018)                       | Gintama.                               |

### Misc

AniDB has "Gekijouban Kyoukai no Kanata: I'll Be Here", it contains both movies as two episodes.

Anilist has 2 separate entries Kyoukai no Kanata: "I'LL BE HERE - Mirai-hen" and "Kyoukai no Kanata: I'LL BE HERE - Kako-hen".

AniDB folder/naming convention will put both movies as one item, but my mapping file links episode 1 and 2 to individual Anilist ids.
