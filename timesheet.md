# Timesheet nrdsp

## week of 2022/07/18

hours: 32,47

contributions:

- Worked on the website for SoN2022 with Simon Bruder, co-authoring commit [#19](https://github.com/NixOS/nixos-summer/pull/28/commits/1e23a55e06eeb9973e0760cd9c58d3865c51cb37) on the zola branch.
- Added a [comment](https://github.com/ngi-nix/ngi/issues/185#issuecomment-1193195414) on the [Wireguard Upscale](https://github.com/ngi-nix/ngi/issues/185#) NGI package, as a result of which issue was closed.
- Worked on a template and guidelines for deployment stories, [commited](https://github.com/ngi-nix/deployment-stories/tree/template) to branch template on ngi-nix's repository for [deployment stories](https://github.com/ngi-nix/deployment-stories).

activities:

- Participated in the first team meeting on July 19th.
- Attended public lecture by Eelco Dolstra on July 19th.
- Researched [NLNET](https://nlnet.nl/project/current.html) and [Github issues assigned to my team](https://github.com/ngi-nix/ngi/labels/SoN%20-%20Team%20EU1) for possible projects to work on.
- Attended Jitsi project meeting on July 21th.
- Participated in mob programming sessions as an observer on July 20th and 22th.
- Attempted contacting [MNT Reform](https://nlnet.nl/project/MNT-Reform/) by sending emails to sosat@mntre.com and support@mntre.com on July 21st and 23rd.
- Attempted contacting [RISCV-Phone](https://nlnet.nl/project/RISC-V-Phone/)'s author by sending an email to majstor@majstor.org on July 23rd.


## week of 2022/07/25

hours: 31,98

contributions:

- Added a [comment](https://github.com/ngi-nix/ngi/issues/178#issuecomment-1193198395) on [Nym Credentials](https://github.com/ngi-nix/ngi/issues/178) NGI package, as a result of which the issue was closed. 
- Found an already existing [PR](https://github.com/ngi-nix/namecoin-core/pull/1) for [Namecoin-Core](https://www.ngi.eu/funded_solution/namecoincore/) awaiting a review.
- [Commited](https://github.com/ngi-nix/namecoin-core/pull/1/commits/dfa1676ab3531b34667fc51540338cf538be0ea5), which fixes deprecation warning.
- Managed to build namecoin-core after syncing my local copy of [jurraca's fork](https://github.com/jurraca/namecoin-core/tree/flake), which is at the origin of the [PR](https://github.com/ngi-nix/namecoin-core/pull/1), with [upstream](https://github.com/ngi-nix/namecoin-core), leaving a [message](https://github.com/ngi-nix/namecoin-core/pull/1#issuecomment-1199600669) to that effect.
- [Asked question on Discourse](https://discourse.nixos.org/t/building-risc-v-phones-firmware-where-is-riscv64-unknown-elf-gcc/20578) on the 26th related to the RISCV-Phone.

activities:

- Participated in a team meeting on July 25th.
- Attended public lecture by Armijn Hemel on July 26th.
- Worked on the RISCV-Phone, focusing on the toolchain needed to compile the firmware, first attempts at writing both a flake and a shell expression.
- On July 28th, had an exchange with Matthew Croughan on Matrix, we worked through the [fw/esp32](http://majstor.org/gitweb/?p=rvPhone.git;a=tree;f=fw/esp32;h=76b1e3e149e635bb8b470521da6d386c675d7508;hb=HEAD) firmware compilation and discussed the difficulties posed by the [yocto layer](http://majstor.org/gitweb/?p=rvPhone.git;a=tree;f=yocto;h=f53b8304d0f27a2b365eaa9a46e41bd98e8e2be0;hb=HEAD), after which he left this [message](https://github.com/ngi-nix/ngi/issues/188#issuecomment-1198547178).
- Researched [NLNET](https://nlnet.nl/project/current.html) and [Github issues assign to my team](https://github.com/ngi-nix/ngi/labels/SoN%20-%20Team%20EU1) for possible low-hanging fruits.
- Met with Jon Ringer on July 28th to discuss the PR for Namecoin-Core and a [roadmap](https://github.com/ngi-nix/namecoin-core/pull/1#issuecomment-1198439546) for the review.


## week of 2022/08/01

hours: 40,08

contributions:

- Had a go with the built-in integration tests for the Namecoin-Core Package, unsure if I should keep going left message [here](https://github.com/ngi-nix/namecoin-core/pull/1#issuecomment-1201809678).
- Created the [RISCV-Phone repository](https://github.com/ngi-nix/riscv-phone/) in the NGI-NIX project repository, moving all work there, also creating two branches for each separate firmware.
- Opened issues [#1](https://github.com/ngi-nix/riscv-phone/issues/1), [#2](https://github.com/ngi-nix/riscv-phone/issues/2), [#3](https://github.com/ngi-nix/riscv-phone/issues/3) and [#4](https://github.com/ngi-nix/riscv-phone/issues/4) on the RISCV-Phone repository, working through all of them and eventually closing the first three. 

activities:

- Participated in a team meeting on August 1st.
- Attended public lecture by Jon Ringer on the 2nd of August.
- Engaged in a pairing session with Bill Wanick on August 3rd.
- Continued reviewing the Namecoin-Core [PR](https://github.com/ngi-nix/namecoin-core/pull/1).
- Continued working on the RISCV-Phone, focusing mostly on the fe310 firmware.
- Engaged in a couple of pairing sessions with Justin Restivo, working together with him over the RISCV-Phone project. 
- Got first reply from Uros Majstorovix, author of the RISCV-Phone, exchanging emails with him since.


## week of 2022/08/08

hours: 35,7

contributions:

- Opened issues [#5](https://github.com/ngi-nix/riscv-phone/issues/5), [#6](https://github.com/ngi-nix/riscv-phone/issues/6), and [#7](https://github.com/ngi-nix/riscv-phone/issues/7) on the RISCV-Phone repository, working through all of them and eventually closing all remaining issues. 
- Opened a [PR](https://github.com/ngi-nix/riscv-phone/pull/8) on August 13th reflecting work done during the previous weeks on the RISCV-Phone's fe310 firmware, awaiting review by Justin Restivo before merging with master branch.
- Added [commit](https://github.com/p2pcollab/bloomf/commit/6e1161a741de5347d3bbd9365ffb51fd0de4e75d) and opened a [PR](https://github.com/p2pcollab/bloomf/pull/2) to address Hydra's [evaluation error #432](https://hydra.ngi0.nixos.org/eval/432#tabs-errors) of jobset `bloomf:nix-flakes` related to NGI package [Bloomf](https://github.com/ngi-nix/bloomf/tree/hydra).

activities:

- Participated in a team meeting on August 8th.
- Attended public lecture by Valentin Gagarin on August 9th.
- Kept working on the RISCV-Phone project, wrapping-up both the devShell and the derivation for the fe310 firmware.
- Exchanged views with Collin Arnett on August 10th on the subject of NixOS-mobile, Calamares and the best way to set up a virtual machine.
- Engaged in a pair session on August 10th with Justin Restivo, working with him on the RISCV-Phone project.


## week of 2022/08/15

hours: 42,51

contributions:

- Addressed [PR](https://github.com/ngi-nix/riscv-phone/pull/8) for the RISCV-Phone's fe310 firmware, specifically [replacing $out with /nanolibs](https://github.com/ngi-nix/riscv-phone/pull/8#discussion_r946726615), [moving bash script into its own file](https://github.com/ngi-nix/riscv-phone/pull/8#discussion_r950674245), and [wrapping the script and making it executable](https://github.com/ngi-nix/riscv-phone/pull/8#discussion_r950675137).
- Added [commit](https://github.com/ngi-nix/opaque-sphinx/commit/9f73e9c953f8dbf8c29e0135ef68fd8d59f44ab7) to fix [evaluation error](https://hydra.ngi0.nixos.org/eval/583#tabs-errors) on Hydra for package [opaque-sphinx](https://github.com/ngi-nix/opaque-sphinx), followed by [PR](https://github.com/ngi-nix/opaque-sphinx/pull/4).

activities:

- Attended team meeting on August 15.
- Wrote [question](https://discourse.nixos.org/t/hydra-hash-and-inputs/21133) and [solution](https://discourse.nixos.org/t/hydra-hash-and-inputs/21133/2?u=nrdsp) concerning flakrefs, inputs and hashes, out of which came a suggestion by Valentin Gagarin to update the documentation.
- Wrote [question](https://discourse.nixos.org/t/readfile-doesnt-find-file/21103) on Discourse concerning function `readFile` not finding the specified file.
- Wrote [solution](https://discourse.nixos.org/t/building-risc-v-phones-firmware-where-is-riscv64-unknown-elf-gcc/20578/7) for [question](https://discourse.nixos.org/t/building-risc-v-phones-firmware-where-is-riscv64-unknown-elf-gcc/20578) previously opened on Discourse.
- Kept reviewing the [PR](https://github.com/ngi-nix/riscv-phone/pull/8) for the RISCV-Phone's fe310 firmware, also researshing the `makeWrapper` setup hook as well as functions `readFile`, `symlinkJoin`, `writeShellScriptBin` and `writeScriptBin`.
- Researched projects on Hydra to work on, picking up the [opaque-sphinx](https://github.com/ngi-nix/opaque-sphinx) package.
- Watched recording of public lecture by Domen Kožar.


## week of 2022/08/22

hours: 20,03

contributions:

- [Added commit](https://github.com/ngi-nix/EgilSCIM/commit/74781d78953d01a98864dcc3d9a8de0b2ec08688), which addresses [Hydra evaluation errors](https://hydra.ngi0.nixos.org/eval/438#tabs-errors) concerning jobset [EgilSCIM:nix-flakes](https://hydra.ngi0.nixos.org/project/EgilSCIM) for NGI package [EgilSCIM](https://github.com/ngi-nix/EgilSCIM/tree/flake-only).
- Opened [issue](https://github.com/NixOS/nix/issues/6963) on the unavailability of the narHash attribute when the git+https URL form is used in inputs or flakerefs metadata.

activities:

- Attended team meeting on August 22.
- Updated [answer](https://discourse.nixos.org/t/hydra-hash-and-inputs/21133/7?u=nrdsp) on Discord concerning how to add a SHA-256 value inline and reverted [solution](https://discourse.nixos.org/t/hydra-hash-and-inputs/21133/8?u=nrdsp) to Hydra evaluation error. 
- Asked [question](https://discourse.nixos.org/t/move-script-from-flake-into-its-own-file/21158) on Discord on the subject of how to move a script from a flake into its own file.
- Added [update](https://discourse.nixos.org/t/hydra-hash-and-inputs/21133/2?u=nrdsp) on the MNT Reform package and started research on packaging firmware for the [MNT Reform Layerscape LS1028A SoM](https://source.mnt.re/reform/mnt-reform-layerscape-ls1028a-som), the [MNT Reform Kintex-7 SoM](https://source.mnt.re/reform/reform-kintex-som), and the [reform-camera](https://source.mnt.re/reform/reform-camera).
- Started new tutorial at [nix.dev](https://github.com/NixOS/nix.dev) on how to move a shell script out of a flake into its own file.
- Watched recording of public lecture by Thomas Bereknyei.


## week of 2022/08/29

hours: 42,58

contributions: 

- Contributed [PR](https://github.com/NixOS/nix.dev/pull/317) for a new tutorial in [nix.dev](https://github.com/NixOS/nix.dev) on how to move a bash script out of a flake into its own file.
- Contributed [PR](https://github.com/NixOS/nix/pull/6998) for an update to the manual concerning how to pass a SHA-256 value inline versus doing it through separate attributes both for an input or a flakeref declaration.

activities:

- Watched public lecture by Michiel Leenaars.
- Started work on the MNT-Reform firmware packages, scaffolding repository and commiting initial work on the [Layerscape LS1028A SoM](https://source.mnt.re/reform/mnt-reform-layerscape-ls1028a-som), the [Kintex-7 SoM](https://source.mnt.re/reform/reform-kintex-som) and the [reform-camera](https://source.mnt.re/reform/reform-camera).
- Read wiki page about [Flakes](https://nixos.wiki/wiki/Flakes) and blog posts [A Tutorial Introduction to Nix](https://rgoswami.me/posts/ccon-tut-nix), [A Tour of Nix Flakes](https://ghedam.at/a-tour-of-nix-flakes), [Nix Flakes: an Introduction](https://xeiaso.net/blog/nix-flakes-1-2022-02-21), [Shell Scripts with Nix](https://www.ertt.ca/nix/shell-scripts/).
- Resumed work on the firmware for the RISCV-Phone's Espressif ESP32 SoC.
- Participated in mob programming sessions on August 29 and September 2.

## week of 2022/09/05

hours: 31,38

contributions:

- Pushed [flake](https://github.com/ngi-nix/riscv-phone/blob/improve-esp32-derivation/flake.nix) with Alex Kenji, which improves the ESP32 derivation, getting us a step closer to packaging the firmware for the RISCV-Phone's Espressif ESP32 SoC. 
- Pushed commits [589368c](https://github.com/ngi-nix/riscv-phone/commit/589368c19e588ef0e8b8ecd87c21b876f8e7e54a), [1796f61](https://github.com/ngi-nix/riscv-phone/pull/8/commits/1796f617f705d720d93eb87f0083580d4dd6b68a), thus removing the Import From Derivation expression from [PR](https://github.com/ngi-nix/riscv-phone/pull/10) and getting rid of flake-utils in [PR](https://github.com/ngi-nix/riscv-phone/pull/8) respectively.

activities:

- Attended team meeting on September 5.
- Watched public lecture by Konrad Hinsen on September 6.
- Participated in mob programming sessions on September 5, 7.
- Engaged in conversation on [PR](https://github.com/NixOS/nix.dev/pull/317) and [PR](https://github.com/NixOS/nix/pull/6998), for work submitted the previous week.
- Engaged in a pairing session with Alex Kenji, working together on the firmware for the RISCV-Phone's Espressif ESP32 SoC, [submitting new work](https://github.com/ngi-nix/riscv-phone/tree/improve-esp32-derivation). 
- Sent new email to MNT Reform asking if they would care joining me on a conference call.

## week of 2022/09/12

hours: 36,49

contributions:

- Submitted [PR](https://github.com/ngi-nix/riscv-phone/pull/12) and merged, which packages RISCV-Phone's firmware for the FE310 SoC. 
- Opened [question on Discord](https://discourse.nixos.org/t/building-derivation-unable-to-find-files/21664) on the subject of not being able to find files when attempting to build a derivation.

activities:

- Attended team meeting on September 12.
- Watched public lecture by John Ericson on September 13.
- Participated in a mob programming session on September 14, working on the Gnunet-messenger with other participants.
- Engaged in pairing sessions with @ctem and Alex Kinji on September 14 and Justin Restivo on September 16. 
- Worked on the [https://github.com/ngi-nix/namecoin-core/pull/1](Namecoin-core)'s package, going through latest suggestions by Jon .

## week of 2022/09/19

hours: 28,5

contributions:

- Submitted [PR](https://github.com/ngi-nix/riscv-phone/pull/15), which packages the firmware for the ESP32 SoC and commits various updates to other bits in the RISCV-Phone package.
- Added [comment](https://github.com/ngi-nix/namecoin-core/pull/1#discussion_r975459293) and resolved suggestions [r967872988](https://github.com/ngi-nix/namecoin-core/pull/1#discussion_r967872988), [r967873063](https://github.com/ngi-nix/namecoin-core/pull/1#discussion_r967873063) on the [PR](https://github.com/ngi-nix/namecoin-core/pull/1#top) for the Namecoin-core package. 

activities:

- Attended team meeting on September 19.
- Engaged in a pairing session with @portothree on September 19, working with him on the Namecoin-core package.
- Participated in mob programming sessions on September 19, 21 and 23, working on the firmware for the Expressif SoC with other participants.
- Watched public lecture by Luc Perkins on September 20.

## week of 2022/09/26

hours: 26,06

contributions:

- Merged [PR](https://github.com/ngi-nix/riscv-phone/pull/15) and finished work on the packaging for the RISCV-Phone.
- Submitted a [reformulated version](https://github.com/NixOS/nix.dev/pull/317/commits/47e6766b7edf19854a04f60e9042d0e66c81f99a) for a tutorial on how to move a bash script out of a flake into its own file on [nix.dev](https://github.com/NixOS/nix.dev).
- Commited changes [15a5bda](https://github.com/ngi-nix/namecoin-core/pull/1/commits/15a5bdaa5fd721f419a9a50322685c50868c7a02), [469419a](https://github.com/ngi-nix/namecoin-core/pull/1/commits/469419a30eb812dd19251536adf072c3628d4da1) to the Namecoin-core package, addressing suggestions in [PR](https://github.com/ngi-nix/namecoin-core/pull/1) to improve versioning and to update the upstream to a more recent checkout.

activities:

- Attended team meeting on September 26. 
- Participated in mob programming sessions on September 26 and 28, reviewing the [PR](https://github.com/ngi-nix/riscv-phone/pull/15) for the RISCV-Phone and working on the [Corteza](https://github.com/ngi-nix/corteza/tree/mob/main).
- Watched public lecture by Connor Brewster on September 27.
