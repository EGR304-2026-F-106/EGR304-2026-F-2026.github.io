---
title: Software Proposal
---

## Introduction
Pictured below is the block diagram for the software to be uploaded to the Curiosity Nano microcontroller. It describes the basic processing loop: after initialization, the microcontroller continually checks and records input data from the sensors and buttons and displays it accordingly. The primary goal of the software design is threefold, listed in reverse order: to display the available data in the format selected by the user, to store data over time as to become available for limited analysis, and to read data from the sensors and buttons. Given that the latter two goals are fairly simple to accomplish, emphasis is placed below on the display and formatting functionality (as seen in the relative size of the rightmost box compared to the left four). There is also limited redundancy in case of any paradigm shifts in the screen state machine, most notably seen in the duplicate entry-setting statements. The below diagram describes completely the structure that fulfills the role of the microcontroller in the wider HeatSmith device.

<img src="/docs/image/SoftwareBlockDiagramForUpload.svg"></img>

