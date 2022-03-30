# PlexAniSync-anidb-to-anilist

This is a list of my custom mappings for [PlexAniSync](https://github.com/RickDB/PlexAniSync). This list will be helpful for you if you meet all of the following criteria:
- your Plex is configured to use HAMA + ASS
- your Plex has language priority set as `x-jat, en`
- you use AniDB naming conventions for your folders

Those mappings will not be useful if you use TVDB naming or folder structure, as none of the mappings contain Season 2.

If you use PlexAniSync 1.3.17 or higher, you can use this list as remote custom mapping. Add below fragment to your custom_mappings.yaml:

```
remote-urls:
  - https://raw.githubusercontent.com/karpik123/PlexAniSync-anidb-to-anilist/main/anidb-to-anilist.yaml
```

I'd gladly accept help for historical anime titles. I'll do my best to keep file up to date from Sprint 2022 season onwards.

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
NFSW/+18 warning - I don't have SFW example, so this one will have to do for now.

[Saezuru Tori wa Habatakanai](https://anidb.net/anime/14889) on AniDB is one entry with 2 episodes, one for each movie. Anilist has both movies listed separately. Since this mapping set assumes you'll be using AniDB structure, episode 1 from Saezuru Tori wa Habatakanai is mapped to [Saezuru Tori wa Habatakanai: The clouds gather](https://anilist.co/anime/109171/Saezuru-Tori-wa-Habatakanai-The-clouds-gather/), episode 2 is mapped to [Saezuru Tori wa Habatakanai: The storm breaks](https://anilist.co/anime/115566/Saezuru-Tori-wa-Habatakanai-The-storm-breaks/).
