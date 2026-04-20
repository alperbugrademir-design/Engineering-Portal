
#  Engineering Portal
**Interactive Simulation Suite for Materials Science and Thermodynamics**

Engineering Portal is a comprehensive toolset designed for Metallurgical and Materials Engineering students and professionals. It bridges the gap between complex theoretical thermodynamics and visual, interactive analysis.

### **Desktop-Web Version (Recommended)**
1. Ensure you have **Python 3.10+** installed on your system.
2. Clone or download this repository.
3. Navigate to the `Desktop-Web-Version` folder.
4. Run the main launcher script:
   ```bash
   python main_code.py

 ### **iOS-Mobile Version (Legacy)**
1. This version requires the **Pythonista 3** app (available on the App Store) installed on an iPad or iPhone.
2. Copy the entire `Mobile-Version` folder into your Pythonista "Local" or "iCloud" directory.
3. Open the `main_code.py` file within the Pythonista editor.
4. Tap the **"Run"** (Play) button to launch the interactive menu.


## Architecture & Migration Status
This project is currently undergoing a strategic migration from a mobile-native (iPadOS/Pythonista) environment to a universal Web/Desktop hybrid architecture.

* **`Desktop-Web-Version` (Current Development Focus):** Uses a Python backend to serve dynamic HTML/JS interfaces in any modern web browser.
* **`Mobile-Version` (Legacy):** The original source code developed for iPad using the `ui` framework.

##  Key Features (WIP)
* **Ellingham Diagram Simulator:** Dynamic stability analysis for metal oxides (ΔG° vs T).
* **Fe-C Phase Equilibrium:** Interactive exploration of the Iron-Carbon system.
* **Eh-pH (Pourbaix) Diagrams:** Thermodynamic boundaries for electrochemical systems.
* **Engineering Utilities:** Fractography decision trees and EN 10020 steel nomenclature tools (currently being ported).
* **Met-Wordle:** A metallurgy-themed word puzzle game designed to reinforce technical terminology.
* **RSVP E-Book Reader:** A rapid serial visual presentation reader optimized for technical metallurgy textbooks and research papers.


> **Note:** The current user interface is in **Turkish**, as it was initially developed for students at Istanbul Technical University (İTÜ). **International language support (English) is on the roadmap and will be implemented in future updates.**

##  Disclaimer
This software is developed for **educational purposes only**. The calculations and diagrams are simulations and should not be used as the sole basis for industrial design or critical manufacturing decisions. Always refer to certified engineering handbooks and standards (e.g., ASTM, DIN, ISO).



 ## Credits & Tools
* **Development Partner:** Built with the assistance of AI (Gemini/Claude) for code optimization and debugging.
* **Libraries:** Matplotlib, Pathlib, and Pythonista UI.
* **Data Sources:** Standard metallurgical handbooks and thermodynamic databases.


---
**Developed at Istanbul Technical University (İTÜ)**
