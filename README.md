

```markdown
# JL Logger — Source Code Archival README

This repository preserves the source code for JL Logger (JL), a Java-based amateur radio contest logging program created by Michael K. Loukides (W1JQ) in the early 2000s. This archive exists for historical and educational reference only.

## About JL

JL is a cross-platform contest logger written entirely in Java. The last known version, 1.06, ran on Windows, Linux, Solaris, and macOS (with manual serial setup). It produced Cabrillo logs, supported CW and voice keying, and provided rig control for Icom radios.

## Supported Contests (Historical)

JL supported many major contests, including:

- ARRL DX, ARRL Sweepstakes, ARRL VHF
- CQ WW DX, CQ WPX, CQ 160m
- NAQP, NA Sprint
- California, Texas, Indiana QSO Parties
- Worked All Europe, Worked All Germany
- IOTA, SAC, LZ-DX, Russian DX, JIDX, Oceania, All Asia

## Features

- Cross-platform Java Swing interface
- CW and voice keyers
- Icom CAT rig control
- Modular contest framework
- Cabrillo log output
- Sample logs included in original distribution

**Not included by design:**

- Partial calls
- DX cluster integration

## Source Code Layout

All source code is located under:

```
com/loukides/jl
```

The archive contains only the original source, not compiled binaries or the JL JAR distribution.

## Getting Started (Historical)

1. Install Java JDK/JRE 1.4+.
2. For rig control or CW keying, install the Java Communications API or RXTX (platform dependent).
3. Build using Ant if desired.
4. Refer to `docs/HOWTO.txt` if present.

## Archival Notice

> “JL Logger source code © 2003 Michael K. Loukides (W1JQ). Reproduced solely for archival and historical study. Only the unmodified source code is included; the compiled JAR is not distributed. All rights remain with the author.”

## Project Status

This is an archival repository only. There is no active development. Users are welcome to study, fork, or modernize the code.
```



