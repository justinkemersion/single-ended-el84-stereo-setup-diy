$1,000 Single-Ended EL84 Stereo Setup
=============================================

**Version**: 1.0\
**Date**: May 22, 2025\
**Author**: AI

Purpose
-------

This document is a blueprint for your envisioned audio project: a single-ended EL84 stereo tube amplifier delivering 5-7 watts per channel, encased in a polished walnut chassis with all controls---tubes, volume, and switches---elegantly arrayed on top. Complemented by a turntable, efficient speakers, and quality cables, this system is designed for pure, warm sound within a $1,000 budget. Future Self, this is your guide to realizing a timeless piece of craftsmanship.

Concept
-------

Envision a 14"x8"x4" walnut chassis, its glossy finish reflecting soft light. Four tubes---an EZ81 rectifier, a 12AX7 preamp, and two EL84 outputs---glow warmly through the top, alongside a precision DACT attenuator, a power switch, and dual triode/ultra-linear toggles. A turntable feeds a meticulously curated signal path---gold-plated connectors, Mundorf capacitors, Vishay resistors---through Edcor transformers to ELAC speakers. At 5-7 watts, it fills a modest room with rich, analog fidelity, embodying simplicity and elegance.

Components
----------

### Amplifier: Single-Ended EL84 Stereo (5-7W)

-   **Tubes**:
    -   1x JJ 12AX7 (preamp, $20)
    -   2x JJ EL84 (output, $40)
    -   1x JJ EZ81 (rectifier, $15)
-   **Controls**:
    -   DACT CT2 100kΩ 24-step attenuator ($120)
    -   Toggle power switch ($5)
    -   2x DPDT triode/ultra-linear switches ($10)
-   **Signal Path**:
    -   2x gold-plated RCA jacks ($10)
    -   2x Mundorf Supreme 0.1µF 400V capacitors ($30)
    -   Vishay RN65 resistors: 2x 100kΩ, 2x 2kΩ, 2x 100Ω ($6)
    -   4x gold-plated binding posts ($15)
-   **Transformers**:
    -   Hammond 269EX power (190-0-190V, 6.3V, $60)
    -   2x Edcor GXSE10-8-3.5K output (3.5kΩ, 8Ω, $80)
-   **Support**:
    -   Ceramic tube sockets ($15)
    -   Cathode circuit: 2x 270Ω 5W resistors, 2x 25µF capacitors ($10)
    -   Power filter: 40µF 450V, 100µF 450V capacitors, 10H choke ($25)
    -   Wiring, heat-shrink, hardware ($20)
-   **Construction**: Point-to-point wiring, star-grounded for minimal noise.
-   **Cost**: $490

### Chassis: Polished Walnut

