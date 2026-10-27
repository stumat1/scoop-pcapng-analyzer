# PCAPNG Analyzer for Scoop

A [Scoop](https://scoop.sh) bucket for
[PCAPNG Analyzer](https://pcapnganalyzer.com): drop in a pcap or pcapng
capture and get a plain-English diagnosis, with the evidence. It runs on
your own computer and opens in your browser. Your captures stay on your
machine.

```powershell
scoop bucket add pcapng-analyzer https://github.com/stumat1/scoop-pcapng-analyzer
scoop install pcapng-analyzer/pcapng-analyzer
```

Start it from the Start menu (**PCAPNG Analyzer**) or by running
`pcapng-analyzer`. A console window shows where it's running, and your
browser opens on it, signed in. Close the window to stop it.

Installed this way, Windows doesn't show the SmartScreen prompt that the
direct download gets.

| | |
|---|---|
| Update | Stop the app, then `scoop update pcapng-analyzer` |
| Remove | `scoop uninstall pcapng-analyzer` |
| Your data | `%LOCALAPPDATA%\PCAPNG Analyzer`, kept when you update or remove the app |

Free to use; a [Pro license](https://pcapnganalyzer.com/pricing.html)
unlocks the rest. The manifest is updated automatically for each release
of [pcapng-analyzer-desktop](https://github.com/stumat1/pcapng-analyzer-desktop).
PCAPNG Analyzer is commercial, source-available software: see the
[license agreement](https://pcapnganalyzer.com/license.html).

Support: support@stumatapps.com
