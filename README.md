# Design of a Portable Monitor

A low-cost portable monitor prototype developed as an open-ended project for the EEE 406 Microprocessor and Embedded System Laboratory course.

![Portable Monitor Prototype](images/prototype-front.jpg)

## Project Overview

This project presents the design, development, assembly, and testing of a portable monitor prototype. The system uses an LCD panel, a compatible display driver board, a power adapter, OSD control buttons, and a custom PVC-board enclosure.

## Objectives

- To design a functional portable monitor prototype.
- To select a compatible LCD panel and display driver board.
- To develop a lightweight and low-cost enclosure.
- To test the display output and physical control buttons.
- To analyse the technical and economic feasibility of the project.

## Main Features

- Compact LCD display
- HDMI video input
- Physical OSD control buttons
- Brightness and contrast adjustment
- PVC-board enclosure
- Lightweight and portable design
- Low prototype cost

## Hardware Components

| No. | Component | Quantity | Cost (BDT) |
|---:|---|---:|---:|
| 1 | LCD Display | 1 | 1,650 |
| 2 | Display Driver Board | 1 | 1,700 |
| 3 | Power Adapter | 1 | 100 |
| 4 | PVC Enclosure | 1 | 500 |
| 5 | Cables and Connectors | 1 set | 90 |
| 6 | Transportation | — | 800 |
|  | **Total Cost** |  | **4,820** |

## System Block Diagram

![System Block Diagram](design/system-block-diagram.png)

## Working Principle

A laptop or another source device sends a video signal to the display driver board through an HDMI cable. The driver board processes the input signal and controls the LCD panel. The power adapter supplies power to the driver board and display. The OSD buttons allow the user to control power, brightness, contrast, volume, menu options, and input selection.

## Prototype Images

### Front View

![Front View](images/prototype-front.jpg)

### Internal Connection

![Internal Connection](images/internal-connection.jpg)

### Final Output

![Final Output](images/final-output.jpg)

## Documentation

- [Experiment 9 Portable Monitor Report](docs/Experiment-09-Portable-Monitor-Report.pdf)
- [Bill of Materials](data/bill-of-materials.csv)
- [Test Results](data/test-results.csv)

## Repository Structure

```text
Design-of-a-Portable-Monitor/
├── README.md
├── LICENSE
├── docs/
├── images/
├── design/
└── data/
