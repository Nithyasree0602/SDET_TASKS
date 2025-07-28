Installation Issues Faced and Resolutions:

1) Python interpreter not detected in VS Code - The `verify_installation.py` script didn’t execute because the virtual environment was not recognized. 
Clicked the Python interpreter selector in the VS Code status bar  and chose `.venv\Scripts\python.exe`, then restarted the terminal.
2) Interpreter mismatch warning - VS Code was using the global Python interpreter instead of the virtual environment, leading to path-related issues. 
Manually set the interpreter to the virtual environment by selecting `./venv/Scripts/python.exe`, then reloaded the VS Code window.
