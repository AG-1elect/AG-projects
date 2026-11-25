# Boost converter: 3.3–4.5 V DC to 9 V at 15 mA

## Specification

| Parameter | Requirement |
|---|---:|
| Input voltage | 3.3–4.5 V DC |
| Output voltage | 9 V DC |
| Output current | 15 mA |
| Output power | 135 mW |

## Notes

- This is a small boost-converter design file.
- Add the exact topology, switching frequency, component values, efficiency, test conditions, and verification results before use.
- Verify the inductor current rating, output capacitor ripple rating, switch current limit, feedback accuracy, start-up behavior, short-circuit behavior, and PCB thermal performance.

## Example design requirements

Use a boost converter that accepts 3.3–4.5 V input and regulates a 9 V output at up to 15 mA. Include input/output decoupling, feedback resistor-divider values, an inductor with suitable current and saturation ratings, and Schottky diode or synchronous rectifier protection where appropriate.

## Safety

This document is not a completed electrical design or a substitute for component datasheets and bench verification.
