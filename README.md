# Pomodoro Timer

This is a simple **Pomodoro Timer** application built using Python's `tkinter` library. The Pomodoro technique is a time management method that uses work intervals followed by short and long breaks to enhance productivity.

## Features

- **Work Timer**: A timer for focused work sessions.
- **Short Break Timer**: After a work session, a short break is given.
- **Long Break Timer**: After several work sessions, a longer break is provided.
- **Visual Feedback**: A dynamic countdown with a tomato-themed user interface.
- **Progress Tracking**: Checkmarks indicate completed work sessions.

## Project Structure

- **Main Script**: The main script contains the timer logic and UI setup.
- **Assets**: The image of a tomato (`tomato.png`) is used as part of the UI.

## Requirements

- Python 3.x
- `tkinter` library (comes pre-installed with most Python distributions)
- A `tomato.png` image in the same directory as the script.

## How to Run

1. Clone this repository or download the Python file.
2. Ensure that you have the `tomato.png` file in the same directory as the script.
3. Run the Python file:
    ```bash
    python pomodoro_timer.py
    ```

## Application Behavior

- **Work Session**: Default length is set to 1 minute.
- **Short Break**: After each work session (except for the 8th session), a short break of 1 minute occurs.
- **Long Break**: After 4 work sessions, a longer break of 3 minutes occurs.
- **Checkmarks**: A checkmark ("✔") appears after every short break, indicating a completed work session.

## Customization

You can customize the timer lengths by modifying these constants in the script:

```python
WORK_MIN = 25      # Work session length (minutes)
SHORT_BREAK_MIN = 5 # Short break length (minutes)
LONG_BREAK_MIN = 20  # Long break length (minutes)
