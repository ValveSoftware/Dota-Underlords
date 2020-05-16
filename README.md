# Dota-Underlords
Tracker for issues specific to Dota Underlords on Linux and macOS.

Notes:

* This tracker is only for issues impacting the Linux and macOS version of Dota Underlords. For all other Dota Underlords bugs, use [this contact form](https://underlords.com/feedback/).
* Before filing a bug, please make sure your system meets the minimum requirements and you have a supported driver installed. 
* Minimum requirements for Dota Underlords:
    * Linux 64-bit: Vulkan-capable GPU from NVIDIA, AMD, or Intel
      - Ivybridge and Haswell requires mesa 19.1.0 or newer
    * macOS 10.13.6+ with a Metal-capable GPU

If the game fails to launch with a "missing executable" error, please use Steam to [verify the integrity](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335) of the game's files in order to acquire the missing binaries.

Known Issues
------------

* The first time you run with Vulkan you may experience short stutters while the engine caches shaders on disk. After playing through or watching a match, these stutters should go away.

Conduct
-------

There are basic rules of conduct that should be followed at all times by everyone participating in the discussions.  While this is generally a relaxed environment, please remember the following:

- Do not insult, harass, or demean anyone.
- Do not intentionally multi-post an issue.
- Do not use ALL CAPS when creating an issue report.
- Do not repeatedly update an open issue remarking that the issue persists.

Remember: Just because the issue you reported was reported here does not mean that it is an issue with Dota Underlords.  As well, should your issue not be resolved immediately, it does not mean that a resolution is not being researched or tested.  Patience is always appreciated.

Reporting Issues
----------------

If you encounter a bug while using Dota Underlords, first search the [issue list](https://github.com/ValveSoftware/Dota-Underlords/issues) to see if it has already been reported. Include closed issues in your search.

If it has not been reported, create a new issue with at least the following information:

- what platform this is occurring  on: Linux or macOS;
- a short, descriptive title;
- a detailed description of the issue, including any output from the command line;
- steps for reproducing the issue; and
- your [system information](#system-information).

Please place logs either in a code block (press `M` in your browser for a GFM cheat sheet) or a [gist](https://gist.github.com).

### System information

Your system information must include:
- your Linux distro or macOS version
- if Linux, your Desktop/Window Manager
- your Graphics card info (manufacturer, card version), any and all graphics driver versions
- anything else that you think may be useful (mouse/keyboard, filesystem type, etc).

The preferred and easiest way to get this information is from Steam's Hardware Information viewer from the menu (`Help -> System Information`).

Once your information appears: right-click within the dialog, choose `Select All`, right-click again, and then choose `Copy`.
Paste this information into your report, preferably in a code block or a [gist](https://gist.github.com).

Feature Requests
-------------------

This repository is not meant for Dota Underlords feature requests. Please use [this contact form](https://www.valvesoftware.com/en/contact?recipient=Dota+Underlords+Team) for suggestions.
