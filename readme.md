# Shutdown Timer

This simple script allows you to set a shutdown timer or cancel a scheduled shutdown on Windows and Linux.

## Usage

1. **Set the shutdown timer:**
   - Run the script.
   - Select option 1 from the menu.
   - Enter the shutdown time in the format: `minutes:seconds` (e.g., 2:30).

2. **Cancel shutdown:**
   - Run the script.
   - Select option 2 from the menu.

## Instructions

### Windows

- Run the script with administrative privileges.
- The script uses the `shutdown` command to set or cancel shutdown.
- Invalid inputs are handled, and the user is prompted to select a valid option.

### Linux

- Run the script.
- The script uses the `shutdown` command to set or cancel shutdown.
- Invalid inputs are handled, and the user is prompted to select a valid option.

## Usage Example

### Windows

```powershell
.\shutdown_script.bat
```

### Linux

```bash
./shutdown_script.sh
```

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

