# 🪐 Solar sistem Simulation with NASA SPICE

This project is a 3D visualization of the real orbits of Earth, the Moon, and Jupiter, computed using real telemetry data (kernels) from NASA.


<img width="1200" height="1000" alt="Figure_1" src="https://github.com/user-attachments/assets/c972b526-fea6-40b3-8862-11dc5995bae2" />
<img width="821" height="797" alt="image" src="https://github.com/user-attachments/assets/b5ccf199-0419-4282-b742-e61b3dafc645" />


## Project Features
- **Ephemeris Calculation:** Uses the `spiceypy` library to process `.bsp` kernels and calculate the exact position of celestial bodies (targeting physical bodies, not just barycenters).
- **3D Visualization:** Rendered with `matplotlib` using a dark mode space aesthetic, including a star field background.
- **Real-Time Data:** Connects to the NASA NAIF node to automatically download the most up-to-date orbital data.

## Technologies
- Python
- NASA SPICE Toolkit (SpiceyPy)
- NumPy & Matplotlib
