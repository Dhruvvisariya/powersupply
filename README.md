# 5V DC Power Supply using 9V Transformer, Bridge Rectifier, and LM7805 IC

This project involves building a 5V DC power supply using a 9V transformer, a bridge rectifier, and an LM7805 voltage regulator IC. This power supply can be used to provide a stable 5V output for various electronic projects and development boards.

## Table of Contents

- [Introduction](#introduction)
- [Components Needed](#components-needed)
- [Circuit Diagram](#circuit-diagram)
- [Assembly Instructions](#assembly-instructions)
- [Testing and Verification](#testing-and-verification)
- [Applications](#applications)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to design and build a simple yet effective 5V DC power supply. The power supply uses a 9V transformer to step down the voltage from the mains, a bridge rectifier to convert AC to DC, and an LM7805 IC to regulate the output to a constant 5V DC. This power supply is ideal for powering microcontrollers and other 5V electronic devices.

## Components Needed

- 9V Transformer
- Bridge Rectifier (4 diodes or a single integrated bridge rectifier)
- Smoothing Capacitors (e.g., 1000µF, 10µF)
- LM7805 Voltage Regulator IC
- Heat Sink for LM7805 (optional but recommended)
- Resistors (as needed for any additional filtering)
- Connecting wires
- Soldering tools and accessories
- Development board (for testing)

## Circuit Diagram

![1718285607001](https://github.com/Dhruvvisariya/powersupply/assets/98723934/0fecbb22-fae3-4d6a-baf1-33c7805eef5c)


## Assembly Instructions

1. **Transformer Connection**:
   - Connect the primary side of the 9V transformer to the AC mains supply.
   - Connect the secondary side of the transformer to the input of the bridge rectifier.

2. **Bridge Rectifier**:
   - Assemble the bridge rectifier using four diodes or a single integrated bridge rectifier.
   - Connect the AC inputs from the transformer to the AC terminals of the rectifier.
   - The rectifier will convert the AC voltage to a pulsating DC voltage.

3. **Smoothing Capacitors**:
   - Connect a large electrolytic capacitor (e.g., 1000µF) across the output of the bridge rectifier to smooth the pulsating DC voltage.
   - Add a smaller capacitor (e.g., 10µF) in parallel for additional filtering.

4. **Voltage Regulation**:
   - Connect the output of the bridge rectifier to the input pin of the LM7805 voltage regulator IC.
   - Connect the ground pin of the LM7805 to the common ground of the circuit.
   - Connect the output pin of the LM7805 to the output terminals where you need a stable 5V DC supply.

5. **Heat Sink (optional)**:
   - If the LM7805 IC gets too hot during operation, attach a heat sink to it to dissipate heat.

6. **Final Connections**:
   - Connect the 5V output to the development board or the device you intend to power.

## Testing and Verification

1. **Initial Testing**:
   - Before powering up the circuit, double-check all connections for correctness.
   - Ensure that there are no short circuits or loose connections.

2. **Power On**:
   - Connect the transformer to the AC mains supply and power on the circuit.
   - Use a multimeter to measure the output voltage at the 5V terminals.

3. **Verification**:
   - Verify that the output voltage is a stable 5V DC.
   - Test the power supply by connecting it to a development board or other 5V electronic devices.

## Applications

- Powering microcontroller development boards (e.g., Arduino, ESP8266)
- Supplying 5V to various electronic circuits and projects
- Educational projects for understanding power supply design

## Contributing

Contributions are welcome! If you have suggestions or improvements, please create an issue or submit a pull request.

---

This README provides an overview of the 5V DC Power Supply project, including setup instructions and usage guidelines. Insert images in the specified spaces to enhance the documentation.
