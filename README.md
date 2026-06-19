# Restaurant Ordering App

A simple Tkinter-based GUI application for ordering bread and spread combinations with automatic tax calculation and CSV order saving.

## Quick Start

### Option 1: Run Without Python (Recommended)

Download the executable file:
- **Restaurant_Ordering_App.exe**

**Important Security Notice:**
Your security software (Windows Defender, antivirus, etc.) may block or warn about the executable because it's a newly created, unsigned application. This is normal for PyInstaller-built executables.

If you see a security warning:
1. Right-click the `.exe` file → "Properties"
2. Click "Unblock" at the bottom (if available)
3. Click "Run as administrator" if prompted
4. Accept the download/run when your security software asks

The app will run without needing Python or any IDE installed.

### Option 2: Run with Python

Download the source code:
- **Restaurant_Ordering_App.py**

Then open it in your preferred IDE (VS Code, PyCharm, etc.) and run it. You'll need Python 3.x installed with no additional packages required (uses only standard library: tkinter, csv, pathlib).

## Features

- Select bread type (Toast, English Muffin, Bagel)
- Select spread type (Plain, Honey, Strawberry Jam, Grape Jam, Rhubarb Jam)
- Add items to cart with running totals
- Automatic 6% sales tax calculation
- Save orders to CSV file (orders.csv)
- Clear order functionality
- Confirmation dialog before placing order

## Requirements

- **For .exe**: Windows 10/11 (no Python needed)
- **For .py**: Python 3.x (standard library only - no pip install needed)

## Files

| File | Description |
|------|-------------|
| `Restaurant_Ordering_App.exe` | Standalone Windows executable (PyInstaller) |
| `Restaurant_Ordering_App.py` | Python source code |
| `orders.csv` | Order data (created when you save an order) |

## License

Feel free to use, modify, and share this application.

---

Made with Python and Tkinter
