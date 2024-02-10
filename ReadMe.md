Game Boy and Game Boy Color for MEGA65
======================================

This is a Git submodule of the Game Boy and Game Boy Color core for MEGA65. It is a fork of the MiSTer Game Boy core, which is itself based on MiST's Game Boy core.

**Go to https://github.com/sy2002/gbc4mega65/ to learn more.**


The MEGA65 port is based on the [MiSTer2MEGA65 framework](https://github.com/sy2002/MiSTer2MEGA65). We forked the [MiSTer core](https://github.com/MiSTer-devel/Gameboy_MiSTer), so that we can easily track upstream changes and merge them into our MEGA65 port as needed. The following structure is being used:

* [master](https://github.com/sy2002/Gameboy_MiSTer/tree/master) branch: Original MiSTer fork with the only exception that we changed this README.md
* [C64MEGA65](https://github.com/sy2002/Gameboy_MiSTer/tree/C64MEGA65) branch: Contains our stable modifications of the upstream MiSTer core
* [develop](https://github.com/sy2002/Gameboy_MiSTer/tree/develop) branch: Is our kind-of stable work-in-progress (WIP) development branch

On modifications:

* Our strategy is to reduce the modifications to the upstream core to the bare minimum.
* We made sure that the code is actually synthesizing using Vivado (used for the MEGA65), which is stricter and more unforgiving than Quartus (used for the MiSTer).
