# Pomodoro Timer

A simple and aesthetic Pomodoro Timer application built with Python and Tkinter. This tool helps you stay productive by breaking your work into intervals, traditionally 25 minutes in length, separated by short breaks.

## Features

- **Work Intervals**: 25-minute focused work sessions.
- **Break Cycles**:
  - 5-minute short breaks after each work session.
  - 20-minute long break after every 4 work sessions (8 reps total).
- **Aesthetic UI**: Features a custom pixel-art tomato and the "Minecraftia" font.
- **Session Tracking**: Displays a checkmark (✓) for every completed work interval.
- **Dynamic Updates**: The title and colors change based on whether you are working or taking a break.

## Requirements

- Python 3.x
- Windows (for custom font loading via `ctypes`)
- `Minecraftia-Regular.ttf` (included)
- `pixel-tomato.png` (included)

## How to Run

1. Ensure you have Python installed on your system.
2. Navigate to the project directory.
3. Run the script:
   ```bash
   python main.py
   ```

## Controls

- **START**: Begins the timer and starts the reps.
- **RESET**: Stops the current timer and resets the progress back to zero.

## Screenshots

| Work Phase | Break Phase |
|:----------:|:-----------:|
| ![Work Phase](images/screenshots/Screenshot%202026-02-20%20164909.png) | ![Break Phase](images/screenshots/Screenshot%202026-02-20%20165024.png) |

## Project Structure

- `main.py`: The main application logic and UI setup.
- `Minecraftia-Regular.ttf`: Custom font file used for the UI.
- `pixel-tomato.png`: Pixel art image for the timer background.


