Dynamic List Alignment & Dictionary Merger

A Python CLI application designed to dynamically collect user input into two separate lists, validate their lengths, and merge them into a key-value dictionary. It features real-time interactive input loops, list size comparison checks, and an animated console delay before rendering the output data structure.
Core Features

Dynamic Data Ingestion: Uses open-ended input loops allowing users to add as many items as needed for both collections.
Structural Alignment Validation: Programmatically checks if both lists contain the exact same number of items before attempting mapping operations.
Graceful Termination: Instantly halts execution thread operations via system checks if array dimensions do not align, protecting against downstream data mapping corruption.
Animated Visual Delays: Simulates terminal background processing by injecting timed dot indicators precisely one second apart using console flushing.
Parallel Key-Value Mapping: Zips parallel list positions together instantly to create a clean, functional standard dictionary.
System Prerequisites

Python Target Version: Python 3.x or later

Dependencies: Implemented purely using native standard modules (`time` and `sys`). No external pip dependencies are required.

Installation & Setup
Copy the script code and save it to your machine as `merger.py`.
Launch your preferred command line terminal.

Target the execution folder and start the script:
```bash
   python merger.py
   ```

Functional Application Workflow

Populate Keys: Input data elements into the first list until typing `yes` when prompted if you are through.

Populate Values: Repeat the same input collection sequence to build the second data list.


Automated Check: The script automatically compares list sizes.

If sizes mismatch: The application displays `length of lists don't match` and closes.

If sizes match: The program outputs `lengths match. Proceeding...` and displays the final compiled key-value mapping structure.
