# Voltage---Current-Characteristics-of-LED/LASER
# Fiber Optic LED and Photo Detector Characteristics

## AIM
- To study the IV characteristics of fiber optic LED and plot the graph of forward current vs. output optical energy.  
- To study the photo detector response.

---

## EQUIPMENTS REQUIRED
- Link-B Kit with power supply  
- FCL-01 & FCL-02  
- Patch chords  
- 20 MHz Dual Channel Oscilloscope  
- 1 MHz Function Generator  
- 1 Meter Fiber Cable  
- Jumper to Crocodile wires  

---

## THEORY
In an optical fiber communication system, the electrical signal is first converted into an optical signal using an **E/O conversion device** such as an LED. The optical signal is transmitted through the fiber and then retrieved in its original electrical form using an **O/E conversion device** such as a photo detector.

Key points:
- **LEDs**:  
  - Emitters vary due to chip fabrication technologies.  
  - Important parameters: peak wavelength, conversion efficiency, optical rise/fall times, max forward current, forward voltage.  
  - Linear optical output with respect to forward current in a certain region.  

- **Photodetectors**:  
  - Types: photoconductive, photovoltaic, transistor-type, diode-type.  
  - Important parameters: response time, wavelength sensitivity, responsivity.  

- **Numerical Aperture (NA)**:  
  - Defines the acceptance cone of the fiber.  
  - Light must enter within this cone to be transmitted properly; otherwise, it refracts out of the core.  

---

## PROCEDURE
1. Refer to the block diagram and make the connections.  
2. Keep all switch faults in **OFF** position.  
3. Loosen the cap of LED SFH756V (660 nm), insert 1-meter fiber, and tighten.  
4. Loosen the cap of Photo Diode SFH250V, insert fiber end, and tighten.  
5. Set jumpers:  
   - JP1 → short for +12 V  
   - JP2 → sine wave  
   - JP3 → short for +12 V  
   - JP4 → TX1 on FCL-01  
6. Keep switch SW2 in **VI** position on FCL-01.  
7. Connect voltmeter and current meter as per block diagram.  
8. Switch on the power supply.  
9. Set potentiometers:  
   - P3 → maximum (anti-clockwise) → controls LED current  
   - P4 → fully clockwise → controls LED bias voltage  
10. Rotate P3 slowly, measure forward current and voltage, and plot IV characteristics.  
11. For each reading:  
    - Calculate electrical power = \( I \times V \).  
    - Assume efficiency ≈ 1.15% (from datasheet: 200 mW optical power at 10 mA).  
    - Compute optical power coupled into fiber.  
12. Plot:  
    - Forward current vs. optical power of LED.  
    - Receiver current vs. optical power of LED.  
13. Repeat for all transmitter & receiver combinations.  

---

## TABULATION

| Forward Voltage \(V_f\) (V) | Forward Current \(I_f\) (mA) |
|-----------------------------|------------------------------|
|                             |                              |
|                             |                              |
|                             |                              |

---

## MODEL GRAPH
*(Insert IV characteristics graph and optical power plots here)*

---

## RESULT
- The IV characteristics of the fiber optic LED were studied.  
- The graph of forward current vs. optical power was plotted.  
- The photo detector response was analyzed.  
