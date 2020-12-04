# Linux Overview

<br>

## Introduction to V7

The new Folding@home (FAH) software is configured, controlled, and monitored through a new simpler graphical interface named Web Control. This new web browser based application has incorporated many new features, including client monitoring and configuration of all FAH clients. Web Control is now the recommended interface for all FAH types (Single core CPU, Multi-core CPU, GPU), replacing both the Systray and the Console versions of FAH.  The more advanced FAHControl application is also available.

<br>

## New Terminology

The V7 software really changes the concept of how people interact with FAH. And with new concepts come new or updated terms to describe those concepts. Learning new references is part of the process for change and improvement.

    
- Web Control – This is the new simpler graphical interface (front-end). Web Control will configure and monitor one or more FAHClient slots through an easy to use web page.  This is the default control program.
    
- FAHControl – This is an alternate new graphical interface (advanced front-end). FAHControl will configure and monitor one or more FAHClient (slots), on one or more computers. This more advanced interface is optional.
    
- FAHClient – This is the (back-end) client software managed by FAHControl and typically runs behind the scene. This is a truly unified client (slot) manager. FAHClient starts one or multiple instances of a Fahcore and manages the work assignments for each of these client “slots.”
    
- FAHSlot – aka “slot” – Each Fahcore and the data associated with it is called a slot. For example, one FAHSlot can be associated with a GPU and another slot associated with the CPU. Each folding slot can download, process, and upload results independently. The FAHClient manages each slot, and FAHControl monitors and displays their progress independently.
    
- FAHViewer – This is the new and fully functional work unit viewer. FAHViewer is modeled after the very popular PS3 viewer, and continues to offer the many rendering options, ball and stick, space fill, zoom, rotation, etc., and adds snapshot capture and cycling to show folding in action.


See also the FAHControl, FAHClient , and FAHViewer documents for more information about setup and customization options.

<br>

## What is new in V7?

We are pleased to say that everything is new in this version, using completely new software coding from the ground up. Our goal is to include the best features from the previous clients, make improvements where possible, discard what was no longer needed, then add new features like the quick start Express mode installer, the new FAHViewer, and the new unified interface. V7 has all of these and more, making installation and configuration much simpler and faster for new users, while continuing to support advanced options.

Note: There are too many updated and new features to list in an Installation Guide, so this section only covers What’s New when installing V7 software. Please read the V7 Introduction page for basic information and explanations of the new client features.

<br>

## Quick Start

This section describes how to get started folding quickly with the new V7 software and the default FAHClient slot(s).

-     Download the package for your distro.
-     Click Install Package.
-     Enter password and click OK.
-     Click Forward, click close.
-     Done.

After the download, the new V7 software is installed as a service and folding in under 1 minute. Very quick and easy. For a more guided installation, please see the Express Installor Custom Setup sections.

<br>

## Express Installation – Recommended!

This section describes the recommended method for installing the V7 FAH software for an individual client slot using a software package in Linux. A first time installation is assumed. And unless otherwised noted, the default setting for each option is the recommended setting.

Select the appropriate V7 package for your Linux distribution from the V7 download page. (see figure 1). There are separate installation packages for the new FAHControl (client manager) interface software, the new FAHClient (slot manager) software, and the new FAHViewer (viewer) software. FAHClient is required, FAHControl is recommended, FAHViewer is optional.



