***********************
HabitatOS Documentation
***********************


HabitatOS is a proof of concept operating system for extraterrestrial habitats and analog simulations

.. image:: https://img.shields.io/pypi/l/habitatOS.svg?style=flat-square

.. image:: https://img.shields.io/pypi/pyversions/habitatOS.svg?style=flat-square

.. image:: https://readthedocs.org/projects/habitatOS/badge/?version=latest
    :target: https://habitatOS.readthedocs.io


Rationale
=========
HabitatOS is the first and only open source operating system for use in human spaceflight habitats.
System supports customizable time delayed communication for Moon and Mars simulations.
With responsive HTML interface it can be used on any device such as: desktop, mobile smartphones, tablets, TV screens and smartwatches.
It has an open and documented API for development of new features and easy to use pluggable add-on structure to build experiments around.


HabitatOS Subsystems
====================

Data Analytics
--------------
* Data acquisition from IoT devices and sensors
* Environmental parameters visualization in real-time on habitat map
* Data analytics using Machine Learning algorithms
* Data visualization
* Data exploration tool

Time subsystem
--------------
* Customizable time delay simulation for communication
* Native implementation Lunar Standard Time, Coordinated Mars Time, Mars Sol Date and all Earth time zones
* Conversion between supported timezones
* Custom time formats and timezones in reporting, communication and everywhere in the system
* Time delayed small and big file upload

Work Scheduling and Reporting
-----------------------------
* Tasks scheduling
* Support for projects and tasks with checklist acceptance criteria
* Tasks with and without deadlines
* Schedule planning with projects, due-dates and categories
* Timeline visualization with time marker
* Procedure viewer for particular tasks
* Attachments support
* Roadmap viewer for long running experiments and projects
* Daily activity tracking
* Complete/Incomplete work tracking

EVA subsystem
-------------
* Planning, tracking and reporting for EVA activities
* EVA contingencies support
* Tracking EVA tools and inventory items placement
* EVA spacesuit bio-sensors monitoring
* Geolocalization and astronaut tracking in realtime (for astronauts, and time-delayed for MCC)

ECLSS subsystems
----------------
* Flexible and extensible habitat light control
* Temperature regulation
* Humidity regulation
* Support for monitoring: Carbon Dioxide, Carbon Monoxide, Humidity, Illuminance, Motion, Network Latency, Oxygen, Pressure, Radiation, Temperature, UV, Vibration, Voltage, Outside Weather
* Real-time or time delayed analytics
* Machine Learning algorithms ECLSS system adjustments
* Waste management and tracking
* Support for Biolab experiments such for hydroponics and aquaponics
* Water (drinking, urine, biolab, technical) usage tracking and analytics
* Shower time tracking

Communication
-------------
* Time delayed communication (Astro-MCC)
* No delays for Astro-Astro, and MCC-MCC
* Attachment support and notifications
* User diaries and journals
* Videologs and audiologs
* Daily briefings/debriefings
* Briefings/debriefings tasks with assignees
* Desktop and smartphone push notification from system
* Tracking crew daily report completeness

Medical and Workout
-------------------
* Medical data collecting from onboard devices and sensors
* Medical evaluations, questionnaires support and data collecting
* Food tracking
* Food expiration date tracking
* Medications and drugs expiration date tracking
* Support for monitoring: Blood Pressure, Glucose, Heart Rate, Pulse Oximetry, Stool, Temperature, Urine (turbidity, color, pH, volume), Weight

Sociodynamics and Psychology
----------------------------
* Sociodynamics, psychological surveying
* Real-time or time delayed
* Sleep tracking
* Mood tracking
* Social interpersonal relations tracking

Inventory Tracking
------------------
* Inventory management
* Barcode and QR code support
* Support for liquids, gasses and solid objects
* Tools tracking
* Incidents logging
* Repair logs

System
------
* Pluggable platform for experiments, surveys, etc.
* Flexible user management with groups support
* Elastic permission model
* Continuous Integration test pipeline
* Continuous Deployment pipeline
* Microservices architecture
* REST+JSON and GraphQL versioned API
* Docker deployments


Contact
=======

**Author**
.. csv-table::
    :widths: 15, 65

    "author", "`Matt Harasymczuk <https://www.astronaut.center>`_"
    "email", "book@astronaut.center"
    "www", "https://www.astronaut.center"
    "github", "https://github.com/astromatt"
    "linkedin", "https://linkedin.com/in/mattharasymczuk"
    "facebook", "https://facebook.com/matt.harasymczuk"
    "slideshare", "https://www.slideshare.net/astrotech/presentations"



