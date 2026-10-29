# modded-nanogpt before five big jumps

Snapshots of https://github.com/KellerJordan/modded-nanogpt (Track 1), each taken just before one of
the speedrun's large jumps, without the records/ run logs. It is the subject of the Kupanga project
nanogpt-speedrun-jumps: each experiment implements one jump in its folder.

| Folder | Upstream commit | The record just after it |
|---|---|---|
| pre-40/ | ebf2dfc | #40 |
| pre-53/ | 4d6fe16 | #53 |
| pre-62/ | 9c11d65 | #62 |
| pre-82/ | 356eaa2 | #82 |
| pre-83/ | b19c4d8 | #83 |

Each folder runs on its own: cd pre-NN && torchrun --standalone --nproc_per_node=8 train_gpt.py
