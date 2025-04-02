![logo](logo_elisa_small.png )

## ELISA Aerospace Working Group

The Aerospace Working Group shall develop use cases to inform and influence Linux architecture and related tools, work to derive technical requirements for avionics operating systems, and seek to enhance and expand avionics software lifecycle processes, practices, and tools to enable use of Linux in avionics systems that are certified to high design assurance levels.  (https://lists.elisa.tech/g/aerospace)

# Minutes

## 02 April 2025

---

# Agenda

- Roll Call
- Brief Notices
- Announcements
- Technical Topics - [Collaboration doc](https://hackmd.io/@AS9atTJpQgeXj_ICWAprZw/By850egu1g/edit)
- Closing

---

# Roll Call

## Attended this meeting

- Matt Weber - Boeing
- Tim Bird - Sony
- Dongshik Won - TelePIX/KAIST
- Ivan Perez - NASA Ames
- Martin Halle - Hamburg University of Technology
- Rob Woolley  - Wind River
- Paul Mani - Collins India
- Iain Galloway - NXP Semiconductors
- Laurent Meilleur
- Vikash Kodati

## Attended recently in the past

- Tim Bird - Sony
- Manuel Beltran - Boeing
- Naga - Timesys/Lynx
- Brennan Stewart - NASA
- Philip Balister - OpenEmbedded
- Ramon Roche - LF
- Olivier Charrier - Wind River
- Sam Thompson - Rapita Systems
- Michael Monaghan - NASA Goddard
- Christopher Heistand - Stoke Space
- Sascha Wise - Elodin
- Andrew Wilson - L3Harris, BYU, FPGA Zealot
- Piotr Skrzypek - ESA
- Wanja Zaeske - DLR
- Walt Miner - Linux Foundation
- Alexey Simonov
- Gary Crum - Voyager
- Tony James - Red Hat
- Allen Brown - Odyssey Space Research
- Qasim Majeed - Siemens
- Merlin Kooshmanian - ESA
- Phaedrus Leeds - Aerospace Corp
- Scott Salmon - Cesium
- Anshul Makkar - Infinitede
- Matt Kelly - Boeing
- Justin Pearson - Lynx Software
- Gaston Gonzalez - VENG
- Emmanuel Gravel - Skytrac
- Abdi Kitesa
- Lenka Koskova - TUL CZ
- Rajesh Kurapati - KMC
- Joseph Lee - Skytrac
- Gabriele Paoloni - Red Hat
- Daniel Riechers - Collins (Security)
- Douglas Landgraf - Red Hat
- Chuck Wolber - Boeing
- Steve VanderLeest - Boeing
- Carole Garrison - NASA Langley
- David Graziano - Collins
- Paul Greenwood - Vorago Technologies
- Shefali Sharma
- Tomas Novotny - Czech Aerospace Research Centre

---

# Brief Notices

## Code of Conduct and Legal Notices

- ELISA Project meetings involve participation by industry competitors, and it is the intention of the Linux Foundation to conduct all of its activities in accordance with applicable antitrust and competition laws. It is therefore extremely important that attendees adhere to meeting agendas, and be aware of, and not participate in, any activities that are prohibited under applicable US state, federal, or foreign antitrust and competition laws.
  - [Linux Foundation Antitrust Policy](http://www.linuxfoundation.org/antitrust-policy)
- Email communication will be treated as documentation and be received and made available by the Project under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0). Please refer to the ELISA Technical Charter section 7 subsection iv. for details.
- The discussions in these meetings are exploratory. The opinions expressed by participants are not necessarily the policy of the companies.
- No recordings of working group meetings are permitted. Special provisions may be arranged for recording in advance with explicit consent of the participants.
- The kernel and LF Code of Conduct applies to all communication with this project
  - [Linux Foundation Code of Conduct](https://www.linuxfoundation.org/code-of-conduct/)
  - Linux [Contributor Covenant Code of Conduct](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/process/code-of-conduct.rst)
  - Linux Kernel Contributor Covenant [Code of Conduct Interpretation](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/process/code-of-conduct-interpretation.rst)


---

# Announcements

Checkout our [Aerospace working group](https://lists.elisa.tech/g/aerospace) page as part of the ELISA foundation.  It includes a schedule of events, link to join the mailing lists, meeting minutes, and [seminar library](https://elisa.tech/seminar-series/).  

## Meetings

## Upcoming Events

- April 2-3: RISC-V in Space Conference, Gothenburg https://indico.esa.int/event/562/overview
- ELISA workshop - May 7-9 at Volvo in Lund, Sweden
  - Is virtual an option? (Asked TSC)
  - TSC discussed on Mar 5th and more details [here](https://lists.elisa.tech/g/devel/topic/meeting_notes_elisa_tsc/111529766)
  - Provided TSC these ideas from AeroWG
    -	Demo our first use case’s verification example
    -	Present the content/outline of the State of Art whitepaper (considering it was restarted today with more contributors)
- June 23-25 - Open Source Summit North America (including Embedded Linux Conference) in Denver, CO
  - Event web site: https://events.linuxfoundation.org/open-source-summit-north-america/
- July 2025 - Space Mission Challenges for Information Technology Space Computing Conference IEEE (Pasadena, CA) (https://2025.smcit-scc.space/) (Occurring for 20yrs, cross industry/global)
  - July 28 - Aug 1
  - Open source for space workshop (Ivan organizing)
  - Located @ California Science Center in LA  (close to USC)
  - Call for papers submission (Closes Apr 3rd)
- Aug - SmallSat - Call for paper is open (Due Feb 4th) - https://www.smallsat.org/downloads/call-for-papers.pdf
- August 25-27 Linux Foundation Open Source Summit EU & Embedded Linux Conference https://events.linuxfoundation.org/open-source-summit-europe/
  - Amsterdam, CFP here: https://events.linuxfoundation.org/open-source-summit-europe/program/cfp/
  - CFP closes April 14
  - See if we can get space content (There has been more EU space topics in the past and may have opportunity for future talks at this event.)
- TBD 10/31/2025, Drone+Space Community Meetup @ KAU (Korea Aerospace University) Ramon & Dongshik Host
- DASC 2025: September 14-18, 2025 44th Digital Avionics Systems Conference (https://2025.dasconline.org/) (Montreal, Canada)
- Dec 11-13: Linux Plumbers Conference 2025, in Tokyo
- ?? NASA SPARK submissions

## Articles / Publications

See our [Literature Database](../literature-database/literature.bib)

See our [Draft(March 5th, 2025 revision) Whitepaper](../docs/20250305_ELISA_AeroWG_Whitepaper.pdf)

---
---
# Technical Topics

[Link to 2025 goals](https://github.com/elisa-tech/wg-aerospace/blob/main/meeting-minutes/ELISA-AeroWG-Meeting-20250205.md#2025-vision-and-direction)

## Flight Software Workshop out brief

- New mailing list subscribers
- Questions from the presentation
  - When to use Linux vs RTOS/Microcontroller?
  - Does SGL go beyond just testing to also produce the formal req, design, tracking ,etc require by FAA, NASA and Space Force safety standards?  Breaking the paradigm, "we can't verify the safety in , we have to build it in."
  - RTEMS vs. Linux
- Slides
  - https://github.com/elisa-tech/wg-aerospace/blob/main/presentations/ELISA-FSW-March2025.pdf   
  - https://github.com/elisa-tech/wg-aerospace/blob/main/presentations/Space%20Grade%20Linux%20Flight%20Software%20Workshop%202025%20Introduction%20-%20STRIVES%20Approved.pdf


## Whitepaper on "Survey State of Art...""

Background
- Edits
  - Via online [Overleaf editor](https://www.overleaf.com/) - we have limited licenses so we've shared the pdf link below
  - latex format and editor can generate documents
- Paper's goal - What is the current state of the art with respect to aerospace
  - Initial document drove use case definition
  - Evolved to be a comparison and a conclusion of industry direction
  - Doc still informs goals and activities of AeroWG & Space
- Martin has restructured the paper based on previous discussion
  - Why the paper / oveview
  - Why would you use OSS in safety critical
  - Challenges
  - Overview
    - closed solutions
    - RTOS  in Aero
    - Linux in other industries
    - Linux in aero and related considerations
  - Comparison / conclusion / criteria
- Paper started really focused and restructure started when the group became more diverse with standards and concerns
  - Suggestion in this call was to consider adjusting the standards language to not just focus on DO-178C but consider NASA / MIL guidance.
- Gaps
  - State of the art - how far back (e.g., Perseverance rover backshell camera control but thats older) - Yes
  - Mention of Phone SATs
  - SWL vs class levels mapped to examples  (human factor vs reliability)
      - Cross roads example could be Touch controls on Dragon

**Open actions**
- Martin - Update the overall abstract for the whitepaper (before we dive into sections)
    - Clear "state of the art" definition with supporting information which could support follow on papers / research specifically comparing approaches
- ALL - Feedback on survey document - https://github.com/elisa-tech/wg-aerospace/blob/main/docs/20250305_ELISA_AeroWG_Whitepaper.pdf
  - Propose what you believe the abstract is for this paper. How would you describe it in a couple mins.
  - What gaps do you see?
  - What is unclear?

## Robotics processing

Iain Galloway (NXP)

- NXP ASIL-D related activities
- Industrial grade linux
    - Robotics: Ubuntu Linux (ROS2)
    - Supervisory functions
- Zephyr RTOS
- Zen enabled communication channel
- Radiation-hardened H/W from NXP (Teledyne)
- Cerebri - a correct by construction autopilot
    - https://cognipilot.org/
    - https://brave.cognipilot.org/cerebri/about/
- Devkits:
    - NavQPLus i.MX8
    - MR-VMU-RT1176 NUTX/PX4 S/W stack (PixHawk)
        - Collaboration between US aerospace company, Purdue University to advance AI driven flight
    - NXP iMX95 reference platform (real-time control domain up to 100Hz)
        - Cortex M33 offload of M7 peripherals for system mode flexibilty (plus A core with Linux)
- RFNM - NXP supporting SDR project - https://rfnm.com/
- Rob asked a good question around ROS (Ubuntu) vs Yocto - discussion was around maintenance tradeoff - Will need to reflect on for SGL.


## Discussion on Features for Aerospace
- Call between Ivan, Martin, Paul, Brian Wood, and I is occurring on testing wkly on Friday @ 9-9:30am CST. The meeting focuses on discussing the testing framework and how to prototype the components together. Anyone is welcome to join us https://zoom-lfx.platform.linuxfoundation.org/meetings/elisa-project?view=week.

## Future topics

Licensing and Developer Agreement - (Open Actions)
- TSC contribution guidance
- Commit license files to repo


---
---

# Closing

## Action Items

Located in [GitHub Issues](https://github.com/elisa-tech/wg-aerospace/issues)

## Round Table
