# wireless-network-simulation
RF spectrogram dataset generation for wireless network simulation

This project contains a Python-based simulation framework for generating RF spectrogram datasets from simulated wireless network scenarios.

The simulation includes four transmitter types:
- Static stations
- Low-mobility objects / pedestrians
- Medium-mobility objects / vehicles
- High-mobility objects / aircraft

Each scenario is generated in a 3D environment with a single receiver located at the origin. The received signal includes QPSK transmissions, Free Space Path Loss, Doppler shift, AWGN, and statistical fading/multipath.

For each scenario, the simulator saves:
- A sequence of spectrogram images
- RSSI values over time
- A 2D scene map
- Metadata with the true labels and simulation parameters

The dataset can be used for RF-based object classification and counting tasks.

## Repository Structure

- `code/` - Python simulation code
- `data_samples/` - Representative examples from the generated dataset
- `README.md` - Project description

## Full Dataset

The full generated dataset is available in the Releases section of this repository under the release titled "Full Dataset".
