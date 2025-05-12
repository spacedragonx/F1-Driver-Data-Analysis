
# F1 Miami 2025 - Data Analysis Project
This project leverages the FastF1 Python library to analyze and visualize telemetry and lap data from the 2025 Formula 1 Miami Grand Prix. The analysis includes driver performance comparisons, racing line visualizations, speed mapping, and animated ghost laps.
#
📊 Sample Visuals

📈 Race position evolution

🌀 Speed-colored racing lines

🧭 Side-by-side driving comparison

#
✅ Requirements

Python 3.8+

fastf1

pandas

matplotlib

numpy
#
📁 Project Features

1. Race Position Evolution
Tracks and visualizes the race position of all drivers throughout the Grand Prix using a step plot. Helpful for understanding race dynamics like overtakes, pit strategies, and consistency.

2. Colored Racing Line (Telemetry-Based)
Draws the racing line of drivers on the circuit map, color-coded by speed. Each segment between GPS points is colored to reflect the driver’s speed at that point.

3. Side-by-Side Racing Line Comparison
Plots the racing lines of two drivers (e.g., VER vs. LEC) in separate subplots to visually compare their line choices and speed patterns through the corners.

5. Multi-Driver Position Comparison
Builds a dataframe of race positions for all drivers and plots each line in a wide range of unique colors for clear visibility.

#
📌 Notes

FastF1 supports Qualifying, Practice, and Race sessions.

Accuracy of ghost laps and interpolation may vary by driver telemetry completeness.

Use pick_fastest() or pick_lap() to select reference laps.

#
🔗 Resources

FastF1 Documentation

Matplotlib Docs

F1 Timing Data provided by ergast.com


## Screenshots

![App Screenshot](https://github.com/spacedragonx/F1-Driver-Data-Analysis/blob/main/posi.png?raw=true)

# 
Race line conparision
![App Screenshot](https://github.com/spacedragonx/F1-Driver-Data-Analysis/blob/main/RacingLineComparision.png?raw=true)

Max speed of Verstappen in Turn 9: 302.0

Max speed of Leclerc in Turn 9: 318.0

Leclercs Racing line is better with more speed in and out of the corner than Verstappen's.

# 
Pit-stop strategies

![App Screenshot](https://github.com/spacedragonx/F1-Driver-Data-Analysis/blob/main/PitStrategy.png?raw=true)