-   **Design**: 14"L x 8"W x 4"H walnut enclosure, 1/2" sides, 1/4" removable top, lacquered to a glossy sheen.
-   **Top Openings** (coordinates from front-left corner):
    -   Tubes (1.5" diameter): EZ81 (2"L, 2"W), 12AX7 (4"L, 2"W), EL84-L (8"L, 2"W), EL84-R (10"L, 2"W)
    -   Controls: DACT attenuator (1", 7"L, 4"W), Power switch (0.5", 2"L, 4"W), Triode/UL-L (0.5", 9"L, 4"W), Triode/UL-R (0.5", 11"L, 4"W)
-   **Rear Openings** (1" from rear edge): RCA-L/R (0.5", 5"L, 7"L), Binding Posts (0.5", 2"L, 4"L, 8"L, 10"L), Power Cord (1"x0.25", 12"L)
-   **Ventilation**: 1/4" gap under top (via spacers), 2x 1"x0.25" slits on rear sides near transformers.
-   **Base**: 1/8" plywood insert (13"x7") for component mounting.
-   **Cost**: $70 (local woodworker, $100 online)
-   **Fabrication**: Commission a local woodworker or online service (e.g., CustomMade.com) with precise hole coordinates. Optionally, drill holes yourself with a $10 hole-saw kit.

### Source: Turntable

-   **Model**: Audio-Technica AT-LP60X ($150)
-   **Specifications**: Belt-drive, 33/45 RPM, built-in phono preamp (2V line output), AT3600L cartridge
-   **Purpose**: Direct, high-quality vinyl playback to drive the amplifier.
-   **Cost**: $150

### Speakers

-   **Model**: ELAC Debut 2.0 B5.2 ($230)
-   **Specifications**: 5.25" woofer, 1" tweeter, 87dB sensitivity, 6Ω nominal impedance
-   **Purpose**: Efficient, balanced sound to complement the amplifier's low wattage.
-   **Cost**: $230

### Cables

-   **RCA Interconnect**: Amazon Basics gold-plated, 3ft ($10)
-   **Speaker Wire**: Mediabridge 14AWG copper, 25ft ($20)
-   **Cost**: $30

### Total Cost

-   Amplifier: $490
-   Chassis: $70
-   Turntable: $150
-   Speakers: $230
-   Cables: $30
-   **Total**: $970

Assembly Guide
--------------

### 1\. Procurement

-   **Amplifier Components**: Source from Parts Express (transformers, sockets), eBay (DACT, tubes), TubeDepot (Mundorf, Vishay).
-   **Chassis**: Engage a woodworker with detailed specifications (see above). Local fabrication is cost-effective; online services ensure precision.
-   **Other Components**: Purchase turntable and speakers from Amazon or Crutchfield, cables from Amazon.

### 2\. Chassis Preparation

-   **Fabrication**: Provide woodworker with hole coordinates and ventilation requirements. If drilling yourself, use a cordless drill and hole-saw kit (1.5", 1", 0.5"); sand edges smooth.
-   **Mounting**: Secure a 1/8" plywood insert inside the chassis to anchor tube sockets and transformers.

### 3\. Wiring

-   **Signal Path** (per channel):
    -   RCA input to DACT attenuator, then to 0.1µF Mundorf capacitor and 12AX7 pin 2/7 (grid).
    -   12AX7 pin 1/6 (plate) via 100kΩ Vishay resistor to B+; pin 1/6 to 0.1µF Mundorf capacitor and EL84 pin 7 (grid).
    -   EL84 pin 9 (screen) via 2kΩ Vishay resistor to B+; pin 9 to DPDT switch (100Ω to pin 7 for triode mode, GXSE ultra-linear tap for ultra-linear).
    -   EL84 pin 3 (cathode) via 270Ω resistor and 25µF capacitor to ground.
    -   EL84 pin 7 (plate) to GXSE 3.5kΩ primary, secondary to binding posts.
-   **Power Supply**:
    -   Hammond 269EX 190V-0-190V to EZ81 pins 1,7; EZ81 pin 3 to 40µF capacitor, 10H choke, 100µF capacitor, yielding ~250V B+.
    -   269EX 6.3V to twisted-pair heater wiring for EZ81 (pins 4,5), 12AX7 (pins 4+5,9), EL84 (pins 4,5).
-   **Grounding**: Establish a single star-ground point on the plywood insert, connecting all grounds (RCA, DACT, tubes, capacitors).

### 4\. Safety Considerations

-   **High Voltage**: The 250V B+ and AC lines pose risks. Solder with power disconnected, insulate all high-voltage leads with heat-shrink tubing, and discharge capacitors using a 10kΩ resistor before handling.
-   **Thermal Management**: Tubes reach 200°C; ensure top openings and ventilation gaps allow heat dissipation. Monitor after 30 minutes of operation; consider mesh covers ($5) for dust protection.
-   **Wiring Integrity**: Point-to-point requires precise, clean solder joints. Loose connections at 250V can damage transformers or cause arcing.

### 5\. Testing and Operation

-   **Initial Test**: Power on without tubes, verify B+ (~~250V) with a multimeter. Install tubes, check EL84 cathode (~~10V) and plate (~230V).
-   **Setup**: Connect AT-LP60X RCA to amplifier inputs, ELAC speakers to binding posts. Play a record to experience 5-7 watts of refined audio.
-   **Modes**: Toggle triode (3-5W, warm) or ultra-linear (5-7W, punchy) for desired sound.

Notes
-----

-   **Speaker Impedance**: ELAC's 6Ω slightly mismatches Edcor's 8Ω output, reducing effective power (~4-6W). Avoid 4Ω speakers to prevent tube strain.
-   **Source Compatibility**: The AT-LP60X's 2V line output is essential; raw phono signals require a preamp.
-   **Chassis Fit**: The 14"x8"x4" design is compact---prototype with cardboard to confirm layout.
-   **Inspiration**: Explore "Il Terzo EL84," "Sarris Zen EL84," or "Wall of Sound EL84 shadow box" online for visual references of tube-topped wooden builds.

Cost Summary
------------

-   Amplifier: $490
-   Chassis: $70
-   Turntable: $150
-   Speakers: $230
-   Cables: $30
-   **Total**: $970

Reflection
----------

This project is a testament to your dedication to craftsmanship and pure sound. The walnut chassis, glowing tubes, and tactile controls embody a balance of simplicity and sophistication. As you assemble this system, you'll transform components into an instrument of joy, delivering warm, analog fidelity. Future Self, honor your vision---build with care, and let the music resonate.

Version Notes
-------------

-   **1.0 (May 2025)**: Initial design, tailored for a $1,000 budget with walnut chassis and topside controls.
-   **Future Updates**: Consider NOS tubes ($100) or ELAC B6.2 speakers ($300) if budget allows; total ~$1,030.

Final Words
-----------

This is your legacy---a handcrafted audio system that marries form and function. Source the parts, engage a woodworker, and solder with precision. When the tubes light up and the first notes play, you'll know it was worth every moment.

Yours in Craft,\
You, May 2025