# OSMS-OKHs: A Searchable Registry for Open-Source Projects
This is a repository that will hold a wide range of open-source projects from the non-profit Open Source Medical Supplies (OSMS). The data from these projects will move into an OpenKnowHow (OKH) format in JSON from [this GitHub repository](https://github.com/iop-alliance/OpenKnowHow/blob/master/res/sample_data/okh-TEMPLATE.toml). Once in this state, a LOSH-krawler can find these projects after a user searchers for them. Ultimately, these files will allow users to easily discover important humanitarian projects for personal use, or as a pathway to become more involved in humanitarian engineering.

## Process and Timeline (Updated Alongside Progress)
**December 2024**

Members of the project team discussed the OKH formatting and exceptions to accomodate the varied data available for each project. Moved several project datasets from the .json OSH-Registry under Public Invention to the OKH repository. Modified the original template from [OSEGermany](https://gitlab.com/OSEGermany) to a more simplified version tailored to the needs for this project.

**January 2025**

Completed conversion of the OSH registry to the OKH format. Validated existing files with the krawler, then tweaked the template and files in accordance with feedback. Continued creation of OKH files working through the OSMS Project Library. 

**March 2025**

The following project folders were uploaded to the Open Source searchable database:
* Aerosol Boxes
* Ear Savers & Nose Bridge Supports
* Face Masks Fabric
* Face Shields
* Goggles
* Gowns
* N95 Respirators
* Powered Air Purifying Respirators (PAPR)
* Scrub Caps
* Scrubs

Additionally, licenses and duplicate repositories were fixed.

**June 2025**

The team updated the images section of the template to include slots/tags, and updated the previous files with the OKH 2.4 version.

## Important notes:
  * These are .toml files. If interested in learning more, check out this link:[TOML](https://toml.io/en/)
  * This project is in partnership with both [Public Invention](https://www.pubinv.org/volunteer/) and [OSMS](https://opensourcemedicalsupplies.org/), with collaboration from members of [OSEGermany](https://gitlab.com/OSEGermany). Check out their websites if you would like to get involved in similar projects.
  * Not all of the projects listed in the files were created by Public Invention or OSMS. Many were created during the Covid-19 pandemic, from various institutions and individuals who wanted to bridge the gap of need for PPE, ventilators, and similar medical devices. If interested in building one, please see the licenser contact information and reach out to the original creators.

## Contributers
  * Robert L. Read (<read.robert@gmail.com>): Provided project direction, organization, and leadership for the OKH team.
  * Mairin O'Grady (<mogrady@udallas.edu>): Created OKH files, converted projects from .json to .toml formats, and built the GitHub repository.
  * Robin Vobruba (<robin.vobruba@gmail.com>): Provided guidance on OKH usage and templates, as well as the krawler.
  * Christina Cole (<christina@opensourcemedicalsupplies.org>): Provided feedback from OSMS.
  * James Butler (<jbutler@helpfulengineering.org>): Worked on related software with Robert Read.
