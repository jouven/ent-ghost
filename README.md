This "my" fork of ent-ghost (https://github.com/uakfdotb/ent-ghost/tree/luna). 

Original readme
---------------

It is licensed under the GNU GPL v3.

== INSTALLATION ==

1. Download the latest official GHost++ files at https://code.google.com/p/ghostplusplus/source/checkout.
2. Replace the ghost/ source directory in GHost++ with this (ent-ghost) repository.
3. Compile by running make from the command-line.
4. Copy the "ghost++" executable to the base of the GHost++ download
5. Follow the GHost++ installation instructions to configure in default.cfg and ghost.cfg.
6. Setup your database using the included install.sql from this repository (do not use GHost++ database schema files).
7. It is highly recommended to additionally setup a cron script based around the included cron_functions.php. This will ensure update of the bans and gametrack tables.
