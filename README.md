# qbt-plugins

87 qBittorrent search plugins, each checked to load in qBittorrent 5.2 (Python 3.13).
Collected from the official repo and the community list:
https://github.com/qbittorrent/search-plugins/wiki/Unofficial-search-plugins

## Install

qBittorrent → Search tab → **Search plugins…** → **Install a new one** → **Local file**,
then select all `.py` files (Ctrl+A).

Or copy them straight in (Flatpak) and restart qBittorrent:

```sh
cp *.py ~/.var/app/org.qbittorrent.qBittorrent/data/qBittorrent/nova3/engines/
```

Some plugins are for private trackers and need your login in the file before they
return results. Each plugin belongs to its author; see the source column.

## Plugins

| File | Site | Source |
|---|---|---|
| `academictorrents.py` | AcademicTorrents | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/academictorrents.py |
| `acgrip.py` | acg.rip | https://raw.githubusercontent.com/nishizhen/qBit-search-plugins/main/acgrip.py |
| `ali213.py` | ali213 | https://raw.githubusercontent.com/hannsen/qbittorrent_search_plugins/master/ali213.py |
| `anidex.py` | AniDex | https://raw.githubusercontent.com/nindogo/qbtSearchScripts/master/anidex.py |
| `animetosho.py` | Anime Tosho | https://raw.githubusercontent.com/AlaaBrahim/qBitTorrent-animetosho-search-plugin/main/animetosho.py |
| `apachetorrent.py` | ApacheTorrent | https://gist.githubusercontent.com/bebetoh/3bb49cdf2b3718937b5446db1e4a4915/raw/1819e3ed75faa0da1571173a677081dc107054aa/apachetorrent.py |
| `audiobookbay.py` | AudioBook Bay (ABB) | https://raw.githubusercontent.com/nklido/qBittorrent_search_engines/master/engines/audiobookbay.py |
| `bakabt.py` | BakaBT | https://raw.githubusercontent.com/MadeOfMagicAndWires/qBit-plugins/master/engines/bakabt.py |
| `bitsearch.py` | Bit Search | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/bitsearch.py |
| `bt4gprx.py` | bt4gprx | https://raw.githubusercontent.com/TuckerWarlock/qbittorrent-search-plugins/main/bt4gprx.com/bt4gprx.py |
| `btdig.py` | btdig | https://raw.githubusercontent.com/galaris/BTDigg-qBittorrent-plugin/main/btdig.py |
| `c411.py` | C411 | https://raw.githubusercontent.com/OptimusKoala/qbittorrent-c411-plugin/refs/heads/main/c411.py |
| `calidadtorrent.py` | CalidadTorrent | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/calidadtorrent.py |
| `cloudtorrents.py` | CloudTorrents | https://raw.githubusercontent.com/elazar/qbittorrent-search-plugins/refs/heads/add-cloudtorrents-plugin/nova3/engines/cloudtorrents.py |
| `danishbytes.py` | DanishBytes | https://raw.githubusercontent.com/444995/qbit-search-plugins/main/engines/danishbytes.py |
| `darklibria.py` | dark-libria | https://raw.githubusercontent.com/bugsbringer/qbit-plugins/master/darklibria.py |
| `divxtotal.py` | DivxTotal | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/divxtotal.py |
| `dmhy.py` | dmhy | https://raw.githubusercontent.com/diazchika/dmhy/main/dmhy.py |
| `dodi_repacks.py` | DODI Repacks | https://raw.githubusercontent.com/Bioux1/qbtSearchPlugins/main/dodi_repacks.py |
| `dontorrent.py` | DonTorrent | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/dontorrent.py |
| `elitetorrent.py` | Elitetorrent | https://raw.githubusercontent.com/iordic/qbittorrent-search-plugins/master/engines/elitetorrent.py |
| `esmeraldatorrent.py` | EsmeraldaTorrent | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/esmeraldatorrent.py |
| `eztv.py` | EZTV | https://raw.githubusercontent.com/qbittorrent/search-plugins/master/nova3/engines/eztv.py |
| `eztvx.py` | EZTVX | https://raw.githubusercontent.com/DrPurp/eztvx-qbittorrent-plugin/main/eztvx.py |
| `filelist.py` | FileList | https://raw.githubusercontent.com/RaresPNet/filelist_search_plugin/main/filelist.py |
| `fitgirl_repacks.py` | FitGirl Repacks | https://raw.githubusercontent.com/afalvarezsite/qbtFitGirl-search/main/fitgirl_repacks.py |
| `gazellegames.py` | gazellegames | https://raw.githubusercontent.com/Ooggle/qbittorrent-search-plugins/master/engines/gazellegames.py |
| `glotorrents.py` | GloTorrents | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/glotorrents.py |
| `goggames.py` | GOG-Games | https://raw.githubusercontent.com/tolotp/qbittorrent-search-plugins-de-busqueda/refs/heads/main/Plugins/goggames.py |
| `iptorrents.py` | IPTorrents | https://raw.githubusercontent.com/txtsd/qB-IPT/master/iptorrents.py |
| `kickasstorrents.py` | Kickasstorrents | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/kickasstorrents.py |
| `kinozal.py` | Kinozal | https://raw.githubusercontent.com/imDMG/qBt_SE/master/engines/kinozal.py |
| `latteam.py` | Lat-Team | https://raw.githubusercontent.com/tolotp/qbittorrent-search-plugins-de-busqueda/refs/heads/main/Plugins/latteam.py |
| `limetorrents.py` | LimeTorrents | https://raw.githubusercontent.com/qbittorrent/search-plugins/master/nova3/engines/limetorrents.py |
| `linuxtracker.py` | Linux Tracker | https://raw.githubusercontent.com/MadeOfMagicAndWires/qBit-plugins/6074a7cccb90dfd5c81b7eaddd3138adec7f3377/engines/linuxtracker.py |
| `lostfilm.py` | LostFilm | https://raw.githubusercontent.com/bugsbringer/qbit-plugins/master/lostfilm.py |
| `magnetdl.py` | MagnetDL | https://raw.githubusercontent.com/nindogo/qbtSearchScripts/master/magnetdl.py |
| `mejortorrent.py` | MejorTorrent | https://raw.githubusercontent.com/iordic/qbittorrent-search-plugins/master/engines/mejortorrent.py |
| `mikanani.py` | mikanani | https://raw.githubusercontent.com/Cc050511/qBit-search-plugins/main/mikanani.py |
| `milkie.py` | Milkie | https://raw.githubusercontent.com/tolotp/qbittorrent-search-plugins-de-busqueda/refs/heads/main/Plugins/milkie.py |
| `mypornclub.py` | MyPorn Club | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/mypornclub.py |
| `naranjatorrent.py` | NaranjaTorrent | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/naranjatorrent.py |
| `ncore.py` | nCore | https://raw.githubusercontent.com/darktohka/qbittorrent-plugins/master/ncore.py |
| `nekobt.py` | NekoBT | https://raw.githubusercontent.com/tolotp/qbittorrent-search-plugins-de-busqueda/refs/heads/main/Plugins/nekobt.py |
| `nyaapantsu.py` | Nyaa.pantsu | https://raw.githubusercontent.com/MadeOfMagicAndWires/qBit-plugins/refs/heads/main/engines/nyaapantsu.py |
| `nyaasi.py` | Nyaa.si | https://raw.githubusercontent.com/MadeOfMagicAndWires/qBit-plugins/master/engines/nyaasi.py |
| `onlinefix.py` | Online-Fix | https://raw.githubusercontent.com/caiocinel/onlinefix-qbittorrent-plugin/main/onlinefix.py |
| `pediatorrent.py` | PediaTorrent | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/pediatorrent.py |
| `piratebay.py` | The Pirate Bay | https://raw.githubusercontent.com/qbittorrent/search-plugins/master/nova3/engines/piratebay.py |
| `pirateiro.py` | Pirateiro | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/pirateiro.py |
| `prowlarr.py` | Prowlarr | https://raw.githubusercontent.com/MANCrimSon/prowlarr-qbittorrent-plugin/main/prowlarr.py |
| `redacted_ch.py` | redacted.ch | https://raw.githubusercontent.com/evyd13/search-plugins/master/nova3/engines/redacted_ch.py |
| `redetorrent.py` | RedeTorrent | https://gist.githubusercontent.com/bebetoh/b5e1f4731462de9b837f5026617b1d4a/raw/e71d0020078d56d3f7e9a903ca7b4d44774e10f7/redetorrent.py |
| `rockbox.py` | RockBox | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/rockbox.py |
| `rutor.py` | Rutor | https://raw.githubusercontent.com/imDMG/qBt_SE/master/engines/rutor.py |
| `rutracker.py` | Rutracker | https://raw.githubusercontent.com/imDMG/qBt_SE/master/engines/rutracker.py |
| `sktorrent.py` | SkTorrent | https://raw.githubusercontent.com/Ashalda/sktorrent-qbt/refs/heads/main/sktorrent.py |
| `smallgames.py` | small-games.info | https://raw.githubusercontent.com/hannsen/qbittorrent_search_plugins/master/smallgames.py |
| `snowfl.py` | Snowfl | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/snowfl.py |
| `solidtorrents.py` | Solid Torrents | https://raw.githubusercontent.com/qbittorrent/search-plugins/master/nova3/engines/solidtorrents.py |
| `speedapp.py` | SpeedAppIO | https://raw.githubusercontent.com/miIiano/SpeedApp.io-qBittorent-search-plugin/main/speedapp.py |
| `subsplease.py` | SubsPlease | https://raw.githubusercontent.com/kli885/qBittorent-SubsPlease-Search-Plugin/main/subsplease.py |
| `sukebeisi.py` | Sukebei (Nyaa) | https://github.com/vt-idiot/qBit-SukebeiNyaa-plugin/raw/master/engines/sukebeisi.py |
| `tapochek.py` | Tapochek | https://raw.githubusercontent.com/MjKey/qBT-SE/refs/heads/master/enigines/tapochek.py |
| `thepiratebay.py` | The Pirate Bay | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/thepiratebay.py |
| `therarbg.py` | The RarBg | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/therarbg.py |
| `toloka_to.py` | toloka_to | https://raw.githubusercontent.com/playday3008/qBittorrent-plugins/refs/heads/main/plugins/search/toloka_to.py |
| `tomadivx.py` | TomaDivx | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/tomadivx.py |
| `torlock.py` | TorLock | https://raw.githubusercontent.com/qbittorrent/search-plugins/master/nova3/engines/torlock.py |
| `torrentclaw.py` | TorrentClaw | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/torrentclaw.py |
| `torrentdownload.py` | TorrentDownload | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/torrentdownload.py |
| `torrentdownloads.py` | Torrent Downloads | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/torrentdownloads.py |
| `torrentgalaxy.py` | TorrentGalaxy | https://raw.githubusercontent.com/nindogo/qbtSearchScripts/master/torrentgalaxy.py |
| `torrentleech.py` | TorrentLeech | https://raw.githubusercontent.com/444995/qbit-search-plugins/main/engines/torrentleech.py |
| `torrentscsv.py` | torrents-csv | https://raw.githubusercontent.com/qbittorrent/search-plugins/master/nova3/engines/torrentscsv.py |
| `tr4ker.py` | TR4KER | https://raw.githubusercontent.com/Apologieze/qbittorrent-tr4ket-plugin/refs/heads/main/tr4ker.py |
| `traht.py` | Traht | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/traht.py |
| `tsukihime.py` | Tsukihime  | https://raw.githubusercontent.com/dominc8/qbittorrent-tsukihime-search-plugin/refs/heads/master/tsukihime.py |
| `unionfansub.py` | Union Fansub | https://gitlab.com/CrimsonKoba/qb-search-plugin/-/raw/master/unionfansub.py |
| `xxxclubto.py` | XXXClub | https://raw.githubusercontent.com/BurningMop/qBittorrent-Search-Plugins/refs/heads/main/xxxclubto.py |
| `yggapi.py` | YggAPI | https://raw.githubusercontent.com/Laiteux/YggAPI-qBittorrent-Search-Plugin/main/yggapi.py |
| `yggtorrent.py` | YGG Torrent | https://raw.githubusercontent.com/CravateRouge/qBittorrentSearchPlugins/master/yggtorrent.py |
| `yggtracker.py` | YGGtracker | https://raw.githubusercontent.com/YGGverse/qbittorrent-yggtracker-search-plugin/main/yggtracker.py |
| `yourbittorrent.py` | YourBittorrent | https://raw.githubusercontent.com/LightDestory/qBittorrent-Search-Plugins/master/src/engines/yourbittorrent.py |
| `yts.py` | YTS | https://codeberg.org/lazulyra/qbit-plugins/raw/branch/main/yts/yts.py |
| `zamundarip.py` | Zamunda.RIP | https://raw.githubusercontent.com/codeobfuscation/qBittorrent-ZamundaRIP-plugin/main/zamundarip.py |
| `zooqle.py` | Zooqle | https://raw.githubusercontent.com/444995/qbit-search-plugins/main/engines/zooqle.py |
