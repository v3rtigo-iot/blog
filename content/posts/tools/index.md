+++
title = "Tools of The Trade"
date = "2023-08-19T13:02:57-07:00"
author = "v3rtigo"
cover  = "lab.png"
description = "Let's look at the tools of the trade from the essentials to quality of life to those for more advanced analysis."
+++

We'll begin our journey with a look at essential tools needed to begin basic analysis of IoT devices. Once we've discussed the basics, we'll move into those that add to quality of life and finally tools for more advanced hardware analysis.

This is by no means an exhaustive list nor are these in a strict order of importance.  That said, all the tools in this initial group are arguably all necessary for the basic analysis deep dives we'll do as the blog progresses. 

It's worth noting that you don't need the exact same brand of tools.  As far as cost, while I didn't purchases the cheapest of everything, I tried to keep costs reasonable as things can add up fast.

| The Basics       | What do I have?         | Important?  |
| ------------- |:-------------:| -----:|
| Multimeter | AstroAI Digital Multimeter | YES |
| Soldering Iron | Hakko FX888D-23BY  | YES |
| Logic Analyzer | DreamSourceLab DSLogic Plus | YES |
| Serial 5V Adapter Cable | DTech FTDI USB to TTL | YES |
| Serial 3.3v Adapter Cable | DTech FTDI USB to TTL      | YES |
| SOIC Clips 8 pin | 5250 - IC Test Clip | YES |
| SOIC Clips 16 pin | ACEIRMC SOP16 IC Test Clip | YES |
| Silicone Soldering Mat | Kaisi Heat Insulation Silicone Mat | IDEAL |
| Helping Hands | QuadHands Workbench | IDEAL |
| Screwdrivers | STREBITO Screwdriver Sets 142-Piece | YES |
| Pliers | WORKPRO 6-piece Mini Pliers Set | YES |
| Dupont Wire | ELEGOO 120pcs Multicolored | YES |
| USB Hub | Apanage Powered USB 3.0 Hub, 11 Ports | IDEAL |
| Breadboards | 4PCS Breadboards kit w/wires | IDEAL |
| Jumper Wires (for breadboard) | AUSTOR 560 Pieces Jumper Wire Kit | IDEAL |
| Fan (Soldering Ventilation) | KOTTO Solder Smoke Absorber | YES | 

| Advanced | What do I have? | Important? |
| ------------- |:-------------:| -----:|
| Oscilloscope | Rigol DS1054Z Digital Oscilloscope | YES |
| Variable Power Supply | KORAD KD3005D | YES |
| JTAG/Serial Debug | Jtagulator | YES |
# So what is all this stuff?

Now that we have an idea of what we'll need, let's describe at a high level what they are and what they do.

*Safety Considerations: It’s vital to follow proper safety guidelines, such as using the correct range and terminal for any measurement being taken. Improper use can lead to damage to the tool or even injury.*

***Multimeter***
A multimeter is an invaluable tool for anyone working with electronics or electrical systems. It can measure several different aspects related to electricity, such as voltage, current, resistance, and sometimes other quantities like capacitance and temperature. In general, the multimeter will be the first tool we use to identify, specifically, **ground** and **voltage**. 

***Soldering Iron***
A hand tool with a heated metal tip used to melt solder, a fusible metal alloy that creates a permanent bond between metal workpieces. In hardware hacking, a soldering iron is vital for attaching and detaching components on printed circuit boards (PCBs). It allows for precise control and enables us to modify, repair, or create custom hardware configurations.

***Logic Analyzer***
Another invaluable tool for understanding the complex interactions between different parts of a digital circuit. By capturing data across multiple channels, it aids in the debugging and reverse engineering of hardware, helping to trace communication and uncover hidden functionalities. Unlike an oscilloscope, which displays voltage against time, a logic analyzer displays timing diagrams of digital signals and can simultaneously analyze many digital signals.

***Serial Adapter Cable***
These are cables specifically designed to interface with devices operating at respective voltage levels. They're essential for connecting microcontrollers, sensors, and other embedded devices to computers. The correct voltage ensures compatibility and prevents damage. They are crucial for reading, writing, and analyzing data directly from the hardware.

***SOIC Clips***
These clips connect to Small Outline Integrated Circuit (SOIC) packages without needing to solder. They come in different pin configurations. In hardware hacking, being able to quickly and temporarily connect to chips is essential. These clips enable us to read or reprogram memory chips or microcontrollers without permanent alteration, aiding in reverse engineering or modification.

***Silicone Soldering Mat***
Made of heat-resistant silicone, these mats provide a safe surface for soldering and handling hot components. Besides protecting the work surface from heat and burns, the mats often feature built-in compartments and magnetic areas for organizing screws and small parts, thus preventing loss and enhancing efficiency.

***Helping Hands***
A tool equipped with adjustable arms with clips and sometimes a magnifying glass. Holding tiny components steady during soldering or inspection can be challenging and helping Handm assits by hold things firmly in place, allowing for more precise and controlled work.

***Screwdrivers/Pliers***
While this may appear obvious, Having various screwdrivers is paramount for opening up electronic devices to access internal components. Specialized types, like **Torx** or **pentalobe**, may be required to open certain proprietary hardware. Similar to screwdrivers, **pliers** serve multiple functions in hardware hacking, including handling, shaping, or cutting wires, and even holding hot components during soldering.

***Dupont Wire***
Flexible jumper wires fitted with Dupont connectors, usually used for breadboard connections. They enable quick and temporary connections between different components, allowing for experimentation without soldering. These wires come in various forms such as male-to-male or male-to-female. It hardware hacking we'll most often use these for connecting to **pin headers**.

***USB Hub***
We'll often be working with multiple devices simultaneously, a USB Hub facilitates the connection and control of multiple targets, such as various microcontrollers or debuggers.

***Breadboards***
A rectangular board with a grid of holes, used for creating temporary electronic circuits without soldering. Ideal for experimenting, testing ideas, and building prototypes. Components can be easily inserted, rearranged, or removed, making it a flexible platform for testing and analysis.

***Jumper Wires***
Insulated wires used to connect components on a breadboard. They provide an easy way to route signals and power around a breadboard, allowing for quick changes and iterations on a circuit design.  I've often found these useful for quick solder work when temporary pins are needed for debugging.

***Fan (Soldering Ventilation)***
A specialized fan used to draw away the fumes produced during soldering. Soldering can produce toxic fumes from the flux and other materials. A soldering fan removes these fumes from the working area.  


## Work In Progress