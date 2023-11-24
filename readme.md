# Shutdown Timer

This simple Windows batch script allows you to set a shutdown timer or cancel a scheduled shutdown. 

## Usage

1. **Set the shutdown timer:**
   - Run the script.
   - Select option 1 from the menu.
   - Enter the shutdown time in the format: `minutes:seconds` (e.g., 2:30).

2. **Cancel shutdown:**
   - Run the script.
   - Select option 2 from the menu.

## Instructions

- Ensure you are running the script with administrative privileges.
- The script uses the `shutdown` command to set or cancel shutdown. 
- Invalid inputs are handled, and the user is prompted to select a valid option.

## Usage Example

```bash
$ ./shutdown_script.bat
```
