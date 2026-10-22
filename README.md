# Smart Charging Station Manager

**Student:** Meryl Binu  
**Roll No.:** 11  
**Course:** Data Structures and Algorithm  
**Institution:** Amal Jyothi College of Engineering, Kanjirappally

## Project overview
Smart Charging Station Manager is a browser-based mini project for managing electric-vehicle charging slots. It demonstrates how arrays, a FIFO queue, searching, and basic algorithms can be used to organize a small EV charging station.

## Features
- Dashboard with total, available, and occupied charging slots.
- Vehicle registration with battery level, battery capacity, charging rate, and priority.
- Automatic allocation to an available slot.
- FIFO waiting queue when all slots are occupied.
- Complete a charging session and automatically allocate the newly free slot to the next vehicle.
- Search vehicle records by registration number or status.
- Estimated charging time and estimated charging cost (illustrative rate: ₹8.50 per kWh).
- Browser Local Storage to retain demo data after refresh.
- Responsive layout for desktop and mobile.
- Demo data on first launch; reset button restores a clean demo state.

## Technologies
- HTML5
- CSS3
- Vanilla JavaScript
- Browser Local Storage

## Data structures used
1. **Array:** stores the six charging slots and the vehicle records.
2. **Queue (FIFO):** stores vehicle IDs waiting for a free slot. The earliest arrival is served first.
3. **Searching:** filters registered vehicle records by registration number, status, or slot.
4. **Basic algorithms:** slot allocation, charging-time estimation, energy estimation, and cost estimation.

## How to run
1. Download or clone this repository.
2. Keep `index.html`, `style.css`, and `script.js` in the same folder.
3. Double-click `index.html` to open it in a modern browser.
4. Use **Vehicle manager → Register vehicle** to add a vehicle.
5. Complete a charging session from a slot card or vehicle record to free the slot and serve the next queued vehicle.

No server, package installation, or API key is required.

## Project files
- `index.html` — page structure and dashboard sections.
- `style.css` — responsive styling and visual theme.
- `script.js` — data structures, allocation logic, search, storage, and UI rendering.
- `Project_Report.docx` — editable project report.
- `Project_Report.pdf` — report in PDF format.
- `output_preview.png` — illustrative dashboard preview.

## Assumptions and limitations
- This is an academic prototype; it does not connect to real charging hardware.
- Charging completion is triggered manually for demonstration.
- Charging time is an estimate based on remaining energy and selected charging rate; real-world charging curves and losses are not modeled.
- Cost uses an illustrative fixed rate of ₹8.50/kWh and is not a live tariff.
- Data is stored in the current browser profile, not a shared online database.
- The high-priority option is recorded and displayed, while slot allocation remains FIFO to preserve the assignment's queue demonstration.

## Future enhancements
- Backend database and user authentication.
- Real charger telemetry and automatic session completion.
- Configurable tariffs and reports.
- More advanced priority scheduling, while clearly separating it from FIFO mode.

## Author
Meryl Binu — Roll No. 11  
Amal Jyothi College of Engineering, Kanjirappally
