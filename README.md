# Sensor Signal Processing and Visualization Tool

This project demonstrates a Python-based tool for visualizing, filtering, and analyzing sensor signals using a custom GUI built with `customtkinter` and Matplotlib. The application provides dynamic noise addition, signal filtering, and Discrete Fourier Transform (DFT) analysis.

## Authors
1. **Akhmad Maulvin Nazir Zakaria** (2042231028)
2. **Dwi Oktavianto Wahyu Nugroho** (Supervisor)

### Teknik Instrumentasi - Institut Teknologi Sepuluh Nopember

## Features

1. **Signal Visualization**: Graphical display of sensor signals from various models, including noise-affected signals.
2. **Dynamic Noise Addition**: Adjustable amplitude and frequency sliders for generating and adding noise to sensor signals.
3. **Signal Filtering**:
   - Low Pass Filter
   - Moving Average Filter
4. **Fourier Analysis**: Perform and visualize the Discrete Fourier Transform (DFT) on both raw and filtered signals.
5. **Sensor Models**: Predefined mathematical models for gas, smoke, flame, voltage, and infrared signals.

## Requirements

### Software
- Python 3

### Libraries
Install the required libraries using pip:
```bash
pip install customtkinter matplotlib numpy scipy
```

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/mauldevrinz/Sensor_Graphc_Visualization.git
cd Sensor_Graphc_Visualization
```

### 2. Run the Application
Run the application using Python:
```bash
python3 ctk.py
```

## Usage

### GUI Layout
- **Sensor Selection**: Use the radio buttons to select the desired sensor signal model.
- **Control Panel**: Adjust noise amplitude and frequency using the sliders.
- **Signal Display**: View the original, noise-affected, and filtered signals in separate plots.
- **Filter Buttons**: Apply Low Pass or Moving Average filters to the noisy signal.
- **Fourier Analysis**: Perform DFT on raw or filtered signals and visualize the frequency domain data.

### Sensor Models
1. **Gas Sensor**: Simulates a gas sensor signal.
2. **Smoke Sensor**: Generates a smoke sensor signal.
3. **Flame Sensor**: Represents flame detection signal.
4. **Voltage Sensor**: Simulates AC voltage waveform.
5. **Infrared Sensor**: Models an IR sensor signal.

## Example Screenshots
### Main GUI
![GUI Screenshot](https://github.com/mauldevrinz/Sensor_Graphc_Visualization/blob/main/GUI_VISUALIZATION.png)

### DFT Analysis
![DFT Screenshot](https://github.com/mauldevrinz/Sensor_Graphc_Visualization/blob/main/DFT_VISUALIZATION.png)

## Future Enhancements
1. Expand to include real-time data acquisition from physical sensors.
2. Add more advanced filtering techniques (e.g., Bandpass, Kalman filters).
3. Enable saving and exporting processed signals and analyses.

## Contributors
- Contributions are welcome! Feel free to submit a pull request or open an issue.

---

This project is a practical tool for students and researchers in signal processing and instrumentation. Developed for educational purposes, it showcases fundamental techniques in signal generation, noise addition, filtering, and spectral analysis.

