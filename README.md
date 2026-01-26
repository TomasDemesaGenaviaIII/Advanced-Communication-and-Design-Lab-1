# Advanced-Communication-and-Design-Lab-1
# EMONA TRAINER 101

---

## Experiment 1 Setting up on Oscilloscope

## INTRODUCTION
An oscilloscope (often called a *scope*) is a test instrument used to **display voltage as a waveform over time**. Instead of only showing a single voltage value (like a multimeter), the oscilloscope lets you *see* how a signal changes, which is essential when working with AC signals and digital pulses.
The Emona Telecomms Trainer 101 is a specialized training platform designed for students and professionals in telecommunications and electronics engineering. It provides a hands-on learning environment that allows users to explore, simulate, and test various telecommunication circuits and systems safely and efficiently. This trainer is widely used in educational institutions to bridge the gap between theoretical concepts and practical implementation in communication systems.
<img width="1026" height="686" alt="image" src="https://github.com/user-attachments/assets/d36247e0-f192-4806-ab0e-c57d6ef3a08e" />
<img width="2050" height="1701" alt="image" src="https://github.com/user-attachments/assets/0d7252f2-4c7d-400b-8d10-afdd5e89e90c" />


## OBJECTIVES
1. To understand the visual representation of voltage (amplitude) and time (period/frequency) on a display.
2. To measure the **peak-to-peak voltage** of the oscilloscope’s CAL signal.
3.  To practice proper oscilloscope handling (intensity, focus, triggering, coupling).
4.  To identify and correctly adjust general, vertical, horizontal, and triggering controls.

## MATERIALS
1. EMONA BISKIT
2. OSCILLOSCOP

## CIRCUIT DIAGRAM
<img width="331" height="305" alt="image" src="https://github.com/user-attachments/assets/e3b1370b-47fb-4b6a-ae95-dbaae0019fb1" />

## PROCEDURES
  > 1. General Controls:
  
    1. Set the Intensity control to about three-quarters of its travel.
    2. Set the Mode control to the CH1 (or CHA) position.

  > 2. Vertical Controls:

    1. Set the Input Coupling control for both channels to the AC position.
    2. Set the Vertical Attenuation control for both channels to the 1V/div position.
    3. Set the Vertical Attenuation Calibration control for both channels to the detent (locked) position.
    4. Set the Vertical Position control for both channels to about the middle of their travel.

   > 3. Horizontal Controls:

     1. Set the Horizontal Timebase control to the 0.5ms/div position.
     2. Set the Horizontal Timebase Calibration control to the detent (locked) position.
     3. Set the Horizontal Position control to about the middle of its travel.

  > 4. Triggering Controls:

      1. Set the Sweep Mode control to the AUTO position.
      2. Set the Trigger Level control to the detent (locked) position (or middle of travel).
      3. Set the Trigger Source control to the CH1 (or INT) position.
      4. Set the Trigger Source Coupling control to the AC position.
      4. Set the Slope (or Sync) control to the "+" position.

  > 5. Powering Up and Testing:

      1. Switched on the scope and allowed it to warm up for approximately 30 seconds until a trace appeared.
      2. Adjusted the Intensity and Focus controls to ensure the trace was sharp and at an appropriate brightness.
      3. Connected the Channel 1 input to the scope's CAL output using the oscilloscope lead.
      4. Verified that a stable square wave appeared on the display, confirming the scope was ready for measurement.

  ## DISCUSSION AND LEARNING

To set up an oscilloscope for use with the Emona Telecoms-Trainer 101, you must first establish a common reference by inserting the black ground plugs of the oscilloscope leads into any available ground (GND) socket on the trainer board. For initial signal verification, connect the first channel of the scope to a known source, such as the 2kHz SINE output in the Master Signals module, and ensure the Trigger Source is set to CH1 (or INT) to stabilize the display. Begin with the scope's Mode control on CH1 and adjust the Timebase until two or three complete cycles of the waveform are clearly visible on the screen.

-----------

## Experiment 2 An introduction to the Telecoms-Trainer 101


    
     

