# MegaMek Project Summary

The MegaMek organization maintains a series of programs that strive to implement the published rules for the tabletop BattleTech game published by Catalyst Game Lab as faithfully as possible. These programs are designed to be accessible across various operating systems and hardware configurations. These programs REQUIRE a minimum of Java 17 to run. See [this post for install directions.](https://github.com/MegaMek/megamek/wiki/Updating-to-Adoptium-%28Eclipse-Temurin-Open-Source-Java%29)

## MegaMek Wiki

### [Our wiki while small does have some answers for common questions.](https://github.com/MegaMek/megamek/wiki)

---

## [MegaMek](https://github.com/MegaMek/megamek)

MegaMek is an open-source implementation of the BattleTech board game, enabling players to engage in tactical battles with various unit types including mechs, vehicles, and aerospace units. It recreates the rules from the Total Warfare manual, with additions from Tactical Operations and Strategic Operations. The game supports single-player and multiplayer modes, and allows the creation of custom units, maps, and scenarios.

[MegaMek Issues](https://github.com/MegaMek/megamek/issues)

[MegaMek Pull Requests](https://github.com/MegaMek/megamek/pulls)

## [MegaMeklab](https://github.com/MegaMek/megameklab)

MegaMekLab is a tool used alongside MegaMek for designing and customizing mechs and other combat units. It offers an in-depth customization interface that adheres to the BattleTech game rules, enabling players to modify their units' weaponry, armor, and equipment specifications.

[MegaMekLab Issues](https://github.com/MegaMek/megameklab/issues)

[MegaMekLab Pull Requests](https://github.com/MegaMek/megameklab/pulls)

## [MekHQ](https://github.com/MegaMek/mekhq)

MekHQ is a campaign management tool that provides an immersive experience in managing a BattleTech mercenary unit. It integrates with MegaMek for battles and MegaMekLab for unit customization, covering personnel, finances, and logistics.

[MekHQ Issues](https://github.com/MegaMek/mekhq/issues)

[MekHQ Pull Requests](https://github.com/MegaMek/mekhq/pulls)

## [MegaMek Data Repository](https://github.com/MegaMek/mm-data)

This is the MegaMek Data Repository. It holds all data used by the suite of MegaMek programs. Unit files, maps, images, etc are all here and normalized.

[Data Issues](https://github.com/MegaMek/mm-data/issues)

[Data Pull Requests](https://github.com/MegaMek/mm-data/pulls)

## Development and Community

The MegaMek suite is developed in Java and is supported by a robust community of developers and players. We are an open-source project, so anyone is welcome to help. Consider what you can offer, and make sure you join our [Discord](https://discord.gg/XM54YH9396) for easy communication and collaboration. Here’s how you can contribute:

- **I know how to code**: Familiarize yourself with our [Coding Style Guide](https://github.com/MegaMek/megamek/wiki/MegaMek-Coding-Style-Guide). Start small, like fixing a bug or addressing an RFE from our tracker, and submit a PR.

- **I'm an Artist**: While we have a precise plan for ground units, we need aerospace sprites. Submit your art in .png format, following the guidelines and discussions for consistency and technical compatibility.

- **I'm a data guy**: Accuracy and canon adherence are critical. Join our community to align with our data standards and contribute meaningfully.

- **I know how to document**: Help expand our documentation to assist users and contributors. Start with the basics and grow the content over time.

- **General support**: Play the games, find bugs, and suggest enhancements. Your gameplay feedback is invaluable.

## Status and Support

Find the latest releases, documentation, and support for MegaMek, MegaMekLab, and MekHQ on their GitHub pages.

## License

MegaMek programs are distributed under the GNU General Public License. See the [GNU GPL](http://www.gnu.org/licenses/) for more details.

## Our Online Presence

- Main website: [MegaMek](https://www.megamek.org)
- GitHub Wiki: [MegaMek GitHub Wiki](https://github.com/MegaMek/megamek/wiki)
- BattleTech Forum: [Official BattleTech Forum](https://bg.battletech.com/forums/index.php?board=29.0)
- Discord: [Join our Discord](https://discord.gg/megamek)
- Facebook: [MegaMek Facebook](https://www.facebook.com/MegaMek), [BattleTech International Group](https://www.facebook.com/groups/5124394675/)
- Email: <megamekteam@gmail.com>

## Current Project Status

| Type           | MM Status                                                                                                                                                              | MML Status                                                                                                                                                                       | MHQ Status                                                                                                                                                        |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Latest Release | [![Release](https://img.shields.io/github/release/MegaMek/megamek.svg)](https://gitHub.com/MegaMek/megamek/releases/)                                                  | [![Release](https://img.shields.io/github/release/MegaMek/megameklab.svg)](https://gitHub.com/MegaMek/megameklab/releases/)                                                      | [![Release](https://img.shields.io/github/release/MegaMek/mekhq.svg)](https://gitHub.com/MegaMek/mekhq/releases/)                                                 |
| Javadocs | [![javadoc](https://badgen.net/badge/javadoc/master/red?icon=github)](https://megamek.org/megamek) | [![javadoc](https://badgen.net/badge/javadoc/master/red?icon=github)](https://megamek.org/megameklab) | [![javadoc](https://badgen.net/badge/javadoc/master/red?icon=github)](https://megamek.org/mekhq) |
| License        | [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)                                                     | [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)                                                               | [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0.html)                                                 |
| Build (CI)     | [![MM Nightly CI](https://github.com/MegaMek/megamek/workflows/MegaMek%20Nightly%20CI/badge.svg)](https://github.com/MegaMek/megamek/actions/workflows/nightly-ci.yml) | [![MML Nightly CI](https://github.com/MegaMek/megameklab/workflows/MegaMekLab%20Nightly%20CI/badge.svg)](https://github.com/MegaMek/megameklab/actions/workflows/nightly-ci.yml) | [![MHQ Nightly CI](https://github.com/MegaMek/mekhq/workflows/MekHQ%20Nightly%20CI/badge.svg)](https://github.com/MegaMek/mekhq/actions/workflows/nightly-ci.yml) |
| Issues         | [![GitHub Issues](https://badgen.net/github/open-issues/MegaMek/megamek)](https://gitHub.com/MegaMek/megamek/issues/)                                                  | [![GitHub Issues](https://badgen.net/github/open-issues/MegaMek/megameklab)](https://gitHub.com/MegaMek/megameklab/issues/)                                                      | [![GitHub Issues](https://badgen.net/github/open-issues/MegaMek/mekhq)](https://gitHub.com/MegaMek/mekhq/issues/)                                                 |
| PRs            | [![GitHub Open Pull Requests](https://badgen.net/github/open-prs/MegaMek/megamek)](https://gitHub.com/MegaMek/megamek/pull/)                                           | [![GitHub Open Pull Requests](https://badgen.net/github/open-prs/MegaMek/megameklab)](https://gitHub.com/MegaMek/megameklab/pull/)                                               | [![GitHub Open Pull Requests](https://badgen.net/github/open-prs/MegaMek/mekhq)](https://gitHub.com/MegaMek/mekhq/pull/)                                          |
| Code Coverage  | [![MegaMek codecov.io](https://codecov.io/github/MegaMek/megamek/coverage.svg)](https://codecov.io/github/MegaMek/megamek)                                             | [![MegaMekLab codecov.io](https://codecov.io/github/MegaMek/megameklab/coverage.svg)](https://codecov.io/github/MegaMek/megameklab)                                              | [![MekHQ codecov.io](https://codecov.io/github/MegaMek/mekhq/coverage.svg)](https://codecov.io/github/MegaMek/mekhq)                                              |
