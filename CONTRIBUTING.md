# CorsixTH Community Content Contributing Guidelines
**This is not the place to report issues with CorsixTH's base code. Continue to do this at https://github.com/CorsixTH/CorsixTH**

## Content Creation Guidance
You can use the CorsixTH Wiki to find some pointers
- [How to create a level file](https://github.com/CorsixTH/CorsixTH/wiki/Custom-Levels)
- [How to use the Map Editor](https://github.com/CorsixTH/CorsixTH/wiki/Map-Editor)
- [A broader article on submitting to Community Content](https://github.com/CorsixTH/CorsixTH/wiki/Submitting-to-Community-Content)

## Pull Requests
### Required files
Depending on your contribution, this may include:
- `.level` file(s)
- `.map` file(s)
- `.campaign` file (if submitting a campaign)
- `LICENSE.txt` file for licensing compliance (always required)

### File mapping
All files that do not already exist in CorsixTH's base install ([levels](https://github.com/CorsixTH/CorsixTH/tree/master/CorsixTH/Levels), [campaigns](https://github.com/CorsixTH/CorsixTH/tree/master/CorsixTH/Campaigns))
must be placed inside a directory named after your level, map, or campaign. They must
also be placed inside the relevant directory at root (CorsixTH Community Content).
These are:
- Campaigns
- Levels (for standalone levels)
- Maps (for map file only submissions)

For example if it were a campaign:
```
CorsixTH Community Content/
├─ Campaigns/
│  ├─ My Campaign/
│  │  ├─ LICENSE.txt
│  │  ├─ My Campaign.campaign
│  │  ├─ FirstLevel.level
│  │  ├─ SecondLevel.level
│  │  ├─ FirstLevel.map
│  │  ├─ SecondLevel.map
```
Do not create additional directories inside your level/campaign folder.

## Copyrights
All original (first author) content submitted to this repository must be licensed
under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](http://creativecommons.org/licenses/by/4.0/).
**There are no exceptions to this.<sup><a href="https://github.com/CorsixTH/CorsixTH/wiki/Submitting-to-Community-Content#why-we-license" title="Learn why">[?]</a></sup>**

### A brief summary of CC BY 4.0 License
- Your work can be distributed so long as you authorship remains attached (known as Attribution)
- Your work is not exempt from Commerical use
- Your work may be modified by another person, as long as your original authorship is
retained on the work (known as Derivative Works)
- You are free of any liability or warranty for your works

### Including works by other authors (aka redistribution and derivative works)
CC BY 4.0 licensed files allow for redistribution providing you attribute the author.
Derivative works must contain the original author and the license used; and your own
authorship. Other licenses used may include the MIT License (used in CorsixTH's base
code), which allow for reuse/modification with reference to original author.
**However, it is your responsibility to ensure all included files have compliant
licenses for your use.**

### License file
The opening of your license must contain a reference to yourself as author with the
year the works were created. It must also include the name of your level/map/campaign
as appropriate.
```
CONTENT NAME level/map/campaign is freely distributed under the following terms:
Copyright (C) YEAR(S) FORENAME "USERNAME" SURNAME
```
where:
- `CONTENT NAME` is the name of your work
- `level/map/campaign` delete as appropriate
- `YEAR` the year of creation
- `FORENAME "USERNAME" SURNAME` Forename and Surname are at your own discretion. You
may use whatever identifier you like as long as it is a representation of you.
- If your submission is a derivative work, place the original author (and year)
before your own authorship if the original work used CC BY 4.0 too e.g. `Copyright
(C) 2020 Joe "jbloggy" Bloggs, 2022 John "TrekkingJim" Doe`. If not, see
redistributed works section below.

The license file must contain for your work a link out to the CC BY 4.0 license.
Luckily, Creative Commons' required text is very small.
```
This work is licensed under a Creative Commons Attribution 4.0 International License - https://creativecommons.org/licenses/by/4.0/
```
If you're **redistrubiting someone elses work**, you must proceed to declare this
under your license using the original author's license and any stipulations given.
This includes mentioning the name of what level/maps of your work are by someone
else. You should include a source URL, if known, in the license file.\
**Tip:** you can view the [MIT License](https://choosealicense.com/licenses/mit/) text here.\
**Important:** If you're using someone else's work and no license is applied, we will
not be able to accept the submission. Please ask the person to apply an appropriate
license (e.g. CC BY 4.0).

### License in level files
You must also follow the practice above again on a per-file basis for `.level` and
`.campaign` files. `.map` files can't currently have authorship appended and rely on
the `LICENSE.txt`. Note, authorship here is file specific. Such as, if one file is
solely your work and a different file is both yours and someone else's work: you must
apply the licensing accordingly.

## Quality Testing
You should always test your work before submitting it to the repository. Ideally, you
should be able to complete the level (or competently make progress) yourself first.
This ensures you can demonstrate the level is balanced enough to not become
frustrating/joyless.

## Updating an Existing Submission
If you wish to upload a new version of existing content make sure you point your PR
at the relevant files. Remember to update any years on your license texts. Please
note that due to the way CorsixTH works, your changes will only apply to people
playing a new game of your level/campaign.