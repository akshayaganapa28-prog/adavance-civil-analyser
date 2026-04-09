# Civil Analysis System 🏗️

## Overview
Advanced Civil Analysis System is a desktop GUI application built with Python and Tkinter. It helps civil engineers quickly assess if construction materials (Concrete, Steel, Brick, Cement) meet quality standards by checking key properties against predefined acceptable ranges.

## Features
- **Material Selection**: Choose from Concrete, Steel, Brick, or Cement.
- **Dynamic Fields**: Input fields update automatically based on selected material, showing acceptable ranges.
- **Instant Analysis**: Click "Analyze" to validate inputs. Green ✅ for SAFE, Red ❌ for issues with details.
- **Standalone**: No external dependencies – runs on any Python 3+ system with Tkinter (standard library).

## Quick Demo
```
Select Material → Enter Property Values → Analyze → See PASS/FAIL
```

*(Add screenshot here: Run the app and capture the GUI in action)*

## How to Run
1. Ensure Python 3 is installed (Tkinter included).
2. Open terminal in this directory.
3. Run:
   ```
   python civil2.py
   ```

## Usage
1. Launch the app.
2. Select a material from the dropdown.
3. Enter numeric values for each property (within suggested ranges shown).
4. Click **Analyze**.
5. Review result: SAFE if all values pass, else see specific failures.

## Material Properties & Ranges

| Material | Property              | Range          | Unit    |
|----------|-----------------------|----------------|---------|
| **Concrete** | Compressive Strength | 20 - 40       | MPa    |
|             | Tensile Strength     | 2 - 5         | MPa    |
|             | Durability           | 5 - 10        |         |
|             | Workability          | 25 - 100      | mm     |
| **Steel**    | Tensile Strength     | 400 - 600     | MPa    |
|             | Yield Strength       | 250 - 500     | MPa    |
|             | Ductility            | 10 - 25       | %      |
|             | Hardness             | 120 - 200     | HB     |
| **Brick**    | Compressive Strength | 7 - 20        | MPa    |
|             | Water Absorption     | 10 - 20       | %      |
|             | Hardness             | 5 - 10        |         |
|             | Shape Quality        | 5 - 10        |         |
| **Cement**   | Compressive Strength | 20 - 50       | MPa    |
|             | Setting Time         | 30 - 600      | min    |
|             | Fineness             | 225 - 400     |         |
|             | Soundness            | 0 - 10        | mm     |

## Limitations
- Basic range checks only (no advanced calculations).
- No data persistence (results not saved).
- Desktop-only (no web/mobile).

## Future Enhancements
- Save/load test results to CSV.
- Add more materials and properties.
- Integrate real standards (e.g., ASTM, IS codes).
- Visual charts for results.

## License
MIT License – feel free to use and modify.

