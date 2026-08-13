Wearable EMG Sensor Enclosure

Overview
A wearable SolidWorks enclosure for an Arduino Uno and MyoWare 2.0 muscle sensor, designed to be worn on the arm during live EMG signal acquisition rather than used purely as a storage case.

Design

- Wearability — chose an operating housing (worn during use) over a protective case, since the goal was to support live signal acquisition, not just transport the electronics.
- Two-compartment layout — a square compartment at the base holds the Arduino Uno and straps directly to the arm; a triangular compartment above rests the MyoWare 2.0 when it's not in use. The triangular pocket is form-matched to the MyoWare's actual board shape, including its rounded corners.
- Wire routing — pass-through slots connect the two compartments (3mm center hole, 5mm outer two) so the MyoWare's signal leads can run to the Arduino while the sensor itself is removed and adhered to the skin.
- Snap-fit lid — chosen for quick access without hardware, balanced against the enclosure needing to stay secure during arm movement.
- Strap channels - exists on the base compartment for arm mounting; USB cutout for power/data access without opening the enclosure.

Design Notes / Iteration
Initial compartment dimensions were sized before double-checking the Arduino Uno's actual footprint against the datasheet — caught partway through modeling that the base compartment was undersized and corrected it before finalizing the design.

Files
- `EMG casing.SLDPRT` — base compartment (Uno + MyoWare pockets)
- `EMG casing lid.SLPRT` — snap-fit lid
- `FULL EMG enclosure.SLDASM` — full assembly
- `FULL EMG enclosure casing - EMG casing-1.STL` — exported STL of the base
- `FULL EMG enclosure ca...- EMG casing lid-1.STL` — exported STL of the lid
- `images/` — renders and concept sketch
