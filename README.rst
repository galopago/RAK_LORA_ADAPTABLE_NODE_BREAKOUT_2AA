=======================================================================================================================================
Breakout board for RAK811/RAK4200 LoRa adaptable nodes, small size, used when both AA battery holders were installed.
=======================================================================================================================================

Breakout board & prototype area to mount a few ( and small ) thru-hole components to interface LoRa node. Also can be used as a template for a custom interface board. 

Read this in other languages: `Español </docs/README.es.rst>`_

.. image:: /docs/pcb3d.png

Key features:
-------------
* Double sided traces and pads for added strength
* Prototype area with two parallel tracks connecting multiple pads, to be used as a power&ground rails
* Solder directly to the node's pcb using male header pins for a permanent, rigid  and low height card
* Connect to the node's pcb using male-female pin header combination, for a more flexible solution

How to use this repository
--------------------------
The PCB was developed in KiCad V5.1,


Directory structure
-------------------
* The root folder contains KiCad files: project, schematic and PCB.
* gerber/single directory contains ready to manufacture files, for a single board.
* gerber/panel_100mmx100mm directory contains ready to manufacture files that fits in a 100mm x 100mm panel (use Vcuts!).

License
-------

.. image:: https://i.creativecommons.org/l/by/4.0/88x31.png
   :target: http://creativecommons.org/licenses/by/4.0/


This is an Open Hardware project and is licensed under a `Creative Commons Attribution 4.0 International License, <http://creativecommons.org/licenses/by/4.0/>`_
