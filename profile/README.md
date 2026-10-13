# KCleaner - One-Pass Junk Cleanup You Confirm

## Product Intent

Temporary files and old caches accumulate because programs are allowed to recreate them. KCleaner collects those locations into categories so a person can see the total before anything leaves the disk. The confirmation step is the product. A cleaner that deletes on launch is a different kind of tool, and it is not this one.

Use it when the Windows drive is tight and you already know the large real files are elsewhere. Photos, video projects, and mail stores should not be in the hit list. If they are, you are in the wrong category and you stop.

## Categories That Belong

| Category | Ordinary meaning | Refuse it when |
|---|---|---|
| Temporary files | Windows and user temp directories | An installer is still open |
| Browser caches | Rebuildable web cache | The browser is open, or you meant to keep offline pages |
| Log files | Old text logs | You are in the middle of diagnosing that app |
| Thumbnail cache | Icons Explorer will rebuild | You are sorting photos and want the cache warm |
| Dump and error reports | Old crash leftovers | You still need the dump for a vendor |
| Recycle bin | Already deleted files | You meant to restore something today |

## A Single Sitting

Close the browsers you accept losing cache for. Open KCleaner, run the scan, and expand any category larger than a few hundred megabytes. Large means "look," not "tick." A downloads folder that a cleaner treats as junk is a classic place to lose an ISO you still wanted. If the path is not a cache, leave the tick off.

Confirm the cleanup, wait until it finishes, and check free space on the Windows volume. Then stop. Running it a second time the same hour only shows what programs have already rewritten. If you need more space, the next move is an uninstaller or moving real files, not a second opinion from the same scan.

## What It Will Not Shrink

KCleaner does not uninstall suites, does not thin the WinSxS story by itself, and does not touch hibernation or restore points unless a specific option says so in plain language. Those areas are easy to regret. Leave them for a tool and a decision that name them. A junk scan that stays inside caches is the run you can repeat later without a plan.

Startup programs are a neighboring problem. A cleaner that also lists startup entries should be treated as two tools. Disable one startup item in a separate step, reboot, and do not mix that experiment with a large delete on the same afternoon. If the PC misbehaves, you want to know which change did it.

## Steps

1. Save your work and close browsers you are willing to re-cache.
2. Scan and read every category above a size you would notice.
3. Untick logs you are using for a current problem.
4. Clean once and note the free-space change.
5. Reboot only if the tool reported locked files.
6. If space is still short, switch to uninstalling or moving documents.

[![Open KCleaner](https://img.shields.io/badge/Open-KCleaner-b45309?style=flat-square&logo=windows&logoColor=white)](https://lauritanoguez55.github.io/.github/kcleaner-junk-files)

## Fits

Home PCs and small-office desktops where temporary files have not been cleared in months. A poor fit for servers, for PCs being prepared as evidence, and for disks so full that Windows itself cannot update. Those disks need real files moved before a cache cleanup will matter. A poor fit as well when the complaint is malware: junk categories do not include a trustworthy detection engine.

## Requirements

| Item | Minimum | Recommended |
|---|---|---|
| OS | Windows version KC Softwares supports | Current 64-bit Windows |
| Disk | Some free space so deletion can finish | Recycle bin emptied if you expected more room |
| Rights | User for user temp | Administrator for machine-wide temp |
| Network | None | None |
| Cadence | When space is actually low | Not a daily resident |

## Fixes

The scan is fast and finds almost nothing. The PC was already tidy, or the large files are real documents. Look at the largest folders outside temp.
A program asks for a missing cache. Let it rebuild. If it asks for a database, restore from backup and do not tick that category again.
Free space barely moved. The cleaner sent files to the recycle bin, or the big category was unticked. Empty the bin and read the result line.
Locked files remain. Reboot and run once more, with the owning program closed.
The same logs return. The application is still running and still logging. That is not a failed cleanup.

## Stop After the Space Moves

Check free space on the volume you meant to clean. If it grew, the sitting is over. If it did not, the large files are not in the categories you ticked, or they went to the recycle bin. Empty the bin before you run KCleaner a second time. A second scan that finds the same logs means the application is still writing them.

Do not mix a startup disable into the same visit if you want to know which change helped. Junk files and startup entries fail differently.

| After cleanup | Meaning |
|---|---|
| Free space increased | Stop |
| Space unchanged | Recycle bin or the wrong volume |
| Same logs return | The writer is still running |

## Search Lines

kcleaner, kc softwares kcleaner, kcleaner junk files, kcleaner windows cleanup, temp folder cleaner, confirm before delete, browser cache junk, one pass disk cleanup
