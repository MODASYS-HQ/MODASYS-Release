# MODASYS

**MODASYS** (Model for Decision-Making in Agri-Environmental Systems) is a whole-farm model and software program developed in the HOLOSEU project. It estimates greenhouse gas (GHG) emissions, carbon balance and production from the information entered for individual farms, and is available at no cost to users.

Users can select scenarios and farm management practices that best describe their operation and then adjust these practices to see the effect on production, emissions and the environment. Examples of these adjustments include changing livestock feed, reducing tillage, including perennial forages in rotation or planting trees in agroforestry systems.

MODASYS builds on Holos V4.0, originally developed by Agriculture and Agri-Food Canada.

This repository holds the released installers. The source code is at [MODASYS-HQ/MODASYS](https://github.com/MODASYS-HQ/MODASYS).

> **Beta version.** MODASYS is in beta, released for testing and case studies. Results may change in later versions, and we would be glad to hear about any problems you find (see [Feedback](#feedback)).

# Download

Download `MODASYS-Setup.exe` (beta) from the latest release on the [Releases](https://github.com/MODASYS-HQ/MODASYS-Release/releases/latest) page. It is a single file of about 100 MB and includes the .NET runtime, so nothing else needs to be installed first.

# Installing MODASYS

- Requires 64-bit Windows 10 or 11.
- Double-click `MODASYS-Setup.exe`, accept the licence terms and click **Install**. No administrator rights are needed: MODASYS is installed for the current user only, in `%LocalAppData%\Programs\MODASYS`, with shortcuts on the Start menu and the desktop.
- The installer is not code-signed yet, so Windows SmartScreen may warn about an unknown publisher. Click **More info**, then **Run anyway**.
- Installing a newer `MODASYS-Setup.exe` replaces the older version. To remove MODASYS, use **Settings → Apps → Installed apps**.

# User guide

The [MODASYS User Guide](docs/MODASYS_User_Guide.pdf) (PDF) walks through setting up a farm, entering its components and reading the results.

# Feedback

We welcome feedback from researchers, farmers and industry to help us improve this software. For more information on MODASYS, please contact ibrahim.khalil1@ucd.ie.

# License

MODASYS is developed by University College Dublin (UCD) from Holos, which is Crown Copyright, Government of Canada. Unless otherwise noted, the original Holos source code remains under Crown Copyright, and the MODASYS modifications and additions are copyright University College Dublin, 2024–2026. The whole project is distributed under the [GNU General Public License (GPLv3)](LICENSE).

The MODASYS name and logo, and UCD's own data, documentation and user guide, may not be used for commercial purposes without prior written permission from UCD and the MODASYS project consortium. This does not limit the rights the GPLv3 gives you over the source code.
