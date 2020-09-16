# HCU400-Memory-Game-Data
Raw data from memory experiments using HCU400 from Amazon Turk

please see [The Intrinsic Memorability of Everyday Sounds](https://www.aes.org/e-lib/browse.cfm?elib=20434)
for details; if you use this data in research please cite:

Ramsay, David, Ishwarya Ananthabhotla, and Joseph Paradiso. "The Intrinsic Memorability of Everyday Sounds." Audio Engineering Society Conference: 2019 AES International Conference on Immersive and Interactive Audio. Audio Engineering Society, 2019.

Please see the included python notebook for loading data and a rough
introduction.  Included are survey results and raw memory game data, as well as
processed memorability scores based on each sound.  In general, the memory task
includes dozens of sounds which we refer to as 'target'-- the sounds under test
that are separated by 60 sounds each (denoted 't' frequently) and 'vigilance'--
the sounds that are spaced 2-3 apart to make sure the person is paying
attention and engaged throughout the memory task.

Our study was conducted off of Turk, and thus we tracked people with
tokens/user ids ourselves, and then cross-referenced those with their Amazon
assigned IDs.  Some people have multiple amazon turk accounts, and some close
their browser in between sessions, so sync between these two IDs is highly
variable.  We attempted to best identify/match people with a cannonical
'USER_ID', which runs throughout this data.

We are happy for others to use/play with it, please cite us and/or contact us
if you have any questions or would like access to some of our scripts; we're
happy to collaborate!
