# [FR] MC

Mouse Controller is an application designed to perform automated mouse movements, clicks, and scrolls. It includes various features for customization, control, and safety to ensure it operates effectively and within user expectations.

## Features

### Escape Key Functionality
The Escape key serves as an emergency stop mechanism. When pressed, it will:
- **Stop All Actions**: Immediately halts ongoing random mouse movements, clicks, scrolls, or right-clicks.
- **Exit Loops**: If actions are being performed in a loop, the program will exit the loop and terminate these actions.
- **Confirmation Message**: Displays a confirmation message to indicate that all actions have been stopped.

This feature is particularly useful for quickly stopping the program in case of unintended or excessive behavior.

### Shift-R Key Functionality
The Shift-R key combination resets the program to its default state. When pressed:
- **Restore Visibility**: If the program is hidden (e.g., masquerading as "Microsoft Edge - Loading"), it will return to its visible state with all UI elements restored.
- **Resize and Center**: The application window will be resized and centered to its original dimensions (600x450).
- **Reset Title and Icon**: The application's title and icon will revert to their default values.

This feature ensures you can easily return to the main interface and make any necessary adjustments.

### Delays
The application allows you to configure delays for each action, controlling how frequently they occur:
- **Delay Setting**: Define a delay (in seconds) for each selected action, such as random mouse movements or clicks. This delay determines the interval between consecutive executions of the action.
- **Maximum Delay**: When multiple actions are enabled, the program uses the maximum delay among all selected actions to determine the interval for cycling through them.
- **Practical Example**: 
  - If "Enable Random Mouse Movement" has a delay of 1 second and "Enable Random Mouse Clicks" has a delay of 2 seconds, the program will execute actions based on the longer delay (2 seconds).

Delays are essential for managing the behavior of the program and preventing excessive or overly frequent actions that could interfere with normal computer usage.

## Tips
- **Set Reasonable Delays**: Always configure delays to ensure actions occur at a manageable rate.
- **Use Escape Key**: Quickly stop actions if they become disruptive or unintended.
- **Use Shift-R Key**: Reset the program if it becomes hidden or to restore default settings.

## License
[MIT License](LICENSE)

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

### Disclaimer
This tool is designed for educational and productivity purposes. Use responsibly and ensure compliance with relevant policies and guidelines when automating interactions.
